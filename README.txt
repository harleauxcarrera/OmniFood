BLOGPOST PROJECT

  Use the box-sizing-border-box CSS property to make width and heigth define the
  entire CSS box model (to avoid annoyance.)

  Block elements use the full width of the browser and force line breaks
  inline elements do not

  Elements will have default margins set by the browser if there are none specified.
    Remove default margin values by using *{ margin: 0, padding: 0, box-sizing: border-box} to affect all elements
    on page.
    Now you can start adding margin/padding to elements to size them as needed.

  Standard width is 960px for elements but screen sizes keep getting bigger (used 1140px as example)
  Center a container div by using margin-left/right: auto

  The float property is used to push an element to the left of to the right allowing other elements
  to wrap around it.
    The clear property is used as a counter to float.
    If two elements are side by side using float: left, the next element in code will appear below the
    last div on the left. So to make it appear again on the bottom of the page, use an empty div with
    class = clearfix and css props : .clearfix:after{ content: "", display: table, clear: both}

  margin: top left bottom right (clockwise)

  Can select a particular element insisde a div by using css prop: .divClass elementTag{...}
    Can use the border-radius prop on an image to make it a circle

LECTURE 19 RELATIVE VS ABSOLUTE POSITIONING OF ELEMENTS

    Relative positioning means elements positions are determined by other elements
    absolute can be positioned any where we wantinside their parent elements
        Have to make sure that the parent element has the position: relative
        and the absolute element has prop absolute

LECTURE 21 Intro to Web Design
    Flat Design - gets rid of all shadows, gradients, bubbles making it a more 2 dimensional feel. Simple clean and modern.

LECTURE 22 Typography

LECTURE 37 Development Steps
  Create Folder structure
    Include resources folder for images and custom CSS
    Include vendors folder for downloaded CSS, Fonts and JS files
  Download normalize CSS
    Include link
  Download Lato Google Font
    Include link
  Include link to our custom CSS file
    Set all elements (*) to margin/padding  = 0 , box-sizing: border-box
      (Gets rid of all default spacing for less annoyance/more accuracy when spacing)
  Set html {} background color, text color, and font family/size/weight/text-rendering:
  to optimizeLegibility for whole file

LECTURE 38 Responsive Web Design
  Fluid Grid: all elements are set in percentage sizes and not absolute
  Flexible images: relative unit percentages
  Media Queries: Allow to specify different CSS style rules for different browser widths

  Download course resources (grid.css) and include in vendor folder

  added props to .row element in custom css file to center div with class= "row"
LECTURE 39

    Worked on header component , added image from resources
    styled header element (included the hero picture)
    set picture height to 100vh which means 100% of the view port height
    set background-size to cover to show full image
    set background-position to center
    add props to heroImage-text-box to center box
    Use linear-gradient in background image to add opaque feel in order to readability header

LECTURE 40 Building the Header part 2
