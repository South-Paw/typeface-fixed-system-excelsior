# typeface-fixed-system-excelsior

The CSS and web font files for the Fixed System Excelsior 3.0.0 typeface

## Install

`npm install --save @south-paw/typeface-fixed-system-excelsior`

or

`yarn add @south-paw/typeface-fixed-system-excelsior`

## Use

This project assumes that you're using webpack to process CSS and files.

The package includes the necessary font files (woff2, woff) and a CSS file with font-face declarations pointing at these files.

You will need to have webpack setup to load css and font files.

Many tools built with Webpack will work out of the box with this package such as [Gatsby](https://github.com/gatsbyjs/gatsby) and [Create React App](https://github.com/facebook/create-react-app).

To use, simply require the package in your project's entry file:

```js
// Load Fixed System Excelsior typeface
require("@south-paw/typeface-fixed-system-excelsior");
```

and then apply the font family via CSS:

```css
body {
  font-family: "FixedSystemExcelsior";
}
```

Note that the font is best used at `16px` or `12pt`.

For larger sizes, use increments of the size (e.g. `16px`, `32px`, `48px`, `64px`...)

## Source

I did not create this font, I only placed it in the repo and published it to NPM for use.

Fixed System Excelsior was originally created by Darien (and used to be hosted on [this website](http://www.fixedsysexcelsior.com/contact.htm))

The CSS for the Webfont is a modified version of [fanfare's](http://stackoverflow.com/a/16973177) that I found on a [Stackoverflow](http://stackoverflow.com/questions/3689426/fixedsys-terminal-fonts) topic.

Package is inspired by the [typefaces project](https://github.com/KyleAMathews/typefaces).
