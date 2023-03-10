# HMTL Intro Review and Expansion
This code is to review the basics Introduction to HTML to include basic skeleton setup,common and extended tags and attributes.<br>

### head tag
This contains the title, meta tags and links to 3rd-party libraries. <br/>
This tag goes in right after the **html** tag and before the **body** tag. <br/>

**title** tag must be text-only and is shown on the browsers title bar on the page's tab. This is a required field.<br/>

**meta** tags contain data about the data. This is not displayed, but used by the browser and search engines. This is a self-closing tag<br/>

**link** tag is most often used to link to external stylesheets. The two most common are boostrap and MUI for React. This is self-closing tag<br/>
**!-- -- ** this is the comment tag. This is for internal reference and not rendered onto the page. 

### body tag
**h1-h6 tags** these are used to define headings in order of importance. Each page must only have 1 h1 tag.<br/>

**img** is for images and requires at ALT attribute. This is a self-closing tag<br/>
The **src** attribute is where the image file is located on the web or local machine.<br/>
The **alt** attribute describes the picture for accessibility and for text-only browser.<br/>
You can size the image using the style attribute together with the width and height attributes<br/>

**a** defines a hyperlink which is used to link one page to another.<br/>
The most important attribute is the **href** url which holds the location to the linked page. <br/>
By default the unvisited link appears underlined and blue. <br/>
A visited link appears underlined and purple.<br/>
An active link appears underlined and red.<br/>
The **target** attribute determines how to view the linked page. It can be in **_blank** page or **_self** for the same page. 
The link doesn't center by itself, but the text element can be centered when wrapped by **a** tag. <br/>

### Semantic and General used tags
**em** emphasized semantic text<br/>
**i** emphasized general use text
<br/>
**strong** important semantic text<br/>
**b** important general use text
<br/>
**del** Strikethrough semantic text<br/>
**s** Strikethrough general use text
<br/>
**ins** Underlined semantic text<br/>
**u** Underlined general use text
<br/>
**sup** this is for superscript<br/>
**sub** this if for subscript<br/>
<br/>
<br/>
**hr** is an horizontal line
<br/>
<br/>
**ul** is to create an unordered list with list items<br/>
This can take a **list-style-type** for bulleting of <br/>
* disc - this is the default
* circle
* square
* none
<br/>
An unordered list can also be used to create a navigation bar
<br/>
<br/>

**ol** is to create an unordered list with list items. This can take value attribute other than bullets.<br/>
* **a** lowercase letter
* **A** upperase letter
* **i** lowercase Roman numerals
* **I** uppercase Roman numberals
* **1** numbers - this is the default

<br/>

**li** is for the list items. <br/>
<br/>
<br/>

### Navbar
This takes a **nav** tag before the unordered list.<br/>
To remove the bullets, add the **list-style-type** style attribute to **none** inside the UL tag. <br>
Add a nested link **a** tag inside the list item<br/> 
to remove the underscore, add the **text-decoration** style and set it to **none** <br/>
By default the list items are displayed row by row because they are considered block style. <br/>
To display them side by side, add the **display** attribute to each list item and set it to "inline". <br/>

<br/>
<br/>

### Table
Tables **table** have three parts. The header **thead** , the body **tbody** and the footer **tfoot** <br>
The header, body and footer can contain rows **tr** and columns **th**<br/>
The table by itself is not styled and requires attributes to style the table. Attributes like:
* border and border color
* padding - space around the content left and right
* colspan - this can merge columns
* rowpsan - this can merge rows
* bgcolor - background colors
<br/>

### Inline Elements
Inline elements are those which are rendered on a web page side-by-side without creating a new line unless the width changes. <br/>
Does not respect attributes of top and bottom padding, margins <br/>
Doesn't take width and height attributes <br/>
common inline elements are **a** , **span**, **img**,**strong**
<br/>

### Block Elements
Block elements are those that create a new line and take up the full width available to them. They can take attributes of width, height, padding and margin <br/>
Common block elements are **div** , **p** , **h1-h6** , **ul** ,**ol** , **li** <br>
<br/>

### Inline Block Elements
Inline-block elements are those that behave like inline elements but can take additional attributes like those of the block elements like, padding,height, width and margins.<br/>
Common examples are **button** , **input** , **label** <br />
<br/>

### Flex Elements
There are 2 types:
* Flex <br/>
These are used to create flexible containers for grouping and laying out items on the webpage. They allow the control of alignment, direction, order and sie fo the elements within the container. <br/>
Common flex elements include **div** and **label**. <br/>

* Inline-Flex
These are similar to inline block element but use the flex display property. They are useful in situations where you want to group inline elements and apply flexbox properties to them. 
<br/>
If the goal is to display a grid layout for a set of images it is best to use a flexbox and apply flex display properties. 
<br/>