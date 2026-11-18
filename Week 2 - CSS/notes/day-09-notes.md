### Day 09 - CSS Grid

## What I Learned

* CSS Grid is used to create layouts with rows and columns.
* The display: grid property enables CSS Grid.
* The grid-template-columns property defines the columns in a grid.
* The gap property adds spacing between grid items.
* repeat() helps define repeated columns.
* auto-fit and minmax() help create responsive grid layouts.

## What I Practiced

* Created an image gallery using HTML.
* Added six nature images to the gallery.
* Used CSS Grid to arrange the images in columns and rows.
* Used gap to add spacing between images.
* Used auto-fit and minmax() to adjust the number of columns based on the available screen width.

# Result :

Successfully created a responsive image gallery using CSS Grid.

# Testing :

### Test Case 1 - Wide Screen

* Action: Opened the gallery in Chrome with a wide browser window.
* Expected Result: Images should appear in multiple columns.
* Actual Result: Images appeared in multiple columns.
* Status: Passed

### Test Case 2 - Narrower Screen

* Action: Reduced the browser window width.
* Expected Result: The number of columns should adjust to the available width.
* Actual Result: The gallery changed to two columns, and the images moved into new rows.
* Status: Passed