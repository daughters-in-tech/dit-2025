# CSS Glossary

* [List of every possible CSS rule](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)

* [List of web colors](https://www.w3schools.com/colors/colors_names.asp)

* [List of web fonts](https://web.mit.edu/jmorzins/www/fonts.html)

# Selectors

Tag selectors are just the name of the tag you want to add styles to and look like this in CSS.

```
main {

}
```

And like this in the HTML

```
<main>
  Some content
</main>
```

## Class selectors (multiple elements)

In CSS create a class and add style rules

```
.my-class {
  background-color: #ff00ff;
  font-size: 12px;
}
```

Add your class to HTML

```
<div class="my-class">Div 1</div>
<div class="my-class">Div 2</div>
```

## ID selectors (one element)

Similar pattern to classes, but IDs are generally used for one specific element, while classes are for a group of elements.

In CSS:

```
#my-id {
  background-color: red;
  border-radius: 2px
}
```

Add your id to HTML

```
<div id="my-id">Stuff goes here</div>
```

## Properties + Values

| Properties                             | Values                                                                                                                                                                                                                                                                                                     |
| -------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `background-color`, `color`            | <ul><li>predefined names (`aqua`, `green`, `teal`, `maroon`, `purple`, `black`... <a href="https://www.w3schools.com/colors/colors_names.asp" target="_blank">see the full list here</a>.) </li><li>or use <a href="https://htmlcolorcodes.com/color-picker/" target="_blank">a color picker</a></li></ul> |
| `padding`, `margin`, `width`, `height` | <ul><li>pixels (`2px`)</li><li>percentages (`50%`)</li></ul>                                                                                                                                                                                                                                               |
| `text-align`                           | `left` (default), `center`, `right`                                                                                                                                                                                                                                                                        |

Some other properties that you can change are:

```
border
border-radius
font-size
font-family
font-weight
text-align
list-style
```

## Flexbox Tools

Listed below are the 5 properties and some of their values we went over during the lesson

### Properties + Values

| Properties        | Values                                                                                                                                                                                                                                          |
| ----------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `display`         | <ul><li><strong>flex</strong></li> <li>inline</li><li>none</li> <li>block</li> <li><a href="https://www.w3schools.com/cssref/pr_class_display.asp" target="_blank">See the full list and definitions here</a></li></ul>                                         |
| `flex-direction`  | <ul><li>row</li><li>row-reverse</li><li>column</li> <li>column-reverse</li><li><a href="https://www.w3schools.com/cssref/css3_pr_flex-direction.asp" target="_blank">See the full list and definitions here</a></li></ul>                                       |
| `justify-content` | <ul><li>flex-start</li><li>flex-end</li><li>center</li><li>space-around</li><li>space-evenly</li><li><a href="https://www.w3schools.com/cssref/css3_pr_justify-content.asp" target="_blank">See the full list and definitions here</a></li></ul>                |
| `align-items`     | <ul><li>center</li><li>stretch</li><li>flex-start</li><li>flex-end</li><li><a href="https://www.w3schools.com/cssref/css3_pr_align-items.asp" target="_blank">See the full list and definitions here</a></li></ul>                                              |
| `flex-wrap`       | <ul><li>wrap</li><li>nowrap</li><li>wrap-reverse</li><li><a href="https://www.w3schools.com/cssref/css3_pr_align-items.asp" target="_blank">See the full list and definitions here</a></li></ul>                                                                |

### Example of Flexbox:
```
.flex-row {
  display: flex; 
  flex-direction: row; 
  justify-content: space-around; 
}
```
## Responsive Design:

### Media Example:

```
@media screen and (max-width: 600px) {
 .example {
	display: none;
  }
}
```

### Relative Length Units:

Documentation can be found [here](https://www.w3schools.com/cssref/css_units.asp). Some examples include:

<ol>
  <li>vh - view height</li>
  <li>vw - view width</li>
  <li>% - percent</li>
  <li>rem - Relative to font-size of the root element</li>
  <li>em - Relative to the font-size of the element</li>
</ol>

You can only use these values on "length" properties, such as height, width, margin, padding, font-size, etc.

## Bootstrap Link:
Documentation and examples can be found [here](https://getbootstrap.com/docs/5.0/components/navbar/)