# g-t-b-pages

A **G**a**t**s**b**y-based static-site generator for **G**i**t**Hu**b** pages for those who want to be a bit more Reactive.

## How to use

### Depedencies

Fork the repository and install the yarn dependencies:

```
yarn install
```

### Development

```
yarn develop
```

Now, you should be able to visit `http://localhost:8000/`

### Deploy

The page should deploy automatically on pushes to `main`; you should see a `deploy-gh-pages` action run in your Actions tab.

### Deploy Manually

```
yarn deploy
```

If it doesn't already exist, a `gh-pages` branch should be created, which should automatically set up and publish the GitHub page.

To view the settings for your repository's Github Page, go to Settings -> Pages.
