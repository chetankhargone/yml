# YAML 

Yaml stands for Ain't Markup Language. Originally it meant Yet Another Markup Language.
Yml is a human-reable data-serialization language.

### Usage
It is used to represent data.
Compare to Json/XML, it is more verbose & compact

### Data Types Supported
1. String
2. Number
3. boolean
4. Key Value Pair
5. Array/List
6. Dictionary/Map

### Notes
1. Whitespace indentation is used for denoting structure; however, tab characters are not allowed as part of indentation.
2. Comments begin with #
3. List members are denoted by a leading hyphen (-) with one member per line
4. Repeated notes are represented by "&" and then referenced using "*"


### Examples
---
a: 123 (integer)
b: "Test" (string)
c: 123.00 (float)
d: !!float 123 (float via explicit data type prefixed by !!)
e: !!str 123 (string via explicit type)
f: true (or false)
g: !myClass {name: Chetan, dob: "21-08-1989"} (Local data type. use a single exclamation mark !)


### Yaml Validator
- http://www.yamllint.com/
- https://codebeautify.org/yaml-validator


