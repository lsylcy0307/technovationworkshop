# technovationworkshop

Basic File Information: 

1. templates: contain all html files

2. static: contain all css files
- go down to learn what css is

3. routes.py: 
- rendering templates into a complete HTML page
- contains different URLs that the application implements

@app.route (decorator)
- when a web browser requests URLs, Flask invokes this function and pass the return value of it back to the browser as a response

ex) http://127.0.0.1:5000/about -> returns the rendered "about.html" template


4. Css
- how HTML elements are to be displayed on screen, paper, or in other media
- In this work, I stored external stylesheets in CSS files

learn more: https://www.w3schools.com/css/css_syntax.asp
