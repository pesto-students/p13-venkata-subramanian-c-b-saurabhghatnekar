# HTML Fundamentals

## What is HTML?

HTML (HyperText Markup Language) is a markup language used to structure and present content on the web. It is the standard markup language for creating web pages and web applications.


## HTML Syntax

HTML is composed of elements, which are represented by tags. Tags are enclosed in angle brackets, like `<tagname>`. Most tags have an opening tag and a closing tag, with the content in between. For example:

```html
<p>This is a paragraph.</p>
```

The opening tag is `<p>` and the closing tag is `</p>`. The content in between is the text "This is a paragraph."

Some tags are self-closing, meaning they don't have a closing tag. For example:

```html
<img src="image.jpg" alt="Image">
```

The `<img>` tag is self-closing. It inserts an image into the page and has two attributes: `src` and `alt`. Attributes provide additional information about an element. In this case, the `src` attribute specifies the image source and the `alt` attribute provides alternative text for the image.

> **Note**: HTML tags are case-insensitive, meaning `<p>` and `<P>` are equivalent.


## HTML Document Structure

An HTML document is composed of the following elements:

- `<!DOCTYPE html>`: The document type declaration, which specifies the document type and version.
- `<html>`: The root element of an HTML document.
- `<head>`: Contains metadata about the document, such as the page title.
- `<body>`: Contains the visible content of the document, such as text, images, and links.
- `<title>`: The title of the document, which is displayed in the browser tab.

Some tags are used to structure the content of the document. For example:
- `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, `<h6>`: Headings of different sizes, with `<h1>` being the largest and `<h6>` being the smallest.
- `<p>`: A paragraph of text.
- `<img>`: An image.
- `<a>`: A hyperlink, which links to another web page or resource.
- `<ul>`, `<ol>`: Unordered and ordered lists respectively.
- `<li>`: A list item.
- `<table>`: A table.
- `<tr>`: A table row.
- `<td>`: A table cell.
- `<div>`: A generic container element.


## HTML Attributes

HTML attributes provide additional information about an element. They are specified in the opening tag and consist of a name and a value, separated by an equals sign. For example:

```html
<a href="https://www.google.com">Google</a>
```

The `<a>` tag is an anchor tag, which is used to create hyperlinks. It has an `href` attribute, which specifies the link destination. In this case, the link destination is `https://www.google.com`.

> **Note**: HTML attributes are case-insensitive, meaning `href` and `HREF` are equivalent.
HTML attributes can be added to any HTML element, but some attributes are only valid for certain elements. For example, the `href` attribute is only valid for the `<a>` tag.


## HTML Comments

HTML comments are used to add notes to the code. They are not displayed in the browser, but can be viewed in the source code. They are written as follows:

```html
<!-- This is a comment -->
```

