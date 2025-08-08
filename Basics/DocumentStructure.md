# Document Structure
- **`<!DOCTYPE html>` declaration**: tells the browser that the code is in HTML5
    - specifies the HTML version being used and helps browsers render the page correctly
    - the latest version of HTML is HTML5
- **`<html lang=en>` element**:
    - the root element of the HTML document, containing all other elements
    - often includes a lang attribute to declare the page's language for accessibility purposes
- **`<head>` element**:
    - this section holds metadata about the page that is not directly displayed to the user
    - common elements within the `<head> </head>` include:
        - **`<meta charset="UTF-8">`**: Specifies the character encoding, ensuring proper display of various characters and symbols
        - **`<meta name="viewport" content="width=device-width, initial-scale=1.0">`**
            - defines how the browser should be displayed your website when it first opens, relative to the screen that it is being rendered on
        - **`<title></title>`** element: Sets the title that appears in the browser tab or window title bar
        - **Links to external CSS files**: `<link rel="stylesheet" href="styles.css">`, for styling
        - **Links to external JavaScript files**: `<script src="script.js"></script>`, for interactivity
-**`<body></body>` element**:
    - this is where the visible content of the web page resides, including text, images, links, forms, and other structural elements


## HTML Boilerplate
- pre-written template of HTML code that serves as a starting point for any new HTML document or web project
- it includes the essential elements and structure required for a valid and functional HTML page, saving developers time and ensuring consistency across projects
- when starting out it is recommened that you type the boilerplate code out yourself, so that you become acustom with what the structure looks like

#### Benefits of using an HTML boilerplate
- **Time-saving**: provides a ready-to-use foundation, eliminating the need to write the basic structure from scratch for every new project
- **Consistency**: ensures that all new projects start with a standardized and well-structured base, promoting best practices
- **Cross-browser compatibility**: often includes elements and practices designed to ensure consistent rendering across different web browsers
- **Improved workflow**: many code editors and IDEs offer shortcuts (like Emmet in VS Code) to quickly generate a boilerplate, further streamlining the development process

## Nesting
- keeps your code tidy by using good indentation and keeping good programming paractices
# Creating a boilerplate
- In VS code there is a shortcut within a `.html` file on the first line you can type `!` and hit enter and the boilerplate will be created for you