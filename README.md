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
> 
    ![Screenshot (41)](https://github.com/user-attachments/assets/ee231618-ee2e-4014-baba-ee6e385c1ad9)
    
    The server uses the EJS templating engine to render HTML pages. When a user requests the root URL, the index.ejs template is rendered.

> Generating Random Band Names:

    ![Screenshot (40)](https://github.com/user-attachments/assets/c9a48d11-cef7-43c4-bd6d-c7824314e082)

    The server has predefined arrays of adjectives and nouns. When a user submits the form, the server selects a random adjective and noun to create a band name.
    When the form is submitted, the server processes the POST request, generates a random band name, and re-renders the index.ejs template with the generated band name.
