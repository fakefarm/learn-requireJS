# Learning Require JS

## What
[RequireJS](http://requirejs.org/) is a JavaScript file and module loader.


## My Summary

Rather than load every js file on every page, use require to manage what gets loaded, where.

## Notes

### Getting started

require's goal is for you to load a single script line and let require load the rest of your scripts.


    <head>
      <script src="lib/require.js" data-main="app"></script>
    </head>

The `data-main='app'` is specifying which file is the primary file to auto load.

### Requre Methods


    define

    require

    config



### JQuery is a special case.

I tried (unsuccessfully) to use jquery in [this comment](https://github.com/woodall/learn-requireJS/commit/92da1712079ccb0d8c0c52aed837f2dcf269bc18) and learned how it's a special :snowflake:. Thankfully, [@eomuraliev](https://github.com/eomuraliev) helped me with some comments there.

## TODO

- create a widget to load on about, but not on index page
- create a widget to load on index, but not on about

### Done
- [load jquery on index, but not on about](https://github.com/woodall/learn-requireJS/commit/996f0ef34a9d706ac1471e4b9bac7031de8fde0d)
