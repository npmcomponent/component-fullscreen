*This repository is a mirror of the [component](http://component.io) module [component/fullscreen](http://github.com/component/fullscreen). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/component-fullscreen`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# fullscreen

  Fullscreen api

## Installation

    $ component install component/fullscreen

## Example

```js
var fullscreen = require('fullscreen');

fullscreen.on('change', function(full){
  console.log('changed to %s', full ? 'fullscreen' : 'regular');
});

setTimeout(function(){
  fullscreen();
}, 2000);
```

## Events

 - "change" (fullscreen) boolean

## API

### fullscreen([el])

  Display fullscreen document or `el`.

### fullscreen.exit()

  Exit fullscreen mode.

### fullscreen.supported

  Check if fullscreen is supported.

## License

  MIT
