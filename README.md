# Thumbify

Product Image Thumbifier


## Quick start

###DEMO

Demo is HERE

### Install

npm will be added after version 1.0.0

### Load

```html
<link rel="stylesheet" href="thumbify.css" />
```

Put the script at the bottom of your markup right after jQuery:

```html
<script src="thumbify.js"></script>
```

### Usage

```html
<div class="product-images-container">
    <img src="image1">
    <img src="image2">
    <img src="image3">
div>
```

```js
$(document).ready(function(){

    var config = {
        width:500,
        showNagivation:true
    };

    $('.product-images-container').thumbify(config);
);
```

## License

The code and the documentation are released under the [GPL](LICENSE).