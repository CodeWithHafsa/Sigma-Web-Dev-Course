## HTML Attributes:
Attribute give function an enhance personality.
E.g.inline css, link tag etc.  

All HTML elements can have attributes\
Attributes provide additional information about elements\
Attributes are always specified in the start tag\
Attributes usually come in name/value pairs like: name="value"

### The href Attribute
The `<a>` tag defines a hyperlink. The href attribute specifies the URL of the page the link goes to:

**Example**
```
<a href="https://www.w3schools.com">Visit W3Schools</a>
```

### The src Attribute
The `<img>` tag is used to embed an image in an HTML page. The src attribute specifies the path to the image to be displayed:

**Example**
```
<img src="img_girl.jpg">
```

There are two ways to specify the URL in the src attribute:
1. Absolute URL - Links to an external image that is hosted on another website. Example: src="https://www.w3schools.com/images/img_girl.jpg".

2. Relative URL - Links to an image that is hosted within the website. Here, the URL does not include the domain name. If the URL begins without a slash, it will be relative to the current page. Example: src="img_girl.jpg". If the URL begins with a slash, it will be relative to the domain. Example: src="/images/img_girl.jpg".

### The width and height Attributes
The `<img>` tag should also contain the width and height attributes, which specify the width and height of the image (in pixels):

**Example**
```
<img src="img_girl.jpg" width="500" height="600">
```

### The alt Attribute
The required `alt` attribute for the `<img>` tag specifies an alternate text for an image, if the image for some reason cannot be displayed. This can be due to a slow connection, or an error in the src attribute, or if the user uses a screen reader.

**Example**
```
<img src="img_girl.jpg" alt="Girl with a jacket">
```

### The style Attribute
The style attribute is used to add styles to an element, such as color, font, size, and more.

**Example**
```
<p style="color:red;">This is a red paragraph.</p>
```

### The lang Attribute
You should always include the `lang` attribute inside the `<html>` tag, to declare the language of the Web page. This is meant to assist search engines and browsers.

The following example specifies English as the language:
```
<!DOCTYPE html>
<html lang="en">
<body>
...
</body>
</html>
```

Note: Country codes can also be added to the language code in the lang attribute. So, the first two characters define the language of the HTML page, and the last two characters define the country.

### The title Attribute
The `title` attribute defines some extra information about an element.

The value of the title attribute will be displayed as a tooltip when you mouse over the element:

**Example**
```
<p title="I'm a tooltip">This is a paragraph.</p>
```

## Chapter Summary
* All HTML elements can have attributes
* The href attribute of `<a>` specifies the URL of the page the link goes to
* The src attribute of `<img>` specifies the path to the image to be displayed
* The width and height attributes of `<img>` provide size information for images
* The alt attribute of `<img>` provides an alternate text for an image
* The style attribute is used to add styles to an element, such as color, font, size, and more
* The lang attribute of the `<html>` tag declares the language of the Web page
* The title attribute defines some extra information about an element