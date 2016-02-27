[This is the link to my website](http://robinsoubry.github.io/index.html)

##What did you learn about CSS padding, borders, and margin by doing this challenge?##
The HTML/CSS box model is additive. If you set an element to a specific width/height, and then add padding, a border or a margin; the element as a whole expands. This may mess up the alignment with other elements that you want to position next to that element.
As a quick recap:
	- __Padding:__Defines the distance from the theorethical div border to the content inside of it. For example if you want some white-space to avoid your text sticking to the edge of a page.
	- __Borders:__De edge of the div that you are looking at. You can give this a thickness, a color and a style (solid line, dotted, dashed etc.)
	- __Margins:__Margins are some kind of aura around the div, where no other elements will take the space. This "transparent" area can be helpful when positioning elements next to each other and helps to define the space between elements.

##What did you learn about CSS positioning?##
I found the positioning in CSS the hardest part because it's very intangible, and requires a lot of trial and error. I tried to solve this by creating a very rudimentary version of the webpage and by giving each element a distinct background color (to see where the elements were actually located on the page). Only when the positionng made sense, I started adding more details to the different elements. Even then, the positioning sometimes got messed up by the additive character of padding, borders etc.

##What aspects of your design did you find easiest to implement? What was most difficult?##
	- __The easiest aspects:__Colors, Fonts and font sizes
	- __The harder aspects:__Positioning and knowing how to use selectors in a "best practice way". For example, I created a class "clear-float" (with the CSS attribute "clear:both;" and added it to the elements I wanted to be cleared. instead of adding it to each and every element in the CSS file… It works well, but I have no idea on whether this is the way to go.

##What did you learn about adding and formatting elements with CSS in this challenge?##
Adding the CSS is fun because you see your creation come alive straight away. On the other hand, it's also very time consuming and even with a simple page, it generates a lot of lines of code. I think that it's essential to study best practices as much as possible and stick to certain naming conventions for classes, id's etc.
I spent for example 30' figuring out a bug in the code and it appeared to be just an error in the naming…