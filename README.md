# ReaDeal

A web application that allows users to effortlessly track their current reading progress and manage their reading wish lists.

## Quickstart

After cloning the project, just install the dependencies and then run the development server. The `run dev` command will output the local url the app is served to.

```
npm install
npm run dev
```

## Contributing

### Develop in branches

Create a new branch for all development. This branch should reference the git issue and milestone that it is addressing.

### Create Pull Request

Once local development is ready to review, create a pull request against the `main` branch. Please use the guidelines here: [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/) to name your pull request. The pull request will run a few automated steps:

- **linting**:
  prettier and eslint checks will run to ensure that the code is properly formatted according to the project guidelines. Any errors in this step can typeically be fixed by running `npm run prettier-fix` and `npm run lint-fix` then commiting the changes made by the tools.
- **preview**:
  a build and deployment of the code in your branch which will be hosted live on firebase, this can be viewed by clicking the preview url in github.

Once the pull request is reviewed by a maintainer it can be merged at which point the project will be automatically deployed to the live production site.

## Project Tech Stack

[vite.js](https://vitejs.dev/) - Project tooling

[react](https://react.dev/) - User interface library

[NextUI](https://nextui.org/) - React compatible UI component library

[PostgreDB](https://www.postgresql.org/) - Backend as a service platform for hosting and backend services and database

[typescript](https://www.typescriptlang.org/) - A strongly typed programming language that builds on JavaScript

[prettier](https://prettier.io/) - Code formatter

[eslint](https://eslint.org/) - Static code analyzer

## Project Structure

`/src`
All application code

`/src/assets`
Static assets for the application.

`/src/components`
React components.

`/src/core`
Pure typescript code which does not reference react.

`/src/routes`
React pages directly referenced by the router.
