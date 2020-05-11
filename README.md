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
* [Notepad]()
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
	<title></title>
</head>
<body>

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
```html
<!DOCTYPE html>
<html>
<head> 
  <!-- In this Head tag you can mention page title name and author details (This is comment line) -->
	<title>Here you can give title name for page </title>
</head>
<body>
<!-- Write your code here  -->
</body>
</html> 
```

### HTML Tags
Every HTML tag has a special meaning to the browser. Each tag performs its own function and helps in creating the proper structure of a web page. You can't create ur own tags, all tags are predefined.

**Syntax:**
```html
<tag> Content </tag>
```

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
**Output**
# This is Heading 1
## This is Heading 2
### This is Heading 3
#### This is Heading 4
##### This is Heading 5
###### This is Heading 6


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
```Output```
![Output](https://github.com/SIVARANGA/WebDevelopment-Document-HTML5/blob/master/para.PNG?raw=true)

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
**Output**
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

Tags of Table:
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

**Output**
![Output](https://github.com/SIVARANGA/WebDevelopment-Document-HTML5/blob/master/tab1.PNG?raw=true)

**imp: You can Apply CSS for tables based on your Requirement**

**Example2**
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
**Output**
![Output](https://github.com/SIVARANGA/WebDevelopment-Document-HTML5/blob/master/tab2.PNG?raw=true)

**Example**
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

**Output**
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

**Example**
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
**Output**
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
**Output**

![Output](https://github.com/SIVARANGA/WebDevelopment-Document-HTML5/blob/master/order.PNG?raw=true)

##### Ordered list Type Attribute
The type attribute is used to change the series type.
* type="1"	The list items will be numbered with numbers (default).
* type="A"	The list items will be numbered with uppercase letters.
* type="a"	The list items will be numbered with lowercase letters.
* type="I"	The list items will be numbered with uppercase roman numbers.
* type="i"	The list items will be numbered with lowercase roman numbers.

**Example:**
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

**Output**
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
**Output**
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

**Output**

![Output](https://github.com/SIVARANGA/WebDevelopment-Document-HTML5/blob/master/unorder2.PNG?raw=true)

#### HTML form Tag:
An HTML form is a section of a document which contains different fields like text fields, password fields, checkboxes, radio buttons, submit button, menus etc.

HTML Forms can be used where we want to collect some data from the site visitor. For example, in case of user registration you would like to collect information such as name, email address, Phone number, etc.

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
