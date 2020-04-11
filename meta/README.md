<style>

h1 {
    /* offset-x | offset-y | blur-radius | color */
    box-shadow: 4px 4px 15px black;
    /* top | right | bottom | left */
    padding: 5px 0px 5px 2.5px;
}

</style>

# Meta:
source : [W3Schools.com](https://www.w3schools.com/tags/tag_meta.asp)
### **Definition**
Metadata is data (information) about data.

```<meta>``` elements are typically used to specify page description, keywords, author of the document, last modified, and other metadata.

The metadata can be used by browsers (how to display content or reload page), search engines (keywords), or other web services.

HTML5 introduced a method to let web designers take control over the viewport (the user's visible area of a web page), through the ```<meta>``` tag.

#### Setting The Viewport
A ```<meta>``` viewport element gives the browser instructions on how to control the page's dimensions and scaling.
```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```
The ```"width=device-width"``` part sets the width of the page to follow the screen-width of the device (which will vary depending on the device).

The ```"initial-scale=1.0 part"``` sets the initial zoom level when the page is first loaded by the browser.

#### Define keywords for search engines:
```html
<meta name="keywords" content="HTML, CSS, XML, XHTML, JavaScript">
```
#### Define a description of your web page:
```html
<meta name="description" content="Free Web tutorials on HTML and CSS">
```
#### Define the author of a page:
```html
<meta name="author" content="John Doe">
```
#### Refresh document every 30 seconds:
```html
<meta http-equiv="refresh" content="30">
```