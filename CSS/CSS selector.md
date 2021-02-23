# CSS selector
There are different ways of selecting an HTML element here is some of the most common ways:
## Common selection
#### **Select elements**
Selects all `<h1>` elements
```css
h1 {
    /* property : value */
}
```
#### **Select id**
Selects the element with id="dog"
```css
#dog {
    /* property : value */
}
```
#### **Select class**
Selects all elements with class="dogs"
```css
.dogs {
    /* property : value */
}
```
#### **Select all**
Selects all elements
```css
* {
    /* property : value */
}
```
---
## Advanced selection

#### **Select nested elements**
Selects all `<p>` elements inside the `<div>` elements
```css
div p {
    /* property : value */
}
```

#### **Select several elements**
Selects all the `<div>`, `<h1>` and `<p>` elements
```css
div, h1, p {
    /* property : value */
}
```

#### **Select attribute**
Selects all a elements with href="https://www.jacobkrag.dk/"
```css
a[href="https://www.jacobkrag.dk/"] {
    /* property : value */
}
```