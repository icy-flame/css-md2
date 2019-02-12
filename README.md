# CSS-MD2
![icon](https://github.com/icy-flame/css-md2/raw/master/css-md2.png)  
Material Design 2 components in a light CSS file.
## Getting Started
Download `css-md2.css` and add the following element to your HTML pages. (Change `href` as needed)  
```
<link rel="stylesheet" type="text/css" href="./css-md2.css" />
```
If you want to change the accent color, edit the line 2 of `css-md2.css` and replace `26,115,232` with the rgb value you want.
> 1 | &nbsp;html {  
2 | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;--accent-color: 26,115,232;  
3 | &nbsp;}
## Components
### HR
```
<hr>
```
### Button
There are 6 styles of buttons without ripple effect.
```
<button class="md-button-negative">Button</button>
```
```
<button class="md-button-positive">Button</button>
```
```
<button class="md-button-negative-noborder">Button</button>
```
```
<button class="md-button-positive-noborder">Button</button>
```
```
<button class="md-button-negative-round">Btn</button>
```
```
<button class="md-button-positive-round">Btn</button>
```
### Checkbox
```
<label class="md-checkbox"><input type="checkbox"><span class="md-checkmark"></span>Checkbox</label>
```
### Radio Button
```
<label class="md-checkbox"><input type="radio" name="radio"><span class="md-radiomark"></span>Radio Button</label>
```
### Textbox
```
<div style="width: 256px"><input type="text" placeholder="Textbox" class="md-textbox"><span class="md-textboxunder"></span></div>
```
### Select
```
<select class="md-select">
    <option selected>Select 1</option>
    <option>Select 2</option>
    <option>Select 3</option>
</select>
```
### Range
```
<input type="range" class="md-slider">
```
## Demo
[CSS-MD2 Demo](https://icy-flame.github.io/css-md2)
