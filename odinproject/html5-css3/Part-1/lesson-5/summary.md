#Summary of lesson 5 (Step 3: Linking Internal and External Pages)

I get some fresh knowledge about pseudo classes

1. Overview

Here’s a description of each pseudo-class:

:link – selects unvisited links.
:visited – selects visited links.
:hover – the state that happens when the user places their mouse pointer on top of a link.
:active – the state that happens when the user clicks on a link. This is the very brief moment between clicking on the link and becoming focused, or the moment between clicking and then going to another web page. Because this state normally lasts for a short duration, you can see this state easier when you click-and-mouse-down on a link without releasing the mouse button.
:focus – the state that occurs when the user focuses on the link. This state can be seen when you tab to a link, or after you click on a link.
Technically, out of the five most commonly used pseudo-classes for links, only two — :link and :visited — are actually the link pseudo-classes that are specifically designed for HTML link (<a>) elements.

The other three — :hover, :active, and :focus — are called dynamic pseudo-classes and can be used on other HTML elements.

2. Suggested order:
a { }
a:link { }
a:visited { }
a:hover { }
a:focus { }
a:active { }

3. Cases insensitivity 

4. Cannot work if there is a space between the colon and the class/pseudo-class after/before.
