## Table of Contents

- [Installation](#installation)
- [Quick start](#quick-start)
- [Features](#features)
  - [Syntax highlighting](#syntax-highlighting)
  - [Disqus](#disqus)
  - [Google Analytics](#google-analytics)
- [About](#about)
- [Contributing](#contributing)
- [Changelog](#changelog)
- [License](#license)

********************

## Installation

#### With `git`

From the root of your Hugo site, clone the theme into `themes/hugo-researcher` by running :
```
git clone https://github.com/clelange/hugo-researcher.git themes/hugo-researcher
```

#### Manual

1. [Download][zip-archive] zip archive.
2. Unarchive it.
3. Move `hugo-researcher` folder in `themes` folder of your blog

For more information read the official [setup guide][hugo-guide] of Hugo.

## Quick start

After installation, take a look in the `exampleSite` folder at. This directory contains an example config file and the content for the demo. It serves as an example setup for your documentation.

```
  exampleSite
  ├── config.toml
  ├── content
  │   ├── projects.md
  │   │
  │   └── blog
  │       ├── creating-a-new-theme.md
  │       ├── go-is-for-lovers.md
  │       ├── hugo-is-for-lovers.md
  │       └── migrate-from-jekyll.md
  │
  ├── data
  │   └── projects.yml
  │
  └── static
```

Copy at least the `config.toml` in the root directory of your website. Overwrite the existing config file if necessary.

Hugo includes a development server, so you can view your changes as you go -
very handy. Spin it up with the following command:

``` sh
hugo serve
```

Now you can go to [localhost:1313][local] and the Sustain
theme should be visible.

## Features

### Syntax highlighting

Use `highlight = true` in the front matter to include [`highlight.js`][highlight-js] javascript and css files.

### Disqus

To use this feature, uncomment and fill out the `disqusShortname` parameter in config.toml`.

### Google Analytics

To add Google Analytics, simply sign up to [Google Analytics][g-analytics] to obtain your Google Tracking ID, and add this tracking ID to the `googleAnalytics` parameter in `config.toml`.

## About

This is a theme meant for researchers who would like to have their own webpage. It is originally based on a port of the Jekyll theme [Sustain][sustain-jekyll] by [Fábio Madeira][sustain-author].

## Contributing

Pull requests, bug fixes, and new features are welcome!

1. Fork the repository
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -a -m 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request on GitHub

## Changelog

> Version 0.1

- Initial release

## License

<a href="./LICENSE"><strong>MIT</strong></a>


[bootstrap]: https://getbootstrap.com/
[hugo]: https://gohugo.io/
[gh-pages]: https://pages.github.com/
[zip-archive]: https://github.com/clelange/hugo-researcher/archive/master.zip
[hugo-guide]: https://gohugo.io/overview/installing/
[local]: http://localhost:1313/
[highlight-js]: https://highlightjs.org/
[g-analytics]: https://www.google.com/analytics/
