# Complex Types

## TypeScript Type for One-dimensional Array
> The type annotation for a one-dimensional array in TypeScript is similar to a primitive data type, except we add a **[]** after the type.

> `// zipcodes is an array of strings`

> `let zipcodes: string[] = ['03255', '02134', '08002', '03063'];`

> `// Pushing a number to zipcodes will generate an error`

> `// Error: Argument of type 'number' is not assignable to parametet of type 'string'.`

> `zipcodes.push(90210);`

## TypeScript Generic Type for One-Dimensional Array
> The type for a one-dimensional array in TypeScript can be annotated with **Array<T>**, where **T** stands for the type.

> `// zipcodes is an array of strings`

> `let zipcodes: Array<string> = ['03255', '02134', '08002', '03063'];`

> `// Pushing a number to zipcodes will generate an error`

> `// Error: Argument of type 'number' is not assignable to parameter of type 'string'.`

> `zipcodes.push(90210);`

## TypeScript Type for Multi-dimensional Array
> The type for a multi-dimensional array can be annotated by adding an extra [] for each extra dimension of the array.

> `// one-dimensional arrays`

> `let zipcodesNH: string[] = ['03255', '03050', '03087', '03063'];`

> `let zipcodesMA: string[] = ['02334', '01801'];`
    ---
> `// two-dimensional array`

> `let zipcodes: string[][] = [zipcodesNH]`
    ---
> `// Pushing a one-dimensional array to a two-dimensional array`

> `zipcodes.push(zipcodesMA);`

> `console.log(zipcodes);`

> `// prints [["03255", "03050", "03087", "03063"] ["02334", "01801"]]`
