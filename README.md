# SimpleArrayCheck
A simple alternative to is Array

Alternatively one could `const checkArray = (arr) => Array.prototype.isPrototypeOf(arr);`
or 
Like this (However this code somehow has a troll MIT license, under the project isArray)
`const checkArray = (arr) => Object.prototype.toString.call(arr) === '[object Array]';` 

