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
The link doesn't center by itself, but the text element can be centered when wrapped by **a** tag.

