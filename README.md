# Testing with React Apps Example

This is a demo React Redux app built with Create React App originally from [the Redux examples folder](https://github.com/reduxjs/redux/tree/master/examples/todomvc).

## Getting started with testing React apps

When testing React apps, there are a couple different things that need testing.  Tests for how components render and behave are the most common.

This [resource](https://www.codementor.io/vijayst/unit-testing-react-components-jest-or-enzyme-du1087lh8) from codementor provides great context for the common libraries currently used to test React components.

Create React App's documentation has *extensive* instructions for getting started with component testing in a way that is compatitble with Create React App (CRA). CRA includes testing with Jest by default.  The documentation includes instructions for adding Enzyme to tests as well.

See documentation [here](https://github.com/facebook/create-react-app/blob/master/packages/react-scripts/template/README.md#running-tests).

## Additional Resources

Will be adding more as we discuss in class.

### Storybook

An interesting new development tool for React components that produces [pretty "books"](https://storybook.js.org/examples/) of components from your project.  This is not something we all need to know, but it's interesting and may be relevant to you if you become a React developer.  It's also very cool that they are tying this in a way of [testing](https://www.learnstorybook.com/react/en/test/) known as ["visual regression testing"](https://www.robinwieruch.de/visual-regression-testing-react-storybook/).


# Redux TodoMVC Example

This project template was built with [Create React App](https://github.com/facebookincubator/create-react-app), which provides a simple way to start React projects with no build configuration needed.

Projects built with Create-React-App include support for ES6 syntax, as well as several unofficial / not-yet-final forms of Javascript syntax such as Class Properties and JSX.  See the list of [language features and polyfills supported by Create-React-App](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#supported-language-features-and-polyfills) for more information.

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.
