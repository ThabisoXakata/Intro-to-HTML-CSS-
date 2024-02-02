# WEEK 1
## Unit 1: Introduction to HTML & CSS
What is HTML?
- Hypertext Mark-up Language, also known as a declarative language, is used as a standard mark-up language designed to create web pages used by the browser to manipulate text, images, and other content, in order to display it in the required format. It serves as a channel for different types of content like words, images, videos, audio, forms, and interactive experiences. It consists of a siries of elements that describe the structure of a web page and tells the browser how to display the content. HTML is a combination of hypertext, which defines the link between web pages, and the markup language that is used to define the text document within the tag that designs the structure of web pages.

What is CSS?
- Cascading style sheets acts as the stylist of web pages, meaning that it is responsible for how the we page looks in terms of the text fonts, colors, sizes, and has the capabilities of adding special animations and other ways of interactions in order to give the page visitor a satisfying web experience and interaction. CSS comes with computer system tricks and that makesit both fragile and powerful at the same time

## Unit 2: Text formating
- HTML Syntax: uses tags that are enclosed in less and greater than symbols "<>" to define elements that are like content containing packages. Many of these elements require both the opening and closing tags to function properly and provide the desired results.
```
To add on,  These tags are used to devide intended information(elements) in your program and let the computer know that these are seperate entities.
<!DOCTYPE html>        - The !DOCTYPE declaration is not a tag/element, but a declaration to the computer that the following document type is going to be HTML, XHTML, PHP, Javascript etc, so that it can be able to 
                         determine which elements are going to be valid. This the first line required for every HTML code.
<title></title>        - Defines the title for the documents
<p></p>                - Refers to the new paragraph's opening and closing tag
<h1></h1> to <h6></h6> - Refers to Headlines and their sizes in respective to their significance and aense of urgence or authority. Headlines play a vital role in making the people understand the structure of the 
                         web 
                         page they are on, as headlines can be  the window top the actual content of the page. There are 6 different sizes of headlines in respective to their levels of authority, and they all have 
                         distinctive visual effects on the web page, with <h1> having the greatest headline authority while <h6> has the least and gets the least attention compared the other headlines. The h1 
                         serves as the main title, while the h2 acts as a subtitle for the content.
<i></i>                - Used to apply visual italics to a text on a web page.
<em></em>              - Refers to emphasized text within a web page, appears the same way as italics but carry a different meaning to the screen reader and the human reading it.
<strong></strong>      - Used to show importance, seriousness, or urgency of a text on a web page. 
<b></b>                - Used to visually bolden text on a web page without carrying any weight nor important meaning for the computer and the human. 
```
- HTML Lists
  There are 3 types of lists used in HTML, namely unordered, ordered, and definition lists                                                                                                                               To define the entire list and specify its type, we use the "ul" element for an unordered list, "ol" for an ordered list, and "dt" for definition term                                                                  Each item in the list is enclosed in an "li" element.

```
An example of how lists are applied to HTML...
<ul>                      -- unordered list: Used when a list has no particular order to follow.
<li>Coffee</li>
<li>Tea</li>
<li>Milk</li>
</ul>
<ol>                      -- ordered list: Used when a list has a specific order or sequence, usually numerical.
<li>Coffee</li>
<li>Tea</li>
<li>Milk</li>
</ol>

<dl>                      -- definition list: Used when we want to create a list that resembles a key-value pair where instead of just items, we have terms and their corresponding descriptions. <dl> enwraps both                                 the <dt> and the <dd> inside.
<dt>                      -- definition term: Defines a single term, which is described with a description detail <dd>. The <dl> tag is used to create a list of terms with their respective descriptions.
<dd>                      -- definition description.
An example of a definition list:

<dl>
<dt>available items</dt>
<dd>This is a list of available items in our database</dd>
<dd>This list only shows item that we currently have in our store shelves and backroom storage.</dd>
<dt>item number</dt>
<dd>This is the number assigned to each item available in our database</dd>
<dd>This number is not the barcode of this item, but the number assigned to it by the store counter for stock taking purposes.</dd>
</dl>
```
HTML Quotes
Quotes are used to attribute certain work or text within the web page to an intended entity. We attribute paragraphs to entities by using the "cite" element enwrapped by a "blockquote". To add on, within a blockquote, one can include any other element they may want to use i.e "h1" "ul" "ol" etc. There are other quoting methods that do not require blockquotes, they are just typed in and the end-result appears as curly quote, meaning that the text will appear with quotation marks in its read-only form.
```
<q></q>                    -- Can for short quotations that don't require paragraph breaks, will show text with quotation marks.
<blockquote></blockquote>  -- Used distinguish what to quote with in certain text and or to attribute to a particular entity/name or word/s. It is also used to make long quotes look in a certain "special" manner,                                 one that does not make use quotation marks but attributes certain text within that web page to a particular entity.
<cite></cite>              -- 
```
