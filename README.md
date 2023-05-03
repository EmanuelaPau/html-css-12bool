<h1><strong> BOOLSTRAP </strong> </h1>
The goal of this exercise was to create a homemade framework and use it to copy a layout image. The frameworks created could also be used to make some creative layouts.
<br>
<br>
<h2><strong>Part 1: Creation of an homemade framework </strong></h2>
The framework was a simplified copy of bootstrap. A 12 colums layout, with the possibility of having also offsets and a free filling column.
The process of creation was done following the steps below:
<ul>
    <li>Was created a dedicated CSS</li>
    <li>Inside the CSS was created a row class, with display flex and a defined dimension</li>
    <li>Inside the CSS was created a col-1 class, with a defined dimension. Were created 12 col classes, from the smallest component to the biggest column that would fill all the row</li>
    <li>Were fixed some bugs that came out from flex behaviors (shrink, grow exc.).</li>
    <li>Were added 11 offset col classes (giving margin left as big as the previusly created columns) </li>
    <li>Was added a new col with width 100% </li>
</ul>

<br>
<h2><strong>Part 2: Recreation of the reference layout</strong></h2>
Were used the framework fo copy the reference image:
<br>
 <img src="https://github.com/EmanuelaPau/html-css-12bool/blob/main/screenshots/image%20(1).png?raw=true" alt="reference img" width="500"> 
<br>
The first group of rows was made simply using the col classes.
The nested part at the end of the first group was a row containing 2 col-6, containing a row with the rigth col classes.
The second group of rows was made combinating numerated cols and a free filling col.
The tird group of rows was made combinating a offset-col whit a free filling col.
<br>
<br>
<h2><strong>Part 3: First Bonus - Animated amongus</strong></h2>
The idea was to make a pixel art of the Amongus red character. <br>
 <img src="https://github.com/EmanuelaPau/html-css-12bool/blob/main/screenshots/sus-1.png?raw=true" alt="sus img" width="300">
 <img src="https://github.com/EmanuelaPau/html-css-12bool/blob/main/screenshots/sus-2.png?raw=true" alt="sus img" width="313">  
<br>
<!-- <br> -->
To achieve this goal, a layout with 12 colums was too small. We needed a new one so we created a new framework with 24 columns.
A problem was that we needed square pixels, but the colums would be empty, so we had to have a defined height. That heigth was impossible to define in pixels or in percentages, becouse the width was in percentage based from the dimensions on the screen. The solution found was to use " aspect-ratio : 1 / 1; ".
<br>
Once the framework was defined, was created a second style sheet to add font style, background colors and transitions behaviors.
<br>
In the end was added a transition with action to make the shooting animation.
<br>
<br>
<h2><strong>Part 4: Second Bonus - Minesweeper</strong></h2>
The goal was to recreate Minesweeper the old Windows game that I loved when I was a child<br>
 <img src="https://github.com/EmanuelaPau/html-css-12bool/blob/main/screenshots/minesweeping.png?raw=true" alt="minesweeping img" width="300">
 <br>
In this case we needed a smaller layout, so was created a 9 columns layout.
The structure wasn't a pixel art, but was made nesting more elements. Shadows and lights were added using two border classes, and images were added inside the colums.<br> 
The central part, were the player had to avoid the mines, and the smile square, had the same problem of the first bonus: the colums had to be squares. So a special class was created to add aspect-ratio 1/1.
<br>
Then where added some :active transitions with display:none and display: inline-block, to achieve the effect of showing the bombs or the flags when pressing the squares.
<br>
In the end was added a countdown animation, using opacity to show or hide the numbers in the right moment.
<br>
<br>
<h2><strong>Conclusions</strong></h2>
All of these projects were made using pure HTML and CSS, without ani library, external frameworks or other tools.
