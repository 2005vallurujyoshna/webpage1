1.What is the Shortcut Emmet Uses to Create Boilerplate of HTML?
The Emmet shortcut to create an HTML boilerplate is ! followed by pressing Tab or Enter. This generates a basic HTML structure with <!DOCTYPE html>, <html>, <head>, and <body> tags.

2.What is DOCTYPE in HTML?
DOCTYPE is a declaration that defines the document type and version of HTML. It tells the browser which version of HTML the document is using. In modern HTML (HTML5), it’s written as <!DOCTYPE html>. It ensures the webpage is rendered consistently across different browsers.

3.What is a Void Element and Example of Void Elements?
A void element is an HTML element that doesn't have a closing tag and cannot have any child elements. Examples of void elements are:
<img>
<br>
<hr>
<input>
<meta>
<link>

4.What is the Difference Between Elements and Attributes?
Element: An element is a part of an HTML document defined by opening and closing tags. For example, <p> is a paragraph element.
Attribute: Attributes provide additional information about elements. They are included inside the opening tag and usually consist of a name-value pair. For example, <img src="image.jpg" alt="image description"> has the src and alt attributes.

5.What are HTML Entities and Why are They Needed in HTML?
HTML entities are special codes used to represent reserved characters or symbols that are not allowed to be directly used in HTML (e.g., <, >, &). They ensure that the browser interprets them as characters instead of HTML code. For example:
&lt; represents <
&gt; represents >
&amp; represents &
They are needed to display special characters, avoid breaking the code, and ensure correct interpretation by the browser.

6.What are Meta Tags and Why are They Used?
Meta tags are used in the <head> section of an HTML document to provide metadata about the webpage. This metadata is not displayed on the page but is essential for browsers and search engines. Common meta tags include:
<meta charset="UTF-8"> for character encoding.
<meta name="description" content="Free Web tutorials"> for a page description.
<meta name="viewport" content="width=device-width, initial-scale=1.0"> for responsive design.
Meta tags are used for SEO, responsive design, and ensuring proper browser behavior.

7.What is the Best Way to Add Images in a Website?
The best way to add images in a website is by using the <img> tag with the following considerations:
Use the src attribute to specify the image URL or file path.
Use the alt attribute to provide an alternative text description for accessibility and SEO.
Optimize the image for web (use formats like JPEG, PNG, or WebP and compress the file size for faster loading).
Consider using responsive images (srcset and sizes attributes) to serve different image versions based on screen size for better performance.
