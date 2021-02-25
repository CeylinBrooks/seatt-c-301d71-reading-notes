Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data

Imagine we want to implement a function that calculates the area of a circle. An impure function would receive radius as the parameter, and then calculate radius * radius * PI

Pure functions are stable, consistent, and predictable. Given the same parameters, pure functions will always return the same result.

When data is immutable, its state cannot change after it’s created. If you want to change an immutable object, you can’t. Instead, you create a new object with the new value.

Here we have: toLowerCase: converts the string to all lower case trim: removes whitespace from both ends of a string split and join: replaces all instances of match with replacement in a given string We combine all these 4 functions and we can "slugify" our string.




https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa





