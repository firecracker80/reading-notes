# CSS (Cascading Style Sheets)

> ## What is CSS?
>
 > CSS controls how HTML looks like in the browser. it's the style, how it's laid out, and even animation. Basically, the asthetics.
 >
 >It is a rule-based language, rule defined by you.
 > - Ex. 'h1{color: red; 
          font-size: 5em}' (*em=px)
> - It contains properties and values.
>   - Color and font-size are properties.
>   - The shade or color and size units are the values.
>
><br/>
>
> ## Three Ways to Insert CSS
>
> - External - allows you to change the entire website by changing one file.
>   - Ex. 
>       - '</link rel="stylesheet" href="mystyle.css">'
> You can use any text editor, but must save the file with a .css extension.
>
> - Internal - can be used if the a single HTML page has a specific style, and is defined by the '</style>' element within the head.
>
> - Inline - this is used to apply a specific style to one element. you can do this by adding the style attribute to the element in question.
>
> <br/>
>
> ## Multiple Style Sheets
>
> If you have multiple styles sheets in the same element, the last read style sheet is the one it will be used.
>
><br/>
>
> ## Cascading Order
>
>Rules:
> 1. Inline style (inside an HTML element)
> 2. External and internal style sheets (head section)
> 3. Browser (default)
