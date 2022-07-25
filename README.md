# Vite & Vue2 & Bootstrap4

There are plenty of tutorials for using Vite with Vue.js 3 and a lot of ready-made starter templates as well. We will be focusing on Vue.js 2 and see how we can create a base for a new project that:

- Uses Bootstrap 4.6 CSS for layout and styling
- Uses vue-router for client-side routing
- Supports global SCSS variables inside Vue components
- Is IE11 compatible
- Removes unused CSS rules from the production bundle.

Original work by [Giannis Koutsaftakis](https://dev.to/kouts/how-to-create-a-vue-js-2-bootstrap-4-project-with-vite-54f1).

## Dependencies:
```
npm i vue@2.7.8 vue-router@3.5.4 bootstrap@4.6.0
```

## Dev dependencies:
```
npm i -D vite-plugin-vue2 @vitejs/plugin-legacy vite-plugin-html vue-template-compiler sass@~1.32.13 postcss @fullhuman/postcss-purgecss autoprefixer
```

## Run
```
npm run dev
```
It should be running on `http://localhost:5173/` with Vite.


