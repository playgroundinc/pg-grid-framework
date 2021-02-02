# PG Grid Framework

This is a mobile-first, classname-based grid framework built on CSS Grid.

## Grid Containers

`.grid-container` - Add the class of  to any elements to turn it into a 25-column grid.
Any direct children of that element will be the grid columns.

`.grid-colums-{ $number }` - You can overwrite the number of columns that the grid can have by adding a class like `.grid-columns-16` along with the `.grid-container` class. The maximum nunmber of columns you can have is set by the `$columns` variable (25 by default). This is especially useful if you come into a scenario and you want to nest a grid inside another.

## Grid Columns

All direct children of a `.grid-container` element automatically become grid columns.

`.grid-column-start-{ $number }` - Determines which grid line an element starts on. You can also target specific breakpoints with this class like `.grid-lg-column-start-2` or `.grid-xl-column-start-2`.

`.grid-column-end-{ $number }` - Determines which grid line an element ends on. You can also target specific breakpoints with this class like `.grid-lg-column-end-20` or `.grid-xl-column-end-20`.

`.grid-column-span-{ $number }` - Determines how many grid columns an element spans. You can also target specific breakpoints with this class like `.grid-lg-column-span-5` or `.grid-xl-column-span-10`.

`.grid-column-order-{ $number }` - If you would like to change the order of your columns, we've got some utility classes for you! You can also target specific breakpoints with this class like `.grid-lg-column-order-5` or `.grid-xl-column-order-1`. Also available are `.grid-column-order-first` which will set the order property to `-1` and `.grid-column-order-last` which will set the order to the grid column number, plus 1 (default is 26).


## FAQs

### I don't want 25 columns, how can I customize this?

Clone or fork this repo, and customize the variables in `/sass/grid.scss`.

### How do I compile my changes?

BYOC (Bring you own compiler).
The purpose of this repo was to generate the `.css` file for us to easily add to our projects.
If you want to customize the grid settings, or work with the sass file, feel free to pull these files into your own project and compile them how you please. 

### Why SASS? Why not LESS, Stylus, or just plain CSS?

Plain ol' CSS can do a lot of things now - but it still can't do loops, which are utilized to reduce a lot of repetition in generating the grid classnames.
We used the `.scss` SASS syntax rather than the others because it's a syntax our team uses regularly.

### I have a problem. 

This framework was created in an afternoon, and there are likely many scenarios that can be designed that won't quite work with it. That's okay. Feel free to file an issue, or perhaps this isn't the right tool for you. 