## Jquery

## Jquery library added

* CDN - `<script defer src="https://code.jquery.com/jquery-3.7.1.min.js"></script>`
* Or download library from [Jquery](https://jquery.com/download/)
* The library must be add in header section of the html

## Documentation

Read details API doc [API Doc](https://api.jquery.com/)

## Starter Code sample

```html

<div>hello</div>
```

```js

$(document).ready(function(){
    $('div').click(function(){
        alert('jquery has been loaded')
    })
});
```

## Some Basic Rules 

* DOM click event - `$('DOM').click(function(){});`
* DOM insert HTML - `$('DOM).html('text');`
* DOM multiple DOM inset `$('div, span, p, a').html('text');`
* Select DOM Id and return HTML - `$('#id').html('Hello World');`
* Hide DOM by a html class- `$('.class').hide();`
* Add css in child DOM - `$('#docs>p').css('color', 'red');`
* Add class to DOM element - `$('.elm').addClass('green');`
* Add class to anchor tag - `$('a[href="google.com"]').addClass('blue');`

## Jquery Deep Dive API

* Append DOM
* toggleClass
* mouseover, mouseleave
* fadeout
* animate

## Go beyond 

* Ajax
* Json