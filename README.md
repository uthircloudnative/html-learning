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
[Global Attributes Documentation](https://www.w3schools.com/tags/ref_standardattributes.asp)

___4. Headings___

   - To display Title or Sub Title of web page we can use headings element.
   - Headings are defined using 6 different tags from \<h1> to \<h6>.
   - **These headings are used by Search engines to index the web page.**
   - By default each heading will have its own font size. But we can change the each headings font size using style attribute.
   - **Don't use heading tags to make a text to BOLD or STRONG.**
      <h1 style="font-size:40px;">This heading default font size is changed using style attribute</h1>.<br>
[Headings Documentation](https://www.w3schools.com/html/html_headings.asp)


___5. HTML Paragraphs or Text Formatting___

   - To define a paragraph text we can use \<p> tag.
   - To break a line in HTML we should use \<br> tag. As it's an empty tag there is no end tag for it.
   - HTML horizontal rule tage \<hr> is used for thematic break.It's used to separate a content in HTML element.
   - To display a text content as is (with line breaks and spaces) we can use \<pre> tag. When a content is specified in this tag it will be displayed the way its given in code.<br>
[Paragraph Documentation](https://www.w3schools.com/html/html_paragraphs.asp)
     
___6. Styles___
   
   - HTML Style attribute is used to provide different styles to a HTML element such as color,size,align,font etc.,
   - Style element has property:value definition. Each style definition will have a property and it's value.
   - **\<body style="background-color:powderblue;">** this will make sure HTML body displayed in specified color.
   - **\<h1 style="background-color:powderblue;">This is a heading</h1>** We can specify style to any specific element. In this case for header.<br>
[Style Documentat](https://www.w3schools.com/html/html_styles.asp)
     
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
[Formatting Documentation](https://www.w3schools.com/html/html_formatting.asp)
     
___8. Quotations___

   - HTML supports different types of quotations.
   - \<blockquote> is used to quote a section of text from another blog or site. By default browser will indent the quoted section when using this element.
   - \<q> is used for text with short quotation. Browser will automatically insert double quotes when this tag is used.
   - \<abbr> is used to define  abbrivation or an acronym like "HTML","CSS". Using this tag will give useful information to browser and search engines and translation systems.
      along with this element use global title attribute to provide abbrivation description as tool tip.
   - \<address> is used to define contact information like address,email,phone number etc.
   - \<cite> is used to define title of a creative work Ex, Book,a poem, a Song etc.
   - \<bdo> bi-directional override tag is used to define a text orientation from right to left and vice versa.<br>
[Quotation Documentation](https://www.w3schools.com/html/html_quotation_elements.asp)
   
   
