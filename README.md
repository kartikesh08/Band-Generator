# Band-Generator
> The band generator project consists of a web server that:
 
    Serves a static HTML page.
    Accepts user input through a form submission.
    Generates a random band name by combining a random adjective and a noun.
    Displays the generated band name on the web page.
  
> Project Structure

    Express Setup: Basic server configuration.
    Static Files: Serving static content.
    Body Parsing: Handling form data.
    Routing: Managing GET and POST requests.
    Template Rendering: Displaying dynamic content using EJS templates.

> Rendering HTML Templates with EJS:

![Screenshot (41)](https://github.com/user-attachments/assets/7c44f5d4-3551-4ec3-9174-c9cba7eef607)
![Screenshot (41)](https://github.com/user-attachments/assets/3bf433a3-6bf7-4690-ad75-68a69d418ed9)

    The server uses the EJS templating engine to render HTML pages. When a user requests the root URL, the index.ejs template is rendered.

> Generating Random Band Names:

![Screenshot (40)](https://github.com/user-attachments/assets/e88799ac-3754-442b-8024-1bee55a5852c)

    The server has predefined arrays of adjectives and nouns. When a user submits the form, the server selects a random adjective and noun to create a band name.
    When the form is submitted, the server processes the POST request, generates a random band name, and re-renders the index.ejs template with the generated band name.
