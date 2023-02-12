# Tez-Lang
A Functional Programming Lnaguage.

[中文在这里 Chinese](./看我.md)

> It has nothing to do with Apache Tez. I hadn't heard of Tez at all when I was developing it, and I didn't expect a rename. I'm too lazy to change it now. Let's just call it that and add a "-lang" to it. I made the name up randomly.

Tezlang is a functional programming language written in *pure python*.  
Its syntax is a little bit similar to `lisp` but with square brackets instead of round brackets

# Hello, world!
```
[put "Hello, world! \n"]
```
The put function in Tezlang is similar to printf in the C programming language  
although I didn't do formatted output

# Comments
```
// This is a line of comments
//. This is also a line of comments
   This is still a line of comments
   They are all comments. /.
```
Comments in Tezlang start with `//`; starts with `/.` and ends with `./` ending (nesting is not supported at this time)

# Operators
```
[+ 5 2] // add
[- 5 2] // subtract (if there is only one argument, it takes the opposite number)
[/ 5 2] // divide
[* 5 2] // multiply
[/- 5 2] // divide by whole (delete the decimal part after the division)
[/+ 5 2] // divide by whole (delete the fractional part after dividing and round up to the whole number)
```


Download:
> [tezlang.exe](./dist/tezlang.exe)
