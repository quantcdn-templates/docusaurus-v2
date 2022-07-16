# Docusaurus (v2) QuantCDN starter template

![Template screenshot](quant/screenshot.png?raw=true)

This template provides everything you need to get started with [Docusaurus 2](https://docusaurus.io/) on QuantCDN.

Click the "Deploy to Quant" button to create a new repo, QuantCDN project, and deployment pipelines.

[![Deploy to Quant](https://www.quantcdn.io/img/quant-deploy-btn-sml.svg)](https://dashboard.quantcdn.io/deploy/step-one?template=docusaurus-v2)


### Installation

```
$ yarn
```

### Local Development

```
$ yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

#### Locally

If Quant CLI is configured (e.g via `quant init`) then you can simply run the following to deploy the latest build to Quant.

```
yarn deploy
```

#### via CI

This template automatically preconfigures your CI pipeline to deploy to Quant. This means you simply need to edit content and commit changes to trigger the build & deploy process.
