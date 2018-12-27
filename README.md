# Ozelot
### Yet another programming language for Minecraft

This is the official specification of the Ozelot programming language. 

## Formatting
### Source code Files
* Ozelot source code is stored in UTF-8 encoded text files with the file extension '`.ozl`'.

### Identifiers
* A valid identifier is composed by a letter or underscore and eventually followed by multiple letters, underscores or digits.
  
* A charcater is considered a letter if it is a member of the Unicode character Category 'UPPERCASE_LETTER', 'LOWERCASE_LETTER', 'TITLECASE_LETTER', 'MODIFIER_LETTER' or 'OTHER_LETTER'.

### Whitespace and Tokenization
* Tokens are seperated by whitespace or boundaries between words and symbols or symbols themselves.
  
* Whitespace is considered every symbol which is not an identifier or part of another token. Thus indentation style or line endings are irrelevant.

## File structure
A Ozelot souce code file is composed of multiple elements which lie in the top level scope:

* Function declarations

* Constant declarations

* Import statements

* Export statements

* Event registration

* Build statements

These elements are **hoisted**, i.e. a function can be declared or imported after it is called.
## Variables
TODO
## Constants
TODO
## Expressions
TODO
## Flow Control
TODO
## Functions
### Declaration

### Building
TODO
## Libraries and Imports
TODO 
### Importing

### Exporting

## Events
TODO

