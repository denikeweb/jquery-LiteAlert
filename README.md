# jquery.LiteAlert
jQuery plugin LiteAlert for beautiful alerts. Demo: [http://lux-blog.org/storage/jquery-LiteAlert/] (http://lux-blog.org/storage/jquery-LiteAlert/)

![Alt text](screenshow.png "Plugin in work")


## Installation

Include script *after* the jQuery library (unless you are packaging scripts somehow else):

```html
<script src="/js/jquery.litealert.js"></script>
```

And inlude css-file or copy styles to your css-file.

```html
<link href="/css/style.css" rel="stylesheet" type="text/css">
```

## Usage

Syntax:

```javascript
$.la('New alert', 'This is alert text');
```
or
```javascript
$.LiteAlert('New alert', 'This is alert text');
```


## Configuration

You can set your own class for elements (don't forget change it at styles).

```javascript
			$.laConfig ({
				classes : {
					box: 'lite-alert-box',
					// alerts container
					item: 'lite-alert-item',
					// class for alert item
					close: 'lite-alert-item-close',
					// close icon
					header: 'lite-alert-item-header',
					// header information
					content: 'lite-alert-item-content',
					// message
					footer: 'lite-alert-item-footer'
					// footer information
				},
				speed: 200
				// animation speed
			});
```

## Authors

[Denis Dragomirik](https://github.com/denikeweb)
