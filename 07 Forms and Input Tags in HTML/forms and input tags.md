# HTML Form:
An HTML form is used to collect user input. The user input is most often sent to a server for processing.

## The `<form>` Element
The HTML `<form>` element is used to create an HTML form for user input.
```html
<form action=""></form>
```
The `<form>` element is a container for different types of input elements, such as: text fields, checkboxes, radio buttons, submit buttons, etc.

Note: There are two types of actions in form tag.
* get request
* post request 

## The `<input>` Element
The HTML `<input>` element is the most used form element.

An `<input>` element can be displayed in many ways, depending on the type attribute.

Here are some examples:

|Type	|Description|
|-------|-------------|
| `<input type="text">`	|Displays a single-line text input field|
| `<input type="radio">`	|Displays a radio button (for selecting one of many choices)|
| `<input type="checkbox">`	|Displays a checkbox (for selecting zero or more of many choices)|
| `<input type="submit">`	|Displays a submit button (for submitting the form)|
| `<input type="button">`	|Displays a clickable button|

## HTML `<label>` Tag
The `<label>` tag defines a label for several elements:
Note: Label should be always input tag id.

```
<input type="checkbox">
<input type="color">
<input type="date">
<input type="datetime-local">
<input type="email">
<input type="file">
<input type="month">
<input type="number">
<input type="password">
<input type="radio">
<input type="range">
<input type="search">
<input type="tel">
<input type="text">
<input type="time">
<input type="url">
<input type="week">
<meter>
<progress>
<select>
<textarea>
```

Example:
```html
    <form action="post">
        <div>
            <label for="username">Enter your username</label>
            <input type="text" id="username" name="username" placeholder="Enter your username">
        </div>

        <!-- For Gender -->
        <div>
            <input type="radio" name="gender" id="male" value="male">
            <label for="male">Male</label>
    
            <input type="radio" name="gender" id="female" value="female">
            <label for="female">Female</label> 
            <!-- here name is same - means dono mein se sirf aik at a time select hoga -->
        </div>

        <div>
            <input type="checkbox" name="subscribe" id="subscribe" value="yes">
            <label for="subscribe">Subscribe to newsletter</label>
        </div>
    </form>
```

### Text area:
The `<textarea>` tag defines a multi-line text input control.

The `<textarea>` element is often used in a form, to collect user inputs like comments or reviews.

A text area can hold an unlimited number of characters, and the text renders in a fixed-width font (usually Courier). The size of a text area is specified by the `cols` and `rows` attributes (or with CSS).

The `name` attribute is needed to reference the form data after the form is submitted (if you omit the name attribute, no data from the text area will be submitted).

The `id` attribute is needed to associate the text area with a label. 

```html
        <!-- Text area tag-->
        <div>
            <label for="comment">Enter your comment</label>
            <br>   <!-- don't recommended br tag -->
            <textarea name="comment" id="comment" cols="50" rows="4"></textarea>
        </div>
```

### Select Tag:
The `<select>` element is used to create a drop-down list.\
The `<select>` element is most often used in a form, to collect user input.

The `name` attribute is needed to reference the form data after the form is submitted (if you omit the name attribute, no data from the drop-down list will be submitted). The `id` attribute is needed to associate the drop-down list with a label.

The `<option>` tags inside the `<select>` element define the available options in the drop-down list.

```html
        <!-- Select tag -->
        <div>
            <select name="fruits" id="">
                <option value="apple">Apple</option>
                <option value="banana">Banana</option>
                <option value="cherry">Cherry</option>
            </select>
        </div>
```
Note: Select Tag creates options

#### Key Point:
* We can use 'input' tag and 'label' tag inside form tag in html.
* Input 'id' and label 'for' should be same. (means dono ka name same hona chahiye hai)


# Some Common Attributes:
There are some common attributes that used in HTML.

## action:
The action attribute specifies the URL where the form data should be sent after submission.
```html
<form action="/submit.php" method="POST">
</form>
```

## method
The method attribute defines how data is sent. The two most common methods are GET and POST.
```html
<form action="/submit.php" method="POST">
</form>
```

## name
The name attribute specifies the name for the form element, making it easier to reference in scripts or the server-side code.

Note: Name se hum mark kartey han server ko.
```html
<input type="text" name="username">
```

## New HTML5 Attributes
## placeholder
This attribute provides a hint to the user as to what can be entered in the field.
```html
<input type="text" placeholder="Enter your username">
```

## required
The required attribute makes a field mandatory to fill out.
```html
<input type="text" required>
```

## autofocus
The autofocus attribute automatically focuses the cursor on the particular input when the page loads.
```html
<input type="text" autofocus>
```

## pattern
The pattern attribute specifies a regular expression that the input must match to be valid.
```html
<input type="text" pattern="[a-zA-Z0-9]+">
```

## Example: 

```html
<body>
    <h1>Form to apply for Sigma Web Development Course - TA </h1>
    <form action="post">
        <div>
            <label for="username">Enter your username</label>
            <input type="text" id="username" name="username" placeholder="Enter your username">
        </div>

        <!-- For Gender -->
        <div>
            <input type="radio" name="gender" id="male" value="male">
            <label for="male">Male</label>
    
            <input type="radio" name="gender" id="female" value="female">
            <label for="female">Female</label> 
            <!-- here name is same - means dono mein se sirf aik at a time select hoga -->
        </div>

        <div>
            <input type="checkbox" name="subscribe" id="subscribe" value="yes">
            <label for="subscribe">Subscribe to newsletter</label>
        </div>

        <!-- Text area tag-->
        <div>
            <label for="comment">Enter your comment</label>
            <br>   <!-- don't recommended br tag -->
            <textarea name="comment" id="comment" cols="50" rows="4"></textarea>
        </div>

        <!-- Select tag -->
        <div>
            <select name="fruits" id="">
                <option value="apple">Apple</option>
                <option value="banana">Banana</option>
                <option value="cherry">Cherry</option>
            </select>
        </div>
    </form>
</body>
```