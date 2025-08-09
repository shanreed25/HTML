# Image tag: `<img />`
- used to embed images into an HTML document
- is a self-closing (or void) element, meaning it does not require a separate closing tag
- `<img src="images/my-image.png">`
- you can use differnt image types such as `.png`, `.jpeg`, and `.gif`
## Key Attributes
- **src (source)**: a required attribute that specifies the path or URL to the image file
    - path can be relative (images/my-image.png) or absolute (https://image.com/images/my-image.jpg)
- **alt (alternative text)**: a required attribute that provides a textual description of the image
    - this text is displayed if the image fails to load, and it is crucial for accessibility, as screen readers use it to describe the image to visually impaired users
- **width and height**: specify the dimensions of the image in pixels
    - not strictly required, but it is good practice to include them to prevent layout shifts and improve page loading performance
- **title**: provides a tooltip that appears when a user hovers over the image

#### [Lorem Picsum](https://picsum.photos/)
- provides placeholder images
- add your desired image size (width & height) after the URL, and you'll get a random image
- `<img src="https://picsum.photos/200/300" alt="Random Image">`