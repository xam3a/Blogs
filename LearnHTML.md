# Blog-HTML-CSS
I started my programming career a short time ago, I begin following ``<a href="https://www.theodinproject.com">`The Odin Project`</a>``, through which I learned how to create a small Web Page using HTML.

1. What is HTML?
- HTML is a language for describing web pages.
- HTML stands for Hyper Text Markup Language.
- HTML is not a programming language, it's a markup language.
- A markup language is a set of markup tags.
- HTML uses markup tags to describe web pages.
2. Why use HTML?
- Controls the layout of the content.
- Provides structure for the web page design.
- The fundamental building block any web page.
### How to practically use HTML??
When I started learning to program, many advised me to use Visual Studio Code, and I felt that it was the easiest to use, as it has many shortcuts that may help you work more easily and quickly, and you can download many programming languages on it and integrate them for example (HTLM, CSS, JavaScript), and there is also a theme feature in which you may find a temple that suits your vision, you can also download help in arranging your work.
3. What this CSS??
- CSS stands for Cascanding Style Sheets.
- Style define **how to display** HTML elements.
- Style were added to HTML 4.0 *to solve* a problem.
- *External Style Sheets* can save a lot of work
- External Style are stored in *CSS files*.
4. Why use CSS??
- Apply Style to the web page design.
- Targets various screen sizes to make web pages responsive.
- Primarily handles the "look and feel" of a web page.
### how you can combine CSS with HTML?
You can combine these two language about this code: ``<link rel="stylesheet" href="(here enter the name of css name)">`` and this code will be added on the first ``<head>``
On CSS I can change more option on HTML for example (font-size/font/backgroud/width/align/....)
Example for HTML with CSS:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <link rel="stylesheet" href="style.css"><!--css-->
  <title>What I do?</title>
</head>
<body>
<h1>Hello</h1>
<ul id="css">Second, how do I use HTML?</ul>
<li>Controls the layout of the content.</li>
<p class="btn"> you can also download help in arranging your work.</p>
</body>
</html>
html{
  background-color: red;
}
body{
  background-color: purple;
  border: 4rem;
}
h1{
  color: yellow;
  font-size: medium;
  font-family: monospace;
}
li{
  color: blue;
  font-style: italic;
}
#css{
color: pink;
background-color: white;
font-style: bold;
font-size: 10px;
}
.btn{
color: gray;
}
```
