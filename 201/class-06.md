# Reading Assignment 6

## Problem Domain

>The problem domain is information you gather from the client, that serves a guide to solving the problem.
>
>It can be solved by either making it easier or by understanding it. The key is to take the necessary time to address it, otherwise you may end up double the work for less.

<br/>

## Primitive Value vs Object References

>*Primitive value* is assigned directly to a variable; immutable.
>*Object reference* contains a variable that references a value; mutable.

<br/>

## Object Literals

>Def: a set of variables (property) and functions (methods) that are grouped together.
>
>Identify keys and separate each key from the value using a colon. To separate a property from a method use a comma.
>
>Access properties or methods by using a dot notation or square brackets (ex. object.property; `object ['property']`)
> - Most commonly used when the method or property contains special characters, the property is a number, or when using a variable instead of a property name.

<br/>

## Document Object Model (DOM)

>Basically the modelof a page that is stored in the browser's memory.
>
>Four types:
> - Document node - the starting point and represents the entire page.
> - Element node - just that, specifically HTML elements.
> - Attribute node - these are attributes carried by the element, but are not children of that element. They are a part of the element.
> - Text node - the text within the element; can't have children, if the element contains achild element and text, the child element belongs to the containing element.
>
>DOM queries are methods that help find elememts within the DOM tree.