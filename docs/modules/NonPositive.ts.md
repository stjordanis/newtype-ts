---
title: NonPositive.ts
nav_order: 9
parent: Modules
---

---

<h2 class="text-delta">Table of contents</h2>

- [NonPositive (interface)](#nonpositive-interface)
- [prismNonPositive (constant)](#prismnonpositive-constant)
- [isNonPositive (function)](#isnonpositive-function)

---

# NonPositive (interface)

**Signature**

```ts
export interface NonPositive extends Newtype<{ readonly NonPositive: unique symbol }, number> {}
```

# prismNonPositive (constant)

**Signature**

```ts
export const prismNonPositive: Prism<number, NonPositive> = ...
```

# isNonPositive (function)

**Signature**

```ts
export const isNonPositive = (n: number) => ...
```