# WebDevelopment-Document-HTML5

### TOPICS
----
#### Basic Content and Tags of HTML
#### Basic Tags
#### Various tags exist in HTML
#### Block Level Elements
#### Inline Elements
#### Semantic Elements
#### Forms in HTML
#### Form Controls
#### Placeholders,id,name,required Properties
#### Form Methods
----

##### Why Learn HTML?
HTML is the foundation of all web pages. Without HTML, you wouldn’t be able to organize text or add images or videos to your web pages. HTML is the beginning of everything you need to know to create engaging web pages!.We can create a static website by HTML only.

HTML is a **markup language** i.e., it is a way for the computers to communicate with each other, to control how text is processed and presented. A website will be opened on various systems with different browsers and the markup language ensures that the website looks the same in all the systems by the help of its various tags. The latest is the HTML5 and now it has a lot of features which are widely used to format web pages.

HTML stands for **Hypertext Markup Language** Let's understand each word-

**Hypertext:** Hypertext is a text that has a link within it, clicking on which will bring the user to a new page. Apart from text, hypertext may contain tables, lists, forms, images, etc.

**Markup language:** A Markup language is the one that uses tags to define elements within a document. It contain standard words which are human readable like forms, tables, link, title and so on. Every tag in a markup language has a special meaning of its own and performs a particular operation.

#### Here is what you can do with HTML-

* Create structure of Web Page or Website.
* It has tags which can help you to optimize the website, to boost the performance and give good results.
* It is the base of designing and developing web pages, once you understand the basic of HTML then other related technologies like Javascript, CSS, etc become easier to understand.
* HTML pages are platform independent and they work on mobile, tabs, desktop, etc.
* You can create offline pages which can load even with no internet.
* HTML 5 can give support in enhancing the experience in gaming arena.
* Every known browser available today, supports HTML.

#### Applications of HTML

**Web pages development** - HTML is used to create pages which are rendered over the web. Almost every page of web is having html tags in it to render its details in browser.

**Internet Navigation** - HTML provides tags which are used to navigate from one page to another and is heavily used in internet navigation.

**Responsive UI** - HTML pages now-a-days works well on all platform, mobile, tabs, desktop or laptops owing to responsive design strategy.

**Offline support** - HTML pages once loaded can be made available offline on the machine without any need of internet.

**Game development** - HTML5 has native support for rich experience and is now useful in gaming developent arena as well.


#### Software Requirement:( In following Softwares we need any one required )
* [Notepad](https://www.google.com/)
* [Notepad++](https://notepad-plus-plus.org/downloads/)
* [Edit-Plus](https://www.editplus.com/download.html)
* [HTML-Kit](http://www.htmlkit.com/)
* [Sublime](https://www.sublimetext.com/3)
* [Bluefish](http://bluefish.openoffice.nl/index.html)
* [CoffeeCup](https://www.coffeecup.com/)

**Download Required Software by Click on Above Names**  or **You can Use online Editor**[ --> Online-Editor](https://www.coderepublics.com/tryit/tryit.php?name=html-examples/html-basic-example.php)

**Rules of HTML**
* Save the file with **.html** extension Example:- registerpage.html
* Use inbuilt tags only
* For Paired Tags You must close with respective closing tag

#### Basic Structure Of HTML

```html
<!DOCTYPE html>
<html>
<head>
	<title><!-- Write title here --></title>
</head>
<body>
<!-- Write the code here -->
</body>
</html> 
```

#### Explanation

```html
<!DOCTYPE>: It defines the document type of HTML version.
<html>: It is the root element that describes the web document. It is a paired tag, i.e., it has a closing tag also, </html>. Everything will be written inside these tags.
<head>: It contains informations about the document like its title, author information, description of the website, etc. It has different tags to perform these functions. It is also a paired tag.
<title>: It is used inside <head> and it specifies the title of the document.
<body>: It contains all the information which will be displayed in the webpage. If you want anything to be displayed on the webpage you have to write it within this tag.
```

### HTML Tags
Every HTML tag has a special meaning to the browser. Each tag performs its own function and helps in creating the proper structure of a web page. You can't create ur own tags, all tags are predefined.

Syntax:
```html
<tag> Content </tag>
```
Different Types of Tags Avaiable in HTML5 [Click here A-Z Tags in HTML](https://www.w3schools.com/tags/tag_comment.asp)

#### Types of Tags
* Paired Tags
* Unpaired Tags

##### Paired Tags
Paired tags are those tags that comes in pair. They have an opening and a closing tag.

Syntax: 
```html 
<tag> Content </tag>
```
###### Some Paired Tags are:
```html 
 <html> </html>
 <table> </table>
 <form> </form>
 <span> </span>
 <p> </p>
```
##### Unpaired Tags
Unpaired tags do not have a closing tag. These are opened same as paired tags but do not have to be closed.

##### Some Unpaired Tags are:
```html
<!DOCTYPE>
<br>
<hr>
<meta>
<input>
```
### Basic HTML Tags

##### Block level elements:
* H1,h2,...,h6
* Div
* P
* Semantic elements

##### Semantic Elements
* Header
* Section
* Article
* Aside
* Footer
* Nav
* Main

##### Inline elements :
* Span
* Img
* Form controls (iput, select, button, submit)
* Navigation (a, href)
* In bound (With in the page)
* Outer bound (between pages)
* Mail to (Email address)
* Tel (Phone number)

#### HTML Heading Tag
Heading tag is used to give headings of particular sizes in a document. There are six different HTML heading tags, which gives different heading sizes and are defined by ```html <h1> to <h6> tags. <h1> gives the largest heading and <h6> gives the smallest one. So <h1> can be used for most important headings and <h6>``` can be used for least important one.
  
##### Example for Heading Tags 

```html
<!DOCTYPE html>
<html lang="en"> 
<!-- lang indicates language 
en indicates english
-->
<head>
	<title>Heading Tags Example </title>
</head>
<body>
	<h1>Heading size1</h1>
	<h2>Heading size2</h2>
	<h3>Heading size3</h3>
	<h4>Heading size4</h4>
	<h5>Heading size5</h5>
	<h6>Heading size6</h6>
</body>
</html>
```
###### Output
![Output](https://github.com/SIVARANGA/WebDevelopment-Document-HTML5/blob/master/htags.PNG?raw=true)


##### HTML Paragraph Tag
The ```html <p> tag is used to define a paragraph in a document. HTML paragraph or HTML <p>``` tag gives the text inside it, a paragraph like finishing. It is a notable point that a browser itself add an empty line before and after a paragraph.

##### Example for Paragraph Tag

```html
<!DOCTYPE html>
<html>
<head>
	<title>Paragraph Example </title>
</head>
<body>
	<p> This is used for writing paragraph.This tag tag gives the text inside it, a paragraph like finishing. It is a notable point that a browser itself add an empty line before and after a paragraph. </p>
</body>
</html>
```
##### Output
![Output](https://github.com/SIVARANGA/WebDevelopment-Document-HTML5/blob/master/para.PNG?raw=true)


##### Div Tag

The ```html <div> tag defines a division or a section in an HTML document.
The <div> tag is used as a container for HTML elements - which is then styled with CSS or manipulated with JavaScript.
The <div> tag is easily styled by using the class or id attribute.
Any sort of content can be put inside the <div> tag! 
Note: By default, browsers always place a line break before and after the <div>``` element.

##### Example

```html
<html>
<head>
<style>
.myDiv {
  border: 5px outset red;
  background-color: lightblue;
  text-align: center;
}
</style>
</head>
<body>

<div class="myDiv">
  <h2>This is a heading in a div element</h2>
  <p>This is some text in a div element.</p>
</div>

</body>
</html>
```
#### Semantic elements:

##### Header

The  header element represents a container for introductory content or a set of navigational links.
A header element typically contains:
* one or more heading elements ```html <h1> - <h6>```
* logo or icon
* authorship information
Note: You can have several ```html <header> elements in one HTML document. However, <header> cannot be placed within a <footer>, <address> or another <header>``` element.

##### Section

The ```html <section> tag defines sections in a document, such as chapters, headers, footers, or any other sections of the document.
The  <section> tag also supports the Global Attributes in HTML.
The  <section> ``` tag also supports the Event Attributes in HTML.

##### Example

```html
<!DOCTYPE html>
<html>
<body>

<h1>The section element</h1>

<section>
  <h2>WWF</h2>
  <p>The World Wide Fund for Nature (WWF) is an international organization working on issues regarding the conservation, research and restoration of the environment, formerly named the World Wildlife Fund. WWF was founded in 1961.</p>
</section>

<section>
  <h2>WWF's Panda symbol</h2>
  <p>The Panda has become the symbol of WWF. The well-known panda logo of WWF originated from a panda named Chi Chi that was transferred from the Beijing Zoo to the London Zoo in the same year of the establishment of WWF.</p>
</section>

</body>
</html>
```
##### HTML Article

The HTML ```html <article>``` tag defines an independent self-contained content in a document. It usually works like a normal div, but is given special name and used as an area where specifically articles should be written.

This tag is usually used on blog post, Forum post, comments etc.

##### Example

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <title> HTML Article Tag </title>
</head>
<body>
<article>  
<h2>Linux OS</h2>
<i>(Operating System) </i>
<p>Linux is a free open-source Operating System, built around the Linux Kernel.
Linus Torvalds is the Father of Linux.</p>  
</article>
</body>
</html>
```
##### Aside Tag:

The ```html <aside>``` tag defines some content aside from the content it is placed in.

The aside content should be indirectly related to the surrounding content.

Tip: The <aside> content is often placed as a sidebar in a document.

Note: The <aside> element does not render as anything special in a browser. However, you can use CSS to style the <aside> element (see example below).

##### Example:

```html
<!DOCTYPE html>
<html>
<body>

<h1>The aside element</h1>

<p>My family and I visited The Epcot center this summer. The weather was nice, and Epcot was amazing! I had a great summer together with my family!</p>

<aside>
  <h4>Epcot Center</h4>
  <p>Epcot is a theme park at Walt Disney World Resort featuring exciting attractions, international pavilions, award-winning fireworks and seasonal special events.</p>
</aside>

</body>
</html>
```

##### HTML Footer Tag
The HTML ```html <footer> ``` tag was introduced in HTML 5. It is used to define a footer for a document or a section. It is specifically used for defining footer at the bottom of the webpage.

##### A Footer element contains:
* Copyright information
* Contact information
* Related documents
* Back to top links
* Sitemap

##### Example
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <title> HTML Footer Tag </title>
</head>
<body>
<footer>
  <p>Posted by: Bill Gates</p>
  <p>Contact information: <a href="mailto:someone@example.com">someone@example.com</a>.</p>
</footer>
</body>
</html>
```
###### Nav Tag:
The ```html <nav> ``` tag defines a set of navigation links.
Notice that NOT all links of a document should be inside a <nav> element. The <nav> element is intended only for major block of navigation links.
Browsers, such as screen readers for disabled users, can use this element to determine whether to omit the initial rendering of this content.

##### Example

```html
<!DOCTYPE html>
<html>
<body>

<h1>The nav element</h1>

<p>The nav element defines a set of navigation links:</p>

<nav>
<a href="https://www.google.com/">Google</a> |
<a href="https://www.google.com/intl/en-GB/gmail/about/#/">G-Mail</a> |
<a href="https://www.w3schools.com/html/default.asp">HTML</a> |
<a href="https://www.w3schools.com/python/default.asp">Python</a>
</nav>

</body>
</html>
```
##### Main Tag:
The ```html <main>``` tag specifies the main content of a document.

The content inside the ```html <main>``` element should be unique to the document. It should not contain any content that is repeated across documents such as sidebars, navigation links, copyright information, site logos, and search forms.

Note: There must not be more than one ```html <main> element in a document. The <main> element must NOT be a descendant of an <article>, <aside>, <footer>, <header>, or <nav>``` element.

##### Example
```html
<!DOCTYPE html>
<html>
<body>

<h1>The main element</h1>

<main>
  <h2>Web Browsers</h2>
  <p>Chrome, Firefox, and Edge are the most used browsers today.</p>

  <article>
    <h3>Google Chrome</h3>
    <p>Chrome is a free, open-source web browser developed by Google, released in 2008.</p>
  </article>

  <article>
    <h3>Microsoft Edge</h3>
    <p>Edge is a free web browser from Microsoft, released in 1995.</p>
  </article>

  <article>
    <h3>Mozilla Firefox</h3>
    <p>Firefox is a free, open-source web browser from Mozilla, released in 2004.</p>
  </article>
</main>

<p><strong>Note:</strong> The main tag is not supported in Internet Explorer 11 and earlier versions.</p>

</body>
</html>
```

##### Span Tag:
The ```html <span>``` tag is an inline container used to mark up a part of a text, or a part of a document.

The ```html <span>``` tag provides no visual change by itself, but when it is marked, you can style it with CSS, or manipulate it with JavaScript.

##### Example
```html
<!DOCTYPE html>
<html>
<body>

<h1>The span element</h1>

<p>My mother has <span style="color:blue;font-weight:bold">blue</span> eyes and my father has <span style="color:darkolivegreen;font-weight:bold">dark green</span> eyes.</p>

</body>
</html>
```

#### Navigation(a,href)

###### Inbound 
A navigation bar needs standard HTML as a base.

In our examples we will build the navigation bar from a standard HTML list.
There are two ways to create a horizontal navigation bar. Using inline or floating list items.
A navigation bar is basically a list of links, so using the <ul> and <li> elements makes perfect sense:

##### Example	
```html
<!DOCTYPE html>
<html>
<body>

<ul>
  <li><a href="#home">Home</a></li>
  <li><a href="#news">News</a></li>
  <li><a href="#contact">Contact</a></li>
  <li><a href="#about">About</a></li>
</ul>

<p>Note: We use href="#" for test links. In a real web site this would be URLs.</p>

</body>
</html>
```

###### Outer bound


#### HTML Anchor Tag

HTML link is defined with the ```html <a>``` tag (Anchor tag). It is used to give link to any other file, webpage, image etc.

This tag is called anchor tag and anything between the opening ```html <a> tag and the closing </a> ``` tag becomes part of the link and a user can click that part to reach to the linked document.

##### Example on Anchor Tag

```html
<!DOCTYPE html>
<html>
<head>
	<title>Anchor tag Example page </title>
</head>
<body>
	<a href="https://www.google.com/">Click here to goto Google page </a>
</body>
</html>
```
##### Output
![Output](https://github.com/SIVARANGA/WebDevelopment-Document-HTML5/blob/master/anch.PNG?raw=true)

#### HTML Image Tag
The Image Tag is used to add Images in HTML documents. The HTML ```html <img> ``` tag is used to add image in a document.The 'src' attribute is used to give source(address) of the image. The height and width of the image can be controlled by the attributes - height="px" and width="px". The 'alt' attribute is used as an alternative in a case if the image is not shown.

##### Example On Image Tag

```html
<!DOCTYPE html>
<html>
<head>
	<title>Image Tag Page </title>
</head>
<body>
	<img src="https://image.shutterstock.com/image-photo/bright-spring-view-cameo-island-260nw-1048185397.jpg" height="200px" height="400px">
</body>
</html>
```
#### HTML Formatting Tags
HTML Formatting is a process of changing appearance of text for better look and feel than the default text. The formatting tags are used to make text bold, italic, underlined, etc. There are almost 12 options available that how text appears in HTML.

**Some tags are:**
```html
Bold Text -- <b>
Italic Text -- <i>
Underlined Text -- <u>
Important Text -- <strong>
Small Text -- <small>
Big Text -- <big>
Mark Text -- <mark>
Emphasized Text -- <em>
Deleted Text -- <del>
Inserted Text -- <ins>
Subscripted Text -- <sub>
Superscripted Text -- <sup>
```
##### Output
![output](https://github.com/SIVARANGA/WebDevelopment-Document-HTML5/blob/master/format.PNG?raw=true)

#### HTML Table
An HTML table is defined with the ```html <table> ``` tag. A table is used to display data in tabular form (rows * column). It is a paired tag. Just use these tags with their attributes to create tables. You can also use CSS stylesheet to beautify these structures. A table structure is represented in ‘rows*columns’ form, i.e. a ‘4*5’ table represents a table with 4 rows and 5 columns.

Tables are also used in websites to present any data to the user. It looks really neat and also everyone prefers tabular form of data nowadays. The HTML tables allows to arrange data like text, images, etc. into rows and columns.

##### Tags of Table:
```html
<table></table> <!-- Table Main Tag -->
	<thead></thead> <!--Table Header tags -->
	<tr></tr> <!-- Table row Tag -->
	<th></th> <!--Table Heafer Name Tag -->
	<tbody></tbody> <!-- Table Tag -->
	<td></td> <!-- Table Data Tag -->
```
##### Example On Table

```html
<!DOCTYPE html>
<html>
<head>
	<title>Sample Table Example </title>
</head>
<body>
	<table>
		<thead>
			<tr>
				<th>Header_Name1</th>
				<th>Header_Name2</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>Row1_Value1</td>
				<td>Row1_value2</td>
			</tr>
			<tr>
				<td>Row2_value1</td>
				<td>Row2_value2</td>
			</tr>
		</tbody>
	</table>
</body>
</html>
```

##### Output
![Output](https://github.com/SIVARANGA/WebDevelopment-Document-HTML5/blob/master/tab1.PNG?raw=true)

**imp: You can Apply CSS for tables based on your Requirement**

##### Example2
```html
<!DOCTYPE html>
<html>
<head>
	<title>Table Example </title>
</head>
<body>
	<table>
		<thead>
			<tr>
				<th> Name </th>
				<th>Salary</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>Hari</td>
				<td>25000</td>
			</tr>
			<tr>
				<td>Krishna</td>
				<td>36000</td>
			</tr>
		</tbody>
	</table>
</body>
</html>
```
##### Output
![Output](https://github.com/SIVARANGA/WebDevelopment-Document-HTML5/blob/master/tab2.PNG?raw=true)

##### Example

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <title> HTML Table Border Attribute </title>
 </head>
<body> 
<table border="1" width="40%"> <!-- Here applied border and width of the table -->
<tr> 
    <th> Name </th> 
    <th> Salary </th> 
    <th> Age </th> 
</tr> 
<tr> 
    <td> Anshuman </td> 
    <td> Rs. 2,00,000 </td> 
    <td> 25 </td> 
</tr> 
<tr> 
    <td> Kuldeep </td>
     <td> Rs. 5,00,000 </td> 
    <td> 22 </td> 
</tr> 
</table>
</body>
</html>
```

##### Output
![Output](https://github.com/SIVARANGA/WebDevelopment-Document-HTML5/blob/master/tab3.PNG?raw=true)

**You can Apply** 
* The 'Cellpadding' and 'Cellspacing' Attribute
* These "cellpadding" and "Cellspacing" attributes are used to adjust the white spaces in your table cells.
* colspan,Rowspan attributes

##### HTML Font Size
We can set font size using size attribute.
* The range of accepted values is from 1 to 7.
* The default size of a font is 3.

##### Example
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <title> HTML Font Size </title>
</head>
<body>
<font size="1">Hello HTML 5!</font>
<font size="2">Hello HTML 5!</font>
<font size="3">Hello HTML 5!</font>
<font size="4">Hello HTML 5!</font>
<font size="5">Hello HTML 5!</font>
<font size="6">Hello HTML 5!</font>
<font size="7">Hello HTML 5!</font>
</body>
</html>
```

##### Font Face
You can set font face using face attribute but be aware that if the user viewing the page doesn't have the font installed, they will not be able to see it. Instead user will see the default font style.

##### Example
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <title>HTML Font Face Attribute </title>
</head>
<body>
<font face="Times New Roman" size="5">Times New Roman</font><br>
<font face="Verdana" size="5">Verdana</font><br>
<font face="Comic sans MS" size="5">Comic Sans MS</font><br>
<font face="WildWest" size="5">WildWest</font><br>
<font face="Bedrock" size="5">Bedrock</font><br>
</body>
</html>
```
##### Output
![Output](https://github.com/SIVARANGA/WebDevelopment-Document-HTML5/blob/master/font.PNG?raw=true)

#### Ordered List in HTML
This list is created by using ```html <ol> ``` tag. Any series can be used to order the elements, like series of digits, alphabets, roman numerals, etc. All these series gets increased by one with every new element entered in the list.

Ex.-For a numbered order list, the numbering starts at one and is incremented by one for each successive ordered list element tagged with ```html <li>```.

##### Example

```html
<!DOCTYPE html>
<html>
<head>
	<title>Order List</title>
</head>
<body>
	<h4>This is Order List </h4>
  <ol> <!-- Here you can mention starting value Ex:<ol start="100"> </ol> -->
		<li>First</li>
		<li>Second</li>
		<li>Third</li>
	</ol>
</body>
</html>
```
##### Output

![Output](https://github.com/SIVARANGA/WebDevelopment-Document-HTML5/blob/master/order.PNG?raw=true)

##### Ordered list Type Attribute
The type attribute is used to change the series type.
* type="1"	The list items will be numbered with numbers (default).
* type="A"	The list items will be numbered with uppercase letters.
* type="a"	The list items will be numbered with lowercase letters.
* type="I"	The list items will be numbered with uppercase roman numbers.
* type="i"	The list items will be numbered with lowercase roman numbers.

##### Example:

```html
<!DOCTYPE html>
<html>
<head>
	<title>Order List</title>
</head>
<body>
	<h4>This is Order List </h4>
	<ol type="A"> 
		<li>First</li>
		<li>Second</li>
		<li>Third</li>
	</ol>
</body>
</html>
```

##### Output
![Output](https://github.com/SIVARANGA/WebDevelopment-Document-HTML5/blob/master/order2.PNG?raw=true)


##### Unordered List:
An unordered list is a collection of related items that are listed with no special order or sequence. This list is created by using HTML ```html <ul> tag. Each item in the list is marked with a bullet. Each item starts with <li>``` tag.

##### Example:
```html
<!DOCTYPE html>
<html>
<head>
	<title>Unordered List Example </title>
</head>
<body>
	<h4>Unordered List Example </h4>
	<ul>
		<li>Line1</li>
		<li>Line2</li>
		<li>Line3</li>
	</ul>
</body>
</html>
```
##### Output
![Output](https://github.com/SIVARANGA/WebDevelopment-Document-HTML5/blob/master/unorder.PNG?raw=true)

##### Unorder List Type Attribute
**The type attribute is used to change the series type.**
* type="disc"	Sets the list item marker to a bullet (default).
* type="circle"	Sets the list item marker to a circle.
* type="square"	Sets the list item marker to a square.
* type="none"	The list items will not be marked.

##### Example
```html
<!DOCTYPE html>
<html>
<head>
	<title>Unordered List Example </title>
</head>
<body>
	<h4>Unordered List Example </h4>
	<ul type="square">
		<li>Line1</li>
		<li>Line2</li>
		<li>Line3</li>
	</ul>
</body>
</html>
```

##### Output

![Output](https://github.com/SIVARANGA/WebDevelopment-Document-HTML5/blob/master/unorder2.PNG?raw=true)

#### HTML form Tag:
An HTML form is a section of a document which contains different fields like **text fields, password fields, checkboxes, radio buttons, submit button, menus** etc.

HTML Forms can be used where we want to collect some data from the site visitor. For example, in case of user registration you would like to collect information such as **name, email address, Phone number,** etc.

##### HTML Forms Elements
```html
* <form>	It defines an HTML form to enter inputs by the used side.
* <input>	It defines an input control.
* <select>	It defines a multi-line input control.
* <option>	It defines an option in a drop-down list.
* <textarea>	It defines a drop-down list.
* <button>	It defines a label for an input element.
* <fieldset>	It groups the related element in a form.
* <legend>	It defines a caption for a <fieldset> element.
* <optgroup>	It defines a group of related options in a drop-down list.
* <label>	It defines a label for a field.
  ```

##### HTML Form Structure
The HTML ```html <form> tag defines a form that is used to collect user input. All the form elements should be written inside <form> and </form>```  tags.

Syntax:
```html
<form>
	........
	
	Form Elements
	........
</form>
```
#### HTML Form Elements
##### 'Input' Element:
The most important form element is the ```html <input> element. The <input>``` element can be displayed in several ways, depending on the type attribute.
Syntax: ```html <input type="value">```

##### HTML```html <input>``` type Attribute:

Attribute_Values --> Value_Description
* **button** --> Defines a clickable button (mostly used with a JavaScript to activate a script)
* **checkbox** --> Defines a checkbox
* **color** --> Defines a color picker
* **date** --> Defines a date control (year, month, day (no time))
* **datetime-local** --> Defines a date and time control (year, month, day, time (no timezone)
* **email** --> Defines a field for an e-mail address
* **file** --> Defines a file-select field and a "Browse" button (for file uploads)
* **hidden** --> Defines a hidden input field
* **image** -->	Defines an image as the submit button
* **month** --> Defines a month and year control (no timezone)
* **number** --> Defines a field for entering a number
* **password** --> Defines a password field
* **radio** --> Defines a radio button
* **range** --> Defines a range control (like a slider control)
* **reset** --> Defines a reset button
* **search** --> Defines a text field for entering a search string
* **submit** --> Defines a submit button
* **tel** --> Defines a field for entering a telephone number
* **text** --> Default. Defines a single-line text field
* **time** --> Defines a control for entering a time (no timezone)
* **url** -->	Defines a field for entering a URL
* **week** --> Defines a week and year control (no timezone)

##### HTML Input Type
Here is a list of some common HTML Form input types.

Type	Description
* **text:**	It defines a one-line text input field.
* **password:**	Defines a one-line password input field.
* **submit:**	It specifies a submit button to submit the form to server.
* **reset:**	The reset button reset all values in the form.
* **radio:**	A Radio button allows select one option.
* **checkbox:**	Checkboxes allow selecting multiple options form.
* **button:**	Defines a clickable button, which can perform a task on an event.
* **file:**	It defines to select the file from device storage.
* **image:**	It Defines a graphical submit button.

##### Example1:
```html
<!DOCTYPE html>
<html>
<head>
	<title>Input Tag Example</title>
</head>
<body>
	User Name: <input type="text" name="username">
</body>
</html>
```
##### Output:
![Output](https://github.com/SIVARANGA/WebDevelopment-Document-HTML5/blob/master/input1.PNG?raw=true)

##### Example2:
```html
<!DOCTYPE html>
<html>
<head>
	<title>Input Tag Example</title>
</head>
<body>
	User Name: <input type="text" name="username"><br>
	<input type="submit" name="submit" value="Click Here"><br>
	<input type="submit" name="button" value="cancel">
</body>
</html>
```
##### Output:
![Output](https://github.com/SIVARANGA/WebDevelopment-Document-HTML5/blob/master/input2.PNG?raw=true)

##### Example3:
```html
<!DOCTYPE html>
<html>
<head>
	<title>Input Tag Example</title>
</head>
<body>
	User Name: <input type="text" name="username"><br>
	Birthday:<input type="date" id="birthday" name="birthday"><br><br>
	<input type="submit" name="submit"><br>
	<input type="button" name="button" value="cancel">
</body>
</html>
```
##### Output:
![Output](https://github.com/SIVARANGA/WebDevelopment-Document-HTML5/blob/master/input3.PNG?raw=true)

##### Checkbox & Radiobutton:
##### Example:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title> HTML Form Input Type Radio Button & Checkbox </title>
</head>
<body>
<form>
	 <!-- Radio Button input type -->
  <h4>This is Radio Button Example </h4>
  <input type="radio" name="gender" value="male" checked> Male<br>
  <input type="radio" name="gender" value="female"> Female<br>
  <input type="radio" name="gender" value="other"> Other<br><br>
  <input type="submit">
  <br> <br> <br> <!-- This is for new line access purpose -->
   <!-- Checkbox input type -->
  <h4>This is checkbox Example </h4>
  <input type="checkbox" name="vehicle1" value="Bike">Samsung
  <input type="checkbox" name="vehicle2" value="Car">Google Pixel<br><br>
  <input type="submit">
</form> 
</body>
</html>
```

##### Output:

![Output](https://github.com/SIVARANGA/WebDevelopment-Document-HTML5/blob/master/radioandcheckbox.PNG?raw=true)

##### Example:
```html
<!DOCTYPE html>
<html>
<head>
	<title>Input Attribute Values </title>
</head>
<body>
	<form>
		Enter Mail: <input type="email" id="email" name="email"><br><br>
		Enter mobile Number: <input type="tel" id="phone" name="phone" pattern="[0-9]{3}-[0-9]{2}-[0-9]{3}"><br><br>
		Enter Date & Time: <input type="datetime-local" id="birthdaytime" name="birthdaytime"><br><br>
		Enter Time: <input type="time" id="appt" name="appt"><br><br>
		Enter Number: <input type="number" id="quantity" name="quantity" min="1" max="5"><br><br>
		Enter Password: <input type="password" id="pwd" name="pwd"><br><br>
	</form>
</body>
</html>
```
##### Output:
![Output](https://github.com/SIVARANGA/WebDevelopment-Document-HTML5/blob/master/input_attr1.PNG?raw=true)

##### Example:
```html
<!DOCTYPE html>
<html>
<head>
	<title>Input Attribute Values </title>
</head>
<body>
	<form>
		Select Range: <input type="range" id="vol" name="vol" min="0" max="50"><br><br>
		Enter url: <input type="url" id="homepage" name="homepage"><br><br>
		Choose File: <input type="file" id="myfile" name="myfile"><br><br>
		Select Image: <input type="image" src="https://github.com/SIVARANGA/WebDevelopment-Document-HTML5/blob/master/cat.jpg?				raw=true" alt="Problem with image" width="48" height="48"><br><br>
		Select Color:<input type="color" id="favcolor" name="favcolor" value="#ff0000"><br><br>
		Search Here: <input type="search" id="gsearch" name="gsearch"><br><br>
	</form>
</body>
</html>
```

##### Output:
```html
<!DOCTYPE html>
<html>
<head>
	<title>Input Attribute Values </title>
</head>
<body>
	<form>
		Select Range: <input type="range" id="vol" name="vol" min="0" max="50"><br><br>
		Enter url: <input type="url" id="homepage" name="homepage"><br><br>
		Choose File: <input type="file" id="myfile" name="myfile"><br><br>
		Select Image: <input type="image" src="https://github.com/SIVARANGA/WebDevelopment-Document-HTML5/blob/master/cat.jpg?				raw=true" alt="Problem with image" width="48" height="48"><br><br>
		Select Color:<input type="color" id="favcolor" name="favcolor" value="#ff0000"><br><br>
		Search Here: <input type="search" id="gsearch" name="gsearch"><br><br>
	</form>
</body>
</html>
```
##### Otput:
![Output](https://github.com/SIVARANGA/WebDevelopment-Document-HTML5/blob/master/input_attr2.PNG?raw=true)

##### Select Element
The ```html <select>``` element defines a drop-down list. It mostly used when you have to show numbers of items.

##### Example
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title> HTML Form Select Attribute </title>
</head>
<body>
<form>
 <select name="Cars">
 	<option value="select"> select </option>
    <option value="Audi"> Audi </option>
    <option value="Mercedes"> Mercedes </option>
    <option value="Lamborghini"> Lamborghini </option>
 </select>
  <input type="submit">
</form>
</body>
</html>
```
##### Output
![Output](https://github.com/SIVARANGA/WebDevelopment-Document-HTML5/blob/master/select.PNG?raw=true)

##### Textarea Element
The ```html <textarea>``` element defines a multi-line input field.

##### Example
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title> HTML Form Textarea Attribute </title>
</head>
<body>
<h2>Textarea</h2>
<p>The textarea element defines a multi-line input field.</p>
<form action="action-page.php">
  <textarea name="message" rows="5" cols="60"> This is a simple Example of Textarea. </textarea>
  <br>
  <input type="submit">
</form>
</body>
</html>
```
##### Output:
![Output](https://github.com/SIVARANGA/WebDevelopment-Document-HTML5/blob/master/testarea1.PNG?raw=true)

##### Button Element
The ```html <button>``` element defines a clickable button.

##### Example
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title> HTML Form Button Attribute </title>
</head>
<body>
	<button type="button" onclick="alert('Hello World..!')">Click Me!</button>
</body>
</html>
```
##### Output
![Output](https://github.com/SIVARANGA/WebDevelopment-Document-HTML5/blob/master/button.PNG?raw=true)

##### Method' Attribute
The method attribute specifies the HTTP method (GET or POST) to be used when submitting the form data.
The GET is the default method when you submitting your form data.

Syntax
```html
<form action="action-page.php" method="get">
<form action="action-page.php" method="post">
```

##### Name Attribute
The name attribute specifies the name of ```html <input>``` element. It is a good practice to use this attribute, and also good for SEO purpose.
##### Example
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title> HTML Form Name Attribute </title>
</head>
<body>
<form>
  First name:
  <input type="text" value="John"><br>
  Last name:
  <input type="text" name="lastname" value="Snow"><br>
  <input type="submit" value="Submit">
</form> 
</body>
</html>
```
##### Output
![Output](https://github.com/SIVARANGA/WebDevelopment-Document-HTML5/blob/master/button_se.PNG?raw=true)

##### Grouping Form Data with ```html <fieldset>
The <fieldset> element is used to group related data in a form and the <legend> element defines a caption for the <fieldset>``` element.
	
##### Example
```html

<!DOCTYPE html>
<html lang="en">
<head>
    <title> HTML Form Fieldset and Legend Attributes </title>
</head>
<body>
<form action="action-page.php">
  <fieldset>
    <legend>Personal information:</legend>
    First name:
    <input type="text" name="firstname" value="John">
    Last name:
    <input type="text" name="lastname" value="Snow">
    <input type="submit" value="Submit">
  </fieldset>
</form>
</body>
</html>
```
![Output](https://github.com/SIVARANGA/WebDevelopment-Document-HTML5/blob/master/field.PNG?raw=true)


##### Placeholder	
It gives a hint about the value to be entered in the ```html <input> ```element.
##### Required	
It specifies that an input field must be filled out before submitting the form.
##### Step	
It specifies the legal number intervals for an ```html <input>``` element.

##### HTML Break
The HTML ```html <br> tag or element breaks line in a paragraph. The <br>``` tag is an Unpaired tag which means that it has no end tag.

#### Form Method Attributes:

The method attribute specifies how to send form-data (the form-data is sent to the page specified in the action attribute).

The form-data can be sent as URL variables (with method="get") or as HTTP post transaction (with method="post").

##### Notes on GET:

* Appends form-data into the URL in name/value pairs
* The length of a URL is limited (about 3000 characters)
* Never use GET to send sensitive data! (will be visible in the URL)
* Useful for form submissions where a user wants to bookmark the result
* GET is better for non-secure data, like query strings in Google

##### Notes on POST:

* Appends form-data inside the body of the HTTP request (data is not shown in URL)
* Has no size limitations
* Form submissions with POST cannot be bookmarked

##### Attribute Values
Value --> Description
get  --> Default. Appends the form-data to the URL in name/value pairs: URL?name=value&name=value
post --> Sends the form-data as an HTTP post transaction

##### Id,Required
###### Id
The HTML id attribute is used to specify a unique id for an HTML element (the value must be unique within the HTML document).
The id attribute is used by CSS or JavaScript to perform certain tasks for the element with the specific id value.

In CSS, to select an element with a specific id, write a hash (#) character, followed by the id of the element.

Tip: The id attribute can be used on any HTML element.
Note: The id value is case-sensitive.
Note: The id value must contain at least one character, and must not contain whitespace (spaces, tabs, etc.).

##### Required
The required attribute is a boolean attribute.
When present, it specifies that an input field must be filled out before submitting the form.
Note: The required attribute works with the following input types: text, search, url, tel, email, password, date pickers, number, checkbox, radio, and file.

Syntax:
```html<input required>```
