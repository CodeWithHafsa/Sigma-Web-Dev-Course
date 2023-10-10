# HTML Tables:
A table in HTML consists of table cells inside rows and columns.
HTML tables allow web developers to arrange data into rows and columns.

## Table Cells
Each table cell is defined by a `<td>` and a `</td>` tag.
Everything between `<td>` and `</td>` are the content of the table cell.

Note:  A table cell can contain all sorts of HTML elements: text, images, lists, links, other tables, etc.

## Table Rows
Each table row starts with a `<tr>` and ends with a `</tr>` tag.

## Table Headers
Sometimes you want your cells to be table header cells. In those cases use the `<th>` tag instead of the `<td>` tag.

**Terms :**
* `td` stands for table data.
* `tr` stands for table row.
* `th` stands for table header.

----

**Example**
```html
<body>

    <table>
        <tr>
            <th>Name</th>         <!-- table heading -->
            <th>Designation</th>
            <th>Fav Language</th>
        </tr>

        <tr>                      <!-- table row -->
            <td>Hafsa</td>        <!-- table data -->
            <td>Programmer</td>
            <td>Javascript</td>
        </tr>

        <tr>                      <!-- table row -->
            <td>Sam</td>        <!-- table data -->
            <td>Programmer</td>
            <td>Java</td>
        </tr>

    </table>
</body>
```

# rowspan and colspan Attributes
**Rowspan:** If you want a table cell to span multiple rows, you can use the rowspan attribute.

```
<td rowspan="value">
```

**Colspan:** If you want a table cell to span multiple columns, you can use the colspan attribute.

```
<td colspan="value">
```

![Alt text](/Tutorial/Images/image.png)

### **Example**
```html

<body>
    <table>
        <tr>
            <th>Name</th>         <!-- table heading -->
            <th>Designation</th>
            <th>Fav Language</th>
        </tr>

        <tr>                      <!-- table row -->
            <td>Hafsa</td>        <!-- table data -->
            <td>Programmer</td>
            <td>Javascript</td>
        </tr>

        <tr>                      <!-- table row -->
            <td colspan="2"> Sam</td>   <!-- table data --> <!-- colspan="2" means it takes 2 column spaces -->
            <td rowspan="2">Java</td>                       <!-- rowspan="2" means it takes 2 row spaces -->
        </tr>

        <tr>                      <!-- table row -->
            <td colspan="2"> Sam</td>   <!-- table data --> <!-- colspan="2" means it takes 2 column spaces -->
        </tr>

    </table>
</body>
```

### Preview :

![Alt text](/Tutorial/Images/TableSection/image-1.png)

# HTML `<caption>` Tag
The `<caption>` tag defines a table caption.

The `<caption>` tag must be inserted immediately after the `<table>` tag.

```html
<body>
<table>
        <caption>Employee Details</caption>
        <tr>
            <th>Name</th>         <!-- table heading -->
            <th>Designation</th>
            <th>Fav Language</th>
        </tr>

        <tr>                      <!-- table row -->
            <td>Hafsa</td>        <!-- table data -->
            <td>Programmer</td>
            <td>Javascript</td>
        </tr>

        <tr>                      <!-- table row -->
            <td colspan="2"> Sam</td>   <!-- table data --> <!-- colspan="2" means it takes 2 column spaces -->
            <td rowspan="2">Java</td>                       <!-- rowspan="2" means it takes 2 row spaces -->
        </tr>

        <tr>                      <!-- table row -->
            <td colspan="2"> Sam</td>   <!-- table data --> <!-- colspan="2" means it takes 2 column spaces -->
        </tr>

    </table>
</body>
```

### Preview :
![Alt text](/Tutorial/Images/TableSection/image-2.png)

## Grouping in Table:
We can group contenet of the table using:
* thead - header of the table.
* tbody - body of the table.
* tfoot - footer of the table.

**Exzmple**
```html
<body>
    <table>

        <!-- header of the table -->
        <thead>           
            <caption>Employee Details</caption>
            <tr>
                <th>Name</th>         <!-- table heading -->
                <th>Designation</th>
                <th>Fav Language</th>
            </tr>
        </thead>

        <!-- body of the table-->
        <tbody>   
            <tr>                      <!-- table row -->
                <td>Hafsa</td>        <!-- table data -->
                <td>Programmer</td>
                <td>Javascript</td>
            </tr>
    
            <tr>                      <!-- table row -->
                <td colspan="2"> Sam</td>   <!-- table data --> <!-- colspan="2" means it takes 2 column spaces -->
                <td rowspan="2">Java</td>                       <!-- rowspan="2" means it takes 2 row spaces -->
            </tr>
    
            <tr>                      <!-- table row -->
                <td colspan="2"> Sam</td>   <!-- table data --> <!-- colspan="2" means it takes 2 column spaces -->
            </tr>
        </tbody>
  
        <!-- footer of the table-->
        <tfoot> 
            <tr>                      <!-- table row -->
                <td colspan="2"> Footer </td>   
                <td rowspan="2">Footer </td> 
            </tr>
        </tfoot>
    </table>
</body>
```

### Preview :
![Alt text](/Tutorial/Images/TableSection/image-4.png)

# HTML `<br>` Tag
* The `<br>` tag inserts a single line break.
* The `<br>` tag is useful for writing addresses or poems.
* The `<br>` tag is an empty tag which means that it has no end tag.

**Example**
```html
<!DOCTYPE html>
<html>
<body>

<h1>A Poem</h1>

<p>Be not afraid of greatness.<br>
Some are born great,<br>
some achieve greatness,<br>
and others have greatness thrust upon them.</p>

<p><em>-William Shakespeare</em></p>

</body>
</html>
```

### Preview :
![Alt text](/Tutorial/Images/TableSection/image-3.png)