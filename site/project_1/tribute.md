### In this project, I designed a simple web page using HTML and CSS. This project made me understand the importance of division element in specifying different parts of the web page for ease of styling.
### A few take home here are:
- While adjusting the distance between elments, first add padding (in all four directions) and preview, then go ahead to add the right set of padding distances before adding your margin. <br>

- To centralize a group of text under a given division element (a very important block elment), explore adjusting the width, aligning, ad most importantly; relative position specification. <br>

- margin: auto; helped me to centralize very well, so that it displays well across various screen size. 
<br>

- I realised that relative positioning displays at different positions on different screen size. <br>

- Adjust image width so that it dosen't go above 100% (I realised that % was helpful here in contrast to pexels) of the screen. Also, when you specify width in %, it is with respect to the container element it is in (the parent element)
<br>

- In adjusting positions, try to work with relative positions and with percentage (%), so as to get good rendering, when displayed on larger screens, because different screen has different sizes. This is very important. 

<br>

### Absolute Positioning
- You can set out a particular layout with a container element and move that container element or offset it all around the screen without having to offset particular values of every element within that container element. Absolute positioning needs a  relative or an absolute parent (or an ancestor) When we set an absolute position for an element, it goes up the chain to check if the next parent has it's position set to either relative or absolute, if NO, it keeps going, to the body element, if No, then finnally to the html element which has it's position set to relative by default. 
<br>

-  Static positioning is default for all elements, except html. Relative positioning offsets the element relative to it's normal document flow position. Absolute positioning is relative to closest ancestor which has positioning set to non-static value. Offsetting the relative container element offsets it's contents as well. 

- Also try as much as possible to keep your work neat.

- To avoid bolding your text, you can start a new line with the p element (a block element)

### Random Tips

- When trying to style elements to look like a table, use a consistent div element selector and id selector to place each entry. See the figure below.
<br>
<br>

![array](./tip.PNG)
<br>
<br>

- Sometimes you could decide to add an animation to your background color. You can do this by creating an id selector and defining the animation-name and animation-duration, then setting aa keyframe for the different color transitions.
<br>
<br>

![array](./background_anim.PNG)
<br>
<br>

![array](./button_animation.PNG)<br>
Animation apllied to a button on hovering around it

For more information on more cool animations, visit the links below:
<br>

[up_down/left_right](https://www.freecodecamp.org/learn/responsive-web-design/applied-visual-design/create-movement-using-css-animation)<br>
[bounce](https://www.freecodecamp.org/learn/responsive-web-design/applied-visual-design/animate-elements-continually-using-an-infinite-animation-count)



