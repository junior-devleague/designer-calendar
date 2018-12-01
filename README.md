# designer-calendar

Create a stylish calendar for the month.

![Example](https://github.com/junior-devleague/designer-calendar/blob/master/example.png)

## Objective

Use **CSS Flexbox** and more to create a stylish calendar.

## Prerequisites

To complete this project, students should have the following:
* Intermediate understanding of HTML elements (divs, images, attributes, structure...etc.)
* Intermediate understanding of CSS (Flexbox, margin, padding...etc.)

## Your Challenge

### Part I

To complete Part I, fulfill the following requirements:

1. Set up your file structure through the command line:
 * index.html
 * styles.css
 * app.js
2. Link your CSS file to your index.html file.

### Part II HTML

To complete Part II, fulfill the following requirements:
1. Create your HTML elements with this nested structure as follows:

* ```div``` with id of "container"
  * ```div``` with id of "section1"
    * ```div``` with id of "year" and text of 2018
    * ```div``` with id of "title-container"
      * ```h1``` with text of "DEC" (short for December)
  * ```div``` with id of "section2"
    * ```div``` with id of "top-title"
      * ```h3``` with text of "DECEMBER 2018"
    * ```div``` with id of "calendar"
      * ```div``` with id of "weeks" and class of "row"
        * ```p``` with text of "S"
        * ```p``` with text of "M"
        * ```p``` with text of "T"
        * ```p``` with text of "W"
        * ```p``` with text of "T"
        * ```p``` with text of "F"
        * ```p``` with text of "S"

      * ```div``` with class of "row"
        * ```p``` with class of "oth-mo" (short for other month) and text of "25"
        * ```p``` with class of "oth-mo" and text of "26"
        * ```p``` with class of "oth-mo" and text of "27"
        * ```p``` with class of "oth-mo" and text of "28"
        * ```p``` with class of "oth-mo" and text of "29"
        * ```p``` with class of "oth-mo" and text of "30"
        * ```p``` with text of "1"

      * ```div``` with class of "row"
        * ```p``` with text of "2"
        * ```p``` with text of "3"
        * ```p``` with text of "4"
        * ```p``` with text of "5"
        * ```p``` with text of "6"
        * ```p``` with text of "7"
        * ```p``` with text of "8"


      * ```div``` with class of "row"
        * ```p``` with text of "9"
        * ```p``` with text of "10"
        * ```p``` with text of "11"
        * ```p``` with text of "12"
        * ```p``` with text of "13"
        * ```p``` with text of "14"
        * ```p``` with text of "15"

      * ```div``` with class of "row"
        * ```p``` with text of "16"
        * ```p``` with text of "17"
        * ```p``` with text of "18"
        * ```p``` with text of "19"
        * ```p``` with text of "20"
        * ```p``` with text of "21"
        * ```p``` with text of "22"

      * ```div``` with class of "row"
        * ```p``` with text of "23"
        * ```p``` with text of "24"
        * ```p``` with text of "25"
        * ```p``` with text of "26"
        * ```p``` with text of "27"
        * ```p``` with text of "28"
        * ```p``` with text of "29"

### Part III CSS

To complete Part III, fulfill the following requirements:

Go to Google fonts and add the ```Lato``` and ```Oswald``` fonts to your HTML file.

1. Target the ```body``` element.
  * Set its margin to 0px
2. Target the ```id``` of "container".
  * Set the width to 100%
  * Set the height to ```calc(100vh)```
  * Activate flexbox!
  * Use flexbox to set the direction of elements to a row.
3. Target the ```id``` of "year".
  * Set the color to white
  * Set the ```font-family``` to ```'Oswald', sans-serif```
  * Set the size of the font to 30px
  * Set the background color to ```rgb(50,50,50)```
  * Set the height to 10%
  * Activate flexbox!
  * Use flexbox to center the items horizontally and vertically
  * Set the ```letter-spacing``` to 3px
4. Target the ```id``` of "section1" {
  * Set the width to 40%
  * Set the height to 100%
  * Set the background color to ```rgb(30,30,30)```
5. Target the ```h1``` element of ```#section1```
  * Set the font family to ```'Oswald', sans-serif```
  * Set the font size to 200px
  * Set the color to white
6. Target the ```h3``` element of ```#section1```
  * Set the font-family to ```'Oswald', sans-serif```
  * Set the font size to 50px
  * Set the color to white
  * Set the padding to 0px
7. Target the ```id``` of "section2"
  * Set the width to 60%
  * Set the height to 100%
8. Target the ```id``` of "title-container"
  * Set the width to 100%
  * Set the height to 80%
  * Activate flexbox!
  * Use flexbox to center items horizontally and vertically
  * Use flexbox to set the direction of items to a column
9. Target the ```id``` of "weeks"
  * Set the color to ```#3b9789```
  * Set the ```font-weight``` to bold
10. Target the ```id``` of "top-title"
  * Set the width to 100%
  * Set the height to 10%
  * Set the font-family to Oswald
  * Set the letter spacing to 2px
  * Activate flexbox!
  * Use flexbox to center items horizontally and vertically
  * Use flexbox to set the direction of items to a column
11. Target the ```id``` of "calendar"
  * Set the width to 100%
  * Set the height to 80%
  * Activate flexbox!
  * Use flexbox to center items horizontally and vertically
  * Use flexbox to set the direction of items to a column
12. Target the ```class``` of "row"
  * Set the width to 100%
  * Activate flexbox!
  * Use flexbox to set the direction of elements to a row
  * Use flexbox to evenly give horizontal space around each element
13. Target the ```p``` elements of ```.row```
  * Set the width to 50px
  * Set the height to 50px
  * Set the font family to Lato
  * Set the padding to 0px
  * Activate flexbox!
  * Use flexbox to center items horizontally and vertically
14. Target the ```class``` of "oth-mo"
  * Set the color to ```rgb(120,120,120)```

## Stretch Goals

1. Mark special days for this month by applying a class to those days and styling them in CSS!
2. Super Stretch: Use click events to add notes to a day on click.
Resources:
  * EventListeners: https://www.w3schools.com/js/js_htmldom_eventlistener.asp
  * Appending Elements: https://www.w3schools.com/jsref/met_node_appendchild.asp
  * Get User Input: https://www.w3schools.com/tags/tag_input.asp
