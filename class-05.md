# Images, Color, Text

A picture can say a thousand words, and great images help make the difference between an 
average-looking site and a really engaging one.

images can be used to set the tone for a site in less time than it takes to read a description. If 
you do not have photographs to use on your website, there are companies who sell stock images; these are images you 
pay to use (there is a list of stock photography websites below).

 Remember that all images are subject to copyright, and you can get in trouble for simply 
taking photographs from another website.If you have a page that shows several images (such as product 
photographs or members of a team) then putting them on a simple, consistent background helps them look better as 
a group


### Storing Images on Your Site

If you are building a site from scratch, it is good practice to create a folder for all of the images 
the site uses.As a website grows, keeping images in a separate folder helps you understand how the site is organized. Here you can 
see an example of the files for a website; all of the images are stored in a folder called images.
On a big site you might like to add subfolders inside the images
folder. 
For example, images such as logos and buttons might sit in a folder called interface, product 
photographs might sit in a page called products, and images related to news might live in a 
folder called news.

### Adding Images

< img> 

To add an image into the page you need to use an < img>element. This is an empty 
element (which means there is no closing tag). It must carry the following two attributes

### src

This tells the browser where it can find the image file. This will usually be a relative URL 
pointing to an image on your own site. 

### alt

This provides a text description of the image which describes the image if you cannot see it.

### title

You can also use the titleattribute with the < img> element to provide additional information 
about the image. Most browsers will display the content of this attribute in a tootip when the 
user hovers over the image.

## Color

The color property allows you to specify the color of text inside 
an element. You can specify any 
color in CSS in one of three ways:

1. rgb values
2.  hex codes
3. color names

### background-color

CSS treats each HTML element as if it appears in a box, and the background-color property 
sets the color of the background for that box.You can specify your choice of 
background color in the same three ways you can specify foreground colors: RGB values, 
hex codes, and color names


### Text

![img](c1.png)

![img](c2.png)


## Bold
### font-weight

### normal

This causes text to appear at a 
normal weight.

### bold

This causes text to appear bold.In this example, you can see 
that the element whose classattribute has a value of credits
has been bolded.

## Italic

### font-style

f you want to create italic text, you can use the font-style
property. There are three values this property can take:normal
This causes text to appear in a normal style (as opposed to italic 
or oblique).

### italic

This causes text to appear italic.

### oblique

This causes text to appear oblique

## UpperCase & LowerCase

### text-transform
The text-transform property is used to change the case of ext giving it one of the following 
values:

* uppercase
* lowercase
* capitalize

## text-decoration

* none
* underline
* overline
* line-through
* blink

