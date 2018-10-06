# npm-module-boilerplate
This is an opinionated boilerplate intended to bootstrap development of npm modules.

There is willingly no compilation task. JavaScript developers need to get the habits of compiling for themselves as it will greatly [improve overall performance](https://babeljs.io/blog/2018/06/26/on-consuming-and-publishing-es2015+-packages) for the end user.

It comes with the strict minimum:
* rollup config to serve both ES module & CommonJS module
* dependencies for eslint (`airbnb-base`, `plugin-import` & `plugin-security`)
* npm scripts to create CJS file from the ESM one (you can even remove that if the module is intended to be used on the server in CJS only)
