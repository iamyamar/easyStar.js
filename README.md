
## :exclamation::exclamation::exclamation: This is README for makestar :exclamation::exclamation::exclamation:



## ⚙ Installation
### CDN
Add styles in `<head>`:

```html
 <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.0/css/all.min.css" integrity="sha512-10/jx2EXwxxWqCLX/hHth/vu2KY3jCF70dCQB8TSgNjbCVAC/8vai53GfMDrO2Emgwccf2pJqxct9ehpzG+MTw==" crossorigin="anonymous"  referrerpolicy="no-referrer"/>```

Add makestar as CDN and initialize it

```html
<script src="https://cdn.jsdelivr.net/npm/makestar@1.1.6/src/index.min.js"></script>
<script>makescript()</script>```

 
### Package

Install `makestar` package:

Add styles in `<head>`:

```html
 <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.0/css/all.min.css" integrity="sha512-10/jx2EXwxxWqCLX/hHth/vu2KY3jCF70dCQB8TSgNjbCVAC/8vai53GfMDrO2Emgwccf2pJqxct9ehpzG+MTw==" crossorigin="anonymous"  referrerpolicy="no-referrer"/>```

Import makestar as module and initialize it:
```js
  import makestar from "makestar"
  makestar()
```
- `yarn add makestar`
- or `npm install makestar`

Import script, styles and initialize AOS:

```js
import makestar from "makestar"
makestar()
```

In order to make it work you'll have to make sure your build process has configured styles loader, and bundles it all correctly.
If you're using [Parcel](https://parceljs.org/) however, it will work out of the box as provided.

---
## 🤔 How to use it?

### 1. Initialize makestar:

```js
makestar()

```

### 2. Set class to star:
Use an empty `div` or `span` tag and give a class star to it 

```html
<div class="star"></div>
```

And adjust behaviour using different Attributes :-

##### - To make Static Rating 
```html
<div class="star" star-rating="2"></div>
```
It will print 2 Star Rating out of 5 Star.
##### - To make Static Rating with Dynamic Stars 
```html
<div class="star" star-rating="3" set-default="8"></div>
```
It will print 3 Star Rating out of 8 Star.
##### - To take Rating Input 
```html
<div class="star" take="input"></div>
```
It will create 5 Star and take Rating when user click on any Star out of 1-5 .
##### - To take Rating Input from Dynamic Stars 
```html
<div class="star" take="input" set-default="8"></div>
```
It will create 8 Star and take Rating when user click on any Star out of 1-8 .

---
🛑May Contains Bugs and Error 

###### Follow Me at [Twitter](https://twitter.com/yashkumarspeak)
