CJSXTape (is Coffeetape)
------------------------

Run [tape](https://github.com/substack/tape) tests written in CJSX or CoffeeScript!

To install: `npm install -g cjsxtape`

The command works exactly the same as the regular `tape` runner, just do `cjsxtape test/*.coffee` to run your tests. You can pipe `cjsxtape` into any standard tap reporter as you would expect.

To write your tests, `require('tape')` and use it exactly like you would if you were writing your tests in javascript. You'll get the same API if you `require()` cjsxtape, but it's not recommended.

## Acknowledgements

This is a port of [@hlfw](https://github.com/hflw)'s [CoffeeTape](https://github.com/hflw/coffeetape).
