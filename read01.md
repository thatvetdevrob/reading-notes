[Back Home](https://thatvetdevrob.github.io/reading-notes/)

#Read: 01 - SMACSS and Responsive Web Design

![GitHub Logo](https://smhttp-ssl-31623-sherocom.nexcesscdn.net/wp-content/uploads/2016/01/github-banner.png)

## Responsive Web Design

Ethan Marcotte coined the term and developed the idea of responsive wed design: The idea that when we use the internet we will be able to do so in any device and screen correctly. 


### General Terms

#### Adaptive

Easily modified to new situations.
#### Responsive

React quickly to any change.
#### Mobile

Mobile has a place (akin to pagers still in use in hospitals) but then it becomes two different systems and needs more resources.
Flexible grids are ideal because they can be used to create layouts that change depending on the relative units (em’s and %) to guide the layout in the size rather than a hard coded size in pixels or points.

*CSS3 has viewport units but they aren’t supported (on iphones for one) but they might become a great solution some day.* 

The biggest takeaway is that if you have the option, start by developing for smaller devices first and then move out from there.

# All About Floats

Chris Coyier talks about the Float CSS attribute that allows us to make sure images and other elements have a desired formation on our pages.
While he does not want us to use float as a general page layout tool (he wants us to use the flexbox or grid as example) he thinks there a place for float.  

One of the most important things to notice is that there are problems that can come from float, and also that float can only be used in certain situations.

One problem that float has is that if the parent contained has nothing but floated elements inside of it will collapse. So it’s easy to fix, but its best to keep an eye out on it.

Also Float needs to be cleared to prevent footers or other problems with layout. Its best to clear a float after it is used but before its parent container is closed.

Float elements must not be outside the regular flow, so absolute and static positioned elements will not use it to move about. 

I’ve booked marked the page, as it has a lot of very important information, but it’s really situational, and studying styles and practice would make the use of the information more useful, because without context it lacks a clear message to someone inexperienced in CSS who’s yet to troubleshoot float.

[Back Home](https://thatvetdevrob.github.io/reading-notes/)

![Git and VS ](https://andrewlock.net/content/images/2017/03/banner.PNG)


