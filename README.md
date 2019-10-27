# Azad & Sons
Website for a furniture business

## Technologies Used
- HTML
- CSS
- jQuery
- Bootstrap
- SCSS
- npm

## Installing Modules
- Clone or download the project.
- Open Terminal.
- Run 'npm install' and all the modules will be downloaded.

## Modifying Styles
- All node_modules should be installed
- Don't modify css/style.css. Write CSS styles inside scss/style.scss.
- In order to compile SCSS to CSS, run `npm run watch:scss` and they will be compiled to style.css.
- Concat CSS files by running `npm run concat:css`. The styles will be applied to to style.concat.css.
- Minify style.concat.css. Copy the whole minified code and overwrite the code inside style.min.css. (I was feeling lazy and instead of writing a script, I just minified using a website :D)

## Adding or editing any JavaScript code.
- All node_modules should be installed
- There is a little custom JavaScript that uses jQuery for the navigation bar.
- If you want to add any scripts, just make a new script.js file and write all your JavaScript inside it.
- On line number 9, change the value of `"concat:js" to "concat -o js/script.concat.js js/jquery.min.js js/bootstrap.min.js js/lightbox.min.js js/lightslider.min.js script.js"`.
- After writing your custom JavaScript, run `npm run concat:js`.
- Now minify it and overwrite the minified code into script.min.js.

## Bugs / Errors

I haven't found any. If you find one, just let me know or fix that for me. Thank you.
