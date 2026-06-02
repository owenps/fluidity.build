# fluidity.build

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
