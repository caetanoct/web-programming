# Web Programming
Contents
* [Annotations](#Annotations)
	* [Data Visualization](#Data-Visualization)	
		* [HTML](#HTML)
		* [CSS](#CSS)
## Annotations
### Data Visualization

* **HTML** - Structure and how the browser should show the content.
* **CSS** - How the HTML elements will be shown.

#### HTML

[HTML Tutorial by w3schools](https://www.w3schools.com/html)

All HTML documents must start with a document type declaration: `<!DOCTYPE html>.`
The HTML document itself begins with `<html>` and ends with `</html>.`
The visible part of the HTML document is between `<body>` and `</body>`.

**View HTML Source Code:**
Right-click in an HTML page and select "View Page Source". This will open a window containing the HTML source code of the page.

**Inspect an HTML Element:**
Right-click on an element (or a blank area), and choose "Inspect" or "Inspect Element" to see what elements are made up of (you will see both the HTML and the CSS). You can also edit the HTML or CSS on-the-fly in the Elements or Styles panel that opens.

**Elements**

An HTML element is defined by a start tag, some content, and an end tag:

```html
<tagname>Content goes here...</tagname>
```

The HTML element is everything from the start tag to the end tag:

* Void Elements - Only 1 tag example is `<br>`

**Attributes**

HTML attributes provide additional information about HTML elements.

The `<a>` tag defines a hyperlink. The href attribute specifies the URL of the page the link goes to:
```html
<a href="https://www.w3schools.com">Visit W3Schools</a>
```

Usually in the format key=value `href="https://www.w3schools.com"`.

* Attribute lang in html tag indicates the language of the document
* Head element - Everything before text -> tag title = title of the page
* Body element - Everything that will be shown to the client

#### CSS

[W3 Tutorial](https://www.w3schools.com/css/)

Cascading Style Sheets - Describe the presentation of the page. 

Before CSS - The software would	choose how to present.
Today - The developers choose how to present.

HTML - STRUCTURE
CSS - FORMAT

Not case sensitive.

**Inline Style**

```HTML
<p style="color:red;">This is a paragraph.</p>
```

**Incorporated Style**
```HTML
<style>
body {
  background-color: linen;
}

h1 {
  color: maroon;
  margin-left: 40px;
}
</style>
```

**External Style**

Imported or Linked; The style sheet document needs to have *.css* extension

Link:
In the head section; href is the path
```HTML
<link rel="stylesheet" href="mystyle.css">
```

Import:
In the head section

```HTML
<style type="text/css">
	@import url("style.css") screen, projection;
</style>
```

**Rules**

Basic unit of a Style Sheet.

The selector points to the HTML element you want to style.

The declaration block contains one or more declarations separated by semicolons.

Each declaration includes a CSS property name and a value, separated by a colon.

Multiple CSS declarations are separated with semicolons, and declaration blocks are surrounded by curly braces.

```css
/*all paragraphs will be red alligned to the center*/
p {
  color: cyan;
  text-align: center;
}
```
text-align is a property, and center is the property value.
*p* is the selector.

together they are a rule.

The CSS element Selector
The element selector selects HTML elements based on the element name.


Here, all <p> elements on the page will be center-aligned, with a red text color: 
```css

p {
  text-align: center;
  color: red;
}
```

The CSS id Selector
The id selector uses the id attribute of an HTML element to select a specific element.

The id of an element is unique within a page, so the id selector is used to select one unique element!

The CSS rule below will be applied to the HTML element with id="para1": 
```css
#para1 {
  text-align: center;
  color: red;
}
```

The CSS class Selector
Unique; Sugestive and Modular
The class selector selects HTML elements with a specific class attribute.

To select elements with a specific class, write a period (.) character, followed by the class name.

In this example all HTML elements with class="center" will be red and center-aligned: 
```css
.center {
  text-align: center;
  color: red;
}
```

ID > CLASS > ELEMENT

There are many Proprieties and numeric values may be in pixels, centimeters or percentages.

**Box Model**

Determines Dimensional, Visual and Positioning characteristics.

Boxes contains the *content* and *internal/external spacements*.

```
        TOP
     +--------+
LEFT |        | RIGHT
     +--------+
       BOTTOM
```
Padding - Internal Margin
Border - Element Border
Margin - External Magin

Work with Internal Left margin? --> Left Padding
Work with Left Border? --> Margin Left/Border Left