# i18n pages-guide

## Important Considerations & Files

- [index.md](index.md) redirects to `/en/home`
- [pages](pages) and [_data](_data) contain `/en` and `/fr` directories; former with content, latter with navigation
- [_includes/navbar.html](_includes/navbar.html) contains drop-down menu for language selection
- [_config.yml](_config.yml) contains a `languages` block with key:value elements

## GitHub Actions

Create a generic Jekyll GitHub page workflow and pick the branch you want it to operate from.

## Local Development

Requirements: ruby 3.2.+

```sh
$ gem install bundler
$ bundle install
$ bundle exec jekyll serve
```