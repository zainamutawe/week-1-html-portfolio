## Day 08 - Flexbox

### What I Learned

* Flexbox is used to arrange elements in a flexible layout.
* The display: flex property enables Flexbox.
* justify-content controls the horizontal alignment of flex items.
* align-items controls the alignment of flex items.
* gap adds space between flex items.
* flex-wrap: wrap allows items to move to a new row when there is not enough space.

### What I Practiced

* Created a navigation bar using Flexbox.
* Arranged the navigation links in a centered row.
* Created a responsive card row using Flexbox.
* Used flex-wrap to allow cards to move to a new row when the available space becomes smaller.
* Used spacing between the cards with the gap property.

# Result :

Successfully created a Flexbox navigation bar and a responsive row of three course cards.

# Testing :

## Test Case 1 - Large Screen

* Action: Opened the Flexbox page in Chrome using a large browser window.
* Expected Result: The three cards should appear next to each other in one row.
* Actual Result: All three cards appeared in one row.
* Status: Passed

## Test Case 2 - Smaller Screen

* Action: Reduced the browser window width.
* Expected Result: Cards should wrap into new rows when there is not enough space.
* Actual Result: Two cards remained in the first row, and the third card moved to the next row.
* Status: Passed