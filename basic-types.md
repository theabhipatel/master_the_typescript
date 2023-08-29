# Variables and  Types : 



### # Variable:  
Variable is a named place in memory where some data/value can be stored. According to the word variable, it can be said that the value of a variable can be changed/vary. While declaring a variable, some rules have to be followed:

- Variable names can contains alphabets both Upper-case as well as Lower-case and digits also.
- Variable name cant start with digit.
- We can use _ and $ special character only, apart from these other special characters are not allowed.


### Identifiers: 
Identifiers are nothing but the names which is given to the members of any class like a variable, method name, class name, array name etc. Certain rules to be followed while declaring Identifiers:

- Identifier name can start with both upper-case as well as lower case letter but can’t start with numbers.
- Only _ and $ symbols can be used for giving name to Identifiers, apart from these symbols, no other special symbol can be used.
- Keywords are different from Identifiers.
Identifier are case sensitive and doesn’t contain spaces.
- Examples of Valid and Invalid Identifiers:

| Valid |	Invalid |
| ----- | --------- |
| helloworld	| 1$helloworld |
| hello_world |	#hello |
| $hello |	hello-world |
| _hello$ |	any |


### Keywords:
 Keywords are words which are responsible to perform some specific task or the words which represent some specific functionality. The following table lists some keywords:

| break	 | as |	any |	switch |	case |	if |
| ---- | --- | --- | ---------- | ------ | ----|
|throw |	else |	var |	number |	string |	get |
| module |	type |	instanceof |	typeof |	public |	private |


### Comments: 
Comments are a way to improve the readability of a program. While coding we use comments for a better understanding of code for other users. While execution of the code, compiler ignore the comments and compile the rest of the code. There are two ways to use comments :

- Single-line comments ( // )
- Multi-line comments (/* */)





### # Data Types :

Whenever a variable is created, the intention is to assign some value to that variable but what type of value can be assigned to that variable is dependent upon the datatype of that Variable. In typeScript, type System represents different types of datatypes which are supported by TypeScript. The data type classification is as given below:

**Built-in Datatypes:** TypeScript has some pre-defined data-types-

| Built-in Data Type |	keyword |	Description |
| ------------------ | -------- | ------------- |
|Number |	number |	It is used to represent both Integer as well as Floating-Point numbers |
| Boolean |	boolean |	Represents true and false |
| String |	string |	It is used to represent a sequence of characters |
| Void |	void |	Generally used on function return-types |
| Null |	null |	It is used when an object does not have any value |
| Undefined |	undefined |	Denotes value given to uninitialized variable |
| Any |	any |	If variable is declared with any data-type then any type of value can be assigned to that variable |

1. **Basic Types :**

- Boolean: Represents a logical value indicating either true or false.
- Number: Represents both integer and floating-point numbers. TypeScript uses the same set of numeric types as JavaScript, including integers and floating-point numbers.
- String: Represents a sequence of characters, similar to strings in other programming languages.
- Array: Represents an ordered list of values of the same type. Arrays can be of a specific type or a union of multiple types.
- Tuple: A tuple allows you to express an array where the type of a fixed number of elements is known, but need not be the same. Each element in the tuple can have a different type.


2. **Enum :**
- Enum: Stands for "enumeration." It's a way to define a set of named constant values. Enums allow you to define a type with a limited set of possible values, making your code more readable and maintainable.

3. **Any :**
Any: Represents a value that can be of any type. Using any effectively removes type checking and type safety, so it's generally advised to use it sparingly, as it undermines TypeScript's main purpose.

4. **Void :**
Void: Represents the absence of a value. Typically used as the return type of functions that don't return a value. Variables of type void can only be assigned undefined or null.

5. **Null and Undefined :**
- Null: Represents an intentional absence of any object value.
- Undefined: Represents an uninitialized or undefined value.


6. **Type Inference and Type Annotations :**

- **Type Inference:** TypeScript's ability to automatically determine the type of a variable based on its initialization value. This eliminates the need to explicitly declare the type of every variable, making the code more concise and easier to maintain.
- **Type Annotations:** Explicitly specifying the type of a variable using syntax like variableName: type. Type annotations are used when TypeScript's type inference might not capture the intended type accurately, or when you want to provide clear documentation to other developers.