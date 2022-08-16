### what is HTML?

- Hyper Text Markup Language
- NOT a programming Language
- Describing the webpage
- HTML was invented by Tim Berners-Lee in 1991.
- HTML is used for creating web pages and web applications.
- It is used to describe the structure of Web pages using markup tags.

### HTML file?

- Page in the internet (docment in the internet)
- file end with a .html
- index.html=abc.com

### HTML Histtory

- Since the early days of the World Wide Web, there have been many versions of HTML:
- 1989 ==> Tim Berners-Lee invented www

### Tag syntax

````bash
- <tag> opening tag
- </tag> closing tag
- URL uniform Resource Location
- http hypertext transfer protocal
- DOM Docment Object Model

# HTML5 RoadMap

1.HTML page structure
2.Elemet,Tags & Attributes
3.Empty/void element
4.Heading Element --->h1 to h6
5.Paragraph Element ----> p,br,hr etc..
6.container Element --->div,span etc...
7.Form based Elements --->Form,input,textarea,select,button,datalist etc...
8.Text Semantics -->b,i,sub,sup,small,strong,em,q,abbr etc...
9.Text Blocks --->Blockquotes,address
10.Hyperlink
11.Image ---> alt,max-width,aspect-radio
12.Lists ---> Ordered,unordered
13.Table
14.Sematic Elements--->header,footer,nav etc...
15.id and class Attributes
16.Include Stylesheets
17.Include javascriptfile
18.Setting FavIcon
19.Setting Title



# 1.HTML PAGE STRUCTURE

<html>
<head>
<title>Page title</title>
</head>
<body>
<h1>This is a heading</h1>
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>
</body>
</html>

# 2.Elemet,Tags & Attributes

Tags:

The HTML element is everything from the start tag to the end tag:
<tagname>Content goes here...</tagname>,example--><h1>,<p>,<br>

The href Attribute
<a href="https://www.w3schools.com">Visit W3Schools</a>

The src Attribute
<img src="img_girl.jpg">

The width and height attributes
<img src="img_girl.jpg" height=100px width=200px>

The alt Attribute
<img src="img_girl.jpg" alt="Girl with a jacket">

The style Attribute

<p style="color:red;">This is a red paragraph.</p>

The lang Attribute

<html lang="en">

The title Attribute

<p title="I'm a tooltip">This is a paragraph.</p>

# 3.Empty/void element

# 4.Heading Element

<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>

# 5.Paragraph Element

<p>This is a paragraph.</p><hr><br><pre>
<p>This is another paragraph.</p>

# 6.container Element

<div class="w3-container w3-red">
  <p>London is the capital city of England.</p>
</div>

<header class="w3-container w3-teal">
  <h1>Header</h1>
</header>

<footer class="w3-container w3-teal">
  <h5>Footer</h5>
  <p>Footer information goes here</p>
</footer>

<article></article>
<section></section>

# 7.Form based Elements

<input>---><input type="text" id="fname" name="fname">
<label>---><label for="cars">Choose a car:</label>
<select>---><select id="cars" name="cars">

<option value="volvo">Volvo</option>
<option value="saab">Saab</option>
<option value="fiat">Fiat</option>
<option value="audi">Audi</option>
</select>

<textarea>---><textarea name="message" rows="10" cols="30">
The cat was playing in the garden.
</textarea>

<button> ----><button type="button" onclick="alert('Hello World!') ">Click Me!</button>

<fieldset> ---><fieldset>
                <legend>Personalia:</legend>
                </fieldset>
<legend>
<datalist>  ---> <input list="browsers">
                <datalist id="browsers">
                <option value="Internet Explorer">
                <option value="Firefox">
                <option value="Chrome">
                <option value="Opera">
                <option value="Safari">
                </datalist>
<output>
<option>
<optgroup>

# 8.Text Semantics

<b> - Bold text
<strong> - Important text
<i> - Italic text
<em> - Emphasized text
<mark> - Marked text
<small> - Smaller text
<del> - Deleted text
<ins> - Inserted text
<sub> - Subscript text
<sup> - Superscript text

# 9.Text Blocks

<address>
<article>
<aside>
<blockquote>
<canvas>
<dd>
<div>
<dl>
<dt>
<fieldset>
<figcaption><figure><footer><form><h1>-<h6><header><hr><li><main><nav><noscript><ol><p><pre><section><table><tfoot><ul><video>

- Inline Elements
  <a>
  <abbr>
  <acronym>
  <b>
  <bdo>
  <big>
  <br>
  <button>
  <cite><code><dfn><em><i><img><input><kbd><label><map><object><output><q><samp><script><select><small><span><strong><sub><sup><textarea><time><tt><var>

# 10.Hyperlink

<a href="url">link text</a>

- HTML Links - The target Attribute
  The Target attribute can have one of the following values:

\_self - Default. Opens the document in the same window/tab as it was clicked
\_blank - Opens the document in a new window or tab
\_parent - Opens the document in the parent frame
\_top - Opens the document in the full body of the window

# 11.Image

# 12.Lists

<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>

<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>

<dl>
  <dt>Coffee</dt>
  <dd>- black hot drink</dd>
  <dt>Milk</dt>
  <dd>- white cold drink</dd>
</dl>

# 13.Tables

<table>
  <tr>
    <th>Company</th>
    <th>Contact</th>
    <th>Country</th>
  </tr>
  <tr>
    <td>Alfreds Futterkiste</td>
    <td>Maria Anders</td>
    <td>Germany</td>
  </tr>
  <tr>
    <td>Centro comercial Moctezuma</td>
    <td>Francisco Chang</td>
    <td>Mexico</td>
  </tr>
</table>

# 14.Semetic element

<article>
<aside>
<details>
<figcaption>
<figure>
<footer>
<header>
<main>
<mark>
<nav>
<section>
<summary>
<time>

# 15.id class

# 16.include style

Inline - by using the style attribute inside HTML elements
Internal - by using a <style> element in the <head> section
External - by using a <link> element to link to an external CSS file

# 17.include js sheet

Scripts can be placed in the <body>, or in the <head> section of an HTML page, or in both.

# 18.setting fav icn

<link rel="icon" type="image/x-icon" href="/images/favicon.ico">

# 19.setting tittle


*Html Medium *

1.figure
2.audio
3.video
4.map
5.objects
6.embed

<---1.figure--->

<figure>
  <img src="pic_trulli.jpg" alt="Trulli" style="width:100%">
  <figcaption>Fig.1 - Trulli, Puglia, Italy.</figcaption>
</figure>


<---2.audio--->

### Basic Commands

```bash
<!DOCTYPE html> #html5 this page is a doucment of htmll
<html lang="en"></html> # element is the root element of an HTML page
<head></head> #the head of the html elemet
<title></title> #the tag used head of the title
<body></body> #element defines the document's body,container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.
<h1></h1> #the tag is largest heading
<h2>,<h3>,<h4>,<h5>,<h6> #HEADINGS
<p></p> #paragraph line
<b></b> #bold text
<abbr title="World Health Organization">WHO</abbr> #The HTML <abbr> tag defines an abbreviation or an acronym, like "HTML", "CSS", "Mr.", "Dr.", "ASAP", "ATM"
<address></address> #Address
 <cite></cite> #tag defines the title of a creative work (e.g. a book, a poem, a song, a movie, a painting, a sculpture, etc.).
<strong></strong> #importent text
<i></i> #italic
<em> # Emphasized text
<mark> # Marked text
<small> # Smaller text
<ins> #Inserted text
<sub></sub> #the text is under the line
<sup></sup> #the text is upper the line
<del></del> #the text del the line
<!-- --> #this is a command tag
<q></q> #quates tag
<blockquates></blockquates> #the space to the blockquate
<a href="https://google.com"> #attribute link html
<img src="w3schools.jpg" alt="W3Schools.com" width="104" height="142">#image tag html
<div></div> #is a block element
<article></article> #block element
<section></section> #some many block elements
<header></header>
<nav></nav> #nav bar
<section> #Defines a section in a document,Chapters,Introduction,News items,Contact information

<article> #Defines an independent, self-contained content,Examples of where the <article> element can be used:,Forum posts,Blog posts,User comments,Product cards,Newspaper articles
<aside> #Defines content aside from the content (like a sidebar)
<footer> # Defines a footer for a document or a section
<details> #Defines additional details that the user can open and close on demand
<summary> #Defines a heading for the <details> element
<br># new line
<hr> # tag is a border botom to line
 <pre> #element defines preformatted text.Poem
 <bdo dir="rtl">This</bdo> # right to left text
 <code>#HTML contains several elements for defining user input and computer code.
 <kbd> #element is used to define keyboard input

<tagname style="property:value;"> #The property is a CSS property. The value is a CSS value.

<a href="https://www.w3schools.com/" target="_blank">Visit W3Schools!</a> #target=_self,_blank,_parent,_top

<button onclick="document.location='default.asp'">HTML</button> #to use an HTML button as a link, you have to add some JavaScript code.


<table></table> #table
<tr></tr> #table row
<th></th> #table head
<td></td> #table data

<ul></ul> #unorder Bullet list
<li></li>
<ol></ol> # order 1 list

<dl>#Description  List
<dt>Coffee</dt>#defines the term (name),
<dd>-black hot tea</dd> #describes each term:
</dl>

<iframe>#Defines an inline frame

````

### Block-element And Inlie

```bash
#Block-element
<address>
<article>
<aside>
<blockquote>
<canvas>
<dd>
<div>
<dl>
<dt>
<fieldset>
<figcaption>
<figure>
<footer>
<form>
<h1>-<h6>
<header>
<hr>
<li>
<main>
<nav>
<noscript>
<ol>
<p>
<pre>
<section>
<table>
<tfoot>
<ul>
<video>

#Inline Elements
<a>
<abbr>
<acronym>
<b>
<bdo>
<big>
<br>
<button>
<cite>
<code>
<dfn>
<em>
<i>
<img>
<input>
<kbd>
<label>
<map>
<object>
<output>
<q>
<samp>
<script>
<select>
<small>
<span>
<strong>
<sub>
<sup>
<textarea>
<time>
<tt>
<var>

```

### The HTML <meta> Element

```bash

<meta charset="UTF-8"> #Define the character set used:
<meta name="keywords" content="HTML, CSS, JavaScript">#Define keywords for search engines:
<meta name="description" content="Free Web tutorials">#Define a description of your web page:
<meta name="author" content="John Doe">#Define the author of a page:
<meta http-equiv="refresh" content="30">#Refresh document every 30 seconds:
<meta name="viewport" content="width=device-width, initial-scale=1.0">#Setting the viewport to make your website look good on all devices:
```
