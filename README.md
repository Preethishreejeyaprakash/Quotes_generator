## Description
This project is a simple HTML webpage that displays a "Quote of the Day" and changes the background color to a random color when a button is clicked. It also displays the current date and time when the button is clicked. The quotes are chosen randomly from a predefined list.

Files
index.html: The main HTML file containing the structure, styling, and JavaScript functionality of the webpage.
thumb.PNG: An image file used in the webpage. Ensure this image is placed in the same directory as the HTML file.
## HTML Structure
The HTML file is structured as follows:
Styles for the paragraph displaying "QUOTE OF THE DAY!!!".
body: Styles for the body, including the background color.
button: Styles for the button, including margin, padding, font size, background color, border, and border radius.
#demo: Styles for the div displaying the quote.
#date: Styles for the div displaying the date and time.
## javascript
date1(): A function that gets the current date and time and displays it in the #date div.
color(): A function that:
Generates random RGB values for the background color.
Selects a random quote from the qoute array and displays it in the #demo div.

Ensure you have the thumb.PNG image in the same directory as your index.html file.
Open the index.html file in a web browser.
Click the "CLICK ME!!!" button to see a random quote, change the background color, and display the current date and time.
Example Usage
When you open the webpage, you will see the text "QUOTE OF THE DAY!!!" centered at the top. Below it, there is a button labeled "CLICK ME!!!". When you click this button, the background color of the page will change to a random color, a random quote will be displayed, and the current date and time will be shown.

## Notes
Ensure the image file thumb.PNG is available in the same directory as the HTML file for the image to display correctly.
The quotes array can be modified to include additional quotes or updated quotes as needed.
