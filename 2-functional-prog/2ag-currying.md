# Currying

To _curry_ a function means to split a function which accepts `n` arguments into a set of functions which accept `[1..n]` arguments.

This is an easy way to create more reuseable functions.

You can also create well-named functions be _pre-loading_ some arguments (see `addFive` below). This is called [partial application](./2ah-partial-application.md).

```
const sum = (a, b, c) => a + b + c;
const curriedSum = curry(sum);

curriedSum(1, 2, 3) // 6

const addFive = curriedSum(2, 3);
addFive(7) // 12
```