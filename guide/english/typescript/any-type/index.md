---
title: Any Type
---

# Any Type

The Any type instructs Typescript to suspend type checking for the specified variables. Useful when working with dynamic content for which you don't know the type, and for transitioning your codebase for Javascript to Typescript in pieces. You can use Javascript's implicit typing with variables declared with a type of Any.

```typescript
  let notSure: any = 4;
  notSure = "maybe a string instead";
  notSure = false;
```

Any is a special data-type, also the super data-type of all data types. If a variable is declared with any data type then we can assign any type value to that variable.
The Any data type is the super type of all types in TypeScript. It denotes a dynamic type. Using the any type is equivalent to opting out of type checking for a variable.

```typescript

  let a: any = null;

  let b: any =123;

  let c: any = 123.456;

  let d: any = ‘Geeks’;

  let e: any = undefined;

  let f: any = true;
  
  ```

