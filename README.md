# JavaScript Basics Quiz

???

JavaScript Basics Quiz

Variables

?: If we declare a variable, `let test = 1`, then later, reassign, stating `test = 2`, what will happen?

(X) `test` will equal `2` ( ) `test` will equal `1` ( ) JavaScript will raise a TypeError ( ) `test` will equal `undefined`

?: If we declare a variable, `const test = 1`, then later, reassign, stating `test = 2`, what will happen?

( ) `test` will equal `2` ( ) `test` will equal `1` (X) JavaScript will raise a TypeError ( ) `test` will equal `undefined`

?: If we declare a variable, `let test = 1`, then later, reassign, stating `var test = 2`, what will happen?

( ) both variables will be declared (X) JavaScript will raise a SyntaxError ( ) `var test` will reassign `let test` ( ) `var test` will be ignored as `test` is already declared

?: If we declare a variable, `var test = 1`, then later, reassign, stating `var test = 2`, what will happen?

( ) both variables will be declared ( ) JavaScript will raise a SyntaxError (X) `var test = 2` will reassign `var test = 1` ( ) `var test` will be ignored as `test` is already declared

?: If we declare a variable, `var test = 1`, then later, reassign, stating `var test = 2`, what will happen?

( ) both variables will be declared ( ) JavaScript will raise a SyntaxError (X) `var test = 2` will reassign `var test = 1` ( ) `var test` will be ignored as `test` is already declared

?: What are the main differences between `let` and `const`?

(X) `let` can be reassigned, `const` cannot be reassigned ( ) `let` cannot be reassigned, `const` can be reassigned ( ) `let` is functional scope, while `const` is block scope ( ) `let` is block scope, while `const` is functional scope

Comparisons

?: The `!=` and `!==` symbols both work the same for inequality comparisons:

( ) True (X) False

?: For strict equality comparisons, we should use:

( ) `=` ( ) `==` (X) `===`

?: The expression `8 >= 8` evaluates to:

(X) True ( ) False

?: The expression `8 > 8` evaluates to:

( ) True (X) False

?: The expression `8 === "8"` evaluates to:

( ) True (X) False

?: The expression `8 == "8"` evaluates to:

(X) True ( ) False

Conditionals

?: What will the return value of the following expression be?

```js
if (5 > 0) {
  return true;
} else {
  return false;
}
```

(X) `true` ( ) `false`

?: What will the return value of the following expression be?

```js
if !(10 > 5) {
  return true;
} else {
  return false;
}
```

( ) `true` (X) `false`

?: What will the return value of the following expression be?

```js
let str = "hello"
if (!!str) {
  return true;
} else {
  return false;
}
```

(X) `true` ( ) `false`

?: What will the return value of the following expression be?

```js
if (NaN) {
  return true;
} else {
  return false;
}
```

( ) `true` (X) `false`

?: What will the return value of the following expression be?

```js
if (typeof NaN) {
  return true;
} else {
  return false;
}
```

(X) `true` ( ) `false`

?: What will the value of `str` be after the following expression runs?

```js
let str = "hello"
if (0 > 5) {
  str = "world"
}
```

(X) `"hello"` ( ) `"world"` ( ) `undefined` ( ) `null`

Functions

?: What will be the value of `result` when this code is run and the function, `quizFunction`, is called with the input of `5`?

```js
function quizFunction(argument) {
  return argument
}

const result = quizFunction(5);
```

( ) `argument` ( ) `"5"` ( ) `"argument"` (X) `5`

?: What will be the value of `result` when this code is run and the function, `quizFunction`, is called with the input of `10`?

```js
function quizFunction(argument) {
  return argument/2
}

const result = quizFunction(10);
```

( ) `argument/2` (X) `5` ( ) `"argument/2"` ( ) `10/2`

?: What will be the value of `result` when this code is run and the function, `quizFunction`, is called with the input of `10`?

```js
function quizFunction(argument) {
  if (argument < 5) {
    return true
  }
  return false
}

const result = quizFunction(10);
```

( ) `argument < 5` ( ) `true` ( ) `10` (X) `false`

?: What will be the value of `result` when this code is run and called with the input of `5`?

```js
function triple(argument) {
  return argument * 3
}

function minusTwo(argument) {
  return argument - 2
}

const result = triple(minusTwo(5));
```

(X) `9` ( ) `13` ( ) TypeError ( ) `undefined`

?: What about if we flipped the order of the same functions?

```js
function triple(argument) {
  return argument * 3
}

function minusTwo(argument) {
  return argument - 2
}

minusTwo(triple(5));
```

( ) `9` (X) `13` ( ) TypeError ( ) `undefined`

???

View [JavaScript Basics Quiz](https://github.com/learn-co-curriculum/js-basics-javascript-basics-quiz) on Learn.co and start learning to code for free.
