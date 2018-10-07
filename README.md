# npm-module-boilerplate
This is an opinionated boilerplate intended to bootstrap development of npm modules.

There is willingly no compilation task. JavaScript developers need to get the habits of compiling for themselves as it will greatly [improve overall performance](https://babeljs.io/blog/2018/06/26/on-consuming-and-publishing-es2015+-packages) for the end user.

It comes with the strict minimum:
* Rollup config & npm script to serve both ES module & CommonJS module
* dependencies for eslint (`airbnb-base`, `plugin-import` & `plugin-security`)

You can even remove the Rollup config alltogether if you're developing for the server with CJS module only.

## Getting started
Just download a copy of this repo (don't clone it, you're going to start a new git project).

Then you'll want to update or change the LICENCE and update the package.json with your own informations (repo, keywords, author, bugs…). And you're good to go!
