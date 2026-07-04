<p align="center"><img src="https://raw.githubusercontent.com/go-ruby-saml/brand/main/social/go-ruby-saml.png" alt="go-ruby-saml/go-ruby-saml.github.io" width="720"></p>

# go-ruby-saml.github.io

The organization's institutional landing page, served at
<https://go-ruby-saml.github.io> and built with [Hugo](https://gohugo.io). It is a
single page (custom `layouts/index.html`).

Documentation lives in a separate repository,
[go-ruby-saml/docs](https://github.com/go-ruby-saml/docs), served at
<https://go-ruby-saml.github.io/docs/>. This page links there.

`.github/workflows/deploy-pages.yml` builds the landing with Hugo and deploys it
to GitHub Pages on every push to `main`.

## Local preview

```bash
hugo server      # http://localhost:1313
```
