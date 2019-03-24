# vue-tmp3

This proejct attempts to demo a build that contains `with` statements, which are rejected by Closure Compile. The OP claims the project must use render functions to reproduce the issue. However, I'm not able to reproduce the problem.

## Steps

 1. Download this repo and install dependecies.
 2. Run `yarn build` to create a production buid.
 3. Observe dist/app.*.js does not contain `with` statements.

## Environment

 * macOS Mojave
 * Chrome 73
 * Node 11.11.0
 * VUe CLI 3.5.1
 * Vue 2.6.10
