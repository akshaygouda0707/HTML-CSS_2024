# CSS_2024 Learning
# What is CSS?

Like HTML, CSS is not a programming language. It's not a markup language either. CSS is a style sheet language. CSS is what you use to selectively style HTML elements. For example, this CSS selects paragraph text, setting the color to red:
```css
p {
  color: red;
}
```
Let's try it out! Using a text editor, paste the three lines of CSS (above) into a new file. Save the file as `style.css` in a directory named `styles`.

Open your **`index.html`** file. Paste the following line in the head (between the `<head>` and `</head>` tags):

```css
<link href="styles/style.css" rel="stylesheet" />
```
Save **`index.html`** and load it in your browser. You should see something like this:





If your paragraph text is `red`, congratulations! Your CSS is working.


# Anatomy of a CSS ruleset
Let's dissect the CSS code for red paragraph text to understand how it works:


The whole structure is called a **`ruleset`**. (The term ruleset is often referred to as just rule.) Note the names of the individual parts:


#### Selector
This is the HTML element name at the start of the ruleset. It defines the element(s) to be styled (in this example, `<p>` elements). To style a different element, change the selector.

#### Declaration
This is a single rule like `color: red;`. It specifies which of the element's properties you want to style.

#### Properties
These are ways in which you can style an HTML element. (In this example, `color` is a property of the `<p>` elements.) In CSS, you choose which properties you want to affect in the rule.

#### Property value
To the right of the property—after the colon—there is the property value. This chooses one out of many possible appearances for a given property. (For example, there are many `color` values in addition to `red`.)


#### Note the other important parts of the syntax:

- Apart from the selector, each ruleset must be wrapped in curly braces. (`{}`)
- Within each declaration, you must use a colon (`:`) to separate the property from its value or values.
- Within each ruleset, you must use a semicolon (`;`) to separate each declaration from the next one.


To modify multiple property values in one ruleset, write them separated by semicolons, like this:

```css

p{
    color: red;
    width: 500px;
    border: 1px solid black;
    text-align: justify;
    margin-left: 50px;
}


```

## Selecting multiple elements
You can also select multiple elements and apply a single ruleset to all of them. Separate multiple selectors by commas. For example:

```css
p,
li,
h1 {
  color: red;
}
```

## Different types of selectors

There are many different types of selectors. The examples above use element selectors, which select all elements of a given type. But we can make more specific selections as well. Here are some of the more common types of selectors:

|Selector name	 | What does it select	 | Example |
|-----------------|-----------------|-----------------|
| Element selector (sometimes called a tag or type selector)   | All HTML elements of the specified type.    | p selects `<p>`   |
| ID selector   | The element on the page with the specified ID. On a given HTML page, each id value should be unique.    | `#my-id` selects `<p id="my-id">` or `<a id="my-id"> `  |
| Class selector	   | The element(s) on the page with the specified class. Multiple instances of the same class can appear on a page   | .my-class selects `<p class="my-class">` and `<a class="my-class"`>  |
| Attribute selector   | The element(s) on the page with the specified attribute.   | `img[src]` selects `<img src="myimage.png">` but not `<img> `  |
| Pseudo-class selector	| The specified element(s), but only when in the specified state. |`a:hover` selects `<a>`, but only when the mouse pointer is hovering over the link.  |

There are more  [selectors](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Selectors)


# Font And Texts
First, find the output from Google Fonts that you previously saved from What will your website look like?. Add the `<link>` element somewhere inside your `index.html's` head (anywhere between the `<head>` and `</head>` tags). It looks something like this:


```html
<link
  href="https://fonts.googleapis.com/css?family=Open+Sans"
  rel="stylesheet" />
```

CSS layout is mostly based on the `box model`. Each box taking up space on your page has properties like:

- `padding`, the space around the content. In the example below, it is the space around the - paragraph text.
- `border`, the solid line that is just outside the padding.
- `margin`, the space around the outside of the border.


[![Box Model](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics/box-model.png)](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics/box-model.png)

In this section we also use:

`width` (of an element).
`background-color`, the color behind an element's content and padding.
`color`, the color of an element's content (usually text).
`text-shadow` sets a drop shadow on the text inside an element.
`display` sets the display mode of an element. (keep reading to learn more)

# Changing the page color

```css
html {
  background-color: #00539f;
}
```

# Styling the body
```css
body {
  width: 600px;
  margin: 0 auto;
  background-color: #ff9500;
  padding: 0 20px 20px 20px;
  border: 5px solid black;
}
```
