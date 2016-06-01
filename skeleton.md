What happens to the layout when you resize the screen to less than 550 px. How do you think that works?

When you resize the screen, as soon as you hit 550px the elements of the page take up 100 percent of the width and the grid does from 12 columns at 550px or higher to just 1 column.
This is achieved via media queries in css which recognise the size of the screen and respong accordingly. 