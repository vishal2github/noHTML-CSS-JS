## Selectors


### Purpose

The CSS selectors are used to select the class and identity elements of the html code for implementation of several CSS rules upon them.


### Theory

To select the class element, the **period symbol '.'** is used following the class name. Similarly for the identity element, the **pound or hash sign '#'** is used following the identity name.

Some of the most common, major and well-supported CSS selectors are:

+ Element Type Selectors
+ Descandant Selectors
+ Class Selectors
+ Id Selectors
+ Child Selectors
+ Adjacent Sibling Selectors
+ Pseudo Selectors
+ Universal Selectors

<br>

#### Element Type Selectors

It's the most basic type of CSS selector. This selector generally targets/used upon the basic elements of html, like, paragraph, head, image element, etc.

For Example, if one wants to make all the paragraphs text to be appear in certain color, then one can use:

```
p {
    color: red;
}
```
<br>

#### Descendant Selectors

It matches an element that is descandant of another element. In simpler terms, basically the children elements of the parent element is targetted/selected and the properties are used upon that children element of the parent element.

For Example, if a paragraph element has one bold element inside it, then the former one is the parent and later one is the child element, then one can use to apply any CSS property on the child element via parent element like:

```
p bold {
    color: purple;
}
```
<br>

#### Class Selectors

It matches an element that has the specified class. To match the specific class attribute, the period symbol is used to indicate for class selection followed by the class name to target upon.

For Example, if one wants to give all the elements of a class named 'blue-bg' to have a blue background color with text color white, then one can follow:

```
.blue-bg {
    background-color: blue;
    text-color: white;
}
```
<br>

#### Id Selectors

The identity selector is unique. That means it can't be used to target the multiple entities as in class. It matches an element that has the specified unique identity. To match the specific indentity attribute, the pound or hash symbol is used to indicate for identity selection followed by the identity name to target upon.

For Example, if one wants to give an element of an identity named 'identity1' to have a text color green, the one can follow:

```
#identity1 {
    text-color: green;
}
```