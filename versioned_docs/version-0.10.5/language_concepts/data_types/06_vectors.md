---
title: Vectors
description:
  Delve into the Vector data type in Noir. Learn about its methods, practical examples, and best practices for using Vectors in your Noir code.
keywords:
  [
    noir,
    vector type,
    methods,
    examples,
    dynamic arrays,
  ]
---

A vector is a collection type similar to Rust's Vector type. It's convenient way to use slices as mutable arrays.

Example:

```rust
use dep::std::collections::vec::Vec;

let mut vector: Vec<Field> = Vec::new();
for i in 0..5 {
    vector.push(i);
}
assert(vector.len() == 5);
```
