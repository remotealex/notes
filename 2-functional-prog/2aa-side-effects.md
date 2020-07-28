# Side effects

A function is said to have a side effect if it updates something outside of it's local environment (in web-development this could be a browsers local-storage or a database).

Side effects are not inherently bad, but it is good practice to **identify and isolate functions with side effects**, and handle them specifically.

## Examples

Mutating variables creates uncertainty at runtime as do functions which rely on shared/global state.

In web-dev, asynchronous functions often call external resouces like a server which could have any number of responses.