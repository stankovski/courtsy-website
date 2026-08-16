# Courtsy website

Jekyll marketing site for Courtsy, built for GitHub Pages.

## Local development

```sh
bundle install
bundle exec jekyll serve
```

Open `http://127.0.0.1:4000/`.

## GitHub Pages

The `Deploy GitHub Pages` workflow builds and publishes the site after every push to `main`. It can also be run manually from the Actions tab.

In the repository settings, open **Pages**, set **Source** to **GitHub Actions**, and set the custom domain to `courtsyapp.com`. Enable **Enforce HTTPS** after GitHub verifies the DNS records. The published site is `https://courtsyapp.com/`.
