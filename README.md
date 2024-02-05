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
<br>                   - Is used for indicating to the system that this is a line break.
<pre> and <code>       - elements are often combined to display a code block with proper indentation
<sub>                  - Defines subscript text, used when you want to lower a certain alphabet or word or section with in a text i.e H2O
<sup>                  - Defines superscripts text, used when you want certain texts or certain parts of a text to appear slightly above the normal text line. i.e 5th of October
```
<p>Practical Examples of Subscripts and Superscripts:</p>
<p>H<sub>2</sub>O</p>
<p>5<sup>th</sup> of october</p>

- HTML Lists
  There are 3 types of lists used in HTML, namely unordered, ordered, and definition lists                                                                                                                               To define the entire list and specify its type, we use the "ul" element for an unordered list, "ol" for an ordered list, and "dt" for definition term                                                                  Each item in the list is enclosed in an "li" element.
```
An example of how lists are applied to HTML...
<ul></ul>                 -- unordered list: Used when a list has no particular order to follow.
<ol></ol>                 -- ordered list: Used when a list has a specific order or sequence, usually numerical.
<li><li>                  --  Each item in the list need to be enwrapped inside the "li" element.
<dl>                      -- definition list: Used when we want to create a list that resembles a key-value pair where instead of just items, we have terms and their corresponding descriptions. <dl> enwraps both                                 the <dt> and the <dd> inside.
<dt>                      -- definition term: Defines a single term, which is described with a description detail <dd>. The <dl> tag is used to create a list of terms with their respective descriptions.
<dd>                      -- definition description.
```
<p>An example of a unordered and ordered lists:</p>

<ul>
<li>Mom</li>
<li>Dad</li>
<li>Brother</li>
<li>Sister</li>
</ul>
<ol>
<li>Mom</li>
<li>Brother</li>
<li>Sister</li>
<li>Dad</li>
</ol>

<p>An example of a definition list:</p>

<dl>
<dt>available items</dt>
<dd>This is a list of available items in our database</dd>
<dd>This list only shows item that we currently have in our store shelves and backroom storage.</dd>
<dt>item number</dt>
<dd>This is the number assigned to each item available in our database</dd>
<dd>This number is not the barcode of this item, but the number assigned to it by the store counter for stock taking purposes.</dd>
</dl>

HTML Quotes
Quotes are used to attribute certain work or text within the web page to an intended entity. We attribute paragraphs to entities by using the "cite" element enwrapped by a "blockquote". To add on, within a blockquote, one can include any other element they may want to use i.e "h1" "ul" "ol" etc. There are other quoting methods that do not require blockquotes, they are just typed in and the end-result appears as curly quote, meaning that the text will appear with quotation marks in its read-only form.
```
<q></q>                    -- Can for short quotations that don't require paragraph breaks, will show text with quotation marks.
<blockquote></blockquote>  -- Used distinguish what to quote with in certain text and or to attribute to a particular entity/name or word/s. It is also used to make long quotes look in a certain "special" manner,                                 one that does not make use quotation marks but attributes certain text within that web page to a particular entity.
<cite></cite>              -- Attributes patragraph texts to specific entities. When used inside a blockquote, attributes that whole text to that specific entity .
```
## Unit 3: Troubleshooting and Debugging.
- When troubleshooting a HTML code, one needs to access the developer tools and `select “inspect elements”, or you can select “tools” on your web browser, then “web developer” and select the ”inspector” option. The developer tools offer a wide range of different tabs that have many different tools and controls that one can use to debug, update, or make the necessary changes that a developer might need.  The ”Inspector” tool has 3 sections to it:
- HTML on the left side, CSS in the middle, and  more options on the right.
- Popular browsers like chrome, firefox and safari have developer tools that contain an HTML panel that we can use to inspect any website and see how other developers use HTML.
HTML Attributes:
Attributes in HTML add power to any element. There are many element attributes in HTML,
- Class: The HTML class attribute is used to specify a class for an HTML element that allows us to assign a reusable name to any element, which can then be styled using CSS for all elements sharing that class. Multiple HTML elements can share the same class.  
```
Other examples of attributes would be:
<a>    - The anchor tag is used to tag a hyperlink, and is always followed be the the href attribute specifies the URL of the page the link goes to: i.e <p>An article By <cite><b> &copy; <a       
         href="https://www.facebook.com/maccheez"> Thabiso Xakata</a></b></cite></p>, would take you to www.facebook.com/maccheez homepage.
<lang> - allows developers to specify the language of the content using a short language code.
<dir>  - Specifies the direction in which the text flows using "ltr" Left-To-Right Scripts and "rtl" Right-To-Left Scripts.
```
ARIA (Accessible Rich Internet Application) roles provide essential information to assistive technologies like screen readers, braille displays, and magnifiers to ensure a website is fully accessible even for people with impairements and disabilities.
HTML Formating: 
```
We now know that we must use "<p>" for short paragraphs, but if we wanted to write longer texts that would, maybe, be attributed to an entity, we use the "<article>" element
- In HTML, comments are inserted by typing "<!--" at the start and "-->" at the end.
```
## Unit 4: Navigation and Links
On websites, one is bound to come across many links that have been placed on navigation bars, option packed menues, enticing teaser cards etc. A link is a specific text on a webpage that, when clicked, takes you to a different page on that website or takes you to a different website page as a whole. These specific texts/ links are called hyperlinks.
HTML URL Pathways:
For URL Pathways, we have absolute and relative links. Relative URLs are based on the current file's location, while absolute URLs start from the root of the website. An Absolute link is the root link that takes you to the home page of a website, i.e HTTPS://www.unitedstreets.com, while a relative link would be used if we wanted to go to a specific place within that website like viewing an image that is in a specific folder within that site, i.e  HTTPS://www.unitedstreets.com/images/profileimage.jpg.
Navigation:
Navigation refers to how a user is going to go around a website using links, navigation bars, menus etc.
Wen creating a navigation bar, each link is wrapped in an element with the correct URL, and then enclosed in an "li" element to create a list of links, and enwrap that list in an "ul" element. CSS styling is used to enhance visual appearance.

An Example of a navigation bar:

<nav role="breadcrumb">
    <ul class="breadcrumbs">
        <li><a href="/Home"> Home</a></li>
        <li><a href="/people"> People</a></li>
        <li><a href="/images"> Images</a></li>
    </ul>
</nav>
or  
<nav role="navigation">
    <ul class="navbar">
        <li><a href="/Home"> Home</a></li>
        <li><a href="/people"> People</a></li>
        <li><a href="/images"> Images</a></li>
    </ul>
</nav>

Footer links: Refers to links found on the footer of the web page
i.e
<footer>
  <a href="/about/privacy"> Privacy Policy</a>
  <a href="/about/legal"> Terms of Service</a>
</footer>


# Week 2
## Unit 5: HTML Working with Graphics and Images
Images: Most, if not all websites have images emebedded in them, wether as downloadable or read/view-only format. in our websites, we are gonna be adding/inserting images to web pages using the "src" element which is used to source out and display images from a stored directory or the web.
```
This is how you write a code that adds or inserts a downloadable image on to your web page:
<img src="FreePalestineArt.png" alt="Free Palestine Art">
img      - Simply means that an image is being inserted in that line or code,  the image can also be manipulated within that line code by increasing or decreasing               it's size and appearance.  
src      - Refers to the source of the item to be selected
alt      - Refers to the alternativetext that describe the image so that it can also be easily found on search engines by just searching for the images key words.               i.e "police dog" search should show you images of duty dogs with their handlers or in uniforms.
If you are sourcing your image from the internet, then the (img src="" alt="") should have the image's url inserted inside the "src" quotaion mark.
i.e <img src="https://www.tiptongov.com/egov/images/1662419877_72085_o.jpg" alt="Police Dog">
```


