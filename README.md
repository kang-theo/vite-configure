# vite-practice

## Vite

Vite is a build tool and development server for modern web development, primarily focused on frontend JavaScript frameworks like Vue.js and React. It's designed to provide a fast development experience by leveraging native ES module imports, allowing for quick startup times and rapid hot module replacement (HMR) during development.

### Key Features

1. **Native ES Module Support**: Vite leverages native ES module imports, which allows developers to directly import ES modules without needing bundling during development. This results in faster startup times and more efficient development workflows.
2. **Lightning-Fast Hot Module Replacement (HMR)**: Vite offers HMR out of the box, enabling developers to see their changes reflected in the browser almost instantly without needing a full page refresh. This greatly speeds up the development process.
3. **Optimized Build Process**: While Vite uses native ES module imports during development, it can also generate optimized production builds using Rollup, which bundles and minifies the code for deployment.
4. **Plugin-Based Architecture**: Vite's architecture is based on plugins, making it highly extensible and customizable. Developers can leverage plugins to add features or customize the build process according to their specific needs.
5. **Framework Agnostic**: While Vite has first-class support for Vue.js, it can also be used with other frontend frameworks like React or Svelte, making it versatile for various project setups.

Overall, Vite aims to provide a highly efficient and optimized development experience for modern web applications, particularly those built with frontend frameworks, by leveraging native browser capabilities and modern development practices.

## Installation and Setup

* npm init vite-app vite-configure | yarn create vite-app vite-configure

  (create React with Vite: npm init vite my-vite-project -- --template react-ts
)
  * cd vite-configure
  * npm install (or `yarn`)
  * npm run dev (or `yarn dev`)
