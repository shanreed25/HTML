# HTML Attributes
- special modifiers added to HTML elements to provide additional information or control their behavior and appearance
- offer details about the element that are not part of its content
- can alter how an element functions or how it is displayed
    - Example: width and height attributes of an <img> tag control the image's dimensions
- always placed within the opening tag of an HTML element and consist of a name-value pair, separated by an equals sign, with the value 
- the value is typically enclosed in quotation marks, it is strongly recommended to always quote attribute values in HTML, even when not strictly required
- can have as many atrributes as you want separated by a space
- `<a attribute="value" attribute=value></a>`

### Element-Specific Attributes
-  attributes are specific to certain HTML elements and define their particular properties or behaviors
- such as `href` for anchor tags or `src` for image, script and audio tags
# Global attributes
- every HTML element has access to global attributes
- Examples:
    - **id**: provides a unique identifier for an element, often used for targeting with CSS or JavaScript
    - **class**: assigns one or more class names to an element, primarily for styling with CSS
    - **style**: allows for inline CSS styling directly on the element
    - **title**: provides extra information about an element, often displayed as a tooltip on hover
    - **draggable**: allos you to set it to true or false to specify if the element may or may not be dragged
    - **lang**: specifies the language of the element's content
    - **tabindex**: controls the order in which elements receive focus when navigating with the keyboard
    - **data-***: used to store custom data private to the page or application