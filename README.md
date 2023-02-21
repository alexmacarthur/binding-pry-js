# binding-pry-js

Use `binding.pry` in your JavaScript. Literally just a wrapper for `debugger`. For those who've been writing a lot of Ruby and can't seem to shake the habit.

## Installation

`npm install binding-pry-js`

## Usage

Import the script in your code (or load via CDN) and call `binding.pry`. A `debugger` statement will be triggered and you, a Ruby dev, won't feel as stupid as you otherwise would.

```js
import 'binding-pry-js';

binding.pry

// or...

binding.irb
```
