# React-TypeScript-Boilerplate

This repo is now deprecated. In the time since it created [TypeScript support](https://facebook.github.io/create-react-app/docs/adding-typescript) is now a default feature of [Create React App](https://facebook.github.io/create-react-app/), [Next.JS](https://nextjs.org) and [Razzle](https://github.com/jaredpalmer/razzle).

This means you can get started with:

```sh
# Creates an app called my-app
npx create-react-app my-app --typescript

cd my-app

# Adds the type definitions
npm install --save typescript @types/node @types/react @types/react-dom @types/jest

echo "Good to go :tada:"
```

This repo offers some exmples on how to take that project into production and handle testing and state. However, you can
also use the official documentation in the Create React App website for that.

If you'd like to know more about how to effectively do React with TypeScript, we recommend looking at the following:

- [React+TypeScript Cheatsheets](https://github.com/typescript-cheatsheets/react-typescript-cheatsheet#reacttypescript-cheatsheets)
- [React & Redux in TypeScript - Static Typing Guide](https://github.com/piotrwitek/react-redux-typescript-guide#react--redux-in-typescript---static-typing-guide)
- [Use TypeScript to develop React applications](https://egghead.io/courses/use-typescript-to-develop-react-applications)
- [Ultimate React Component Patterns with Typescript 2.8](https://levelup.gitconnected.com/ultimate-react-component-patterns-with-typescript-2-8-82990c516935)

Below is the original README for this sample.

---

# TypeScript React Starter

This quick start guide will teach you how to wire up TypeScript with [React](http://facebook.github.io/react/).
By the end, you'll have

- a project with React and TypeScript
- linting with [TSLint](https://github.com/palantir/tslint)
- testing with [Jest](https://facebook.github.io/jest/) and [Enzyme](http://airbnb.io/enzyme/), and
- state management with [Redux](https://github.com/reactjs/react-redux)

We'll use the [create-react-app](https://github.com/facebookincubator/create-react-app) tool to quickly get set up.

We assume that you're already using [Node.js](https://nodejs.org/) with [npm](https://www.npmjs.com/).
You may also want to get a sense of [the basics with React](https://facebook.github.io/react/docs/hello-world.html).

# Install create-react-app

We're going to use the create-react-app because it sets some useful tools and canonical defaults for React projects.
This is just a command-line utility to scaffold out new React projects.

```shell
npm install -g create-react-app
```

# Create our new project

We'll create a new project called `my-app`:

```shell
create-react-app my-app --scripts-version=react-scripts-ts
```
