# HTML Forms
The HTML `<form>` element is used to create an HTML form for user input:

---
## The Action Attribute
The action attribute defines the action to be performed when the form is submitted.

### example:
When the form is submitted go to the index.html site
```html
 <form action="index.html">
```
---
## The Target Attribute
The target attribute specifies where to display the response that is received after submitting the form.


Value | Description
---------|----------
_blank | The response is displayed in a new window or tab 
_self | The response is displayed in the same frame

```html
<form action="https://www.jacobkrag.com/" method="get" target="_blank">
```
---
## The Method Attribute
The method attribute specifies the HTTP method to use used when submitting the form data.

The default HTTP method when submitting form data is GET. 
### Get
```html
 <form action="/login" method="get"> 
```
### Post
```html
 <form action="/login" method="post"> 
```
---
## Form elements
The HTML `<form>` element can contain one or more of the following form elements:
```html
<input>
<label>
<select>
<textarea>
<button>
<fieldset>
<legend>
<datalist>
<output>
<option>
<optgroup>
```
---

## Input
These are some of the common input types:
```html
<input type="button">
<input type="checkbox">
<input type="color">
<input type="date">
<input type="email">
<input type="file">
<input type="image">
<input type="password">
<input type="radio">
<input type="reset">
<input type="search">
<input type="submit">
<input type="tel">
<input type="text">
```