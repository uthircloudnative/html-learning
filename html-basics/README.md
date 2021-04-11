# html-basics

___1. Elements___

   - A HTML element will have start tag -- Content -- End tag format.
   - A HTML element with no content is called empty element.  
   - Empty elements will not have end tags, ex \<br>  tag is one of the example of it.
   - **Even though few HTML elements with content will work without end tag as a good practice we must specify an end tag for elements with content**
   - **As HTML is not case sensitive we can write HTML code in any case. But always use small case as a best practice.**

___2. Attributes___

   - Every HTML elements will have one or more attributes.
   - These attributes will give additional information about the elements.
   - Any HTML element attribute will be specified in the **start tag**
   - **Always use Lower Case Attributes even though HTML supports both cases** 
   - **Always use double quote when defining attribute values. In case an attribute value itself contains quotes then use single quotes.**

___3. Global Attributes___

   - Global Attributes are attributes which can be used in any HTML element tags.
   - Even though Global attributes can be used in any of the HTML element tags in few elements using of these attributes doesn't have any impact.
   - Ex, class, id, lang, style etc.<br>
[Global Attributes Ref](https://www.w3schools.com/tags/ref_standardattributes.asp)

___4. Headings___

   - To display Title or Sub Title of web page we can use headings element.
   - Headings are defined using 6 different tags from \<h1> to \<h6>.
   - **These headings are used by Search engines to index the web page.**
   - By default each heading will have its own font size. But we can change the each headings font size using style attribute.
   - **Don't use heading tags to make a text to BOLD or STRONG.**
      <h1 style="font-size:40px;">This heading default font size is changed using style attribute</h1>.<br>
[Headings Ref](https://www.w3schools.com/html/html_headings.asp)


___5. HTML Paragraphs or Text Formatting___

   - To define a paragraph text we can use \<p> tag.
   - To break a line in HTML we should use \<br> tag. As it's an empty tag there is no end tag for it.
   - HTML horizontal rule tage \<hr> is used for thematic break.It's used to separate a content in HTML element.
   - To display a text content as is (with line breaks and spaces) we can use \<pre> tag. When a content is specified in this tag it will be displayed the way its given in code.<br>
[Paragraph Ref](https://www.w3schools.com/html/html_paragraphs.asp)
     
___6. Styles___
   
   - HTML Style attribute is used to provide different styles to a HTML element such as color,size,align,font etc.,
   - Style element has property:value definition. Each style definition will have a property and it's value.
   - **\<body style="background-color:powderblue;">** this will make sure HTML body displayed in specified color.
   - **\<h1 style="background-color:powderblue;">This is a heading</h1>** We can specify style to any specific element. In this case for header.<br>
[Style Ref](https://www.w3schools.com/html/html_styles.asp)
     
___7. Formatting___

   - HTML will have some special formatting text available.
   - \<b> is used for display text in BOLD.
   - \<strong> is used for display a text in BOLD to indicate it's important.
   - \<i> is used to display text in italic.It's used to indicate technical term.
   - \<em> is used to define a text as emphasized. When this element is used screen reader will pronounce that text with verbal stress.
   - \<small> is used to indicate a text smaller.
   - \<mark> is used to highlight a specific text.
   - \<del> is used to indicate a text is deleted. It's displayed with striked line.
   - \<ins> is used to indicate a text is newly inserted. It will be displayed with unnderscore.
   - \<sub> when this subscript element is used text inside this element is displayed half line below the normal text. Ex, H<sub>2</sub>O.
   - \<sup> when this superscript element is used text inside this element is displayed half line above the normal text. Ex, a<sup>2</sup>+b<sup>2</sup>.<br>
[Formatting Ref](https://www.w3schools.com/html/html_formatting.asp)
     
___8. Quotations___

   - HTML supports different types of quotations.
   - \<blockquote> is used to quote a section of text from another blog or site. By default browser will indent the quoted section when using this element.
   - \<q> is used for text with short quotation. Browser will automatically insert double quotes when this tag is used.
   - \<abbr> is used to define  abbrivation or an acronym like "HTML","CSS". Using this tag will give useful information to browser and search engines and translation systems.
      along with this element use global title attribute to provide abbrivation description as tool tip.
   - \<address> is used to define contact information like address,email,phone number etc.
   - \<cite> is used to define title of a creative work Ex, Book,a poem, a Song etc.
   - \<bdo> bi-directional override tag is used to define a text orientation from right to left and vice versa.<br>
[Quotation Ref](https://www.w3schools.com/html/html_quotation_elements.asp)
     
___9. Colors___

  - HTML supports 140 standard colors. We can define backgound color and Font color and broder color etc using respective style element.
  - \<h1 style="color:Tomato;">This is for Font color</h1>
  - \<h1 style="border:2px solid Tomato;">This is for border color</h1>
  - We can also specify colors using RGB - (RED,GREEN,BLUE), HEX - (#ff6347), hsl - (9, 100%, 64%).
  - Shades of gray is defined using same value of RGB combination \rgb(255,255,255).<br>
[Colors Ref](https://www.w3schools.com/html/html_colors.asp)
    
___10. Links___

  - Links are used to navigate from one page to another page.
  - Links are defnied using \<a> element tag with **href** attribute.
  - A link doesn't have to be a text. It can be an image or another HTML element like button.
  - By default an unvisited link is underlined and **Blue**.A visited link is underlined and in **Purple**.An active link is underline and in **RED**.
  - By default linked page is displayed in the current browser window. We can change in using different **target** attribute value in \<a> tag.
  - _self - Default. Opens the link in current browser window/tab.
  - _blank - Opens the link in new window or a tab.
  - _parent - Opens the document in the parent frame.
  - _top - Opens the document in the full body of the window.
  - We can provide complete URL or Relative URI path as link.
  - We can provide a link to email which opens Email application when its clicked.\<a href="mailto:someone@example.com">Send email</a>.
  - We can create bookmark in a page using **href** attribute. Which is useful to navigate to respective part of the page when page is long.<br>
[Links Ref](https://www.w3schools.com/html/html_links_bookmarks.asp)
    
___11. Images___

 - Using **img** tag we can specify an image in our page. It must have two attributes **src** from where to load an image and **alt** alternate text to be displayed when image is not been able to loaded by browser.
 - **Its good practice to define image size using either style or width and height attributes. Using style attribute is recomended**
 - \<img src="html5.gif" alt="HTML5 Icon" style="width:128px;height:128px;">.
 - **HTML <map> tag defines an image map. It's an image with clickable areas. These areas are defined with one or more <area> tag.**
 - By using <style> element we can add background image.If we want the image to be displayed in entire page needs to specify image in body element of style.
 - If the image is small it will be repeated horizontally. To avoid this set **background-repeat** to **no-repeat**.
 - To cover the entire element with background image set **background-attachment** to **fixed**. It will avoid image being stretched.
 - \<picture> element is used to display different picture for different devices.<br>
[Images Ref](https://www.w3schools.com/html/html_images_picture.asp)
   
___12. Tables___

 - HTML tables are used to define HTML data in tabular format. A table is defined using \<table> tag.
 - \<th> specifies table header, \<tr> specifies table row, \<td> specifies cell or its values, its data containers can support all kind of HTML elements like text,img,list etc.
 - We can add table border using **border** property, **border-collapse** is used to collapse border lines, **padding** property used to specify cell padding.
 - By default table headings are bold and center aligned. Using **text-align** we can align content right or left.
 - **colspan** and **rowspan** is used to merged columns and rows respectively.
 - With table **id** attribute we can specify table style which can be reused anywhere.<br>
[Tables Ref](https://www.w3schools.com/html/html_tables.asp)
   
___13. Lists__

 - HTML list are used to display contents as list of items either ordered or unordered and list of items with description.
 - Ordered and unordered list will support different types of style attributes to display contents.
 - Ordered list support Number,Alpha(Upper and Lower),Roman(Small and big) ordering.<br>
[Lists Ref](https://www.w3schools.com/html/html_lists_ordered.asp)
   
___14. Block vs Inline Elements___

 - Block-level elements always starts new line.A block-level element always take up full width available and stretches both right and left as far as it can.
 - Block-level elements will have top and bottom margin. Ex **\<div>** 
 - An Inline-element doesn't start in a new line also it will take only necessary space required. Ex **\<span>**.<br>
[Block-Inline Elements Ref](https://www.w3schools.com/html/html_blocks.asp)
   
___15. Classes___
 
 - HTML class attribute is used to specify a class for an HTML element.Different properties are specified under a class attribute and then it can be used across multiple elements.
 - class attribute is often used in CSS style sheet to define style parameters for an element. 
 - **class attribute can be used in any HTML element and class name is case sensitive**
 _ .<class_name> {// different style properties} is the syntax for class.
 - single HTML element can have multiple class names.<br>  
[Classes Ref](https://www.w3schools.com/html/html_classes.asp)
   
___16. ID___

 - id attribute is used to specify a unique HTML element. **We can't have more than one element with same id in a HTML document.**
 - id attribute can be used to specify a style for a particular HTML element. Also it can be used by JavaScript to access and manipulate a particular element using.
 - \document.getElementById("headerStyle").innerHTML = "This is a Book". 
 - **id name is case sensitive.**
 - **id name must contain atleast one character and must not contain whitespaces or tabs**.
 - \#<nameofId>{} is the syntax
 - **Main difference between id and class attribute is class can be used in multiple HTML elements but id is unique and used in only one element.**
 - An id attribute can be used in HTML bookmark definition.
 - A class attribute can be used when a same style can be applied in different HTML elements. <br>
[ID Ref](https://www.w3schools.com/html/html_id.asp)
   
___17. IFrames___

 - iframe element is used to specify an inline frame in a HTML element.
 - An inline frame is used to embed another HTML document within current HTML document.
 - **It's always best practice to use title attribute when defining iframe element. This title is used by screen reader.**
 - Along with title specify width and height either using style or individual attributes.
 - \<iframe src="demo.html" title="This is demo HTML" height="100" width="100">. <br>
[IFrame Ref](https://www.w3schools.com/html/html_iframe.asp)
   
___18. Head___

 - HTML head element will contains elements which is used to provide meta data information of the document.
 - It can have following elements **\<title>,\<style>,\<meta>,\<script>,\<link>,\<base>**.
 - \<title> it will define title of the web page in browser tab or title bar. **It should be text only**.
 - \<title> is used by search engines to define page optimization indexes.
 - \<style> element is used to specify style information for given page.
 - \<link> element is used to define the relationship between current page and external resource.Mostly it's used to refer external style sheets.
 - \<meta> element is used to specify different kinds of meta information like character set,page description, keywords author info and viewport settings.
 - These metadata is not displayed in browser but its been used by search engines for page optimization.
 - \<meta http-equiv="refresh" content="30"> this will refresh the page every 30 seconds.
 - \<meta name="viewport" content="width-device-width, initial-scale=1.0"> this will define users visible area in the device.It will vary depending on the device this element will make sure content is adjusted according to device.
 - \<script> is used to specify client-sdie java script function for the page.
 - \<base> is used to define base URL for all relative URL defined in the page.This element must have either href or target or both.<br>
[Head Ref](https://www.w3schools.com/html/html_head.asp)
   
___19. Layout___

 - HTML supports to design a web page in specific layout pattern using set of different elements.
 - \<header> defines a header for a document or a section.
 - \<nav> defines a set of navigation links.
 - \<section> defines a section in a document.
 - \<article> defines an independent, self-contained content.
 - \<aside> defines a content aside content like a side bar.
 - \<footer> defines a footer for a document or section.
 - \<details> defines additional details user can open or close on demand.
 - \<summary> defines a heading for the \<details> element.
 - There are 4 types of layout techniques.
 - **CSS framework** it uses CSS float property to design entire web page and eacy to learn and use.Floating elements are tied to document it harm page flexibility.
 - **CSS Flexbox Layout** this layout ensures page elements behave predictably when the page is displayed in different devices.
 - **CSS Grid Layout** its based on rows and columns. It makes design easy.<br>
[Layout Ref](https://www.w3schools.com/html/html_layout.asp)
   
___20. Responsive Web Design___

 - A responsive web design is designing a webpage which can be adjust itself for various differet device screens.
 - It can be achieved using HTML \<meta> element **viewport** attribute.
 - \<meta name="viewport" content="width=device-width, initial-scale=1.0"> this will make the webpage a responsive one.
 - We can define images also responsive as well by defining  CSS style with **width** as 100%.
 - By defining  **max-width** to 100% an image will only scale down from its original size bit won't enlarge than its original size.
 - \<img src="img_girl.jpg" style="max-width:100%;height:auto;">
 - Similarly we can define responsive text as well using **vw** viewport width style attribute.
 - \<h1 style="font-size:10vw">Hello World</h1>
 - Using **Media Queries** we can design web pages which can align it self either vertical or horizontaly based on screen size.
 - There are few popula frameworks available to design responsive web pages Ex **W3.css**, **Bootstrap**.<br>
[Responsive Web Design Ref](https://www.w3schools.com/html/html_responsive.asp)
   
___21. Computer Code___

 - HTML will have few specific HTML elements to define Software code text and Keyboard shortcuts in HTML.
 - \<kbd>  used for keyboard input. \<p>Save the document by pressing <kbd>Ctrl + S</kbd></p>
 - \<samp> used to specify sample program output.
 - \<code> element is used to specify piece of computer code.Use \<pre> tag along with it to make the code appear with line breaks.
 - \<var> element is used to define program varibales.<br>
[Computer Code Ref](https://www.w3schools.com/html/html_computercode_elements.asp)
   
___22. Character Entities___

 - In HTML some characters are reserved. To display these characters correctly we have to use character entites.
 - Ex less than and greater than symbols should be defined with character entities to make it visible properly.
 - \< &lt; or &#60;
[Character Entities Ref](https://www.w3schools.com/html/html_entities.asp)
   
___23. Symbol Entities___

 - Mathamatical,Technical and Currency symbols are defined using Symbol entities.
 - \<p>I will display &euro;</p> This is to display euro symbol.<br>
[Symbol Entities](https://www.w3schools.com/html/html_symbols.asp)
   
___24. Emojis___

 - Emojis are defined by characters. To display these Emojis we should define correct UTF number for the given emoji.
 - **Each and every web page must define a UTF char-set as browser will always expect a char-set for a given web page.**
 - Character set is defined  using \<meta> element if its not defined UTF-8 is considered as default by browser.<br>
[Emojis Ref](https://www.w3schools.com/html/html_emojis.asp)
   
___25. Charset___

 - To display a web page correctly browser should know about the charset used in the page. It's been specified using \<meta> element.
 - If not charset is defined its default to UTF-8.
 - ASCII, ANSI, 8859, UTF-8 are some of the char set used.
 - **As per HTML 5 its recomended to use UTF-8 as it's support almost all symbol and characters.**<br>
[CharSet Ref](https://www.w3schools.com/html/html_charset.asp) 
   
___26. URL Encoding___

 - URLs can only be sent over the internet using the ASCII character set. If the URL contains any character which is outside of ASCII then it should be converted.
 - URL encoding converts non-ASCII characters into a format that can be transmitted over internet.
 - It replaces non-ASCII characters with a "%" followed by hexadecimal digits.
 - URLs cannot contain spaces.If present it will be replaced with + sign or \%20.<br>
[URL Encoding Ref](https://www.w3schools.com/html/html_urlencode.asp)
   
___27. Style Guide___

 - **Always declare Document Type as first line in HTML page**. \<!DOCTYPE html>
 - **Always use lowercase element names.**
 - **Close all HTML elements.**
 - **Always use lower case attribute names**
 - **Always quote attribute values.**
 - **Always specify alt,height,width for img elements.**
 - **Do not use spaces when define key values.**
 - **Avoid long code lines.**
 - **Do not  add blank lines, spaces, indentation without reason.**
 - **Never skip the title element.**
 - **Always define \<html>, \<head>, \<body> elements.**
 - **Close empty HTML elements.** \<meta charset="utf-8" />
 - **Always add lang attribute in html element.** \<html lang="en-us">
 - **Define correct char encoding as early as possible in HTML document. It will ensure proper interpretation and indexing.**
 - **Set the viewport attribute of meta element to make sure web page is responsive in all devices.** \<meta name="viewport" content="width=device-width, initial-scale=1.0">
 - **Use lower case for file names.** <br>
[Style Guide Ref](https://www.w3schools.com/html/html5_syntax.asp)







   
