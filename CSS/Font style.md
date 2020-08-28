# Font style

## Pre installed fonts:
Every operating system has pre-installed fonts.

https://www.cssfontstack.com/

---
### **Font family:**
In CSS, there are two types of font family names:

* generic family: e.g. "Serif" or "Monospace".
* font family: e.g. "Times New Roman" or "Arial".

**Note**: If the name of a font family is more than one word, it must be in quotation marks, like: "Times New Roman".

Generic family | Description
---------|---------
 Sans-serif | Without feets
 Serif | With feets
 monospace | Characters with equal widths
#### **Code example**
```css
h1 {
    font-family: "Times New Roman", serif;
}

p {
    font-family: Arial, Helvetica, sans-serif;
}
```
---
### **Font size:**
The font-size property sets the size of the text.

Three values to choose from:
* px
* em
* %
```css
p {
    font-size: 18px;
}
```
---
### **Font weight**

weight | boldness
---------|---------
 100 | 
 200 | 
 300 | lighter
 400 | normal
 500 | 
 600 | 
 700 | bold
 800 | 
 900 | 
```css
p {
    font-weight: 400;
}
```
---
### **Line height**
Sets the line height:
```css
p {
    line-height: 1.7;
}
```
---
### **Letter spacing**
Sets the space between each letter:
```css
p {
    letter-spacing: 1px;
}
```
---
### **Text alignment**
The text-align property specifies the horizontal alignment of text in an element.

`text-align: left|right|center|justify|initial|inherit;`
```css
p {
    text-align: center;
}
```
---
### **Text decoration**
The text-decoration property specifies the decoration added to text
```css
p {
    text-decoration: underline;
}
```
---
## Google fonts:
https://fonts.google.com/

Chose a font and a style, then chose embed and @import.

Insert the embedded code inside your CSS file e.g. :

```css
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;700&display=swap');
```