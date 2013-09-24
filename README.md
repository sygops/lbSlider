lbSlider
========

jQuery scrolling slider plugin

## Usage

### HTML

 ```html
<div class="slider-wrap">
  <div id="slider">
      <ul>
          <li>
              content here...
          </li>
          <li>
              content here...
          </li>
          ...
      </ul>
  </div>
  <a href="javascript://" id="arrow-left">left</a>
  <a href="javascript://" id="arrow-right">right</a>
</div>
 ```
 
 .slider-wrap block is not necessary, but I use it to absolute position arrows. 
 Arrows shouldn't be inside #slider, because it has overflow: hidden property
 
 ### CSS

You can style arrows and content as you like.
 
 ### Javascript
 
 ```javascript
 $('#slider').lbSlider({
    leftBtn: '#arrow-left', // left control
    rightBtn: '#arrow-right', // right control
    visible: 3, // visible elements quantity
    autoPlay: true, // autoscroll flag (default: false)
    autoPlayDelay: 5 // delay of autoscroll in seconds (default: 10)
});
```

## Demo

Demo on [JSFiddle](http://jsfiddle.net/equinoxlb/qZNnk/477/ "open demo")
