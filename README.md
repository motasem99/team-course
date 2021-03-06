## Start Course

Hi everyone good job to reach here. now we are going a head to the next step in our way. 

before you start [this](https://www.youtube.com/watch?gl=GB&hl=en-GB&v=OGg8A2zfWKg) is 6 minute youtube video to introduce you to the concept of the semantic web.

### Semantic HTML5


#### Resources:

* Read [this article](https://www.smashingmagazine.com/2013/01/the-importance-of-sections/#the-problem-with-div) to stop using too many divs. Do not be fooled by the scroll bar - the article is not particularly long, but there are many comments below.

* In [this codepen artical](https://codepen.io/mi-lee/post/an-overview-of-html5-semantics) you must learn the main structure HTML5 and there tages. [ important ]

* Signup in [freecodecamp](https://www.freecodecamp.org/). then solve [Basic HTML and HTML5](https://www.freecodecamp.org/learn/) 0-28. please do not forget to signup in freecodecamp with your github to save your work and you did not lost it.

#### Learning outcome:

* Be familiar with new HTML5 elements.


### CSS3

Here we are reviewing the information you learned it with zeroweb then we will go to learning all about CSS3.

after we start with main topics we have to solve problem with codecamp :-

* [basic css ](https://www.freecodecamp.org/learn) 44 point.

#### The main topics
* Position Element
* Working with image and background
* Size & Units
* Making your website responsive
* Flexbox
* Grid
* Transforming Element
* Animations

#### Position Element:

The position CSS property set how an element is positioned in a doucement.

we have three levels to be familer with positions in CSS:

* [CSS Layout - The position Property](https://www.w3schools.com/css/css_positioning.asp) W3School.

* [Position MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/position) developer mozilla.

* Solve [Applied Visual Design](https://www.freecodecamp.org/learn/) 52 questions on freecodecamp.

* after you end all that you can read [this artical](https://medium.com/@leannezhang/difference-between-css-position-absolute-versus-relative-35f064384c6) about difference between absolute and relative.


#### working with image and background:

* Read this [artical](https://www.w3schools.com/css/css_background.asp) as a start to deal with background.

* After you read first artical read this articals:
>   1. [background-attachment](https://www.w3schools.com/cssref/pr_background-attachment.asp) 
    
>  2. [background-blend-mode](https://www.w3schools.com/cssref/pr_background-blend-mode.asp)

 >   3. [background-clip](https://www.w3schools.com/cssref/css3_pr_background-clip.asp)

>    4. [background-color](https://www.w3schools.com/cssref/pr_background-color.asp) 

 >   5. [background-image](https://www.w3schools.com/cssref/pr_background-image.asp) 

  >  6. [background-origin](https://www.w3schools.com/cssref/css3_pr_background-origin.asp)

 >   7. [background-position](https://www.w3schools.com/cssref/pr_background-position.asp)

  >  8. [background-repeat](https://www.w3schools.com/cssref/pr_background-repeat.asp) 

   > 9. [background-size](https://www.w3schools.com/cssref/css3_pr_background-size.asp)

#### Size & Units

CSS has several units for expressing a length.

here we will learn about two type of unite in css absoulte and relative length.

we will [start with small artical](https://www.w3schools.com/cssref/css_units.asp) to understand the main point of using different units in our projects.

#### The differences between rem, em, px, & vw/vh units

This artical should hopefully help explain the difference between the various size units.

The basics
##### rem
rem units are relational to the font-size value of the HTML tag. For example, if the font size of the HTML tag is 16px (that is the default size for an html document), then 1rem unit is equal to 16px. That makes .5rem=8px, 2rem=32px, etc.

##### em
em units are similar to rem units, but whereas a rem unit always references the HTML tag, an em unit is relational only to it's nearest defined parent element. For example, if the div wrapper for a callout is set to font-size:20px, then any child element set to 1em would be the equivalent of 20px, .5em=10px, 2em=40px, etc.

##### vw & vh
the vw (view-width) and vh (view-height) units are relational to the viewport size, where 100vw or vh is 100% of the viewport's width/height. For example, if a viewport is 1600px wide, and you specify something as being 2vw, that will be the equivalent of 2% of the viewport width, or 32px.

##### px
Pixels are defined as a single point in a graphic image, and are often tied to viewport resolution. If a viewport is 1600x90, that typically means that there are 1600px pixel columns & 900 pixel rows, with a pixel in each cell. This definition is maybe overly simple when factoring in dpi or pixel density, but can stand as reference for the most part.

##### Where things get interesting:
There is a lot of potential between the dynamic units (rem/em/vw/vh) to build extremely responsive controls on a page. One common problem with responsive design is ensuring that text displays & wraps properly as everything around it shrinks and collapses. This is mainly because even if you leverage em/rem units, you are ultimately still referencing a static HTML font size, even if set to 100%.

##### Consider this: 

on a monitor that is 1600px wide, 1vw is equivalent to 16px, which is the same as the default font size on an HTML document. As the viewport grows and shrinks, that vw value will grow and shrink relationally with it. This means that you can set a dynamic size value on the HTML tag, reference it at a component parent level with rem, and then match against that value in the child elements with em. That provides a fairly granular level of control, and a set of elements that proportionally resize according to the viewport. Click Here for an example

after you finish the first artical now we will go deeper to learn it perfectly.

*  [Rem/Em Units](https://webdesign.tutsplus.com/tutorials/comprehensive-guide-when-to-use-em-vs-rem--cms-23984): this artical to understand different between using rem and em and what is the best.

* [this artical](https://stackoverflow.com/questions/31039979/css-units-what-is-the-difference-between-vh-vw-and) to understand the different between using vh & vw or %.


#### Flexbox

the flex css property set how a flex item will grow or shrink to fit the space avalible in its flex container.

to be familer with felx box you will go to throw this articals..

* [W3school flex](https://www.w3schools.com/css/css3_flexbox.asp).

* solve question css [Flexbox freecodecamp](https://www.freecodecamp.org/learn) [17 questions].

#### Grid

The grid CSS property is a shorthand property that sets all of the explicit grid properties (grid-template-rows, grid-template-columns, and grid-template-areas), and all the implicit grid properties (grid-auto-rows, grid-auto-columns, and grid-auto-flow), in a single declaration.

* [Grid Intro](https://www.w3schools.com/css/css_grid.asp)
* [Grid Container](https://www.w3schools.com/css/css_grid_container.asp)
* [Grid Items](https://www.w3schools.com/css/css_grid_item.asp)
* Solve question css [Grid freecodecamp](https://www.freecodecamp.org/learn) [22 questions]

#### Making your website responsive

there are many of the framworks make your website responsive but here we will learn how to make website response with css only (no framworks). so we will using flex or grid with media queries.

* [build responsive website layout](https://coder-coder.com/build-flexbox-website-layout/)

* [responsive design of the future](https://blog.teamtreehouse.com/responsive-design-of-the-future-with-flexbox)

* This is [15min vedio youtube](https://www.youtube.com/watch?v=WzLuTCRpvag) about make your as intro to media queries.

* [Responsive Web Design - Media Queries](https://www.w3schools.com/css/css_rwd_mediaqueries.asp).


##### why we need media queries when we using flexbox or grid?

Sometime when using flex box or grid you want to change your structure app from column to row or from row to column or solve some problem you find it in your design.


### Thanks for everyone reaches to this level

now we finishing what we started now we able to go far and go to next level.

the finial points:-

* [Learn Layout](http://learnlayout.com) is a helpful, lightweight, well-ordered guide that covers a lot of concepts in CSS to help you understand how to create a super basic layout. Additional links are provided in each section for more detailed explanations of concepts.

* [CSS Specificity](https://www.smashingmagazine.com/2007/07/css-specificity-things-you-should-know/) is an essential guide to understanding how CSS rules are applied and how CSS works in general.

* [Applied Accessibility](https://www.freecodecamp.org/learn) freecodecamp. (22 point)

Now you learn alot about HTML5 and CSS3 and able to do alot see you in the exercise and projects.


## Projects

* [Download this file](https://mega.nz/#!nOh1TByK!4fAWG9qWHBqoI2pHdWTsLCWCe7t4ChwPTpnObriSktU) and you will find design to your first project and sould be responsive with small devices.

* Now we have five challenges from freecodecamp site and after all you ready to challenges:-

   1. [First Project](https://www.freecodecamp.org/learn/responsive-web-design/responsive-web-design-projects/build-a-tribute-page) this project is a sample page as a begin.

   2. [Second Project](https://www.freecodecamp.org/learn/responsive-web-design/responsive-web-design-projects/build-a-survey-form) learn how to create good forms.

   3. [Thrid Project](https://www.freecodecamp.org/learn/responsive-web-design/responsive-web-design-projects/build-a-product-landing-page) Build a Product Page you learn create page to show your product on it.

   4. [Fourth Project](https://www.freecodecamp.org/learn/responsive-web-design/responsive-web-design-projects/build-a-technical-documentation-page)  Build a Technical Documentation Page, learn how to create a good documentation.

* Finilay probably you want to create your first portfolio this [finial project](https://www.freecodecamp.org/learn/responsive-web-design/responsive-web-design-projects/build-a-personal-portfolio-webpage) you create a portfolio for you.
### Authors
[Mohammed M Zourob](https://github.com/dash7ou): [@dash7ou](https://github.com/dash7ou)