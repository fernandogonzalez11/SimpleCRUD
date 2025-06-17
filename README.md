Dead simple CRUD app
===

This is a simple CRUD app made with Node.js, Express and HTML.

It is meant to:

* Work as boilerplate for my future CRUD apps from my CS major.
* Be as (personally) frictionless as possible
* Be data driven as I dislike OOP, but maintain an MVC classes scheme so that teachers will be happy
    - Note: one can easily change controller and model classes for modules
* Have simple but robust validation with [Zod](https://zod.dev/)

## how2run

Needs latest Node.js version (v22+?) because of `node:sqlite`, unless you remove that part.

```bash
git clone https://github.com/fernandogonzalez11/SimpleCRUD
cd SimpleCRUD
npm i

# on one terminal
node api/server.js # (with `init` argument if it's the first time running)

# on another terminal
node frontend/server.js
```