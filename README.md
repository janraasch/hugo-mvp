# Hugo MVP ![Test](https://github.com/janraasch/hugo-mvp/workflows/CI/badge.svg?branch=master&event=push) [![Pay me][paypal-svg]][paypal-dot-me] [![Sponsor me][github-sponsors-svg]][github-sponsors]

🏇 A [Hugo](https://gohugo.io/)-theme based on [MVP.css](https://andybrewer.github.io/mvp/).

> No class names, no frameworks, just semantic HTML and you're done.

## Demo

For a current & working demo of this theme, please check out https://janraasch.github.io/hugo-mvp/ 🎯.

## Screenshot

👷‍♂️ `# TODO` 👷‍♂️

## Sponsor 💟

Support my work on this theme via [GitHub Sponsors][github-sponsors] (recurring) or [PayPal][paypal-dot-me] (one-time).

[![GitHub Stats](https://github-readme-stats.vercel.app/api/?username=janraasch)][github-sponsors]

## Installation

If you already have a Hugo site on your machine, you can simply add this theme via

```
git submodule add https://github.com/janraasch/hugo-mvp.git themes/hugo-mvp
```

Then, adjust the `config.toml` as detailed below.

For more information, read the official [setup guide][hugo-setup-guide] of Hugo.

## Adjust configuration / config.toml

Please check out the [config.toml](https://github.com/janraasch/hugo-mvp/blob/master/exampleSite/config.toml) included in the [exampleSite](https://github.com/janraasch/hugo-mvp/tree/master/exampleSite) of this theme.

## Content & structure

### Starting fresh

If you are starting fresh, simply copy over the contents of the `exampleSite`-directory included in this theme to your source directory. That should give you a good idea about how things work, and then you can go on from there to make the site your own.

### Adding / editing content

👷‍♂️ `# TODO` 👷‍♂️

### Adding your branding / colors / css

Add a `custom_head.html`-file to your `layouts/partials`-directory. In there you may add a `<style>`-tag, *or* you may add a `<link>`-tag referencing your own `custom.css` (in case you prefer to have a separate `.css`-file). Check out the [`mvp.css`](https://github.com/janraasch/hugo-mvp/blob/master/public/assets/mvp.css)-file to find out which CSS-styles are applied by default.

## Issues / Feedback / Contributing

Please use [GitHub issues][github-issues-url] and [Pull Requests][github-pulls-url].

If you do not have a GitHub-account, feel free to hit me up via email (see [janraasch.com][author-url]).

## Special Thanks 🎁

A special thank you goes out to [Andy Brewer](https://www.andybrewer.com), for creating the original [MVP.css](https://andybrewer.github.io/mvp/).

## License

[Hugo Product Launch][github-url] by [Jan Raasch][author-url] is licensed under [CC BY 4.0][license-url]

### Attribution

Please keep the original attribution link when using this theme for your project.

### More Permissions

If you would like to use this theme without attribution, permissions beyond this license's scope are available at [MORE_PERMISSIONS.md][more-permissions-url].

[![CC][license-cc-svg] ![BY][license-by-svg]][license-url]

[more-permissions-url]: https://github.com/janraasch/hugo-mvp/blob/master/MORE_PERMISSIONS.md
[github-url]: https://github.com/janraasch/hugo-mvp
[github-example-site-url]: https://github.com/janraasch/hugo-mvp/tree/master/exampleSite
[github-issues-url]: https://github.com/janraasch/hugo-mvp/issues
[github-pulls-url]: https://github.com/janraasch/hugo-mvp/pulls
[author-url]: https://www.janraasch.com
[license-url]: https://creativecommons.org/licenses/by/4.0
[license-cc-svg]: https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1
[license-by-svg]: https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1
[hugo-io-url]: https://gohugo.io/
[netlify-forms-url]: https://www.netlify.com/products/forms/
[favicon-io-url]: https://favicon.io
[favicon-io-example-site-url]: https://favicon.io/favicon-generator/?t=BF&ff=Catamaran&fs=110&fc=%23FFFFFF&b=rounded&bc=%2338b2ac
[pexels-url]: https://www.pexels.com
[paypal-dot-me]: https://www.paypal.me/janraasch/49,00
[paypal-svg]: https://img.shields.io/badge/onetime-donation-11dde2.svg?logo=paypal
[github-sponsors-svg]: https://img.shields.io/badge/recurring-sponsorship-ee4aaa.svg?logo=github
[github-sponsors]: https://github.com/sponsors/janraasch
