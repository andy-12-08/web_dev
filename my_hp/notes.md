### Some of the new things I learnt from building this page:
- I used CSS flex for building the menu bar, this functionality in aligning the row and spacing them. I converted the list to inline elements then embed them in a container whoose display was set to *flex*. This gave me a good understanding of how *flex* really works. 
<br>

- I made use of CSS grid in the section below the header. I made use of 3 by 6 grid and this hlped me to position the elements containing (the degrees, the image, the biography).This was later changed to 3 by 8 grid to obtain a better positioning of the image and the width of the image set to 100%. From this I saw that:
     <br>
    
    - ONLY width really matters: your height does not really effect until you begin to place tour contents. <br>

    - Choosing the grid size is also crusial to ensuring a good alignment/space management of elements within the grid.

- This image represents a  3 x 6 grid: 
<br>

![css_grid](./images/css_grid.PNG)
<br>

- A negative margin (-1%) on the header helped to push it out to the top and edges of the window. <br>

- Specify line height to control spcing between text: <br>
**line-height: 200%**
<br>

-  Adding box-shadow property can really help beautify your website. Don't forget to at least one box-shadow id selector or class selector to a group of elements. <br>
***box-shadow: 0 10px 20px rgba(500,0,0,0.5), 0 6px 6px rgba(0,0,0,0.23);*** <br>

- ***On CSS GRID :***  To achieve that dynamic response when you shrink the elements in your cells, enusre that the heights and widths of the elements are set to 100% (i.e. aligning with the grid cells, so that as the cells move when the grid shrinks, the contents maintain same behaviour. This is very neccessary, esppecially if you have images in your cells). This is not completely true. The best way to achieve such responsive behaviour is to use ***media queries*** for your *images*, *width* and *heights* where necessary. Always ensure you preview your work across different devices, using *chrome developer tools* <br>

-  Combine ***media queries*** with your ***flexbox*** and or ***CSS grid*** to achieve your RESPONSIVE behaviour and POSITIONING. 
<br>

- Most responsive framework (e.g Bootstrap) uses the 12-column grid responsive layout. 12 is used because it has several factors (1,2,3,4,6 & 12). Which means we could subdivide our page into sections that are evenly split and nicely layout themselves.

