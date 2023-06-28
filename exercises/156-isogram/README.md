# `156` isIsogram

## 📝 Instructions:

1. The function `isIsogram` receives a string and returns `true` if the string is an isogram, otherwise it returns `false`.

## 📎 Example:

```js
console.log(isIsogram("Camile")); // --> true
console.log(isIsogram("Camille")); // --> false
```

## 💡 Hints:

+ An **isogram** is a word that has no repeating letters, consecutive or non-consecutive. 

+ Suppose your input string has only letters (no spaces).

+ Suppose that an empty string is an isogram.

+ Ignore letter casing.

+ You can begin by adding each character to a `new Set()` https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Set
