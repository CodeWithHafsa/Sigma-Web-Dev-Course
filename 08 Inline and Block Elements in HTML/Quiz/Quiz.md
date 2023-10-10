## Quiz Question
Without using br tag, write a vertically aligned form asking for name, city and pincode of a user.

```html
<body>
    <h3>Details Form</h3>
    <form action="#">
        <div>
            Enter your details
        </div>
        
        <!-- name -->
        <div>
            <label for="name">Name:</label>
            <input type="text" name="name" id="name">
        </div>

        <!-- city -->
        <div>
            <label for="city">City:</label>
            <input type="text" name="city" id="city">
        </div>

        <!-- pincode -->
        <div>
            <label for="pincode">Pincode:</label>
            <input type="number" name="pincode" id="pincode">
        </div>
    </form>
</body>
```