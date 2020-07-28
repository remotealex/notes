# FP fundamentals

Functional programming is most useful when doing 1-to-1 data transforms. That's to say, we put some data in to a _function_ and we expect it to return a certain result or the data in a new, specified format.

Functions which return the same output for any given input, are called **pure** functions, and are the basis of _functional programming_, which is a style of software development where we build programs by stringing (_composing_ [see [2ac-composition.md](./2ac-composition.md)]) these pure functions together.

A function which is no pure, is said to have "side-effects". See [2aa-side-effects.md](./2aa-side-effects.md).