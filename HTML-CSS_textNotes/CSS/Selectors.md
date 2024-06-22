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
    color: white;
}
```
<br>

#### Id Selectors

The identity selector is unique. That means it can't be used to target the multiple entities as in class. It matches an element that has the specified unique identity. To match the specific indentity attribute, the pound or hash symbol is used to indicate for identity selection followed by the identity name to target upon.

For Example, if one wants to give an element of an identity named 'identity1' to have a text color green, the one can follow:

```
#identity1 {
    color: green;
}
```
<br>

#### Child Selectors

It matches an element that is an immediate child of another element.

For Example, if one wants all emphasized text in paragraphs to have a certain color (suppose orchid), but not emphasized text in any other elements, then the one can follow:

```
p > em {
    color: orchid;
}
```
<br>

#### Adjacent-sibling Selectors

It matches an element that is an immediately after (adjacent) the another element element, but not a child of it.

For Example, if one wants all paragraphs that immediately followed an h3 to have a certain color (suppose orange), but not other paragraphs, then the one can follow:

```
h3 + p {
    color: orange;
}
```
<br>

#### Pseudo Selectors

These selectors come in variety of shapes and sizes. The most common pseudo selectors are used for links-styling. There are four primary states of a link are: link, visited, hover, and active.

<b>:link -</b> A link that has not been previously visited (visited is defined by the browser history)

<b>:visited -</b> A link that has been visited

<b>:hover -</b> A link that that mouse cursor is "hovering" over

<b>:active -</b> A link that is currently being clicked

For Example, if one wants certain unvisited links to be visible in red color, visited links in blue, green during hovering over links, and for active links be lime, then one can follow:

```
a:link {
    color: red; // for unvisited links
}

a:visited {
    color: blue; // for visited links
}

a:hover {
    color: green; // links upon hovering
}

a:active {
    color: lime; // for active links
}
```
<br>

#### Universal Selector

It matches every element on the page.

For Example, if one wants every element to have a solid blue border of 1px, then the one can follow:

```
* {
    border: 1px solid blue;
}
```
