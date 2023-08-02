- [Zero Value](#zero-value)
- [Literal](#literal)
  - [Integer literal](#integer-literal)
  - [Floating point literal](#floating-point-literal)
  - [Rune literal](#rune-literal)
  - [String literal](#string-literal)
- [Types](#types)
  - [Booleans](#booleans)
  - [Numeric Types](#numeric-types)
    - [Integer types](#integer-types)
    - [Floating point types](#floating-point-types)
  - [String and Rune](#string-and-rune)
- [Type Conversion](#type-conversion)


# Zero Value
Go assign a default zero-value to any variable that is declared but not assign a value. It assign every bit of that variable to zero.

# Literal
A literal in Go refer to writing out number, character or string and there are four common kinds of literal
## Integer literal
any integer number such as `1` or `0x3`
## Floating point literal
any number that has decimal point such as `1.231` or `6.3e4`
## Rune literal
represent characters and are surrounded by single quotes. Rune literals can be written as single Unicode characters ('a') or other format such as octal numbers, hexadecimal numbers, hexadecimal numbers or 32-bit Unicode numbers.
## String literal
there are two different ways to indicate string literal which are using Double Quote "Peace" or Backquote \`Peace\` for raw string literal.

---
# Types

## Booleans
Can be true or false and the zero-value is false

## Numeric Types
### Integer types
this is a integer value such as int, uint, int8,uint8 and up to int64. By default, use int or uint and Go will decide whether int will become int32 or int64 based on CPU.
### Floating point types
a number with decimal points which are these two types `float32` and `float64`
## String and Rune
String zero value is the empty string. We can put any Unicode character into a string. We compare string quality by using `==` and `!=`, or ordering with `>`, `>=`, `<`, `<=`. They are concatenated by using `+`.
> ⚠️ String in Go are immutable, you can reassign the value of a string variable, but you cannot change the value of the string that is assigned to it. Basically you can't not change character at N index of any string variable, you need to reassign the value to the variable.

The `rune` type is an alias for the `int32` type just like `byte` is an alias for `uint8`.

>💡 if you are referring to a character, use the rune type not int32

# Type Conversion
TODO: write the detail