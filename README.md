# fluidity.build

[![Deploy site to GitHub Pages](https://github.com/owenps/fluidity.build/actions/workflows/pages.yml/badge.svg)](https://github.com/owenps/fluidity.build/actions/workflows/pages.yml)

Hugo marketing site for [fluidity](https://github.com/owenps/fluidity), published at [fluidity.build](https://fluidity.build).

## develop

```sh
git submodule update --init --recursive
hugo server
```

## build

```sh
hugo --gc --minify
```

## deploy

Push to `main`. GitHub Actions builds the site and deploys it to GitHub Pages.
