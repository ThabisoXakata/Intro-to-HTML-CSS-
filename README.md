# WEEK 1: What I have learnt so far.
## Unit 1: Introduction to HTML & CSS
What is HTML?
- Hypertext Mark-up Language, also known as a declarative language, is used as a standard mark-up language designed to create web pages used by the browser to manipulate text, images, and other content, in order to display it in the required format. It serves as a channel for different types of content like words, images, videos, audio, forms, and interactive experiences. It consists of a siries of elements that describe the structure of a web page and tells the browser how to display the content. HTML is a combination of hypertext, which defines the link between web pages, and the markup language that is used to define the text document within the tag that designs the structure of web pages.
  
What is CSS?
- Cascading style sheets acts as the stylist of web pages, meaning that it is responsible for how the we page looks in terms of the text fonts, colors, sizes, and has the capabilities of adding special animations and other ways of interactions in order to give the page visitor a satisfying web experience and interaction. CSS comes with computer system tricks and that makesit both fragile and powerful at the same time

## Unit 2: Text formating
- HTML Syntax: uses tags that are enclosed in less and greater than symbols "<>" to define elements that are like content containing packages. Many of these elements require both the opening and closing tags to function properly and provide the desired results.
```
To add on,  These tags are used to devide intended information(elements) in your program and let the computer know that these are seperate entities.
<!DOCTYPE html>        - The !DOCTYPE declaration is not a tag/element, but a declaration to the computer that the following document type is going to be HTML, XHTML, PHP, Javascript etc, so that it can be able to determine which elements are going to be valid. This the first line required for every HTML code.
<title></title>        - Defines the title for the documents
<p></p>                - Refers to the new paragraph's opening and closing tag
<h1></h1> to <h6></h6> - Refers to Headlines and their sizes in respective to their significance and aense of urgence or authority. Headlines play a vital role in making the people understand the structure of the web page they are on, as headlines can be  the window top the actual content of the page. There are 6 different sizes of headlines in respective to their levels of authority, and they all have distinctive visual effects on the web page, with <h1> having the greatest headline authority while <h6> has the least and gets the least attention compared the other headlines. The h1 serves as the main title, while the h2 acts as a subtitle for the content.
<i></i>                - Used to apply visual italics to a text on a web page.
<em></em>              - Refers to emphasized text within a web page, appears the same way as italics but carry a different meaning to the screen reader and the human reading it.
<strong></strong>      - Used to show importance, seriousness, or urgency of a text on a web page. 
<b></b>                - Used to visually bolden text on a web page without carrying any weight nor important meaning for the computer and the human.
<br>                   - Is used for indicating to the system that this is a line break.
<pre> and <code>       - elements are often combined to display a code block with proper indentation
<sub>                  - Defines subscript text, used when you want to lower a certain alphabet or word or section with in a text i.e H2O
<sup>                  - Defines superscripts text, used when you want certain texts or certain parts of a text to appear slightly above the normal text line. i.e 5th of                            October
<span></span>          - Add mark-up to a text within a text/paragraph. I.E if you want to change the color of a specific word inside a text, you would have to enwrap that                          word inside of the span tag and add the desired styling properties inside the open span tag.
<div></div>            - Used when we want to devide a page by sections and, maybe, add features or styles to a certain section of your page. This element can be applied                            to devide paragraphs by sections so that you can be able to do change to a certain paragraph with in a page.
```
<p>Practical Examples of Subscripts and Superscripts:</p>
<p>H<sub>2</sub>O</p>
<p>5<sup>th</sup> of october</p>

- HTML Lists
  There are 3 types of lists used in HTML, namely unordered, ordered, and definition lists                                                                                                                               To define the entire list and specify its type, we use the "ul" element for an unordered list, "ol" for an ordered list, and "dt" for definition term                                                                  Each item in the list is enclosed in an "li" element.
```
An example of how lists are applied to HTML...
<ul></ul>                 <!-- unordered list: Used when a list has no particular order to follow.-->
<ol></ol>                 <!-- ordered list: Used when a list has a specific order or sequence, usually numerical.
<li><li>                  <!--  Each item in the list need to be enwrapped inside the "li" element.
<dl>                      <!-- definition list: Used when we want to create a list that resembles a key-value pair where instead of just items, we have terms and their corresponding descriptions. <dl> enwraps boththe <dt> and the <dd> inside.-->
<dt>                      <!-- definition term: Defines a single term, which is described with a description detail <dd>. The <dl> tag is used to create a list of terms with their respective descriptions.-->
<dd>                      <!-- definition description.-->
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
<blockquote></blockquote>  -- Used distinguish what to quote with in certain text and or to attribute to a particular entity/name or word/s. It is also used to make long quotes look in a certain "special" manner, one that does not make use quotation marks but attributes certain text within that web page to a particular entity.
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
<a>    - The anchor tag is used to tag a hyperlink, and is always followed be the the href attribute specifies the URL of the page the link goes to: i.e <p>An article By <cite><b> &copy; <a href="https://www.facebook.com/maccheez"> Thabiso Xakata</a></b></cite></p>, would take you to www.facebook.com/maccheez homepage.
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


# Week 2: What I have learnt so far.
## Unit 5: HTML Working with Graphics and Images
Images: Most, if not all websites have images emebedded in them, wether as downloadable or read/view-only format. in our websites, we are gonna be adding/inserting images to web pages using the "src" element which is used to source out and display images from a stored directory or the web.
```
This is how you write a code that adds or inserts a downloadable image on to your web page:
<img src="FreePalestineArt.png" alt="Free Palestine Art">
img      - Simply means that an image is being inserted in that line or code,  the image can also be manipulated within that line code by increasing or decreasing               it's size and appearance.  
src      - Refers to the source of the item to be selected
alt      - Refers to the alternativetext that describe the image so that it can also be easily found on search engines by just searching for the images key words.               i.e "police dog" search should show you images of duty dogs with their handlers or in uniforms.
Any image format is acceptable on HTML, we just need to specify it on HTML when we source it, i.e /images/FreePalestineArt.jpg">
PNG, JPG are the most common image formats available, PNG great for transparent feature, while JPG focuses on the quality of the picture.
GIF are also popular for being responsive but not good on quality as they only support 256 shades of color, and SVG which is perfect for logos, icons and other types of illustrations that can be upsized or scaled to  without losing picture quality
If you are sourcing your image from the internet, then the (img src="" alt="") should have the image's url inserted inside the "src" quotaion mark.
i.e <img src="https://www.tiptongov.com/egov/images/1662419877_72085_o.jpg" alt="Police Dog">
One might also add the height and width description to their image to manipulate it's size and how its hould look as an output by adding the width and height properties.
```
Responsive Images: Refers to web pages being able to resize uploaded immages to the web to view the desired version of the image with the least space possibly taken, while delivering the best image quality. The aim oif having responsive images is to send the smallest image file possible and still deliver beautiful images that may appear quite large.

## Unit 6: Working With Media
- Audio: The audio element is different from the image tag because it has both the opening and the closing tag, which promotes more power to the element. Just like the image tag, we use the "src" attribute to source out the audio and where it is placed on the pc or server. Media player controls like the "volume" and "play" button can be added or created using Javascript and HTML media element API. The reason for having an opening and closing tag for the audio element is because "src" can be used to specify multiple audio file.
```
An example of uplaoding an audio file to your page for each audio file:
<audio controls>
<source
        src="Recording1.mp3"
        type ="audio/mpeg">
<source
        src="Recording2.mp3"
        type ="audio/mpeg">
</audio>
```
- Video: Just like the audio insertion feature, HTML has one for uploading, viewing and downloading video files on web pages. To source and display a video in HTML, we use the source attribute to specify the video we want to display. To add media player controlos to your video, we simply need to type in " <video controls src="...video.mp4"."
Captions and Subtitles: We now know that we can add sound and video to any web page we create, but not every one can hear what is being hear on the audio, that could be caused by disabilities and impairements, language barriers, accents and so many other factors. In order to combat such issues, the implimentation of captions and subtitles comes into place. With the "track" element, we are able to insert captions and subtitle to video and audio files on the web.
```
An example of how you would add captions/subtitles to a video on the web:
<source src=”documents/videos/video1.mp4”
Type=”video/mp4”>
<source src=”https://www.youtube.com/watch?v=klxJBAAOJ3c”
Type=”video/webm”>

<track src=” documents/videos/video1.mp4”
	Kind=”captions”
	Label=”english”
	Srclang=”en”
Default>

<track src=” https://www.youtube.com/watch?v=klxJBAAOJ3c”
	Kind=”subtitles”
	Label=”Spanish”
	Srclang=”es”>

```
Embedding Media via Iframes: Embedding media refers to taking content from another site and simlply placing it on to another site's page. There is a large variety of content that can be embedded on a web page like Maps, code demo and many other things..
## Unit 7: HTML Content Identification
Language Support - The internet is used by the entire world meaning that people are gonna understand things differently... HTML has a feature that allows for a creation of web pages that cater to people from different demographic and geographical backgrounds. The language feature is inserted at the begining of your HTML code. i.e "html lang="en-US">"
HTML language attribute is not ony limited to ENGLISH (lang="en-US"/"en-GB") AND ESPANOL (lang="es"), infact there are many other language HTML documents ca be written in. Other languages like Arabic are available to use even though the writing direction may differ as many languages have a left-to-right "ltr" direction. Now, in order for us to be able to to that, we have to specify which direction is the text going to go. 
Here are a few language examples: 
html lang="en-US"(English from United States)
html lang= "en-GB" dir="ltr"(English from Great Britain, text direction goes from left to right)
html lang="ar" dir="rtl"(arabic, text direction goes from right to left)
Different languages have different character sets and symbols. To define what character set to use, we use the meta attribute along with the unicode UTF8 to gain access to 137000 characters aiming to encompass all known languages to men kind. To inform the browser what character sets you are going to use, you simply need to type (meta charset="UTF-8").
HTML Generic Elements, Div and Span:
Div : Are widely used to create/devide sections, sidebars, and everything in between. Simply put, the div element is a block level element.
Span: Is an inline element that is used to make changes or enhancements to a certain part of a text or a certain text/word in a sentence.
HTML Integration
HTML Page: All the elements, attributes, roles, and tools used to mark up content put together in a meaningful way make up an HTML page. To visit a web page, one needs to open a web browser and type in the page URL, then press enter for it to take you to that particular site, or you could just visit it by clicking a link/hyperlink linked to that particular website. In the earlier days of the internet, everything needed to display a webpage was contained in a single HTML file, along with all the images, audio and videos needed for that website's content. To make internet webpages visually impressive, things have gotten complex with the needed addition of Cascading Style Sheets and CSS files, that are solely used to add and store visual styles and visual features, and JavaScript is in separate JavaScript files that are used to add interactiveness within your web page.
```
This is what a web page looklike in HTML code
<!DOCTYPE html>                                                            <!--The !DOCTYPE declaration is not a tag/element, but a declaration to the computer that the following document type is going to be HTML, XHTML, PHP, Javascript etc, so that it can be able to determine which elements are going to be valid. This the first line required for every HTML code-->
<html lang="en">						 	   <!-- Defines the language the computer is going use for that particula HTML page, quote, or paragraph -->
<head>									   <!-- Inside the head of a webpage is you put important information that the browser needs to know about the website -->
    <meta charset="UTF-8">						   <!-- Defines the character set that is going to be used on this HTML web page.
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web Page Name</title>					   <!-- It is the name that appears under top sites when a new browser is opened-->
</head>
<body>									   <!-- This where the full structure of your HTML document goes.
    
</body>
									   <!-- The footer navigation bar, if there is one, goes here-->
</html>
```
meta attribute.		- The <meta> tag defines metadata(information) about an HTML document. Amongst many things we can use the meta tag on in an HTML document, one common use is to inform the browser that the layout has been adjusted to fit small screens, therefore making it a responsive website.
Link			- The link element is used to connect various assets that should be loaded on to you html docoment, such as CSS files, fonts, and faicons. The <link> tag is most often used to link to external style sheets or to add a favicon to your website.
href			- the href attribute is employed to specify the URL/source for the asset
rel			- Informs the browser about the type of asset being utilized in this programme.
script 			- Used to load a javascript file on to your html document.
```
<head>
  <link href="styles.css" rel="stylesheet">				  <!--The <link> tag defines the relationship between the current document and an external resource.-->
</head>
__________________________________________________________________________________________________________________________________________________________________________________
<head>
<script src="javascriptfile1.js"></script>				  <!--Used to instruct the browser to load a JavaScript file-->
</head>
<main></main>			<!--Informs the browser where the main content is located on the web page-->
<Header>			<!--Marks the header arear of the page-->
<footer>			<!--Marks the footer arear on your web page and signifies that there are extra things to convey, regardless of its position on the page.-->
<section>			<!--Used to mark sections of content, i.e when writing a 2000 word online newspaper article, you would need to section your paragraphs up, especially if it would have subheadings.-->
<aside>				<!--Used for content that is to be place on a certain side of your web page, like a sidebar information type of design is achieved using the aside element-->
```
This covers most of the basics of creating web pages using just HTML code. To get a sense of how to assemble web pages using many nested elements to structure the web page to your liking. In order for one to fully grasp the syntax and how to structure web pages, we need to travel around the web looking for sites similar to the one you may want to create and making use of web developer tools to see how other developers used html elements on their web pages.

# Week 3: What I have learnt so far.
## Unit 9: Working with Forms and Interactive Elements
Form Fundamentals		- Forms have always played a very important role in web, as they have been used in many different tasks like logging in to a website, leaving a comments on websites, conducting searhes on the net, making payments online i.e Paypal is a form based type of website. To create forms, we use the "form" element to inform the browser to expect a form in a certain section of a code. If a form has 4 fields designated for a name, surname, age, and gender, we would be able to turn those field names to labels using the label element. An "input" element is used to input their name, surname, age and gender on those designated fields, note that the input element does not have a closing tag. To submit the input on to the web page, we use a button element(we can change the text on the button to whatever name we might want to call it...). To add fucntionality to forms on the web, we need to connect to a back-end.
To make forms accessible to everyone, we have to add a "for" attribute to the label that matches the "id" attribute of the input or simply enwrap the input with the label element.
```
An example of a form in HTML:
<section class="Form-A">
	<h2>Form A</h2>
	<form>
		<label>Name</label>
		<input>
		<label>Surname</label>
		<input>
		<label>Age</label>
		<input>
		<label>Gender</label>
		<input>
		<button>Submit</button>
	</form>
</section>
```
For the above form code, any text can be placed inside the labels, even on the "age" field, mainly because we did not specify the type of input we are going to collect. Adding the "type" attribute to define the type of data expected in those fields.
Other Form Element Types: Simply refers to the features that allows us to style our form to appeal more.

```
<form action="index.html" method="get">
	<label for="name"> Name</label>
		<input name="name" id="name" type="text">				

	<label for="surname">Surname</label>
		<input name="surname" id="surname" type="text">

	<label for="Age">Age</label>
		<input name="age" id="age" type="number"> 				<!--Field designated for age/number of years-->

	<label for="Gender">Gender</label>
		<input name="gender" id="gender" type="text">				<!--Field designated for -->

	<label for="email">email</label>
		<input name="email" id="email" type="email"
		required placeholder="someone@example.com">				<!--Field designated for the email address-->

	<label for="cellphone">phone</label>
		<input name="cellphone" id="cellphone" type="tel">			<!--Field designated for the cellphone number-->

	<label for="password">password</label>
		<input name="password" id="password" type="password">			<!--Field designated for a Password-->

	<label for="search">search</label>
		<input name="search" id="search" type="search"				<!--Field designated for a search phrase, or text to search-->
		placeholder="Search">

	<div>
		<label for="textarea">textarea</label>
		<textarea id="textarea" type="text" cols="30" rows="15"></textarea>	<!--Field designated for a complaints, comments and compliments Text area, "cols" 											stands for number of columns, and rows for the number of rows. -->
		
	</div>

	<button type="submit">login</button>

</form>
```
## Unit 10: Organizing Tabular Information in HTML
HTML Tables	- Tables in  html are used when we have content that is plotted on a table format. To style them and add the actual boarders on our table sontents, we have to make use of CSS styles to arrange how the table is going to be displayed on the screen.
```
This is an example of a table with 3 rows: one header and 2 datarows(fields)

<table>							<!-- Table openning tag-->
  <tr>							<!-- "tr" Table Row element defines the row on your table-->
    <th>Weeks</th>					<!-- "th" Table Header element defines the header cell, displays header texts for each column, text is bold and centered by default-->
    <th>Activities</th>
  </tr>
  <tr>
    <td>Week 1</td>					<!-- "td" Table data defines the data cells that contain the data-->
    <td>Introduction to HTML</td>
  </tr>
</table>						<!-- Table closing tag-->
```
## Unit 11: Create a website Portfolio
For unit 11, we are supposed to create portfolio websites for ourselves to establish an online presence that is active and viewable. Our portfolio websites should include sections for our bio, skills, projects, and contact information. Lastly, incorporate images of your work, establish clickable links to your projects, and create interactive forms for visitor feedback.

#CSS: Introduction to Cascading Style Sheets.
## Unit 1:
Cascading Style Sheets contain all the visual styles for our webpahges, adding a visual appeal to your websites. To use CSS style on HTML codes, one has to connect them by using a link that woill allow them to work hand-in-hand. CSS has two parts: The selector and the declaration block.
The selector: Used to specify the elements that you want to style in your code. There are 5 categories of CSS selectors:
Declaration Block: Refers to the properties and values stored inside the calebraces of your CSS styling in your stylesheet. i.e {color: tomato; font-size: 10p; text-alignment:center}

## Unit 2
Types of Selectors:
- Simple	- refers to elements based on "name, id, class" elements, always preceded by "." to apply styles on CSS.
  		- id: Used to select a specific HTML element and make it uninque to a specific page.
  		- To select an element with a specific "id", a "#" symbol is inserted on the stylesheet, followed by the id of the element.
```
i.e To make changes to a specific paragraph that has been given the "id" name para1: <id="para1">

 #para1 {
  text-align: center;
  color: gold;
} 					<!--Specifies that all that is on para1 will be aligned towards the center, and the color of that text will be gold-->
 ```
  - Class: Selects elements with a specific class attribute. Can be used to create a reference point for styling, meaning that we can add changes to content that is inside a specific class
```
i.e To make changes to a specific paragraph that has been given the "id" name para1: <id="para1">

 .playlist {
  text-align: center;
  color: gold;
} 					<!--Specifies that all elements output in class="playlist" will be aligned towards the center, and the color of that text will be gold-->
```
- combinator	- Selects elements based solely on a specific relationship between them
- Attribute	- Selects elements based on a specific attribute or attribute value in our code.
- Universal	- Selects all HTML elements on a specific page
```
An example of how a universal selector works.
* {
  text-align: left;
  color: green;			
  background-color: Goldenrod;
}					<!--Simply means that every text within that page will be aligned on the left, the color of the text is going to be green, and the background of this specific page will be goldenrod-->
```
We can add styles to HTML selectors such as "h1 to h6"and "p", you simply type "p" followed by calebraces and then you add the necessary styles you want to feature on your page. To add the same styles to multiple selectors is simple:
```
h1, h2, p {
  text-align: center;
  color: green;			
  background-color: Goldenrod;
}					<!--Simply means that every text within "h1", "h2", and "p" will be aligned on the left, the color of the text is going to be green, and the background of thi will be goldenrod-->
```
CSS style declaration consists of 3 parts: 

Selector
Property 
Value 
```
p					<!--Refers to the selector-->
{
  color:				<!--Refers to the Property-->
  red;					<!--Refers to the Value-->
}
```
## Unit 3: Color Schemes
Refers to the colors you might want to include on to your website. For colorways that we don't know the names of, we use a color pallete that can be easily found even on google, as the goal is to choose a color scheme or specific colors to enhance the visual of your website. If one struggle to find the perfect color scheme for their website, we have many resources we can choose from online, one example that we are currently exploring is the "Canva" online app.
Canva: Canva is a user-friendly graphic designing online platform for people who do not have a graphic design background. Canva makes it easy to find color schemes by allowing us to upload images, and creates a color pallete for our page based on that specific image.

### Margin and Padding
Styling with CSS VS Styling Inline.

In-line styling - Refers to adding visual enhancements to your code within HTML without linking a stylesheet from CSS. When used, it can only add style to the sides of the text(from left to right)
- Margin  - Refers to the area that starts after the section's border.
- Padding - Refers to the area just outside text's border
