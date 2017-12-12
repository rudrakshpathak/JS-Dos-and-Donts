JavaScript is a wonderful scripting language and one of my favorite from many. JavaScript offers a wide variety of functionalities in a very easy to write and understandable syntax. No web application is complete without the use of JavaScript. JS plays a key role in web applications and it is must that we write correct JS and in a standard format in-order to avoid the mis-happenings and issues.

Based on the some good and bad experiences with JavaScript, I’ve compiled some of the points that one should consider while writing JavaScript for your next project.

## DO’s
- Always surround your source code in a `try/catch` block. Give preference to exception handling while performing critical tasks like I/O operations, dealing with files or making a `XHR` request.

- Always check your objects for `null` entries and your variables for `undefined`. And don’t just limit to that, for sake of robust code, check for function calls too.

- Use global objects instead of global variables. Use variables as a property of that global object.

- Always prefer to use `//` or double slash in the CDN urls or any 3rd party asset that you are loading via live URL.

- Use console functions appropriately. Like if you want to display a warning message, use `console.warn()`. And others like `console.info` and `console.error`.

- Use `" "` double quotes for string literals until unless there is a requirement for `' '`.

- Use `.on()` event handler as it saves memory and can handle dynamically generated elements.

- When there is a requirement for handling large chunk of common DOM elements on page, cache the reference of elements in a variable and use that variable to perform operations in-order to optimize the performance by reducing the lookup time.

- Use `this`, `callbacks`, and `closures`.

- Use `Prototyping` whenever required.

- Use `-` or dash separated files names.

- Use JsDoc comments at function level and use //for comments inside functions.

- Use `use strict` mode at file level.

- Declare constants in uppercase at the top of the file.

- If not sure with the value of variable, initialize it with null.

- Always assign a default value to function arguments. Doing this can save your code from halting execution in case any error occurs due to null entries.

- Use `localStorage` when need to persist the data and use `sessionStorage` when need to store data for a particular browser session.
undefined and null are two different things. Check for both.

- Use `lodash` library to perform operations on array, objects, looping in a highly optimized and easy to use syntax.

- Use `window.onerror = function(message, source, lineno, colno, error) { ... }` to suppress the errors and handle accordingly.
 

## DONT’s
- Avoid using features which are in beta mode and haven’t supported by all the browsers like ES6. Because these features may only work in webkit browsers and may crash in browsers like IE and Safari.

- Avoid trailing commas in arrays and objects. Internet Explorer doesn’t handles it well.

- Avoid making con-current XHR requests. IE doesn’t handles it well.

I’ll keep updating the post as I will have new things to add. Till then make sure you write a robust code and use JavaScript’s capabilities at fullest.
