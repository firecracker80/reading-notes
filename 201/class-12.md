# Reading Assignment 12

>## `<canvas>` Element
>
>It's similar to the `<img>` tag with a few differences. It contains height and width attributes, requires a closing tag, and uses DOM properties. Canvas isn't always compatible with all browsers, therefore fallback content may be required to display the desired information. It is added using the `<script>` tag in your HTML.
>
>*Grid*
>
>In canvas, one unit corresponds with 1 px. It onlys supports rectangles and paths. To create other shapes, you have to combine paths.
>
>*Color*
>
>To apply color to the drawn shapes, you have to use `fillStyle` and `strokeStyle`. The color returns as a string.
> - `fillStyle` - controls the color of the shape.
> - `strokeStyle` - controls the color of the outline or the shape.
>
>You can use rgba to set the transparency, because the "a" sets the transparency of the color when using either of these styles. Another way to set the tranparency is to use `globalAplpha`, very useful when drawing several shapes with the same transparency.
>
>*Draw Text*
>
>Draw and style text using `fillText` and `strokeText`. Canvas uses the same CSS syntax to accomplish this.

<br/>

## Things I want to know more about...

>What is the difference between `<canvas>` and CSS if they are using the same syntax?