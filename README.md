[![Build Status](https://travis-ci.org/phantomesse/code-names.svg?branch=master)](https://travis-ci.org/phantomesse/code-names)

# Development
Runs on NodeJS using Socket.IO.

## Install all node modules
`npm install`

## Start up app
`node app.js`

## Editing files
Do not edit files in `public/css`. Edit the files in `sass/` since they compile to the CSS in `public/css`.

Frontend scripts are located in public/js.

# Best Practices
Use `$unit` in CSS for calculating dimensions. We use `1rem` as the base unit, so please don't mix in `px`.

Alphabetize all CSS properties.

Use single quotes in JS and CSS. Use double quotes in HTML.
