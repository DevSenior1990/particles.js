## particles.js

### A lightweight JavaScript library for creating particles.

Load particles.js and config the particles :

**index.html**
```html
<div id="particles-js"></div>
```

**app.js**
```javascript
particlesJS('particles-js', {
	canvas: {
		color_hex_bg: '#15414e',
		opacity: 1
	},
	particles: {
	    color_hex: '#fff',
		opacity: 1,
		size: 2.5,
		nb: 200,
		anim: {
			speed: 2
		}
	},
	/* Retina Display Support */
	retina_detect: true
});
```
<img src="http://cl.ly/XPlB/particles-2.gif">
