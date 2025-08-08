# HTML Tags
- are the fundamental building blocks of web pages, used to structure and define the content within an HTML document
- provide instructions to web browsers on how to render and display various elements, such as text, images, links, etc...

### Key Characteristics of HTML Tags
- **Enclosed in Angle Brackets `< >`**: tags are always enclosed within angle brackets 
- **Opening `< >` and Closing Tags`</>`**: most HTML tags come in pairs: an opening tag and a corresponding closing tag
    - the closing tag includes a forward slash before the tag name
    - `<p>This is a paragraph.</p>`: `<p>` is the opening tag and `</p>` is the closing tag
- **Content**: the content to be affected by the tag is placed between the opening and closing tags
- **Self-Closing Tags**: some tags, like the `<img>` tag for images or the `<br />` tag for line breaks, are self-closing and do not require a separate closing tag
- **Attributes**: tags can have attributes, which provide additional information or properties about the element
    - attributes are placed within the opening tag and consist of a name-value pair
    - `src="image.jpg"`
- **Structure and Semantics**: HTML tags are crucial for defining the structure and semantic meaning of a web page, helping browsers, search engines, and assistive technologies understand the content
    - For instance, `<h1>` signifies a main heading, while `<p>` denotes a paragraph

### Tags Vs Elements
- `<p>This is a paragraph.</p>`
    - `<p> </p>`: are the tags
    - `<p>This is a paragraph.</p>`: is the element
- **Non-Void Elements**: elements that have content in between, elements with opening and closing tags
- **Void Elements**: elements with no content, self closing tag elements such as `<hr />`(horizational rule) and the `<br />`(break element)
    - these void elements have a space between the tag name and the forward slash by convention: `<br />`
    - the forward slash is optional but, it would make it easier for you as the developer to know that it is a self closing tag, HTML5 ignores the forward slash so `<br>` is valid code also 

### Some Common Tags
- **Heading**: `<h1></h1>`: Levels: h1(largest) - h6(smallest)
    - it is not good practice to have more than 1 `<h1></h1>`
    - do not skip levels: if you have a `<h4>` tag you should have already used `<h1>`, `<h2>` and `<h3>`
        - breaking these rules will not break you code but it will make your code look less professional
    - [MDN Docs - Headings](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/Heading_Elements)
- **Paragraph**: `<p>This is a paragraph.</p>`
    - without paragraph tag the content would have no structure and you would not be able to tell where one line begin and end
- **Horizational Rule `<hr />`**: , creates a  horizontal line, signifies a change in topic, a shift in content focus, or a separation between distinct sections within a document
- **Break `<br />` or `**: break element, allow you to separate things onto different lines 
    - do not use break element to separate text, if the text can go inside another paragragg tag for example

### Placeholder Text: Lorem Ipsum
- helps us simulate content in a paragraph so we can see what a natural block of text will look like, because we dont want to spend time creating paragraphs just for testing and web design
- [Lorem Ipsum](https://www.lipsum.com/) comes from Latin classical Literature by a famous author named Cicero and is over 2000 years old
    - has been used since the 1500s, as placeholder text for the layout for newspapers
- You can get your own Lorem Ipsum text [here](https://www.lipsum.com/) 
- there are tons of ipsum text that you can get such as 
    - [Baconipsum](https://baconipsum.com/)
    - [Officeipsum](http://officeipsum.com/)
    - [Obama Ipsum](https://obamaipsum.com/)
    - [30 Awesome Lorem Ipsum Alternatives](https://www.justinmind.com/blog/awesome-lorem-ipsum-alternatives/)

