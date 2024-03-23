# HTML-CSS
Html stands fo hyper text markup language
It is a document that contains text and is very easy to read.
Html is also known as a declarative language, that means it simply declares instructions for eaxample,"This is a paragraph" or "make a line break here”
Html Syntax
Html is all about tags
If you have an opening tag you need to also have a closing tag.
The closing tag is identified by a foward slash.
Inside the opening and closing tags we have what we call a content 
Therefore a set of tags with content in between them is called a markup element
The are some tags that do not have end tags and we call these empty elements ie Br(line break)
A line break does not need a closing tag we do not put anything in between
Html Capabilities-Trouble shooting and debbuging
Troubleshooting and debugging in html involves identifying and fixing issues that may arise in your web pages
Validation: ensures your html code follows the specifications by ising online validators like W3C markup validation service.
Browser developer tools: utilize browser devoper tools to inspect and debug html elements, styles and JavaScript
Html Attributes:
They are used to define characters of elements.
All html tags have some attributes with some default values
Attributes are usually made up of two parts the name and the value, name="value".
For example if you want to change the background color to red, your bgclor will be your name and value red
Aria Roles(Accessible Rich Internet Applicatiom)
Defines a way to make web content and web applications more accessible to people with disabilities.
Aria attributes are used or are added to the markup to better communicate control, names, roles and state information , with the aim of supporting people with disabilities that are using assistative technology usage.
Unusul characters 
In html some characters are special due to their reserved roles in the markup language.
Character entities represent special characters using entities for example &lt, for <.
UTF-8 Encoding : use proper character encoding for your html document.
Html navigation and linking
Html links are also known as hyperlinks, they allow you to navigate from one web page to another or different sections within the same page.
When we want to create a link we use the a element which stands for anchor.
To do this we need a href attribute with a URL enclosed in quotes.
Href stands for hypertext referencing.
The most important attribute of the <a>element is the href attribute which indicates the links destination.
Absolute URL contain the the full web address including the protocol, domain and path.They specify tha exact location of a resource on the internet
Relative URL, are specified in relation to the current pages URL, they only include the path to the resource making their shorter
URLs are often uses within the same Website to link the pages or resources within the site
Html-Working with graphics and images 
When we want to add an image we use the image element which is simply written as img.
We use the following syntax to add an image
<img src= "img.jpg"alt"brown dog" width "400” height "300"
There are four attributes you need to for every image:
The first one is the (src), which tells the browser which image file to load or path to the image
The second one is the (alt),which provides the description of the image. It identifies what is going tk show up if the image can't be found
Lastly, we have the width and the height attributes, which identifies the size of the image
There are four file fomarts commonly used in nowadays, each with it's own strengths and weaknesses when it comes to compressing images:
GIF,SVG,JPG,PNG.                    
Working with media
The audio element has both opening and closing tag unlike the image element
It uses the src attribute to provide the URL of the audio file
The following is the audio element:
<auio controls src "audio.mp3"></audio>
Working with videos
The video element has both opening and closing tag.
It's element is as follows:
<video src=video.mp4>
<embeded> is a tag that causes the browser itself to include the controls for the multimedia to automatically provide browser support.
Html content Identification
The lang attribute is used to specify the language of the website.
It's syntax or element is as follows
<html lang ="en-us">
The en-us is the lang attribute that means U.S english
DIVS AND SPAN
The div tag is used to make divisions of the content on web pages like text, images, header, footer, navigation bar etc
It is used as a block part of the webpages
Div element takes all the available width
The html span element is a generic inline container for inline elements and content
It is used to group elements for styling purposes(by using the class or Id attribute)
 WORKING WITH FORMS AND INTERACTIVE ELEMENTS
 An html form is used to collect user input.The user input is then sent to a server for processing.
 The html form element is used to create an html form for user input.
 The form element is a customer for different types of input elements: text fields, checkboxes, radio buttons, submit buttons etc
 Input elememt is the most used form element.
 Examples:
 Input type="text" displays a single line text input field.
 Input type="radio" displays a radio button for selection of one of many choices.
Input type="checkboxes" displays a checkbox for selecting zero or more of many choices.
Input type="submit" displays a submit button for submitting a form.
Input type="button" displays a declarable button.
ORGANAZING TABULAR INFORMATION IN HTML
BUILDING TABLES IN HTML:
 HTML tables allow web developers to arrange data into rows and columns.
To create ana html table, you use several different HTML elements in just the right combination.
Table:wraps the whole table.
Table row(TR):wraps around a set of elements, defining them as belonging to the same row.
Table header: Defines the header of the column.
Table data:marks the actual bits of data.
Html table can have different sizes of each comn row or entire table.
We use the style attribute with the width or height properties to specify the size of a table, row or column.
The span is used as a inline part.
INTRODUCTION TO CSS
CSS is used to make web pages look better and more appealing.
It stands for Cascading Style Sheets.
We can style the web pages by changing fonts, colors and spacing.
CSS syntax:
CSS has two parts:
The selector-which points to the html elements you want to style.
The declaration box- which contains one or more declarations separated by a semicolon.
CSS Selectors
CSS selectors are patterns used to select the Html elements you want to style.
CSS selectors can be divided into five categories:
Simple selectors
Combinator selectors
Pseudo class selectors
Pseudo element selectors
Attribute selectors
The CSS element selectors.
The element selector selects the html elements based on the element name.
Example:  p: {text-align: center; color: blue;}
Here all the <p> elements will be center aligned, with a blue text color.
The CSS Id selector:
The Id selector selects the html element with specific Id attribute.
It is written with the (#) character, followed by the Id of the element.
Example: #para1 {text-align: center; color: blue;}
The rule will be applied to the html element with id=para1
The CSS class selector
The CSS class Selector selects the Html elements with a specific class attribute.
To select elements with specific class, write a period character (.), followed by the class name.
Example:  .class1 {text-align: center; color: blue;}
The rule will be applied to the html element with class= class1.
Grouping selectors
The group selector is used to select all the elements with the same style definition.
Commas are used to separate each selector in grouping.
Example:   h1, h2, p {text-align: center; color: blue; }
The best way is to minimize the code.
CSS Images & Colours
The background-color property sets the background color of an element. It applies to the entire size of the element, including padding and border (but not the margin). 
 To ensure readability, choose a background color that contrasts well with the text color. 
The syntax for setting the background color:
               body {background-color: rgb(red, green, blue);} 
Altering the color of the text can add visual interest or align with a specific design scheme. The color property is used to set the color of the text.  
The syntax for setting the text color:   .my-text {color: #FF5733;  }
Understanding Images in CSS
 JPEG (Joint Photographic Experts Group): It uses lossy compression, meaning that the image quality may be slightly degraded in order to reduce file size.
PNG (Portable Network Graphics): PNG images use lossless compression, meaning that image quality is preserved without sacrificing file size. 
GIF (Graphics Interchange Format): GIF images support transparency and animation, making them popular for memes and social media content.
The syntax for setting the back-ground image:
       body{

          background-image:url(‘the.png’);

          }
CSS Boxes, Sizes & Types

The fonts, height, width, margins, padding, etc. are set on a web page with the length units. For example, height 100px, width 100px, font 2em, etc. 
These length units are categorised into Absolute and Relative Units.
CSS uses a box model to define the size of elements on a web page. 
Styling Links in CSS
