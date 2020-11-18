# Main Idea

Create a live preview of the CardConnect iFrame tokenizer with a text field for CSS properties. The text field will properly URL encode the value and dynamically change the css value of the iFrame src field.


# To do

- Add a drop down or entry field for the site
- Add a url output and copy button
- 

# Issues

- The iFrame is refreshed everytime a new key is entered. This is essentially hitting that URL everytime a key is pressed. Create button that will refresh or maybe create a delay?

# Dev ideas

Use JQuery to set the src value of the iframe

$(iframe).attr("src", Callback function to appending URL and the CSS)

uri encode the css values from the editor text area
