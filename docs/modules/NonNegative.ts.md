---
title: NonNegative.ts
nav_order: 7
parent: Modules
---

---

<h2 class="text-delta">Table of contents</h2>

- [NonNegative (interface)](#nonnegative-interface)
- [prismNonNegative (constant)](#prismnonnegative-constant)
- [isNonNegative (function)](#isnonnegative-function)

---

# NonNegative (interface)

**Signature**

```ts
export interface NonNegative extends Newtype<{ readonly NonNegative: unique symbol }, number> {}
```

# prismNonNegative (constant)

**Signature**

```ts
export const prismNonNegative: Prism<number, NonNegative> = ...
```

# isNonNegative (function)

**Signature**

```ts
export const isNonNegative = (n: number) => ...
```