<h1 align="center">📚 cookbook.js</h1>

<p align="center">
  <img src="https://img.shields.io/npm/v/cookbook.js.svg" alt="npm version">
  <img src="https://img.shields.io/npm/dt/cookbook.js.svg" alt="npm downloads">
  <img src="https://img.shields.io/github/license/emptydev1/cookbook.js.svg" alt="license">
</p>

<p>📦 Welcome to cookbook.js, a versatile library designed to simplify recipe retrieval from <strong><a href="https://www.tudoreceitas.com/">tudoreceitas.com</a></strong>.</p>

<h2 align="center">Overview</h2>

<p>Cookbook.js offers a straightforward and intuitive interface for accessing a vast collection of recipes available on <strong><a href="https://www.tudoreceitas.com/">tudoreceitas.com.</a></strong>. With just a few lines of code, you can seamlessly integrate recipe fetching functionality into your project.</p>

<h2 align="center">Installation</h2>

<p>To install cookbook.js, simply run the following command in your project directory:</p>

```bash
npm install cookbook.js
```

<h2 align="center">Usage</h2>

<p>Getting started with cookbook.js is quick and easy. Once installed, you can use it to retrieve recipes with minimal effort.</p>

<h3 align="center">Example:</h3>

```js
const cookbook = require('cookbook.js');

// Retrieve a recipe
cookbook('chocolate cake').then(data => console.log(data));
```

<h3 align="center">Response Format</h3>

<p>When you request a recipe, you'll receive a detailed object containing various attributes. Here's an overview of the response format:</p>

```json
{
    "title": "String",
    "description": "String",
    "imageUrl": "String",
    "category": { "name": "String", "link": "String" },
    "url": "String",
    "author": { "name": "String", "avatarUrl": "String" },
    "published_at": "String",
    "review": { "stars": "Number", "votes": "Number" },
    "comments": "Array",
    "duration": "String",
    "dificulty": "String",
    "ingredients": "Array",
    "instructions": "Array",
    "similar": "Array",
    "responseTime": "Number"
}
```

<h2 align="center">Contribution</h2>

<p>We welcome contributions from the community to make cookbook.js even better. If you have ideas for improvements, bug fixes, or new features, feel free to submit a pull request on <strong><a href="https://github.com/emptydev1/cookbook.js">GitHub</a></strong>. Your contributions are greatly appreciated! 🚀</p>
