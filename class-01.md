## HTML 

### HTML Describes the Structure of Pages


 HTML stands for HyperText Markup Language. The HyperText part refers to the fact that HTML allows you to create links that allow visitors to move from one page to another quickly and easily. A markup language allows you to annotate text, and these annotations provide additional meaning to the contents of adocument

 To describe the structure of a web page, we add code to the words we want to appear on the page.

The HTML code  is made up of characters that live inside angled
brackets — these are called HTML elements. Elements are usually
made up of two tags: an opening tag and a closing tag. (The closing tag has an extra forward slash in it.) Each HTML element tells the browser something about the information that sits between its opening and closing tags.

### Example :


##### <html> 
#### <body>
 #### <h1>This is the Main Heading</h1>
 #### <p>This text might be an introduction to the rest of the page. And if the page is a long one it might be split up into several sub-headings.<p>
 #### <h2>This is a Sub-Heading</h2>
 #### <p>Many long articles have sub-headings so to help you follow the structure of what is being written.There may even be sub-sub-headings (or lower-level headings).</p>
 
 #### <h2>Another Sub-Heading</h2>
 #### <p>Here you can see another sub-heading.</p>
#### </body>
#### </html>


in the previous example there are several different elements. Each
element has an opening tag and a closing tag
Tags act like containers. They tell you something about the information that lies between their opening and closing tags.

The opening < html> tag indicates that anything between it and a closing < /html> tag is HTML code

The < body> tag indicates that anything between it and the closing
< /body> tag should be shown inside the main browser window

Words between < h1> and < /h1> are a main heading.

A paragraph of text appears between these < p> and < /p> tags.

Words between < h2> and  < /h2> form a sub-heading.

Here is another paragraph between opening < p> and closing < /p> tags.

Another sub-heading inside < h2> and < /h2> tags.

Another paragraph inside < p> and < /p> tags

The closing < /body> tag indicates the end of what should appear in the main browser window

The closing < /html> tag indicates that it is the end of the HTML code.


  ## <p>
The characters in the brackets indicate the tag's purpose , in the tags above the p stands for paragraph.


### Attributes Tell Us More About Elements

Attributes provide additional information about the contents of an element. They appear on the opening tag of the element and are made up of two parts: a name and a value, separated by an equals sign.

example 

#### <p name ="value">Paragraph in English</p>

The attribute name indicates what kind of extra information you are supplying about the element's content. It should be written in lowercase.
The value is the information or setting for the attribute. It should be placed in double quotes. Different attributes can have different values

### <p lang="en-us">Paragraph in English</p>
Here an attribute called lang is used to indicate the language used in this element. The value of this attribute on this page specifies it is in US English.

The majority of attributes can only be used on certain elements although a few attributes (such as lang) can appear on any element

Most attribute values are either pre-defined or follow a stipulated format. We will look at the permitted values as we introduce each new attribute

## Body, Head & Title

#### <body>

You met the < body> element in the first example we created.Everything inside this element is shown inside the main browser window.

#### <head>
Before the < body> element you will often see a < head> element.This contains information about the page .You will usually find a < title> element inside the < head> element

#### <title>
The contents of the < title> element are either shown in the top of the browser, above where you usually type in the URL of the page you want to visit, or on the tab for that page (if your browser uses tabs to allow you to view multiple pages at the same time).



## Extra Markup

### DOCTYPES
Because there have been several versions of HTML, each web page should begin with a DOCTYPE declaration to tell a browser which version of HTML the page is using (although browsers usually display the page even if it is not included).

### Comments in HTML
##### <!-- -->
If you want to add a comment to your code that will not be visible in the user's browser, you can add the text between these characters:
 ##### <!-- comment goes here -->
 * Although comments are not visible to users in the main browser window, they can be viewed by anyone who looks at the source code behind the page.

 * Comments can also be used around blocks of code to stop that code from being displayed in the browser


 #### ID Attribute
 Every HTML element can carry the id attribute. It is used to
uniquely identify that element from other elements on the page. Its value should start with a letter or an underscore (not a number or any other character). It is important that no two elements on the same page have the same value for their id attributes


* The id attribute is known as a global attribute because it can be used on any element.

#### Class Attribute
Every HTML element can also carry a class attribute. Sometimes, rather than uniquely identifying one element within a document, you will want a way to identify several elements as being different from the other elements on the page.

* By default, using these attributes does not affect the presentation
of an element. It will only change their appearance if there is a CSS rule that indicates it should be displayed differently

#### Block Elements

Some elements will always appear to start on a new line in the browser window. These are known as block level elements.

Examples of block elements are
 * < h1>, < p>, < ul>, and < li>


#### Inline Elements
Some elements will always appear to continue on the same line as their neighbouring elements. These are known as inline elements

Examples of inline elements are
* < a>, < b>, < em>, and < img>

### Grouping Text & Elements In a Block

#### <div>
 The < div> element allows you to group a set of elements together in one block-level box.
In a browser, the contents of the <div> element will start on a new line, but other than this it will make no difference to the presentation of the page.
### Grouping Text & Elements Inline

#### <span>
The < span> element acts like an inline equivalent of the <div> element. It is used to either:

* Contain a section of text where there is no other suitable element to differentiate it from its surrounding text

* Contain a number of inline elements

The most common reason why people use < span> elements is so that they can control the appearance of the content of these elements using CSS

You will usually see that a class or id attribute is used with < span> elements:

● To explain the purpose of this < span> element

● So that CSS styles can be applied to elements that have specific values for these attributes

### IFrames
#### <iframe> 

An iframe is like a little window that has been cut into your page — and in that window you can see another page. The term iframe is an abbreviation of inline frame.

An iframe is created using the < iframe> element. There are a few attributes that you will need to know to use it:
* src

The src attribute specifies the URL of the page to show in the frame.

* height

The height attribute specifies the height of the iframe in pixels.

* width

The width attribute specifies the width of the iframe in pixels.

### Information About Your Pages
#### <meta>
The < meta> element livesinside the < head> element and contains information about that web page. It is not visible to users but fulfills a number of purposes such as telling search engines about your page, who created it, and whether or not it is time sensitive. (If the page is timesensitive, it can be set to expire.)

The < meta> element is an empty element so it does not have a closing tag. It uses attributes to carry the information.

### Escape Characters
There are some characters that are used in and reserved by HTML code. (For example, the left and right angled brackets.)

Therefore, if you want these characters to appear on your page you need to use what are termed "escape" characters (also known as escape codes or entity references). For example, to write a left angled bracket,you can use either & lt;" or & #60;. For an ampersand, you can use either & amp; or & #38;.


### Headers & Footers

The < header> and < footer> elements can be used for:

● The main header or footer that appears at the top or bottom of every page on the site.

● A header or footer for an individual < article> or < section> within the page

### Navigation
#### <nav>
The < nav> element is used to contain the major navigational
blocks on the site such as the primary site navigation.


### Articles
#### <article>

The < article> element acts as a container for any section of a page that could stand alone and potentially be syndicated.

This could be an individual article or blog entry, a comment or forum post, or any other independent piece of content

### ASIDES

#### <aside>

The < aside> element has two purposes, depending on whether it is inside an < article> element or not. When the < aside> element is used inside an < article> element, it should contain information that is related to the article but not essential to its overall meaning

When the < aside> element is used outside of an < article> element, it acts as a container for content that is related to the entire page. For example, it might contain links to other sections of the site, a list of recent posts, a search box, or recent tweets by the author.

### Sections

##### <section>
The < section> element groups related content together, and typically each section would have its own heading.

### Heading Groups
#### <hgroup>

The purpose of the < hgroup> element is to group together a set of one or more < h1> through < h6> elements so that they are treated as one single heading

### Figures
##### <figure> <figcaption>

It is important to note that the article should still make sense if the content of the < figure> element were moved (to another part of the page, or even to adifferent page altogether).

Examples of usage include:

● Images

● Videos

● Graphs

● Diagrams

● Code samples

● Text that supports the main body of an article

### Process & Design
Every website should be designed for the target audience—not just for yourself or the site owner. It is therefore very important to understand who your target audience is

### Target Audience: individuals

● What is the age range of your target audience?

● Will your site appeal to more women or men? What is the mix?

● Which country do your visitors live in?

● Do they live in urban or rural areas?

● What is the average income of visitors?


● What is their marital or family status?

● What is their occupation?

● How many hours do they work per week?

● How often do they use the web?

● What kind of device do they use to access the web?


### Target Audience: Companies

● What is the size of the company or relevant department?

● What is the position of people in the company who visit your site?

● Will visitors be using the site for themselves or for someone else?

● How large is the budget they control?


### Why People Visit YOUR Website

Your content and design should be influenced by the goals of
your users.To help determine why people are coming to your website,
there are two basic categories of questions you can ask:

1: The first attempts to discover the underlying motivations for why visitors come to the site. 

2: The second examines the specific goals of the visitors.These are the triggers making them come to the site now

### What Your Visitors are Trying to Achieve
It is unlikely that you will be able to list every reason why someone visits your site but you are looking for key tasks and motivations. This information can help guide your site designs.

### What Information Your Visitors Need
You know who is coming to your site and why they are coming, so now you need to work out what information they need in order to achieve
their goals quickly and effectively

### How Often People Will Visit Your Site
Some sites benefit from being updated more frequently than others. Some information (such as news) may be constantly changing, while other content remains relatively static.

### Site Maps
The aim is to create a diagram of the pages that will be used to structure the site. This is known as a site map and it will show how those pages can begrouped

To help you decide what information should go on each page, you can use a technique called card sorting.

This involves placing each piece of information that a visitor might need to know on a separate piece of paper and then organizing the related information into groups.

Each group relates to a page and, on larger sites the, pages can in turn can be grouped together to create different sections of the
website

### WireFrames
A wireframe is a simple sketch of the key information that needs to go on each page of a site. It shows the hierarchy of the information and how much space it might require.
