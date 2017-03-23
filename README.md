# uglify-js-temp-es2015

This is a very temporary solution to get the "harmony" version of Uglify onto npm.
The real repo is here: https://github.com/mishoo/UglifyJS2#harmony

This existsbecause we had trouble using a `git:` uri in our **package.json**, and want to use `let` without transpiling.

`let` is ready for primetime in modern browsers. [Let us [`let`](http://caniuse.com/#feat=let)

> you probably should use the [harmony branch of UglifyJS2 instead](https://github.com/mishoo/UglifyJS2#harmony).
