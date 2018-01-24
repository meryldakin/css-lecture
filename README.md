# OBJECTIVES

Become familiar with CSS and Frameworks that make styling web applications faster and easier

Things to cover:

* What is HTML?
Hypertext Markup Language - HTML is the language for describing the structure of Web pages

* What is CSS?
Cascading Style Sheets - describes how HTML elements are to be displayed on screen

* CSS Formats
  - inline
  - internal
  - external

* Selectors
  ** Element Type
    - Ex. p {…}
  ** Id
    - Ex. #box {…}
  ** Class
    - Ex. .thick {…}

* Selectors Continued
  ** Descendent
   - Ex. #nav li {…}
  ** Child
   - Ex. #list > li {…}
  ** Sibling
   - Ex. h3 + p {…}
  ** Preceded
 ta  - Ex. .styleafter ~ h2 {…}

* Authority and Inheritance rules
If you use conflicting styles on the same element, ID over rules Class which over rules Element Type which over rules * (universal). Generally the more specific a selector the more authority it has. If a more specific selector is not defined for an element it will inherit styles from a previously defined general selector statement.

For Example - If multiple Classes are applied to the same element, the Class described last in the CSS file overrules
