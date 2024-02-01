# Introduction-to-HTML
==================================================================

What is html ? 
Html, known as Hypertext Markup Language, is a markup language crucial for building and designing web pages. It structures content using tags, defining elements and their relationships like headings, paragraphs, and links, enabling browsers to render information.

What is css ?
CSS, known as Cascading Style Sheet, is a coding language essential for web development. It dictates the visual aspects of a website, determining how elements like test, images, layouts appear, ensuring a consistent and attractive user interface.

What is JavaScript ?
JavaScript is versatile but mainly used for web development. It enables dynamic content, interactivity, and asynchronous behavior on browsers. As a client-side scripting language, it manipulates the Document Object Model (DOM) to create responsive and engaging user interfaces.

What is Document Object Model (DOM) ?
DOM is a web development concept where a document’s structure is represented as tree of objects. JavaScript interacts with DOM, enabling dynamic manipulation of webpage content. 

HTML TEXT FORMATING
====================================================================

- Inline elements are elements are meant to wrap around phrases of text that are inline with other content.

Basic elements in HTML (all elements are wrapped in entities)
-------------------------------------------------------------
- h1 - first headline
- h2 - second headline
- p - for paragraphs
- em - for text to appear Italic (used to grab attention ) 
- I - for text to appear Italic (used for visuals like titles) 
- strong - for text to appear bold (to show importance and urgency)
- b - for text to appear bold (used for generic and neutral purposes)


Headlines
-------------------------------
- There are six different types : h1, h2, h3, h4, h5, h6
- The h1 element is the largest and most prominent, while h6 is the smallest and least attention-grabbing.

HTML Lists (all elements should be closed using their closing tags)
--------------------------------------------------------------------
- there are three types of lists > unordered lists, ordered lists and definition lists
- li - represents a list item (these tags are nested in list tags)
- ul - unordered lists are commonly used (lists items in bullet form) 
- ol - ordered lists are simiar to unordered lists, an ordered list follows a specific order and are numbered.
- dt - stands for definition term 
- dd - stands for definition description
 > both  definition tags must be nested in "dl" tags, which represents the definition lists

HTML Quotes (all elements should be closed using their closing tags)
------------------------------
- blockquote - used to distinguish what is nested inside the tags. Any other tags can be added in the blockquotes tags. 
- cite - renders in italic. This tag defines creative work such as poems or books.
- q - used to automatically add the appropriate quotes to the text.

Date and Time Elements
------------------------------
- date element is written as < time datetime="2025-05-08">May 8, 2025< /time>
- time element is written as < time datetime="14:15:28.5">14:15:28.5< /time>

HTML Code, pre and br (all elements should be closed using their closing tags)
------------------------------------------------------------------------------
- &It ; = <                              
- &gt ; = >
> these are known as entities

- code – changes code to monospace font
- br - adding these tags at the end of a line creates a line break
- pre – wrapping the code in pre elements and placing character’s anywhere will make the character’s stay exactly where it is.
- pre and code can be used together

HTML Superscripts, Subscripts and Small Text (all elements should be closed using their closing tags)
-----------------------------------------------------------------------------------------------------
- sub = placing characters at the bottom
- sup = placing characters at the top
- small = adjusting the size of the code (commonly used for footers)

 HTML Capabilities
================================================

Troubleshooting and Debugging HTML Code
------------------------------------------------
In browsers, there is a way for users to see what is going on with a website's code and performance. To access the developer tools, we can either right-click on the demo and select "inspect element" or opt to go to "tools," then "web developer," and choose "inspector." This will open up the developer tools, which offer a wide range of tabs with different tools or controls as it is sometimes also referred to.

-if there's an error in your code, the page will render around the error, trying to fix it.

HTML Attributes (these tags uses closing paragraph tags)
----------------------------------------------------------
- class attribute < p class="intro" >
 > The class attribute is the most commonly used. It allows us to assign a reusable name to any element, which can then be styled using CSS for all elements sharing that class.
  
- id attribute < p class="intro"
                 id="article-intro">
> Can only use unique names once on an entire HTML page. IDs can be used for CSS targeting, but are more specific, which can sometimes cause issues.
> The "dir" attribute explicitly indicates the direction in which the text flows, using "LTR" for left-to-right scripts and "RTL" for right-to-left scripts.


ARIA Roles
-------------------------------------------------------
- ARIA Roles are extra attributes that we can add to HTML elements to make them more meaningful and help browsers understand what they represent.
- ARIA Roles come into play when we want to provide essential information to assistive technologies like screen readers, braille displays, and magnifiers to ensure a website is fully accessible.
  

Formatting HTML
-------------------------------------------------------
- use style tages and css to modify whitespace
- use "<!--" at the start and "-->" at the end to comment in the actual code, the website does not render comments.


Unusual Characters
--------------------------------------------------------
- Character entity are formatted as an ampersand, a short code, and a semicolon. When we include these in HTML, they are transformed into specific characters.
- Example - &copy ; (no spaces) becomes &copy;
- We can use the code "&nbsp;" to insert a non-breaking space between the two names, ensuring they stay on the same line.


HTML Links
-------------------------------------------------------
- When we want to create a link, we use the A element, which stands for anchor.
- To create a link, we need to add ah hred attribute with URL enclosed in quotes.
- href - Hypertext reference
- the A element is inline and can be placed within a paragraph or any other text.
- Absolute URL - a complete web address that spcifies the exact location of a file on the internet, including protocol, domain name, and the path to the specific file.
-  The "S" in HTTPS stands for Secure.
-  In an absolute URL, the HTTP or HTTPS part must be included which stands for Hypertext Transport Protocol. This protocol defines the rules for communication on the web and is crucial for linking.


HTML URL Pathways 
-----------------------------------------------------
- relative URL - a URL that indicates a file's location based on it's relationship to the current directory, streamlining navigation within a project
- absolute URL - a complete web address that specifies that exact location of a file on the internet, including the protocol, domain name, and the path to the specific file.

Creating Local URLs (relative URLs)
-----------------------------------------------------
1. /images/logo.gif
2. ../images.logo.gif

   1 - relative to the root level. The browser will start looking for the specific file from the root of the website.<br>
   2 - relative to the location of the file where URL is written. The ".."means going up one level in the directory structure


Navigation
----------------------------------------------------
- when making a menu navigation, each link is wrapped in an element with the correct URL and enclosed in an "li" element to create a list.
- the entire menu should be enclosed with a "nav" element to indicate that it is the navigation.
- to create a footer with links, all links should be enclosed with a "footer" element


