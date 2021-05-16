# eStartup theme for Hugo

![GitHub](https://img.shields.io/github/license/miguelsimoni/hugo-estartup-theme.svg?style=flat-square)
![GitHub top language](https://img.shields.io/github/languages/top/miguelsimoni/hugo-estartup-theme.svg?style=flat-square)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/miguelsimoni/hugo-estartup-theme.svg?style=flat-square)
![GitHub last commit (branch)](https://img.shields.io/github/last-commit/miguelsimoni/hugo-estartup-theme/main.svg?style=flat-square)
![GitHub closed issues](https://img.shields.io/github/issues-closed/miguelsimoni/hugo-estartup-theme.svg?style=flat-square)
![GitHub forks](https://img.shields.io/github/forks/miguelsimoni/hugo-estartup-theme.svg?style=flat-square)
![GitHub stars](https://img.shields.io/github/stars/miguelsimoni/hugo-estartup-theme.svg?style=flat-square)
![GitHub watchers](https://img.shields.io/github/watchers/miguelsimoni/hugo-estartup-theme.svg?style=flat-square)

[Hugo-eStartup](https://miguelsimoni.github.io/hugo-estartup-site/) is ported from the [eStartup](https://bootstrapmade.com/estartup-bootstrap-landing-page-template/) template by [BootstrapMade.com](https://bootstrapmade.com/) for [Hugo](https://gohugo.io/).

![screenshot](https://raw.githubusercontent.com/miguelsimoni/hugo-estartup-theme/main/images/tn.png)

### Original Template Info

**Description:** eStartup - Bootstrap Landing Page Template
**Designer:** BootstrapMade
**Template Version:** 4.2.0
**Bootstrap Version:** 5.0.0
**Last Updated:** May 10, 2021
**Created:** Aug 19, 2018
**License:** [Licensing information](https://bootstrapmade.com/license/)

## Installation

```
$ cd /<your-hugo-site-directory>
$ git submodule add https://github.com/miguelsimoni/hugo-estartup-theme.git themes/hugo-estartup-theme
```

More info: [hugo setup guide](https://gohugo.io/overview/installing/)

## Configuration

[Live Demo](https://miguelsimoni.github.io/hugo-estartup-site/)

[Example Site](https://github.com/miguelsimoni/hugo-estartup-theme/tree/main/exampleSite)

[config.toml](https://github.com/miguelsimoni/hugo-estartup-theme/blob/main/exampleSite/config/_default/config.yaml)

[params.toml](https://github.com/miguelsimoni/hugo-estartup-theme/blob/main/exampleSite/config/_default/params.yaml)

### Sections

You can show or hide each home page section from `config/_default/params.yaml`:

```yaml
showAboutUs: true
showFeatures: true
showScreenshots: true
showVideo: true
showTeam: true
showTestimonials: true
showPricing: true
showBlog: true
showNewsletter: true
showContact: true
```

### Multilingual

You can show or hide the Languages dropdown menu from `config/_default/params.yaml`:

```yaml
languagesMenuEnabled: true
```

### Breadcrumb

You can show or hide the current page in the breadcrumb from `config/_default/params.yaml`:

```yaml
breadcrumb:
  showCurrent: true
```

### Load more items

You can enable or disable the Load More button in the list pages from `config/_default/params.yaml`:

```yaml
pagination:
  loadMore: true
```

Disabling it will show the standard pagination widget.

### Contact

You can enable de Contact form to let visitors send you messages using [Formspree](https://formspree.io/) just adding your form code in `config/_default/params.yaml`:

```yaml
formspree:
  endpoint: https://formspree.io/f/yourformcode
```

### Footer

You can configure the footer content from `i18n/en.yaml` (or the correspondant language file) and from `data/footer.yaml`:

- en.yaml

```yaml
# Footer
footer_text: "Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s."

designed_by: "Designed by"
```
- footer.yaml

```yaml
- title:
    en: "About us"
    es: "Sobre nosotros"
  links:
  - label:
      en: "About us"
      es: "Sobre nosotros"
    link: "#about-us"
  - label:
      en: "Features"
      es: "Características"
    link: "#features"
  - label:
      en: "Live Streaming"
      es: "Transmisión en vivo"
    link: "#video"
  - label:
      en: "Privacy Policy"
      es: "Política de privacidad"
    link: "#"
```

### Social Networks

You can add the usernames for the current supported social networks in `config/_default/params.yaml`:

```yaml
# Social Networks
social:
  facebook: estartup
  twitter: estartup
  instagram: estartup
  linkedin: estartup
```

### Comments

Powered by [Disqus](https://disqus.com)

```yaml
disqusShortname: "yourdiscussshortname"
```

Disable the comments system by leaving the `params.disqus.site` empty.

### Google Analytics

```yaml
googleAnalytics: "UA-123-45"
```

Disable the Google Analytics by leaving `params.google.analytics.trackerID` empty.

### More Settings!

See the whole configuration in the [config/_default/](https://github.com/miguelsimoni/hugo-estartup-theme/blob/main/exampleSite/config/_default/) folder.

### Almost there...

In order to see your site in action, you can run Hugo's built-in local server.

```
$ cd exampleSite
$ hugo server -t ../..
```

Now enter [`http://localhost:1313/`](http://localhost:1313/) in the address bar of your browser.

## Deployment

- [Hosting on GitHub](https://gohugo.io/hosting-and-deployment/hosting-on-github/)
- [More hosting and deployment options](https://gohugo.io/hosting-and-deployment/)

## Contributing

- Found a bug?
- Got an idea for a new feature?

Let me know it using the [issue tracker](https://github.com/miguelsimoni/hugo-estartup-theme/issues).
Or make it directly: [pull request](https://github.com/miguelsimoni/hugo-estartup-theme/pulls).

## License

This port is released under the MIT License. Check the [original theme license](https://bootstrapmade.com/license/) for additional licensing information.

## Thanks

Thanks to [Steve Francia](https://github.com/spf13) for creating Hugo and the awesome community around the project. And also thanks to [BootstrapMade](https://bootstrapmade.com/) for creating this awesome theme.
