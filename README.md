
# index.html

![image](https://github.com/EaswaranPottiK/Assignment9-MediaQueries/assets/38095510/4de17c10-fbd0-4998-9309-3ce05648c83c)

doctype html defines that this is an html file 

html lang = en says that the language used here is english 

meta charset utf 8 is the encoding used 

meta charset name and viewport is used to ensure consistancy in view among different screen sizes 

title is the text that appear on tab in this case it is document 

link href (location) and rel (relationship - stylesheet) is used to bind this html code with stylesheet 

i have also imported poppins font from google using the 2th link 

![image](https://github.com/EaswaranPottiK/Assignment9-MediaQueries/assets/38095510/4a2a2531-d5eb-4db6-9ad6-4d56944260cb)

inside body there is div with class container where everthing is printed 

inside container there are 2 more div; one for the image and one for all the text and the button 

inside p tag i have used span tag to apply underline style to the text "Freepik"


# style.css

![image](https://github.com/EaswaranPottiK/Assignment9-MediaQueries/assets/38095510/285dfba8-d318-4bc9-9114-1167a36aa4b8)

* is the universal selector to select all elements

here i have applied margin (gap between current div and parent div) and padding (gap between element and current div) to 0 

i have made box-sizing as border box so the contents does not overflow alloted space 

using google fonts i have imported poppins font 

i have applied a background to the page (white yello)

no repeat is used so that image does not get repeated 

background size is cover to fit the entire screen 

height is 100vh so that image takes up entire screen size 

![image](https://github.com/EaswaranPottiK/Assignment9-MediaQueries/assets/38095510/eacdcbf5-dcc8-4100-9181-afbe750c78a1)

display flex is so as to use flexbox 

justify content is a spacing property so that image is aligned at the center

align item is to aling thing along on main axis; in this case along y axis 

gap is used to achieve a spacing between 2 elements 

the maxwidht of all the text is 300 pixels and text is aligned center (text begins from mid of the div)

![image](https://github.com/EaswaranPottiK/Assignment9-MediaQueries/assets/38095510/f2de01e6-54b8-4bef-9264-bb72590cc57c)

margin bottom is used to create a distance between two element

font weight is the thickness of the font (boldness)

padding is used to create gap inside button 

color is the color of text inside button 

background color the color of button 

border is set to none to remove border of rectangle (button)

![image](https://github.com/EaswaranPottiK/Assignment9-MediaQueries/assets/38095510/c959d044-bf77-4135-95a7-b7133362dc55)

media query is used to create responsive designs 

here when screen size falls below 670 pixels of width the flex direction of container becomes column so text get displayed below coffee image 














