#### There are several basic types in TypeScript, including:

number: For numeric values.
string: For textual data.
boolean: For true/false values.
any: A wildcard type that can be anything.
arrays: For collections of values, denoted by Type[] or Array<Type>.

#### 允许定义变量持有特定的类型范围

``` typescript
// For example, to create a variable that can hold either null or a number
let numberOrNull: number | null;

// these assignments will work
numberOrNull = 3;
numberOrNull = null;

// this is not allowed in TypeScript
numberOrNull = "invalid assignment";

```