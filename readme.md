<h1 align="center"> 🔥 Neo HTML 🔥 </h1>
<p align="center">
  <b>
⭐ ⭐ The Better HTML ⭐ ⭐
  </b>
</p>
<p align="center">
Neo HTMl, or nHTML for short, is the better HTML, adding alot more fun, useful tags.
</p>
<!--toc -->
<details>
  <summary>Table of Contents</summary>
  
* [Docs](#docs)
  * [Adding to your HTML project](#1)
  * [New Tags](#2)
* [Errors](#error)
</details>
<!--toc -->
<h2 align="center" name="docs"> 📗 Docs 📗 </h1>
<h3 align="center" name="1"> 🚀 Adding to your HTML Project 🚀 </h1>
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
<h3 align="center" name="2"> 🎫 New Tags 🎫 </h3>
<h4 align="center"> neo-toggle </h4>
<p align="center">
Neo toggle is an element which has a special property; everytime it is clicked, it will toggle its <kbd>on</kbd> property.
</p>

```html
<neo-toggle> Type Something here </neo-toggle>
```
<p align="center">
You can use the <kbd>hasAttrbute()</kbd> function of javascript to check if it is on or off
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
The Element also has a <kbd>disabled</kbd> property, making it grey out & uninteractable
</p>

```html
<neo-toggle disabled> Type Something here </neo-toggle> <!-- Disabled Toggle -->
```


<h2 align="center" name="error"> ❓❌ Errors ❌❓ </h1>
<p align="center">
Here is a list of error codes and what they mean
</p>
<div align="center">

| Error Name         | Explanation                                                               | Code |
| ------------------ | ------------------------------------------------------------------------- | ---- |
| <kbd>Invalid_Data_Type</kbd>  | You have used the wrong type of data<br>For ex. String instead of Integer | 1    |
| <kbd>Data_Out_Of_Bounds</kbd> | Your data is not within the limits<br>For ex. max = 20, but value = 21    | 2    |

</div>
