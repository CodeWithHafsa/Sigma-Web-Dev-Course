# HTML Images:
Images can improve the design and the appearance of a web page.

**Example**
```html
<img src="image.png" alt="Train-image" > 
```

### Preview:
![Alt text](/Tutorial/Images/ImagesSection/image-10.png)

## HTML Images Syntax
The HTML `<img>` tag is used to embed an image in a web page.

Images are not technically inserted into a web page; images are linked to web pages. The `<img>` tag creates a holding space for the referenced image.

The `<img>` tag is empty, it contains attributes only, and does not have a closing tag.

The `<img>` tag has two required attributes:
* src - Specifies the path to the image
* alt - Specifies an alternate text for the image

## The src Attribute
The required `src` attribute specifies the path (URL) to the image.

**Example**
```
<img src="image.jpg" alt="Train-Image>
```

## The alt Attribute
The required `alt` attribute provides an alternate text for an image, if the user for some reason cannot view it 

The value of the `alt` attribute should describe the image. If a browser cannot find an image, it will display the value of the `alt` attribute.

**Example**
```
<img src="image2.jpg" alt="Train-Image>
```

## Image Size - Width and Height
You can use the style attribute to specify the width and height of an image.

**Example**
```html
<img src="image.jpg" alt="Train-Image" style="width:500px;height:600px;">
```

Alternatively, you can use the width and height attributes:

**Example**
```html
<img width="230" height="230"src="image.png" alt="Train-image" >
```

## Images in Another Folder
If you have your images in a sub-folder, you must include the folder name in the `src` attribute:

**Example**
```html
<img src="/images/html5.gif" alt="HTML5 Icon" style="width:128px;height:128px;">
```

## Images on Another Server/Website
Some web sites point to an image on another server.

To point to an image on another server, you must specify an absolute (full) URL in the src attribute:

**Example**
```html
<img src="https://www.w3schools.com/images/w3schools_green.jpg" alt="W3Schools.com">
```

## Animated Images
HTML allows animated GIFs:

**Example**
```html
<img src="programming.gif" alt="Computer Man" style="width:48px;height:48px;">
```

## Image as a Link
To use an image as a link, put the `<img>` tag inside the `<a>` tag:

**Example**
```html
<a href="default.asp">
  <img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">
</a>
```

## Image Floating
Use the CSS float property to let the image float to the right or to the left of a text:

**Example**
```html
<p><img src="smiley.gif" alt="Smiley face" style="float:right;width:42px;height:42px;">
The image will float to the right of the text.</p>

<p><img src="smiley.gif" alt="Smiley face" style="float:left;width:42px;height:42px;">
The image will float to the left of the text.</p>
```

## Common Image Formats
Here are the most common image file types, which are supported in all browsers (Chrome, Edge, Firefox, Safari, Opera):

|Abbreviation|	File Format |	File Extension|
|-------------- |-------------- |-----------------|
|APNG	|Animated Portable Network Graphics	|.apng|
|GIF	    |Graphics Interchange Format	  |  .gif|
|ICO	    |Microsoft Icon	         | .ico, .cur|
|JPEG	|Joint Photographic Expert Group image|	.jpg, .jpeg, .jfif, .pjpeg, .pjp|
|PNG  	|Portable Network Graphics	|.png|
|SVG   	|Scalable Vector Graphics	|.svg|

## Chapter Summary
* Use the HTML `<img>`  element to define an image
* Use the HTML src attribute to define the URL of the image
* Use the HTML alt attribute to define an alternate text for an image, if it cannot be displayed
* Use the HTML width and height attributes or the CSS width and height properties to define the size of the image
* Use the CSS float property to let the image float to the left or to the right