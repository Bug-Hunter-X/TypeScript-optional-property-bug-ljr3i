# TypeScript Optional Property Bug

This repository demonstrates a subtle bug in TypeScript related to optional properties and type checking. The `bug.ts` file contains a function that expects an object with `x` and `y` properties. However, TypeScript's type checking doesn't prevent calls to this function with an object missing one of these properties, leading to a runtime error.  The solution, `bugSolution.ts`, shows how to correctly handle optional properties to avoid this issue.