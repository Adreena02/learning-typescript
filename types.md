# Types

> ## Primitive Types
> All "primitive", or built-in data types in JavaScript are recongized by TypeScript.
> ## TypeScript Type Inference
> Type inference assumes the expected type of the variable throughout a program based on the data type of the value intially assigned to it at declaration. Type inference will log a complaint if the variable is later reassigned to a different type.
> ## The Shape of an Object
> TypeScript knows the *shape* of an object - what memeber properties it does or doesn't contain. TypeScript will log an error if the code attempts to access members of an object known not to exist. It may even suggest possible corrections.
> ## TypeScript any
> When a variable is declared without being assigned an intial value, TypeScript considers it to be of type 