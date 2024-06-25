# HTML Document Structure

This README provides a guide to the basic structure of an HTML document, including the essential elements and their functions.

## Table of Contents

1. [Document Type Declaration](#doctype)
2. [HTML Tag](#html-tag)
3. [Head Tag](#head-tag)
4. [Body Tag](#body-tag)
5. [Common HTML Elements](#common-html-elements)
6. [Example HTML Document](#example-html-document)

## Document Type Declaration

The `<!DOCTYPE html>` declaration defines the document type and version of HTML. It helps the browser render the page correctly.

```html
<!DOCTYPE html>
```

## HTML Tag

The `<html>` tag encloses the entire HTML document. It indicates the beginning and end of the HTML code.

```html
<html>
    <!-- Document content goes here -->
</html>
```

## Head Tag

The `<head>` tag contains meta-information about the HTML document, such as the title, character set, styles, and links to external resources.

```html
<head>
    <title>My First HTML Page</title>
</head>
```

### Common Elements in the Head Tag

- **`<title>`**: Sets the title of the HTML document, which appears in the browser's title bar or tab.
- **`<meta>`**: Provides metadata about the document, such as the character set and author.
- **`<link>`**: Links to external stylesheets or other resources.
- **`<style>`**: Contains internal CSS styles.
- **`<script>`**: Links to or contains JavaScript code.

## Body Tag

The `<body>` tag contains the content of the HTML document that is displayed in the browser.

```html
<body>
    <!-- Visible content goes here -->
</body>
```

## Common HTML Elements

### Headings

Headings range from `<h1>` to `<h6>`, with `<h1>` being the most important and `<h6>` the least.

```html
<h1>Main Heading</h1>
<h2>Subheading</h2>
```

### Paragraphs

The `<p>` tag defines a paragraph of text.

```html
<p>This is a paragraph.</p>
```

### Links

The `<a>` tag defines hyperlinks.

```html
<a href="https://www.example.com">This is a link</a>
```

### Images

The `<img>` tag embeds images into the document.

```html
<img src="image.jpg" alt="Description of the image">
```

### Lists

Ordered lists (`<ol>`) and unordered lists (`<ul>`) contain list items (`<li>`).

```html
<ol>
    <li>First item</li>
    <li>Second item</li>
</ol>

<ul>
    <li>First item</li>
    <li>Second item</li>
</ul>
```

## Example HTML Document

Here is a complete example of a simple HTML document that includes the elements discussed above:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Example HTML Page</title>
</head>
<body>
    <h1>Welcome to My Webpage</h1>
    <p>This is a paragraph explaining what my webpage is about.</p>
    <h2>About Me</h2>
    <p>Here is some information about me.</p>
    <a href="https://www.example.com">Visit my blog</a>
    <h2>My Hobbies</h2>
    <ul>
        <li>Reading</li>
        <li>Coding</li>
        <li>Traveling</li>
    </ul>
    <h2>Gallery</h2>
    <img src="photo.jpg" alt="A photo from my gallery">
</body>
</html>
```

This example demonstrates the basic structure and elements needed to create a simple web page. Each element plays a specific role in organizing and presenting content on the web.

---
