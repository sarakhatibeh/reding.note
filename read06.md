# JavaScript

JavaScript (JS) is a lightweight, interpreted, or just-in-time compiled programming language with first-class functions. While it is most well-known as the scripting language for Web pages, many non-browser environments also use it, such as Node.js, Apache CouchDB and Adobe Acrobat. JavaScript is a prototype-based, multi-paradigm, single-threaded, dynamic language, supporting object-oriented, imperative, and declarative (e.g. functional programming) styles. 

### Introducing JavaScript objects
In JavaScript, most things are objects, from core JavaScript features like arrays to the browser APIs built on top of JavaScript. You can even create your own objects to encapsulate related functions and variables into efficient packages and act as handy data containers. The object-based nature of JavaScript is important to understand if you want to go further with your knowledge of the language, therefore we've provided this module to help you. Here we teach object theory and syntax in detail, then look at how to create your own objects

### JavaScript data types and data structures

Dynamic typing
JavaScript is a loosely typed and dynamic language. Variables in JavaScript are not directly associated with any particular value type, and any variable can be assigned (and re-assigned) values of all types:

Data and Structure types
The latest ECMAScript standard defines nine types:

### Six Data Types that are primitives, checked by typeof operator:

undefined : typeof instance === "undefined"

Boolean : typeof instance === "boolean"

Number : typeof instance === "number"

String : typeof instance === "string"

BigInt : typeof instance === "bigint"

Symbol : typeof instance === "symbol"

### Structural Types:
Object : typeof instance === "object". Special non-data but Structural type for any constructed object instance also used as data structures: new Object, new Array, new Map, new Set, new WeakMap, new WeakSet, new Date and almost everything made with new keyword;

Function : a non-data structure, though it also answers for typeof operator: typeof instance === "function". This is merely a special shorthand for Functions, though every Function constructor is derived from Object constructor.

### Structural Root Primitive:
null : typeof instance === "object". Special primitive type having additional usage for its value: if object is not inherited, then null is shown

### JavaScript Variables

JavaScript variables are containers for storing data values.

In this example, x, y, and z, are variables, declared with the var keyword:

### JavaScript Data Types
JavaScript variables can hold numbers like 100 and text values like "John Doe".

In programming, text values are called text strings.

JavaScript can handle many types of data, but for now, just think of numbers and strings.

Strings are written inside double or single quotes. Numbers are written without quotes.

If you put a number in quotes, it will be treated as a text string.

### JavaScript Arithmetic
As with algebra, you can do arithmetic with JavaScript variables, using operators like = and +


### JavaScript Dollar Sign $
Remember that JavaScript identifiers (names) must begin with:

A letter (A-Z or a-z)
A dollar sign ($)
Or an underscore (_)
Since JavaScript treats a dollar sign as a letter, identifiers containing $ are valid variable names