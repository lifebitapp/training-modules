# Module 8c: Vue.js
## Introduction
_Some of the following snippets are taken from the
[overview section](https://vuejs.org/guide/overview.html) of the Vue.js guide. It
is recommended that you read through this to get an understanding of Vue's main
purpose and methodologies._

Vue.js is a library for building interactive web interfaces. The goal of Vue.js
is to provide the benefits of **reactive data binding** and **composable view
components** with an API that is as simple as possible.

At the core of Vue.js is a reactive data-binding system that makes it extremely
simple to keep your data and the DOM in sync. When using jQuery to manually
manipulate the DOM, the code we write is often imperative, repetitive, and
error-prone. Vue.js embraces the concept of **data-driven view**.

## Resources
- [Vuejs.org](https://vuejs.org)
- [Laracast's Learning Vue 1.0: Step by Step](https://laracasts.com/series/learning-vue-step-by-step)
- [Vue DevTools Chrome Extension](https://chrome.google.com/webstore/detail/vuejs-devtools/nhdogjmejiglipccpnnnanhbledajbpd) & [vue/devtools](https://github.com/vuejs/vue-devtools)
- [Awesome Vue](https://github.com/vuejs/awesome-vue)

## The Test
_We will be building out a simple todo app as part of this module. You'll be
provided some boilerplate files and snippets to speed up progress, but please let
your mentor know if there are any snippets that you would like explained before
using them._

1. Start by forking [realpage/vue-module-template](https://github.com/realpage/vue-module-template) into your own namespace (yourusername/vue-module-template). You will commit your work to this new repo.
  - The vue-module-template has multiple branches to help you move between different tasks within this module more quickly
  - To start, there is a basic `index.html` providing bootstrap-v4 and vue.js
  - There is also `app.js`, which we will use as a starting point for using Vue
  - Lastly, it's recommended that you install an npm package called live-server
     - `npm i -g live-server # i is a shortcut for install`
     - You can then run `npm run dev` to start an live-reload server for development
2. Checkout `task-1-hello-vue` to get started
3. Take a look at the `app.js` file to see how the global Vue instance is created for this app.
4. Update the Vue instance in `app.js` to bind to the `<div>` with an id of `app`.
5. Update the "Hello, World!" message in `index.html` to render the `message` data from the Vue instance.
6. Update the Vue instance data with another attribute titled `name` with a value of your name.
  - e.g. Mine would be `name: 'John'`
7. Below the `h1` tag, update `index.html` to ask how you are by using the new `name` data.
  - e.g. Mine would say "How are you, John?"
8. This is where we get to start with the dynamic nature of Vue. Below the new question, add an `input` element with the `v-model` attribute with a value of `name`.
9. You should now see a text input field showing your name! Try updating the field value to use your first and last name. The question updates according to the data passed in. If you have the Vue Devtools installed and are running `live-server`, take a look at the `<Root>` Vue object and watch the data update as you change the value of the input field.
