Files Submitted
Page1.html
Page2.html
Page1.css
Page2.css
01ReadMe.txt

Role of each file
Page1.html contains the HTML code and JavaScript for the first page
Page2.html contains the HTML code and JavaScript for the second page
Page1.css contains CSS styling for the first page
Page2.css contains CSS styling for the second page
01ReadMe.txt contains documentation for the other files

Customization done
Page 1
buttons - The buttons  on this page have been changed to a blue color with rounded edges. 
          I've also included a hover attribute that  changes the color to white when hovering over them.
          
Page 2
.poem - is a generic class i've made to alter the text in the poem to font-style: italic
.synopsis - is a generic class i've made to alter the text in the brief summary to make the font-size 60% of the default.
            I've also included a text indentation of 45px.
            
table - The table has been set to a width of 780
        The table within the table (for the buttons) has been altered to make the columns equal thirds of the width of the table.
        The border on the second table has also been set to 0 with a center alignment.
        
body - the background has been changed to a gradient image and repeated on the y-axis

h2 - the h2 title of the page has been changed to a white color with a monospace font-family

textarea - the text area has been changed to a width of its entire cell and a height of 100px
           I've also made it resizable via the border-box attribute
           the borders have also been rounded with a box radius of 5px
           the background color has also been changed to lightblue 
           
select - the width of the drop down menu has been changed to 80% of its cell
         its padding has been changed to 12px up/down and 20px left/right
         its margins have been set to 8px up/down and 5px left/right
         its borders have been rounded with a box radius of 5px
         its background color has been changed to lightblue 
         
img - the images have been centered

p - all text within p tags have been centered

buttons - the buttons have been changed to a dark blue color
          the size of the buttons has been increased to 60% of the width of their cells
          the font-size has been changed to 14px
          the padding has been set to 5px up/down and 5px left/right
          the borders have been rounded with a border radius of 5px
          a hover attribute has been added that changes the button color to light blue and adds a dark blue border
          
          
Role of JavaScript
Page 1
simulateSubmit(frm) - the submit button triggers an alert that shows the hidden field 

Page 2
textPost - the text within the text area is shown as an alert after the text is changed
checkPost(str) - upon clicking a selection in the check list an alert will appear saying "You seem to like: " + the string entered
genrePost(genre) - upon clicking a selection among the radio buttons, a short description of the genre will appear via an alert
idPost(frm) - upon changing a choice on the drop down list, two successive alerts will appear displaying the value and text of the                   choice
simulateSubmit(frm) - the submit button triggers an alert that shows the hidden field
          