# Hugo Starter Theme

Dead-simple Hugo theme with everything you need to get started. Intended to be a starter for creating your own theme without including useless bloat like most Hugo themes.

## Getting started

Inside your project folder, copy the theme to your `themes` folder. Since you're just using it as a starter for your theme, remove the git history.

```bash
git clone https://github.com/ericmurphyxyz/hugo-starter-theme themes/your-theme-name
rm -rf themes/your-theme-name/.git
```

If you'd like some example content and an example config file to get started, you can copy the `exampleSite` directory into your root Hugo directory.

```bash
cp -r themes/your-theme-name/exampleSite/* ./
```

To learn more about building themes in Hugo, refer to Hugo's [templating documentation](https://gohugo.io/templates/).
