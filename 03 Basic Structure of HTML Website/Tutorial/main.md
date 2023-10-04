## Basic Structure of HTML Website
The basic structure of html:
* Doc type html
* Html tag includes:
   - head opening and closing tag
   - body opening and closing tag
* title tag - It can be used as search engines, it also tells content of the page. 
* meta tag - meta tag is a self closing tag.

## Head Section of Html:
Head section of html - contains meta data of page.
Like: Title, Link

### What are meta tags:
It describe metadata within an HTML document.
The `<meta>` tag defines metadata about an HTML document. Metadata is data (information) about data.

```html
<head>
  <meta charset="UTF-8">
  <meta name="description" content="Free Web tutorials">
  <meta name="keywords" content="HTML, CSS, JavaScript">
  <meta name="author" content="John Doe">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
```

**More Examples**

**Define keywords for search engines:**
```
<meta name="keywords" content="HTML, CSS, JavaScript">
```

**Define a description of your web page:**
```
<meta name="description" content="Free Web tutorials for HTML and CSS">
```

**Define the author of a page:**
```
<meta name="author" content="John Doe">
```

**Refresh document every 30 seconds:**
```
<meta http-equiv="refresh" content="30">
```

**Setting the viewport to make your website look good on all devices:**

```
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```


## Body Section of HTML:
The `<body>` tag defines the document's body.

The `<body>` element contains all the contents of an HTML document, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.

---
There are two types of tag:
1. self closing tag
2. Paired tag

### Self Closing Tag:
A self-closing tag in HTML is a kind of HTML tag that does not need to be closed manually by its closing tag, which means it does not have a separate closing tag as `</tag>`. 

Some few self-closing tags are `<input/>, <hr/>, <br/>, <img/>`, etc.

### Paired Tag:
Paired tags require an opening tag that turns a formatting feature on and a closing tag that turns the feature off. Paired tags must surround the text you want formatted with that feature. 

For example, `</u>`and `</u>` will underline text. You must include the slash ( / ) in the closing tag in order for the pair to work.


```html
<!DOCTYPE html>  <!-- doc type html -->

<!-- HTML tag -->
<html lang="en">
<head>  <!-- head openeing tag -->
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">  <!-- meta content -->
    <title>Title of the page</title>  <!-- title content -->
    <link rel="stylesheet" href="style.css">
</head> <!-- head closing tag -->

<body>   <!-- body openeing tag -->
    Contact
    <script src="script.js"></script>
</body>  <!-- body closing tag -->
</html>
```

Note: lan=en (This is an attribute) That is **KEYVALUE PAIR**