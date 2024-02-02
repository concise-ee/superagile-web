# #superagile documentation and website

## Getting started

### Dependencies

**1. Ruby**

- For **Windows** easiest solution is [RubyInstaller](https://rubyinstaller.org/).
- For **Linux** just use your favorite package manager.
- **MacOS** comes with Ruby v2 by default. You need to install newer version of Ruby. For instructions, see [Install Ruby MacOS].

**2. Bundler and Jekyll**: ```gem install bundler jekyll```

### Building and previewing locally

1. Change your working directory to the root directory of your site.
2. Run `bundle install`.
3. Run `bundle exec jekyll serve` to build your site and preview it at `localhost:4000`.

    The built site is stored in the directory `_site`.

## Advanced

### Customizing color scheme

Jekyll will use the files in your project first before falling back to the default versions of the theme.

See also: [How to define a custom scheme](https://just-the-docs.github.io/just-the-docs/docs/customization/#define-a-custom-scheme) for just the docs

### Changing the version of the theme and/or Jekyll

Simply edit the relevant line(s) in the `Gemfile`.

### Adding a plugin

The Just the Docs theme automatically includes the [`jekyll-seo-tag`] plugin.

To add an extra plugin, you need to add it in the `Gemfile` *and* in `_config.yml`. For example, to add [`jekyll-default-layout`]:

- Add the following to your site's `Gemfile`:

  ```ruby
  gem "jekyll-default-layout"
  ```

- And add the following to your site's `_config.yml`:

  ```yaml
  plugins:
    - jekyll-default-layout
  ```

### Publishing the site on a different platform

Just upload all the files in the directory `_site`.

### Licensing and Attribution

Just the docs theme is licensed under the [MIT License]. The deployment GitHub Actions workflow is heavily based on GitHub's mixed-party [starter workflows]. A copy of their MIT License is available in [actions/starter-workflows].

### Useful resources

- [Jekyll]
- [Just the Docs]
- [GitHub Pages]

---

[Jekyll]: https://jekyllrb.com
[Just the Docs]: https://just-the-docs.github.io/just-the-docs/
[GitHub Pages]: https://docs.github.com/en/pages
[`jekyll-default-layout`]: https://github.com/benbalter/jekyll-default-layout
[`jekyll-seo-tag`]: https://jekyll.github.io/jekyll-seo-tag
[MIT License]: https://en.wikipedia.org/wiki/MIT_License
[starter workflows]: https://github.com/actions/starter-workflows/blob/main/pages/jekyll.yml
[actions/starter-workflows]: https://github.com/actions/starter-workflows/blob/main/LICENSE
[Install Ruby MacOS]: https://mac.install.guide/ruby/13
