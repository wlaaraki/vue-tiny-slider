# tiny-slider 2.0 for Vue

Wrapper for Tiny slider for all purposes by [ganlanyuan](https://github.com/ganlanyuan/tiny-slider) in Vue.

[![experimental](http://badges.github.io/stability-badges/dist/experimental.svg)](http://github.com/badges/stability-badges)

## Install

`npm install vue-tiny-slider`

## Use

````javascript
import VueTinySlider from 'vue-tiny-slider';

new Vue({
  components: {
    'tiny-slider': VueTinySlider
  }
})
````

````html
<tiny-slider :mouse-drag="true" :loop="false" items="2" :controls-text="['', '']" gutter="20">
    <div>Slider item #1</div>
    <div>Slider item #2</div>
    <div>Slider item #3</div>
    <div>Slider item #4</div>
    <div>Slider item #5</div>
    <div>Slider item #6</div>
</tiny-slider>
````

## Options

````
items
gutter
edge-padding
fixed-width
slide-by
controls
controls-text
controls-container
nav
nav-container
arrow-keys
speed
autoplay
autoplay-timeout
autoplay-direction
autoplay-text
autoplay-hover-pause
autoplay-button
autoplay-button-output
autoplay-reset-on-visibility
animate-in
animate-out
animate-normal
animate-delay
loop
rewind
auto-height
responsive
lazyload
touch
mouse-drag
nested
freezable
disable
on-init
````
For more detailed information about the optoins, see the [Tiny-slider documentation](https://github.com/ganlanyuan/tiny-slider#options).

## Todo
* Better handling of the responsive-settings
* Add Custom Events
* Add Methods

## Contributors
* [Morgan Eklund](https://github.com/rymdkapten)
* [Viktor Sarström](https://github.com/viktorlarsson)