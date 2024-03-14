# HTML BASIC CONCEPTS

## HTML DOCUMENTS
All HTML documents must start with a document type declaration: `<!DOCTYPE html>`

This declaration must appear at the top of the page(before any HTML tags). It helps the browser to display the elements correctly. Also note that this declaration is not case sensitive.

The HTML document itself begins with `<html>` and ends with `</html>`

The visible part of the HTML document is between `<body>` and `</body>`

```
<!DOCTYPE html>
<html>
<body>
<h1>First Heading</h1>
<p>First Paragraph</p>
</body>
</html>
```

## HTML Headings
HTML headings are defined with the `<h1>` to `<h6>` tags.

`<h1>` defines the most important heading while `<h6>` defines the least important heading.

```
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h1>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```

## HTML Paragraphs
HTML paragraphs are defined with th `<p>` tag:

`<p>This is a paragraph</p>`

## HTML links
HTML links are defined with the `<a>` tag

`<a href="https://github.com/enzeyi">Emmanuel's Github</a>`

The link's destination is specified in the **href** attribute.

Attributes are used to provide additional information about HTML elemnts.

## HTML images
HTML images are defined with the `<img>` tag.

The source file **(src)**, alternative **(alt)**, width, and height are provided as attributes.

`<img src="images/pic.jpg" alt="MyPic" width="144" height="190">`

## Viewing HTML Source Code
Click **CTRL + U** in an HTML page to view the page's HTML source. A new tab containing the HTML source code will be opened.

## Inspecting an HTML Element
Right click on an element (or a blank area), and choose **"inspect"** to see what elements are made up of. You can also edit the HTML or CSS on-the-fly in the elements or styles panel that opens.

