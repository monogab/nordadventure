1. basic structure:

<!DOCTYPE html>

<html>

  <head>
    <title>Page Title</title>
  </head>

  <body>
    <h1>This is a Heading</h1>
    <p>This is a paragraph.</p>

  </body>

</html>


2. Html elements 

<tagname attributes>Content goes here...</tagname>

e.g.

<p class="class1">My first paragraph.</p>

rules : 
I Nested HTML Elements

<p>My first <bold>parag</bold>raph.</p>

II Do Not Forget the End Tag!!!


III Empty HTML Elements

e.g.

<br> or <br />


IIV. Use Lowercase Tags

3. Html attributes
e.g.
<a href="https://www.w3schools.com">This is a link</a>
<img src="img_girl.jpg" width="500" height="600">
<img src="img_girl.jpg" alt="Girl with a jacket">
<p style="color:red">I am a paragraph</p>
<p title="I'm a tooltip">



4. Important elements : 

heading
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>


paragrah
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>

preformat
<pre>
  My Bonnie lies over the ocean.

  My Bonnie lies over the sea.

  My Bonnie lies over the ocean.

  Oh, bring back my Bonnie to me.
</pre>

formating
<b> - Bold text
<strong> - Important text
<i> - Italic text
<em> - Emphasized text
<mark> - Marked text
<small> - Small text
<del> - Deleted text
<ins> - Inserted text
<sub> - Subscript text
<sup> - Superscript text

<!-- This is a comment -->


<a href="url">link text</a>


<img src="html5.gif" alt="HTML5 Icon" style="width:128px;height:128px;">
<img src="html5.gif" alt="HTML5 Icon" width="128" height="128">
<img src="/images/html5.gif" alt="HTML5 Icon" style="width:128px;height:128px;">
<img src="https://www.w3schools.com/images/w3schools_green.jpg" alt="W3Schools.com">
<img src="programming.gif" alt="Computer Man" style="width:48px;height:48px;">

image as a link
<a href="default.asp">
  <img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;border:0;">
</a>

background image
<body style="background-image:url('clouds.jpg')">


resolution dependent pictures
<picture>
  <source media="(min-width: 650px)" srcset="img_pink_flowers.jpg">
  <source media="(min-width: 465px)" srcset="img_white_flower.jpg">
  <img src="img_orange_flowers.jpg" alt="Flowers" style="width:auto;">
</picture>


tables
<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th> 
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td> 
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td> 
    <td>94</td>
  </tr>
</table>

list 
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>

<!-- type can be 1 A a I i -->
<ol type="1">
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

nestling
<ul>
  <li>Coffee</li>
  <li>Tea
    <ul>
      <li>Black tea</li>
      <li>Green tea</li>
    </ul>
  </li>
  <li>Milk</li>
</ul>


blocks
<p>
<div>
<span>    
<figure>
<footer>
<form>
<h1>-<h6>
<header>
<section>
<table>
