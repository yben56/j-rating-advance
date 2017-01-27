J-Rating-Advance jquery Plugin
==============================

##Demo
https://yben56.github.io/j-rating-advance/

##Dependencies
jquery-3.1.1 & Bootstrap v3.3.6

##Usage

```html
//html
<link href="src/j-rating-advance/j-rating-advance.css" type="text/css" rel="stylesheet" />
<script src="src/j-rating-advance/j-rating-advance.js"></script>

Create a div, add an id and place inside of form. <form><div id="rating"></div></form>
```
```javascript
//javascript
$("#rating").jRatingAdvance();

You can change default stars, size, buttons's color, active's color and display text
 $("#rating").jRatingAdvance({
		size: "18px",
		buttons_color: "purple",
		active_color: "red",
		text: true,
		rating: 3.5 //for edit purpose
	});
	
//If you wish to use this inside of user's edit page, simple pass {rating: 'user's rating value'} into it
```

```php
//backend(php)
(backend will receive a radio button post or get)
$_POST['j-rating']
```
##License
This work is licensed under a [MIT License](http://opensource.org/licenses/MIT).

##Author
This Javascript plugin was written by Benjamin Wong benjamin-w@hotmail.com
