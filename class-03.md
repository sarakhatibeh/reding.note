# HTML Lists, Control Flow with JS, and the CSS Box Model

There are lots of occasions when we need to use lists. HTML provides us with three different types:

1. Ordered lists are lists where each item in the list is numbered. For example, the list might be a set of steps for a recipe that must be performed in order, or a legal contract where each point needs to be identified by a section number

2. Unordered lists are lists that begin with a bullet point (rather than characters that indicate order)

3. Definition lists are made up of a set of terms along with the definitions for each of those terms.

## Ordered Lists

1. < ol>

The ordered list is created with the < ol> element

2. < li>

Each item in the list is placed between an opening < li> tag and a closing < /li> tag. (The listands for list item.)

## Unorderedlist

* < ul>

The unordered list is created with the < ul> element.

* < li>

Each item in the list is placed between an opening < li> tag and a closing < /li> tag. (The listands for list item.)

## Definition Lists
 
 * < dl>

The definition list is created with the < dl> element and usually consists of a series of terms and 
their definitions.Inside the < dl> element you will usually see pairs of < dt> and < dd> elements

* < dt>

This is used to contain the term being defined (the definition term).

* < dd>
This is used to contain the definition.
 

 ## Nested list

 You can put a second list inside an < li> element to create a sublist or nested list

 ## Box Dimensions

### width, height
 
 by default a box is sized just big enough to hold its contents. To set your own dimensions for a 
box you can use the height and width properties.The most popular ways to specify the size of a box are 
to use pixels, percentages, or ems. Traditionally, pixels have been the most popular method 
because they allow designers to accurately control their size.

When you use percentages, the size of the box is relative to the size of the browser window or, if the box is encased within 
another box, it is a percentage of the size of the containing box.


## Overflowing Content

### overflow

The overflow property tells the browser what to do if the content contained within a box is larger 
than the box itself. It can have one of two values

* hidden

This property simply hides any extra content that does not fit in the box

* scroll

This property adds a scrollbar to the box so that users can scroll to see the missing content.
On the left, you can see two boxes whose contents expand beyond their set dimensions. The first example has the overflow
property with a value of hidden. The second example has the overflow property with a value of scroll


## Border, Margin & Padding

![img](sa.png)

## Border Width

the border-width property is used to control the width of a border. The value of this 
property can either be given in pixels or using one of the following values:
 
* thin
* medium
* thick
(You cannot use percentages with this property.)

 You can control the individual size of borders using four separate properties:

* border-top-width
* border-right-width
* border-bottom-width
* border-left-width

## Border Style

### border-style

You can control the style of a border using the border-styleproperty. This property can take the following values:

solid  a single solid line

dotted  a series of square dots

(if your border is 2px wide, then the dots are 2px squared with a 
px gap between each dot)

dashed  a series of short lines double two solid lines (the value of the border-width
property creates the sum of the two lines)

groove appears to be carved into the page ridge appears to stick out from the page
inset appears embedded into the page


## Padding

The padding property allows you to specify how much space should appear between the content of an element and its border. 
The value of this property is most often specified in pixels (although it is also possible to use percentages or ems). If a 
percentage is used, the padding  is a percentage of the browser window (or of the containing box if it is inside another box)

* padding-top
* padding-right
* padding-bottom
* padding-left


## Mergin 

The margin property controls the gap between boxes. Its value is commonly given in pixels, although you may also use 
percentages or ems.If one box sits on top of another, margins are collapsed , which means the larger of the two margins will be used and the smaller will be disregarded

* margin-top
* margin-right
* margin-bottom
* margin-left

## Change Inline/Block

### display

The display property allows you to turn an inline element into a block-level element or vice 
versa, and can also be used to hide an element from the page

The values this property can take are:

1. inline
2. block
3. inline-block
4. none

## Basic JavaScript Instructions

### ARRAYS 

An array is a special type of variable. It doesn't just store one value; it stores a list of values.

![img](ssa.png)


## VALUES IN ARRAYS 

Values in an array are accessed as if they are in a numbered list. It is important to know that the numbering of this list starts at zero (not one). 

![img](ssss.png)


![img](sa1.png)

![img](sa12.png)

![img](s23.png)
