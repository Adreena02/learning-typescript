# Complex Types

## TypeScript Type for One-dimensional Array
> The type annotation for a one-dimensional array in TypeScript is similar to a primitive data type, except we add a **[]** after the type.

`
`// zipcodes is an array of strings
let zipcodes: string[] = ['03255', '02134', '08002', '03063'];

// Pushing a number to zipcodes will generate an error
// Error: Argument of type 'number' is not assignable to parametet of type 'string'.
zipcodes.push(90210);`
`
