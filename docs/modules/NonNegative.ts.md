---
title: NonNegative.ts
nav_order: 7
parent: Modules
---

# NonNegative overview

Added in v0.2.0

---

<h2 class="text-delta">Table of contents</h2>

- [NonNegative (interface)](#nonnegative-interface)
- [isNonNegative](#isnonnegative)
- [prismNonNegative](#prismnonnegative)

---

# NonNegative (interface)

**Signature**

```ts
export interface NonNegative extends Newtype<{ readonly NonNegative: unique symbol }, number> {}
```

Added in v0.2.0

# isNonNegative

**Signature**

```ts
export const isNonNegative = (n: number) => ...
```

Added in v0.2.0

# prismNonNegative

**Signature**

```ts
export const prismNonNegative: Prism<number, NonNegative> = ...
```

Added in v0.2.0
