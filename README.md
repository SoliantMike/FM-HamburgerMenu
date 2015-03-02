FM-HamburgerMenu
===========
You may have seen the three little horizontally stacked lines in the upper corner of your favorite website or app. That is what is known as a Hamburger Menu

The premise is simple: click the widget and get a drawer to slide out. The drawer contains more buttons to click on. It might seem obvious to use a slider, and that is the main object we are using. We will just want to have some control over animating this control to make it intuitive. In this example, we will use it as a navigation menu.

There are two panels involved; one is blank and the other panel will contain our menu. The blank panel is there to give the appearance of the other panel opening and closing.

To reveal our Menu Content, we must start at Stage Left, and move to Center Stage. To close the menu, we then move back to Stage Left.

We use a combination of a popover object and a slider object. By placing the entire slider object into a popover, we get the best of both worlds. When you click out of a popover, it closes automatically. Even better, we can capture the close event with a script trigger and animate the closing of the menu.

Another advantage in using popovers is that you do not "click through" popovers, so it helps in keeping the layout tidy and navigable. Using a popover allows us to use this technique in list view as well.

Hopefully this demonstrates an easy-to-use technique that you can leverage in your own solutions. It doesn't have to be exactly as presented here, but this should provide a starting point and possibly give you ideas of how to build on what we have shown. Let your imagination run wild.


Read more here:
http://www.soliantconsulting.com/blog/2015/03/filemaker-hamburger-menu

Video walk through:
Coming soon
