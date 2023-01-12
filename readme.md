<h1 align="center"> 🔥 Neo HTML 🔥 </h1>
<p align="center">
  <b>
⭐ ⭐ The Better HTML ⭐ ⭐
  </b>
</p>
<p align="center">
Neo HTMl, or nHTML for short, is the better HTML, adding alot more fun, useful tags.
</p>
<h2 align="center"> 📗 Docs 📗 </h1>
<h3 align="center"> 🚀 Adding to your HTML Project 🚀 </h1>
<p align="center">
Add the JS link in your project files
</p>

```html
<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>My Totally Awesome Project</title>
  <link href="style.css" rel="stylesheet" type="text/css" />
  
  <script src="the-link-to-the-js"></script> <!-- Add this to your HTML -->
  
</head>

<body>
  Hello world
</body>
<script src="script.js"></script>
</html>
```
<h3 align="center"> 🎫 New Tags 🎫 </h3>
<h4 align="center"> neo-toggle </h4>
<p align="center">
Neo toggle is an element which has a special property; everytime it is clicked, it will toggle its 'on' property.
</p>

```html
<neo-toggle> Type Something here </neo-toggle>
```
<p align="center">
You can use the 'hasAttrbute()' function of javascript to check if it is on or off
</p>

```javascript
if (document.getElementById('my-toggle').hasAttribute('on')) {
  // On
}
else {
  // Off
 }
```
<p align="center">
The Element also has a disabled property, making it grey out & uninteractable
</p>

```html
<neo-toggle disabled> Type Something here </neo-toggle> <!-- Disabled Toggle -->
```


<h2 align="center"> ❓❌ Errors ❌❓ </h1>
<p align="center">
Here is a list of error codes and what they mean
</p>
<div align="center">

| Error Name         | Explanation                                                               | Code |
| ------------------ | ------------------------------------------------------------------------- | ---- |
| Invalid_Data_Type  | You have used the wrong type of data<br>For ex. String instead of Integer | 1    |
| Data_Out_Of_Bounds | Your data is not within the limits<br>For ex. max = 20, but value = 21    | 2    |

</div>
