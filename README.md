
# 1. Setup
---
### Install TypeScript Compiler

```
npm intall -g typescript 
```
After installation, `tsc` command should be available

```
tsc --v

// Outputs Version 4.5.3
```

`tsx` or `ts-node` module runs TypeScript directly without need to precompile, but to be noted, both packages have subtle differences in type checking and configuration needs.

# 2. The Types in TypeScript
---
*Please mark, case in typescript becomes important, for example, `Number` is type in JavaScript but `number` is TypeScript data type.*

*The type names `String`, `Number`, and `Boolean` (starting with capital letters) are legal, but refer to some special built-in types that will very rarely appear in your code. _Always_ use `string`, `number`, or `boolean` for types.* - TypeScript Docs

## 2.1 Primitives

| **Name** | **Description**                 |
| -------- | ------------------------------- |
| string   | Represent text data. Can b      |
| number   | Represent numeric values.       |
| boolean  | Have `true` and `false` values. |

### 2.1.1 `string`
All text or string data get the `string` type. Double (`""`), Single (`''`) or backticks (\`\`) can be used to surround the strings

### 2.1.2 `number`
All numbers, either binary, decimal, octal, hexadecimal or float. Comes under `number` datatype.

`bigint` represents a number which is very large. Its support has been added recently. But its suggested to use `number` for almost all use cases.

### 2.1.3 `boolean`
`true` or `false` is represented as `boolean` datatype.

