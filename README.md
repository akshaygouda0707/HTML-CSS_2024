# Html_2024
## What is HTML?
- HTML stands for Hyper Text Markup Language
- HTML is the standard markup language for creating Web pages
- HTML describes the structure of a Web page
- HTML consists of a series of elements
- HTML elements tell the browser how to display the content
- HTML elements label pieces of content such as "this is a heading", "this is a paragraph", "this is a link", etc.

# A Simple HTML Document
```html
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
```
### Example Explained
- The `<!DOCTYPE html>` declaration defines that this document is an HTML5 document
- The `<html>` element is the root element of an HTML page
- The `<head>` element contains meta information about the HTML page
- The `<title>` element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab)
- The `<body>` element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.
- The `<h1>` element defines a large heading
- The `<p>` element defines a paragraph.

# What is an HTML Element?
An HTML element is defined by a start tag, some content, and an end tag:
```html
<tagname> Content goes here... </tagname>
```
The HTML `element` is everything from the start tag to the end tag:
```html
<h1>My First Heading</h1>
<p>My first paragraph.</p>
```

| Start tag | Element content | End tag |
| --------- | --------------- | ------- |
| `<h1>`    | My First Heading| `</h1>`|
| `<p>`     | My first paragraph. | `</p>`|
| `<br>`    | none            | none    |

# Nested HTML Elements
HTML elements can be nested (this means that elements can contain other elements).

All HTML documents consist of nested HTML elements.

The following example contains four HTML elements (`<html>`, `<body>`,` <h1>` and `<p>`):

Example
```htm
<!DOCTYPE html>
<html>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
```
Example Explained
The `<html>` element is the root element and it defines the whole HTML document.

It has a start tag <html> and an end tag `</html>`.

Then, inside the `<html>` element there is a `<body>` element:
```htm
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
```
The `<body>` element defines the document's body.

It has a start tag `<body>` and an end tag `</body>`.

Then, inside the `<body>` element there are two other elements: `<h1>` and `<p>` :
```htm
<h1>My First Heading</h1>
<p>My first paragraph.</p>
```
The `<h1>` element defines a heading.

It has a start tag `<h1>` and an end tag `</h1>`:
```htm
<h1>My First Heading</h1>
```
The `<p>` element defines a paragraph.

It has a start tag `<p>` and an end tag `</p>`:
```htm
<p>My first paragraph.</p>
```
Never Skip the End Tag
Some HTML elements will display correctly, even if you forget the end tag:

Example
```htm
<html>
<body>

<p>This is a paragraph
<p>This is a paragraph

</body>
</html>
```
# Empty HTML Elements
HTML elements with no content are called empty elements.

The `<br>` tag defines a line break, and is an empty element without a closing tag:

Example
```htm
<p>This is a <br> paragraph with a line break.</p>
```

# Web Browsers
The purpose of a web browser (Chrome, Edge, Firefox, Safari) is to read HTML documents and display them correctly.

A browser does not display the HTML tags, but uses them to determine how to display the document:
![Chrome Logo](https://www.w3schools.com/html/img_chrome.png)

# HTML Page Structure
Below is a visualization of an HTML page structure:
![Attribute Tuning HTML](https://bpdocs.blueprism.com/bp-7-0/en-us/Resources/Images/img-attribute-tuning/attribute-tuning-html.png)

# HTML Editors
# Learn HTML Using Notepad or TextEdit
Web pages can be created and modified by using professional HTML editors.

However, for learning HTML we recommend a simple text editor like Notepad (PC) or TextEdit (Mac).

We believe that using a simple text editor is a good way to learn HTML.

Follow the steps below to create your first web page with Notepad or TextEdit.

# Step 1: Open Notepad (PC)
Windows 8 or later:

Open the Start Screen (the window symbol at the bottom left on your screen). Type Notepad.

Windows 7 or earlier:

Open Start > Programs > Accessories > Notepad
# Step 1: Open TextEdit (Mac)
Open Finder > Applications > TextEdit

Also change some preferences to get the application to save files correctly. In Preferences > Format > choose "Plain Text"

Then under "Open and Save", check the box that says "Display HTML files as HTML code instead of formatted text".

Then open a new document to place the code.

# Step 2: Write Some HTML
Write or copy the following HTML code into Notepad:

```htm

<!DOCTYPE html>
<html>
<body>

<h1>My First Heading</h1>

<p>My first paragraph.</p>

</body>
</html>
```
![Chrome Logo](https://www.w3schools.com/html/img_notepad.png)


# Step 3: Save the HTML Page
Save the file on your computer. Select File > Save as in the Notepad menu.

Name the file "index.htm" and set the encoding to UTF-8 (which is the preferred encoding for HTML files).

![Chrome Logo](https://www.w3schools.com/html/img_saveas.png)

# Step 4: View the HTML Page in Your Browser
Open the saved HTML file in your favorite browser (double click on the file, or right-click - and choose "Open with").

The result will look much like this:

![chrome](https://www.w3schools.com/html/img_chrome.png)

# HTML Basic Examples

## HTML Documents
All HTML documents must start with a document type declaration: `<!DOCTYPE html>`.

The HTML document itself begins with `<html>` and ends with `</html>`.

The visible part of the HTML document is between `<body>` and `</body>`.

```htm
<!DOCTYPE html>
<html>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
```
# The <!DOCTYPE> Declaration
The `<!DOCTYPE>` declaration represents the document type, and helps browsers to display web pages correctly.

It must only appear once, at the top of the page (before any HTML tags).

The `<!DOCTYPE>` declaration is not case sensitive.

The `<!DOCTYPE>` declaration for HTML5 is:
```htm
<!DOCTYPE html>
```

# HTML Headings
HTML headings are defined with the `<h1>` to `<h6>` tags.

`<h1>` defines the most important heading. `<h6>` defines the least important heading: 
```htm
<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
```
# HTML Paragraphs
HTML paragraphs are defined with the `<p>` tag:

Example
```htm
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>
```
# HTML Links
HTML links are defined with the `<a>` tag:
Example
```htm
<a href="https://www.w3schools.com">This is a link</a>
```
The link's destination is specified in the href attribute. 

Attributes are used to provide additional information about HTML elements.

# HTML Images
HTML images are defined with the `<img>` tag.

The source file `(src)`, alternative text `(alt)`,`width`, and `height` are provided as attributes:

Example
```htm
<img src="w3schools.jpg" alt="W3Schools.com" width="104" height="142">
```
# HTML Attributes
- All HTML elements can have attributes
- Attributes provide additional information about elements
- Attributes are always specified in the start tag
- Attributes usually come in name/value pairs like: `name="value"`
  
The `href` Attribute
The `<a>` tag defines a hyperlink. The `href` attribute specifies the URL of the page the link goes to:

Example
```htm
<a href="https://www.w3schools.com">Visit W3Schools</a>
```
# The src Attribute
The `<img>` tag is used to embed an image in an HTML page. The `src` attribute specifies the path to the image to be displayed:

Example
```htm
<img src="img_girl.jpg">
```

1. Absolute URL - Links to an external image that is hosted on another website. Example: src="https://www.w3schools.com/images/img_girl.jpg".

Notes: External images might be under copyright. If you do not get permission to use it, you may be in violation of copyright laws. In addition, you cannot control external images; it can suddenly be removed or changed.

2. Relative URL - Links to an image that is hosted within the website. Here, the URL does not include the domain name. If the URL begins without a slash, it will be relative to the current page. Example: src="img_girl.jpg". If the URL begins with a slash, it will be relative to the domain. Example: src="/images/img_girl.jpg".

# The width and height Attributes
The `<img>` tag should also contain the `width` and `height` attributes, which specify the width and height of the image (in pixels):

Example
```img
<img src="img_girl.jpg" width="500" height="600">
```
# The alt Attribute
The required `alt` attribute for the `<img>` tag specifies an alternate text for an image, if the image for some reason cannot be displayed. This can be due to a slow connection, or an `error` in the src attribute, or if the user uses a screen reader.

Example
```htm
<img src="img_girl.jpg" alt="Girl with a jacket">
```
# The style Attribute
The `style` attribute is used to add styles to an element, such as `color`, `font`, `size`, and more.

Example
```html
<p style="color:red;">This is a red paragraph.</p>
```
# The lang Attribute
You should always include the `lang` attribute inside the `<html>` tag, to declare the language of the Web page. This is meant to assist search engines and browsers.

The following example specifies English as the language:
```htm
<!DOCTYPE html>
<html lang="en">
<body>
...
</body>
</html>
```

# The title Attribute
The `title` attribute defines some extra information about an element.

The value of the `title` attribute will be displayed as a tooltip when you mouse over the element:

Example
```htm
<p title="I'm a tooltip">This is a paragraph.</p>
```
# Always Quote Attribute Values
- Good:
```htm
<a href="https://www.w3schools.com/html/">Visit our HTML tutorial</a>
```
- Bad:
```htm
<a href=https://www.w3schools.com/html/>Visit our HTML tutorial</a>
```
# Single or Double Quotes?
Double quotes around attribute values are the most common in HTML, but single quotes can also be used.
```htm
<p title='John "ShotGun" Nelson'>
//Or vice versa:

<p title="John 'ShotGun' Nelson">
```
# HTML Headings
HTML headings are titles or subtitles that you want to display on a webpage.

HTML headings are defined with the `<h1>` to `<h6>` tags.

`<h1>` defines the most important heading. `<h6>` defines the least important heading.

Example
```htm
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```
# Bigger Headings
Each HTML heading has a default size. However, you can specify the `size` for any heading with the `style` attribute, using the CSS `font-size` property:

Example
```htm
<h1 style="font-size:60px;">Heading 1</h1>
```
# HTML Paragraphs
The HTML `<p>` element defines a paragraph.

A paragraph always starts on a new line, and browsers automatically add some white space (a margin) before and after a paragraph.

Example
```htm
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>
```
# HTML Horizontal Rules
The `<hr>` tag defines a thematic break in an HTML page, and is most often displayed as a horizontal rule.

The `<hr>` element is used to separate content (or define a change) in an HTML page:

Example
```htm
<h1>This is heading 1</h1>
<p>This is some text.</p>
<hr>
<h2>This is heading 2</h2>
<p>This is some other text.</p>
<hr>
```
# HTML Line Breaks
The HTML `<br>` element defines a line break.

Use `<br>` if you want a line break (a new line) without starting a new paragraph:

Example
```htm
<p>This is<br>a paragraph<br>with line breaks.</p>
```
The `<br>` tag is an `empty tag`, which means that it has no end tag.

# The HTML <pre> Element
The HTML `<pre>` element defines preformatted text.

The text inside a `<pre>` element is displayed in a fixed-width font (usually Courier), and it preserves both spaces and line breaks:

Example
```htm
<pre>
  My Bonnie lies over the ocean.

  My Bonnie lies over the sea.

  My Bonnie lies over the ocean.

  Oh, bring back my Bonnie to me.
</pre>
```
# HTML Styles
The HTML style attribute is used to add styles to an element, such as color, font, size, and more.

Setting the style of an HTML element, can be done with the style attribute.

The HTML style attribute has the following syntax:
```htm
<tagname style="property:value;">
```

The property is a CSS property. The value is a CSS value.
Background Color
The CSS background-color property defines the background color for an HTML element.

Example
Set the background color for a page to powderblue:
```htm
<body style="background-color:powderblue;">

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
```
Example
Set background color for two different elements:
```htm
<body>

<h1 style="background-color:powderblue;">This is a heading</h1>
<p style="background-color:tomato;">This is a paragraph.</p>

</body>
```
- Text Color
The CSS color property defines the text color for an HTML element:

Example
```htm
<h1 style="color:blue;">This is a heading</h1>
<p style="color:red;">This is a paragraph.</p>
```
- Fonts
The CSS font-family property defines the font to be used for an HTML element:

Example
```htm
<h1 style="font-family:verdana;">This is a heading</h1>
<p style="font-family:courier;">This is a paragraph.</p>
```
- Text Size
The CSS font-size property defines the text size for an HTML element:

Example
```htm
<h1 style="font-size:300%;">This is a heading</h1>
<p style="font-size:160%;">This is a paragraph.</p>
```
- Text Alignment
The CSS text-align property defines the horizontal text alignment for an HTML element:

Example
```htm
<h1 style="text-align:center;">Centered Heading</h1>
<p style="text-align:center;">Centered paragraph.</p>
```
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
