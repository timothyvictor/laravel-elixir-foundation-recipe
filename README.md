# laravel-elixir-foundation-recipe
An Elixir recipe for Foundation Framework. Be sure you've followed the instructions in the Laravel documentation to get started with Elixir.

## How to use

First, you'll need to install Foundation, using Bower, to the `resources/assets` folder. After you've done that...

* Download or clone this repository and copy the contents of `gulpfile.js` into your Laravel project's `gulpfile.js`
* Run `gulp` from the terminal
* Add the `app.scss` file from this repository into the `resources/assets/sass` folder in Laravel
* Add the `app.js` file from this repository into the `resources/assets/js` folder in Laravel
* Run `gulp` from the terminal, one more time

That should do it!

You can use app.scss file to choose which of the CSS components to import into your project and you can use gulpfile.js to chose which of the JS components to import into your project.
