# WaterMorphism

An advanced SVG-based water refraction and distortion effect for web interfaces.

WaterMorphism creates an animated water-like distortion using SVG filters and can be applied to elements with `backdrop-filter`.

<video src="https://jumpshare.com/embed/U8kWU66xttTVxlq5wIyA" width="600"></video>

## Usage

Add the following script to your HTML:
```html.
<script>fetch('https://raw.githubusercontent.com/FoxLangTM/WaterMorphism/main/svg.html').then(r=>r.text()).then(s=>document.body.insertAdjacentHTML('afterbegin',s))</script>
```

This loads the WaterMorphism SVG filters directly into the page DOM.
Then apply the main filter to your element:
```
backdrop-filter: url(#water-ripple);
-webkit-backdrop-filter: url(#water-ripple);
```
## Optional:
### background: rgba(255, 255, 255, 0.01);

## How it works
WaterMorphism uses animated _SVG_ filters to create:
<br> ๐ multi-scale water distortion
<br> ๐ animated refraction
<br> ๐ organic surface movement
<br> ๐ water-like edges
<br> ๐ pressure and tension effects
<br> ๐ subtle secondary distortions
<br> ๐ animated caustic and shadow effects
The SVG filters are loaded separately so the main HTML implementation stays minimal.
Filters

### The main filter is:
```url(#water-ripple)```


## Attribution
If you use WaterMorphism, please credit the original author:
"Watermorphism effect by The Lang".
Commercial use is allowed according to the included LICENSE.

## License
WaterMorphism is licensed under the WaterMorphism License 1.0.
See LICENSE for the full license terms.

### Author | The Lang
