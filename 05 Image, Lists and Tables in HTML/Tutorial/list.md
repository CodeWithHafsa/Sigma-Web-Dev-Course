# HTML List:
HTML lists allow web developers to group a set of related items in lists.

## Types of HTML Lists
HTML provides different types of lists to display data in various forms. Each list contains one or more list items.
* Unordered List: Displays items using bullets.
* Ordered List: Displays items in a numerical sequence, and supports various numbering styles like Arabic numerals, Roman numerals, and so on.
* Definition List: Organizes items in a format similar to a dictionary, with terms and their corresponding definitions.

## Unordered HTML List
An unordered list is a list of items that are not arranged in any specific, sequential order. An unordered list starts with the `<ul>` tag. Each list item starts with the `<li>` tag.\
The list items will be marked with bullets (small black circles) by default.

### Example:
```html
    <ul>
        <li>Hafsa</li>
        <li>Rohan</li>
        <li>Ali</li>
    </ul>
```

### Preview :
![Alt text](/Tutorial/Images/ListSection/image-7.png)

## Customizing Bullet Points with 'type' Attribute
You can specify the style of bullet points using the type attribute. It supports three values:
* disc - default bullet style
* square
* circle


### Example:

Using Square bullet
```html
<ul type="square">
  <li>Notebook</li>
  <li>Marker</li>
</ul>
```

### Preview :
![Alt text](/Tutorial/Images/ListSection/image-8.png)


## Ordered HTML List
An ordered list is a list of items that are arranged in a specific, sequential order. Each item in the list is usually numbered to indicate its position in the sequence. Ordered lists are commonly used when the sequence of the items is important, such as in step-by-step instructions or rankings.

An ordered list starts with the `<ol>` tag. Each list item starts with the `<li>` tag.\
The list items will be marked with numbers by default.

### Example:
```html
    <ol>
        <li>Hafsa</li>
        <li>Rohan</li>
        <li>Ali</li>
    </ol>
```

### Preview :
![Alt text](/Tutorial/Images/ListSection/image-6.png)

## Setting the 'type' Attribute
The type attribute specifies the style of numbering. You have several options:
* Uppercase Roman Numerals: Use type="I"
* Lowercase Roman Numerals: Use type="i"
* Arabic Numerals: Use type="1" (This is the default if the type attribute is not specified)
* Lowercase Alphabetical Letters: Use type="a"
* Uppercase Alphabetical Letters: Use type="A"

### Example:
```html
    <ol type = "A">
        <li>Hafsa</li>
        <li>Rohan</li>
        <li>Ali</li>
    </ol>
```

### Preview :
![Alt text](/Tutorial/Images/ListSection/image-9.png)


## HTML Description Lists
HTML also supports description lists.\
A description list is a list of terms, with a description of each term.\
The `<dl>` tag defines the description list, the `<dt>` tag defines the term (name), and the `<dd>` tag describes each term.

### Example:
```
<dl>
  <dt>Coffee</dt>
  <dd>- black hot drink</dd>
  <dt>Milk</dt>
  <dd>- white cold drink</dd>
</dl>
```

### Preview :
![Alt text](/Tutorial/Images/ListSection/image-5.png)