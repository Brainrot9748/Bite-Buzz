***

This project was set up using [Create React App](https://github.com/facebook/create-react-app), a toolchain designed to streamline modern React development by providing sensible defaults and an out-of-the-box build configuration.

## Getting Started

After cloning the repository and installing dependencies, you can use these scripts to manage and develop your application:

### `npm start`
Starts the web application in development mode.  
- Opens your app in the browser at [http://localhost:3000](http://localhost:3000).
- Automatically refreshes the page whenever you update source files.
- Displays real-time build errors and ESLint warnings directly in the browser and terminal, making debugging straightforward during development.

### `npm test`
Runs the project's test suite in an interactive watch mode.  
- By default, runs tests related to files changed since your last commit.
- Offers a streamlined workflow for writing, running, and organizing unit and integration tests.
- Reference: [Running tests guide](https://facebook.github.io/create-react-app/docs/running-tests).

### `npm run build`
Creates a production-ready build of your app in the `build` directory.  
- Compiles your React code in production mode, applying performance optimizations.
- Minifies JavaScript and CSS files to reduce bundle size.
- Adds hashes to filenames for cache busting.
- The contents of the `build` folder can be deployed to any static site host or server.
- For deployment guidance, see the [deployment documentation](https://facebook.github.io/create-react-app/docs/deployment).

### `npm run eject`
Enables advanced configuration and customization by “ejecting” from the default setup.  
- **Note:** This command is irreversible—once run, you cannot reapply the simplified setup.
- Copies all configuration files (including webpack, Babel, and ESLint) and build dependencies directly into your project.
- Grants full control over build configurations, scripts, and underlying tools for further customization.
- Most users never need to eject; the default configuration supports the majority of use cases for small and mid-sized apps. Only use this command if you require a custom build setup.

***

**Tip:** For more details about these commands and the underlying tooling, please refer to the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).
