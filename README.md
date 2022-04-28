## Description

Ovestock Assessment (FED II)

For styling it comes with SASS, Emotion, and TailwindCSS ready to use. Choose your favorite CSS framework and get started. It also includes the @namics/stylelint-bem plugin for BEM style validation.

## Goal
Using the [ Dog API ]( https://dog.ceo/dog-api/documentation/ ), we want to: 

*    fetch a list of breeds. 
*    present this list in some sort of sortable way to be presented to the user. 
*    We want a user to be able to select a breed. 
*    After selecting we will use the breed specific API endpoint to fetch 3 or more images to present on the screen.
*    Write tests asserting that we've displayed the images

If you care to mock fetch requests, you can read the docs for [jest-fetch-mock here](https://www.npmjs.com/package/jest-fetch-mock).

## Built With

- [Vite](https://vitejs.dev/) Next generation frontend tooling.
- [Babel](https://babeljs.io/) The compiler for next generation JavaScript.
- [React Router](https://reactrouter.com/) Declarative Routing for React.js
- [ESLint](https://eslint.org/) Find and fix problems in your JavaScript code.
- [Prettier](https://prettier.io/) Opinionated code formatter.
- [Stylelint](https://stylelint.io/) A mighty, modern linter that helps you avoid errors and enforce conventions in your styles.
- [@emotion/react](https://emotion.sh/) Emotion is a library designed for writing css styles with JavaScript.
- [@emotion/styled](https://emotion.sh/) Styled is a way to create React components that have styles attached to them.
- [Sass](https://sass-lang.com/) Syntactically Awesome Style Sheets.
- [TailwindCSS](https://tailwindcss.com/) Rapidly build modern websites without ever leaving your HTML.
- [Jest](https://jestjs.io/) Delightful JavaScript Testing.
- [Testing Library](https://testing-library.com/) The React Testing Library is a very light-weight solution for testing React components

### Other Plugins

- [prop-types](https://www.npmjs.com/package/prop-types) Runtime type checking for React props and similar objects.
- [react-error-boundary](https://www.npmjs.com/package/react-error-boundary) Simple reusable React error boundary component.
- [eslint-config-airbnb](https://www.npmjs.com/package/eslint-config-airbnb) Airbnb's extensible shared config.
- [eslint-plugin-import](https://www.npmjs.com/package/eslint-plugin-import) Linting support of ES2015+ (ES6+) import/export syntax.
- [eslint-plugin-jsx-a11y](https://www.npmjs.com/package/eslint-plugin-jsx-a11y) Enforce accessibility best practices for React components.
- [eslint-plugin-unused-imports](https://www.npmjs.com/package/eslint-plugin-unused-imports) Report and remove unused es6 modules.
- [postcss](https://www.npmjs.com/package/postcss) PostCSS is a tool for transforming CSS with JavaScript plugins.
- [stylelint-config-idiomatic-order](https://www.npmjs.com/package/stylelint-config-idiomatic-order) Order your styles based on idiomatic-css.

## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

- Recommended `node` : `>=16.13.0`
- `npm` or `pnpm` or `yarn`

After that the syntax is the same as `npm` e.g. `npm install` becomes `pnpm install`.

### Setup

- `npm install` or `pnpm install` or `yarn`

## Scripts

### Start dev server

- `npm run dev` or `pnpm run dev` or `yarn run dev` and open the browser at `http://localhost:3000`

### Build for production

- `npm run build` or `pnpm run build` or `yarn run build`

### Locally preview production build

After creating the production build, run:

- `npm run preview` or `yarn run preview`

### Start server

- `npm run serve` or `pnpm run serve` or `yarn run serve` and open the browser at `http://localhost:4173`
