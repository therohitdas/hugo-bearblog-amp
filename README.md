# Hugo ʕ•ᴥ•ʔ Bear Blog - AMPlified!  ⚡️

🧸 A fork of the [Hugo Bear Blog theme](https://github.com/janraasch/hugo-bearblog) with added AMP ⚡️ support. Best for mobile SEO 🤌

##  Why AMP?

We all know mobile is where it's at these days!  This theme takes the simplicity and speed of the original Bear Blog and gives it an extra boost with AMP, so you can capture all that sweet, sweet mobile SEO traffic. 

## Features

- **AMP Support:**  Get those lightning-fast page load times that Google loves, especially on mobile.
- **`amp-img` Integration:** Images are automatically optimized for AMP with responsive sizing and layout. 

## Anti-Features Branch

Want to add some more spice to your AMPlified Bear Blog?  Check out the  [`anti-features` branch](https://github.com/therohitdas/hugo-bearblog-amp/tree/anti-features):

- **`amp-ad` Support:**  Monetize your content with AdSense ads.
- **`amp-analytics` Integration:** Track your traffic with Google Analytics.
- **`amp-iframe` for YouTube Embeds:**  Easily add YouTube videos to your pages while using the privacy-conscious `youtube-nocookie` domain.

## Demo

See it in action, honey: [https://therohitdas.github.io/hugo-bearblog-amp/](https://therohitdas.github.io/hugo-bearblog-amp/) 🎯

## Installation

If you already have a Hugo site on your machine, you can simply add this theme via

```bash
git submodule add https://github.com/therohitdas/hugo-bearblog-amp.git themes/hugo-bearblog-amp
```

Then, add theme='hugo-bearblog-amp' to the `hugo.toml`-file.

For more information, read the official [setup guide](https://gohugo.io/getting-started/installing) of Hugo.

## Adjust configuration / hugo.toml

Please check out the [hugo.toml](https://github.com/therohitdas/hugo-bearblog-amp/blob/master/exampleSite/hugo.toml) included in the [exampleSite](https://github.com/therohitdas/hugo-bearblog-amp/tree/master/exampleSite) of this theme.

## Content & structure

### Starting fresh

If you are starting fresh, simply copy over the contents of the `exampleSite`-directory included in this theme to your source directory. That should give you a good idea about how things work, and then you can go on from there to make the site your own.

### Adding / editing content

#### Index-Page

The contents of the `index`-page may be changed by editing your `content/_index.md`-file.

#### Page

You can add **a new page** via running

```bash
hugo new my-new-page.md
```

#### Blog-Post

You can add **a new blog-post** via running

```bash
hugo new blog/my-new-post.md
```

### Adding your branding / colors / css

Add a `custom_head.html`-file to your `layouts/partials`-directory. In there you may add a `<style>`-tag, *or* you may add a `<link>`-tag referencing your own `custom.css` (in case you prefer to have a separate `.css`-file). Check out the [`style.html`](https://github.com/therohitdas/hugo-bearblog-amp/blob/master/layouts/partials/style.html)-file to find out which CSS-styles are applied by default.

## Issues / Feedback / Contributing
Please use [GitHub issues](https://github.com/therohitdas/hugo-bearblog-amp/issues) and [Pull Requests](https://github.com/therohitdas/hugo-bearblog-amp/pulls).

## Development
Run the `exampleSite` locally via

```bash
hugo server --source ./exampleSite --themesDir ../..
```

## Special Thanks 🎁

A huge thank you to [Jan Raasch](https://www.janraasch.com), for creating the original [Hugo ʕ•ᴥ•ʔ Bear Blog](https://github.com/janraasch/hugo-bearblog). Your work inspired this AMPlified version! 

## License
[MIT License](http://en.wikipedia.org/wiki/MIT_License) © [Rohit Das](https://therohitdas.com)