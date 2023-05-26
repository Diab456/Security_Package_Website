# Security_Package_Website

# HTML:

HTML (Hypertext Markup Language) is used to structure the content and define the elements of the webpage.
The HTML code defines the structure of the webpage, including the head and body sections.
The head section contains metadata such as character encoding, viewport settings, and the title of the webpage.
The body section contains the visible content of the webpage, including the header, main content, and script tags.
The header section includes an h1 heading with the text "Algorithm Cipher".
The main section contains various input elements, such as text inputs and a select dropdown, for user input.
It also includes buttons for encryption and decryption, a container for displaying the result, and a script tag to include the JavaScript file.

# JavaScript:

JavaScript is a programming language used to add interactivity and functionality to webpages.
The JavaScript code defines several variables that reference HTML elements using their ids.
Event listeners are added to the encrypt and decrypt buttons, so when they are clicked, the corresponding functions are executed.
The encrypt function retrieves the values entered by the user for message, key, and cipher type, and sends them to the server using the Fetch API with a POST request to the "/encrypt" endpoint.
The server is expected to respond with the encrypted message, which is then displayed in the result container on the webpage.
The decrypt function works similarly to the encrypt function but sends a POST request to the "/decrypt" endpoint.

# CSS:

CSS (Cascading Style Sheets) is used to describe the presentation and visual styling of the HTML elements.
The CSS code includes styles for different elements and classes used in the HTML file.
It sets the background color, font styles, padding, and margins for the body element.
The header styles define padding, text alignment, and color for the header section.
Styles for input containers, labels, text inputs, select dropdowns, buttons, and result containers are also defined.
There is a media query that applies specific styles when the screen width is less than or equal to 600px, adjusting the font size and input size for responsive design.
Overall, the code represents a webpage that allows users to enter a message, key, and cipher type and perform encryption or decryption operations. The result is displayed on the webpage using JavaScript to handle user input and communicate with the server, and CSS to style the elements and make the webpage visually appealing.
