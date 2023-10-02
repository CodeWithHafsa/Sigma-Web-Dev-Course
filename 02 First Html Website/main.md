## How to create a basic website.
First create `index.html`, `style.css` and `script.js`

For Index.html:

* Write ! (exclamation mark) so main format of html will automatically complete.
* To link css file in html file use `link:css` tag above head ending tag.  
* To link css file in html file use `script:src` tag above body ending tag. 

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>First Website</title>
   <!-- to link css file in html file -->
   <link rel="stylesheet" href="style.css">  
</head>
<body>
   Hey this is my first website. Sigma Web Development course is the best course. 
   
   <!-- to link javascript file in html file -->
   <script src="script.js"></script> 
</body>
</html>
```

For Style.css:
To add styling on website.

```css
body{
    background-color: red;  /* to make background red */
    color: white;  /* to make text color white */
}
```

For Script.js:
To add alert message on website

```javascript
alert("Welcome to Sigma Web Development Course")
```

Some Infomation:
* Install vscode-icons from updates - to present code beautifully.
* Some famous vs code themes can also be installed: jellyfish, github theme, material theme, Es7+react/Reduct...(for react)
* Install live preview: To preview website