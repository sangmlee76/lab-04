# LAB - 04

## SMACSS and Responsive Web Design
In lab 1, you built a web page where each box of content was rendered with a unique color in desktop view and in mobile view. You will be completing this assignment again, using either Flexbox or CSS grids for styling.

### Author: Sang Lee | sanglee76@yahoo.com | https://github.com/sangmlee76/lab-04

### Version: 0.1.0

### Links and Resources
+ [submission PR](https://github.com/sangmlee76/lab-01/pull/4)
+ [seattle-301d69 Class-01 demo](https://github.com/codefellows/seattle-301d69/tree/main/class-01/demos/smaccs-practice-flex)
+ [Responsive web design](https://learn.shayhowe.com/advanced-html-css/responsive-web-design/#viewport)
+ [CSS Media Queries](https://www.w3schools.com/css/css3_mediaqueries_ex.asp)
+ [BitDegree](https://www.bitdegree.org/learn/responsive-media)


### Reflections and Comments
+ Consider including the answers to your daily journal and submission questions here
+ This is also a good place to reflect on the tools and resources used and learned

### Updates
+ N/A

*****

## [Assignment Instructions](https://canvas.instructure.com/courses/2433455/assignments/18669462?module_item_id=39246635)

### Overview
In lab 1, you built a web page where each box of content was rendered with a unique color in desktop view and in mobile view. You will be completing this assignment again, using either Flexbox or CSS grids for styling.

Refer back to the lab 1 assignment details for a reminder of the problem domain. Deploy when done.

### Feature #1: Responsive design

**Why are we implementing this feature?**
As a user, I want the dimensions and colors of the application to change so that I can have a unique view in desktop, mobile, and tablet viewports.

**What are we going to implement?**
Given that a user opens the application in the browser, on a tablet, or on a mobile device
When the user changes the size of the viewport
Then the boxes should scale proportionally and change colors

**How are we implementing it?**
+ Use Flexbox or CSS grids for styling this application.
+ Use relative units so the elements scale proportionally when the viewport dimensions change.
+ Use at least two breakpoints and change the background colors of each box. There should be three possible views: desktop, tablet, and mobile device. You may choose the exact pixel values for each breakpoint.

*******

## [Assignment Instructions](https://canvas.instructure.com/courses/2433455/assignments/18669459?module_item_id=39246619)

#### Overview (Lab 01)
In lab today, you will be building a single responsive web page based off of the provided design comp assets. These contain images of what you are striving to build in HTML and CSS, so be sure to open them up and keep them handy, but note that they are not for actual use on the page. You can also print out these comps and use them to mark up and sketch out page structure.

Your document must be designed in a mobile-first approach and must be responsive when the screen size changes and the page is refreshed. The details of the media query specifications are up to you, but your breakpoint must be at 768 pixels.

This is an independent project, but your are free to collaborate with your classmates.

#### Resources
+ [SMACSS Official Documentation](http://smacss.com/)
+ Desktop wireframe
+ Mobile wireframe

#### Feature Tasks
+ Create a new repository named lab-01.
+ Work on a non-master branch.
+ Use good HTML structure to scaffold this site, using semantic elements where possible.
+ Container elements (a box outside of your content box that might contain multiple content boxes) are very useful in managing layout. You will need to think about the relationship between parent and child / descendant elements as well as the order in which you place them in the HTML. Be thoughtful about your layout strategy.
Add a reset.css file to your project, like this one.
+ Use SMACSS-style modularity to organize your CSS.
+ Style the page using float-based layout to reflect the comp images provided as closely as possible. The only text you should have in each box is the identifying letter, which should be centered horizontally and vertically.
+ For the desktop view, the content should be inside of a channel that is a maximum of 960 pixels wide and is centered on wider screen sizes.
+ Each box should have a unique background color in mobile view and in desktop view. We are not working with jQuery events yet, so these changes should be observed when the screen size changes and the page is refreshed.

#### Stretch Goal
+ Create an additional breakpoint for a new set of colors when the page is viewed on a tablet.
+ Use jQuery to change the color of each box based on the screen size.