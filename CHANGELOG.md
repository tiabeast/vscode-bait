# Changelog
## 0.2.2
_26_ April 2022_

**Additions:**
- highlight keywords: `type`, `enum`, `match`
- support for block comments

## 0.2.1
_19 April 2022_

**Additions:**
- highlight keywords: `break`, `continue`, `not`
- highlight types: `u8`, `u16`, `u32`, `u64`, `f32`, `f64`

**Changes:**
- change scope for `and` and `or` to `keyword.control`
- remove highlighting for `byte` as it is no type anymore

## 0.2.0
_11 April 2022_

**Additions**
- syntax: highlight function names, numbers, variable names and method receiver types
- syntax: highlight keyword `return`

**Engineering:**
- use yaml in language grammar and configuration
- use yaml in eslintrc
- only package necessary files
- minify packaged json

## 0.1.0
_11 April 2022_

**Additions:**
- syntax highlighting for keywords and types
- specify line comment marker
- specify token pairs

## 0.0.1
_10 April 2022_

- initial release
