# Development

- Requires `Ruby >= 2` 
- `$ bundle install`
- `$ bundle exec jekyll serve`

# Adapting the content

- Edit the contact info JSON files in `_data/`
- Edit your project metadata in `_config.yml`
- Add new pages as markdown files in `./`
- Add navigation links in `_includes/page-header.html`

# Publishing

- Log into your VM and setup your ssh keys
- Run `jekyll build` on your machine
- Push your site to the vm:
  `scp -r _site/* <VM name>@nitron.se.rit.edu:~<VM name>/public_html`

# License

This work is licensed under a [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/) license.

[1]: https://jekyllrb.com/
[2]: https://pages.github.com/
[3]: https://github.com/jasonlong/cayman-theme
