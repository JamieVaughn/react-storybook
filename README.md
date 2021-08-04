# subassemblies
A React Storybook Component Library

This storybook library uses Vite.js & ESBuild
- see [setup](https://storybook.js.org/blog/storybook-for-vite/)

# Start Storybook Dev Server

    npm run storybook

# Building Storybook

    npm run build-storybook -- -o ./docs

# Deploying to GH Pages

[storybook-deployer](https://github.com/storybookjs/storybook-deployer)
Deploys a generated static site build to the gh-pages branch that can be publish via github pages by pointing to that branch in settings

    npm run deploy-storybook

    // or for other configurations:
    npm run deploy-storybook -- --out=docs
    npm run deploy-storybook -- --dry-run

other notes on [publishing](https://storybook.js.org/docs/react/workflows/publish-storybook) a storybook site

# Using storybook as a documentation site

[Docs](https://storybook.js.org/docs/react/writing-docs/introduction)
