### CSS3 with Ease

Make your life a little easier and do your CSS3 animating with Ease.

I based this module on the work of [Matthew Lein and his Ceaser tool](http://matthewlein.com/ceaser/).
And of course the equations of Robert Penner. It's currently intended to work with [the Gfx jQuery plugin](http://maccman.github.com/gfx/)
and ti's setup to be AMD compliant so you can use it in your Backbone apps.

### Example usage

``` js

// After requiring the ease module and
// passing it into your View with the
// name 'Ease'

this.$el.gfx({
    translateY: '300px'
}, {
    duration: 500,
    easing: Ease.easeInExpo 
});
```