# Basic Types : 

1. Basic Types:

Boolean: Represents a logical value indicating either true or false.
Number: Represents both integer and floating-point numbers. TypeScript uses the same set of numeric types as JavaScript, including integers and floating-point numbers.
String: Represents a sequence of characters, similar to strings in other programming languages.
Array: Represents an ordered list of values of the same type. Arrays can be of a specific type or a union of multiple types.
Tuple: A tuple allows you to express an array where the type of a fixed number of elements is known, but need not be the same. Each element in the tuple can have a different type.
2. Enum:

Enum: Stands for "enumeration." It's a way to define a set of named constant values. Enums allow you to define a type with a limited set of possible values, making your code more readable and maintainable.
3. Any:

Any: Represents a value that can be of any type. Using any effectively removes type checking and type safety, so it's generally advised to use it sparingly, as it undermines TypeScript's main purpose.
4. Void:

Void: Represents the absence of a value. Typically used as the return type of functions that don't return a value. Variables of type void can only be assigned undefined or null.
5. Null and Undefined:

Null: Represents an intentional absence of any object value.
Undefined: Represents an uninitialized or undefined value.
6. Type Inference and Type Annotations:

Type Inference: TypeScript's ability to automatically determine the type of a variable based on its initialization value. This eliminates the need to explicitly declare the type of every variable, making the code more concise and easier to maintain.
Type Annotations: Explicitly specifying the type of a variable using syntax like variableName: type. Type annotations are used when TypeScript's type inference might not capture the intended type accurately, or when you want to provide clear documentation to other developers.