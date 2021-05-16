# eStartup Example Site

This repository is based on [Hugo Basic Example](https://github.com/gohugoio/hugoBasicExample), offers an example site for [Hugo eStartup Theme](https://github.com/miguelsimoni/hugo-estartup-theme) that are hosted on the [Hugo Themes Showcase](https://themes.gohugo.io/).

# Using

1. [Install Hugo](https://gohugo.io/overview/installing/)

2. Clone this repository

```bash
git clone https://github.com/miguelsimoni/hugo-estartup-site.git
cd hugo-estartup-site
```

1. Clone the repository of the eStartup theme from [here](https://github.com/miguelsimoni/hugo-estartup-theme).

2. Run Hugo (the theme is already selected in the [config.toml](https://github.com/miguelsimoni/hugo-estartup-site/blob/main/config.toml) file):

```bash
hugo server
```

5. The `/content/` folder contains the following:

- A section called `/post/` with sample markdown content
- A headless bundle called `homepage` that you may want to use for single page applications. You can find instructions about headless bundles over [here](https://gohugo.io/content-management/page-bundles/#headless-bundle)
- An `about.md` that is intended to provide the `/about/` page for a theme demo
- A section called `/getstarted/` with sample content for Get Started section.
- A section called `/features/` with sample content for Features section.
- A section called `/pricing/` with sample content for Pricing section.
- A section called `/testimonials/` with sample content for Testimonials section.

1. The `/data/` folder contains the following:

- A file called `screenshots.yaml` with sample content for Screenshots section.
- A file called `team.yaml` with sample content for Team section.
- A file called `footer.yaml` with sample content for the page footer.
