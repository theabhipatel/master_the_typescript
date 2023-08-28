# Introduction to TypeScript


TypeScript is an Open Source Object Oriented programming language developed and maintained by Microsoft Corporation. TypeScript is a strongly typed language and its first version was introduced in 2012. It is a Strict Super Set of JavaScript, which means anything that is implemented in JavaScript can be implemented using TypeScript along with the choice of adding enhanced features (every existing JavaScript Code is a valid TypeScript Code). As TypeScript code is converted to JavaScript code it makes it easier to integrate into JavaScript projects. It is designed mainly for large Scale projects.

>TypeScript ===>>> JavaScript + Type + Some Added Features

### # What does TypeScript offer ?

1. **Static Type Checking (Optional)** – Like other high level programming languages like Java, C etc. TypeScript does provide static type checking unlike JavaScript. Although static typing requires some extra steps while writing code but it has its own advantages. With TypeScript, we can check and assign variables, parameters and function types. It is completely Optional and helps us find and prevent bugs. Also helps make code more readable and descriptive.
2. **Class Based Objects** – Another huge advantage is the use of Classes which provides the ability to use true object oriented programming in our applications and prevents use of prototype based objects. It also provides encapsulation, inheritance and modifiers.
3. **Modularity** – It helps make the code more modular.
4. **ES6 Features** – Support for ES6 features is also one of the main reasons for its popularity.
5. **Syntax** – TypeScript provides syntax which is closer to java and other high level languages (Syntactical Sugaring).

TypeScript Code cannot be interpreted by the Browser directly so there is a need to compile the TypeScript code into plain JavaScript Code, for this purpose we need the TypeScript Compiler (tsc).

### # TypeScript Compiler (tsc)

- Written in TypeScript itself.
- Compiles .ts files to .js files.
- Installed as an NPM package (NodeJS).
- Supports ES6 syntax.


| TypeScript | JavaScript |
| ---------- | ---------- |
| It is an Object Oriented Language (Class based) |	It is an Object Based Language (Prototype based) |
| Statically Typed language	| Dynamically Typed language |
| Supports Modules | Does not Support Modules |
| Provides Errors at Compile time / during development |	Doesn’t provide Compile time errors |
| Takes more time as the code needs to be Compiled |	No need of compilation |


### # Why is TypeScript gaining popularity ?

- JavaScript was initially developed to be a light weight easy to learn language mainly focusing on simple DOM manipulations but the standards changed with time and that is where TypeScript came into picture as it adds enhanced features to JavaScript.
- The support for Classes and Objects is also one of the main reasons for its increasing popularity as it makes it easier to understand and implement OOPS concepts as compared to the standard prototype based implementation provided by native JavaScript.
- Also the use of TypeScript in popular JavaScript Frameworks like Angular has helped TypeScript gain interest.


### # Why do we use TypeScript ?

- **Better developer experience** – One of the biggest advantages of TypeScript is to enable IDEs to provide a richer environment for spotting common errors as you type the code. For a large scale project adopting TypeScript might result in more robust software, while still being deployable where a regular JavaScript application would run.
- **Code quality** – Defining data structures in the beginning, using types and interfaces, forces you to think about your app’s data structure from the start and make better design decisions.
- **Prevents bugs** – TypeScript won’t make your software bug free. But it can prevent a lot of type-related errors. Along with the Clever IntelliSense many browsers and IDEs support direct debugging through Source Maps .
- **Active community** – TypeScript is getting more and more popular. It’s used by the top tech companies like Google, Airbnb, Shopify, Asana, Adobe, and Mozilla so we can assume that it reaches their expectations in terms of scalability – as they are developing large and complex applications.
- **TypeScript Is Just JavaScript** – TypeScript starts with JavaScript and ends with JavaScript. Typescript adopts the basic building blocks of your program from JavaScript. All TypeScript code is converted into its JavaScript equivalent for the purpose of execution.


**types.ts**
```ts
let myString: string;
  
myString = 'Hello from ts'
  
console.log(myString);
```

After Saving the above files we need to transpile the TypeScript Code. 

In the terminal, type the following command:

```bash
 tsc types.js (syntax : tsc filename). 
```

On successful compilation a JavaScript file with the same name and .js extension will be created i.e. types.js containing the transpiled code in the same directory. As discussed above TypeScript code is transpiled into standard JavaScript Code.

Generated JavaScript Code in **types.js** File:

**Javascript code**
```js
var myString;
myString = 'Hello from ts';
console.log(myString);
```


### # Why TypeScript is developed while having JavaScript?

When JavaScript was developed, the JavaScript development team introduced JavaScript as a client-side programming language. But as people were using JavaScript, developers also realized that JavaScript could be used as a server-side programming language. However, as JavaScript was growing, JavaScript code became complex and heavy. Because of this, JavaScript wasn’t even able to fulfill the requirement of an Object-Oriented Programming language. This prevented JavaScript from succeeding at the enterprise level as a server-side technology. So TypeScript was created by the development team to bridge this gap. 

#### Features of TypeScript:

- **TypeScript Code is converted into Plain JavaScript Code :** TypeScript code can’t be natively interpreted by browsers. So if the code was written in TypeScript, it gets compiled and converted into JavaScript. This process is known as Trans-piled. With the help of JavaScript code, browsers are able to read the code and display it.
- **JavaScript is TypeScript :** Whatever code is written in JavaScript can be converted to TypeScript by changing the extension from .js to .ts.
- **Use TypeScript anywhere :** TypeScript can be compiled to run on any browser, device, or operating system. TypeScript is not specific to any single environment.
- **TypeScript supports JS libraries :** With TypeScript, developers can use already existing JavaScript code, incorporate popular JavaScript libraries, or call the TS Code from native JavaScript code.


Difference between TypeScript and JavaScript:

- TypeScript is known as an Object-oriented programming language whereas JavaScript is a prototype-based language.
- TypeScript has a feature known as Static typing but JavaScript does not support this feature.
- TypeScript supports Interfaces but JavaScript does not.


| Feature |	TypeScript |	JavaScript |
| ------- | ---------- | ------------- |
| Typing | 	Provides static typing	| Dynamically typed |
| Tooling |	Comes with IDEs and code editors  |	Limited built-in tooling |
| Syntax |	Similar to JavaScript, with additional features |	Standard JavaScript syntax |
| Compatibility |	Backward compatible with JavaScript  |	Cannot run TypeScript in JavaScript files |
| Debugging |	Stronger typing can help identify errors |	May require more debugging and testing |
| Learning curve | 	Can take time to learn additional features | 	Standard JavaScript syntax is familiar |
 


### # Advantages of using TypeScript over JavaScript 

- TypeScript always points out the compilation errors at the time of development (pre-compilation). Because of this getting runtime errors is less likely, whereas JavaScript is an interpreted language.
- TypeScript supports static/strong typing. This means that type correctness can be checked at compile time. This feature is not available in JavaScript.
- TypeScript is nothing but JavaScript and some additional features i.e. ES6 features. It may not be supported in your target browser but the TypeScript compiler can compile the .ts files into ES3, ES4, and ES5 also.

### # Disadvantages of using TypeScript over JavaScript
- Generally, TypeScript takes time to compile the code.
