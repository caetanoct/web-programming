# Web Programming
Contents
* [Annotations](#Annotations)
	* [Data Visualization](#Data-Visualization)	
		* [HTML](#HTML)
## Annotations
### Data Visualization

* **HTML** - Structure and how the browser should show the content.
* **CSS** - How the HTML elements will be shown.

#### HTML

All HTML documents must start with a document type declaration: `<!DOCTYPE html>.`
The HTML document itself begins with `<html>` and ends with `</html>.`

The visible part of the HTML document is between `<body>` and `</body>`.

**View HTML Source Code:**
Right-click in an HTML page and select "View Page Source" (in Chrome) or "View Source" (in Edge), or similar in other browsers. This will open a window containing the HTML source code of the page.

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