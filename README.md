<h3>Source: Handy-Abovergleich</h3>

<h2>New MacBook Pro Touch</h2>

##Demo 
####https://devforlive.github.io/MacBookPro-Touch/

jQuery.HSlider
==============

A Full-Page Scrolling, Touch-Friendly jQuery Slider

* Create an Full-Page Scrolling web slider has never been so easy
* All animations are powered by CSS3 with GPU acceleration
* Page Index now powered by URL hash for URL Sharing
* For mobile or modern desktop browser

##Document
==============
#### Get Started
==============

import styles and scripts

```html
<link rel="stylesheet" type="text/css" href="style/reset.css">  	<!--recommended-->
<link rel="stylesheet" type="text/css" href="style/hslider.css">  	  <!--essential-->
<link rel="stylesheet" type="text/css" href="style/default-style.css"> <!--optional-->
<script type="text/javascript" src="jquery-2.0.3.min.js"></script>
<script type="text/javascript" src="jquery.HSlider.min.js"></script>
```

HTML Structure:
```html
<div class="wrap">
	<div class="slider">
		<section>
			<article>
				<h1> Title </h1>
			<article>
			<img src="yourimage.jpg">
		</section>
		<section>
			<!-- same -->
		</section>
	</div>
</div>
```

Init HSlider!
```javascript
// deathly simple!
$(".slider").HSlider();		
```

#### HSlider Options

use options:

```javascript
$(".slider").HSlider({
	easing: "ease-in-out",
	animationTime: 400,
	pagination: false
});
```

##### `easing {String}`

- The easing function used in page transition. Default value is `ease`

##### `animationTime {Number}`

- The duration used for page transition. Default value is `1300`

##### `pagination {Boolean}`

- Auto generate pagination or not. Default value is `true`

====================================================================================
Rights: Ⓒ https://opensource.org/licenses/mit-license.php

If you interested study < code >, Try this resources for free:

Ⓒ https://www.codeschool.com, Ⓒ http://poiemaweb.com, Ⓒ https://www.sololearn.com

This repo`s is a self-part of big Workshop Ⓒ BeetRoot Academy: https://beetroot.se