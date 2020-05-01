# bullframe.css

_bullframe.css_ is a (S)CSS framework to be used as an alternative to CSS resets.<br> 
It's a solid starting-point for a **IE8+**, progressive, mobile-first responsive web design.<br>
Write semantic HTML, drop the styles you need, add some polyfills if needed, and you are ready to go everywhere!

## Best features

- Add responsiveness as normalize as much as possible HTML elements <i>out-of-the-box</i><br>
- Support IE8+ and a wide range of desktop and mobile browsers<br>
- Mobile-First Responsive Web Design ready<br>
- Progressive Enhancement development ready<br>
- Flexible images and media elements (video, audio, iframe, embed) by default<br>
- Flexible, cross-browser HTML5 form elements by default<br>
- Simple 12-columns fluid grid system IE8+<br>
- Choose utility classes (e.g. '.h1', '.clearfix') or not (classless)<br>
- Dark mode included<br>
- Lightweight: just 10KB~ minified/gzipped (Bootstrap is 10 times more)<br>

## How to use it

Include it via CDN in the `<head>`

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/marcop135/bullframe.css/bullframe.min.css">
```

Or include some polyfills via JSDelivr CDN for a wide cross-browser support:

### IE11+ (minimal setup)

```html
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/marcop135/bullframe.css/bullframe.min.css">
</head>
<body>
  <h1>Hello World!</h1>
</body>
</html>
```

### IE8+ (minimal setup)

```html
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/marcop135/bullframe.css/bullframe.min.css">

<!-- enable HTML5 elements, CSS3 media queries, and fix IE10 viewport on Windows 8 -->
<script src="https://cdn.jsdelivr.net/combine/npm/html5shiv@3.7.3,npm/html5shiv@3.7.3/dist/html5shiv-printshiv.min.js,npm/respond.js@1.4.2/src/matchmedia.polyfill.min.js,npm/respond.js@1.4.2/src/matchmedia.addListener.min.js,npm/respond.js@1.4.2/src/respond.min.js,npm/ie10-viewport-bug-workaround.js@1.0.0"></script>
</head>
<body>
  <h1>Hello World!</h1>
</body>
</html>
```

### IE8+ (verbose version)

```html
<!DOCTYPE html>
<html lang="en-US">
<head>
<meta charset="utf-8" />
<meta http-equiv="X-UA-Compatible" content="IE=edge" />
<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no" />
<link type="text/css" rel="stylesheet" href="https://cdn.jsdelivr.net/gh/marcop135/bullframe.css/bullframe.min.css"
integrity="sha384-xL9PVrDQt5lFLFaPOMR1xJKpBz83hP1cjuND8oIMxl3kIM6yFyp7xzRChkB5ugUN" crossorigin="anonymous">

<!-- enable HTML5 elements, CSS3 media queries, and fix IE10 viewport on Windows 8 -->
<script type="text/javascript" src="https://cdn.jsdelivr.net/combine/npm/html5shiv@3.7.3,npm/html5shiv@3.7.3/dist/html5shiv-printshiv.min.js,npm/respond.js@1.4.2/src/matchmedia.polyfill.min.js,npm/respond.js@1.4.2/src/matchmedia.addListener.min.js,npm/respond.js@1.4.2/src/respond.min.js,npm/ie10-viewport-bug-workaround.js@1.0.0" integrity="sha384-gREdttsFCQA+/jAI4yYFCtTs3d2gbjqhjAyUdoQprlF40Ig05yfwvRpZuM9yO5O6" crossorigin="anonymous"></script>
</head>
<body>
  <h1>Hello World!</h1>
</body>
</html>
```

### IE11+ (verbose version)

```html
<!DOCTYPE html>
<html lang="en-US">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/marcop135/bullframe.css/bullframe.min.css" integrity="sha384-xL9PVrDQt5lFLFaPOMR1xJKpBz83hP1cjuND8oIMxl3kIM6yFyp7xzRChkB5ugUN"  crossorigin="anonymous">
</head>
<body>
  <h1>Hello World!</h1>
</body>
</html>

```



## Classless

```html
<link type="text/css" rel="stylesheet" href="https://cdn.jsdelivr.net/gh/marcop135/bullframe.css/bullframe-classless.min.css">
```

Drop the main CSS file in your webpage, and the job is done!
Just semantic HTML and you get nice styles and cross-browser normalization.<br>
More info [on this CSS-tricks article](https://css-tricks.com/no-class-css-frameworks/).

## Dark mode

This enables a dark-mode style in all browsers:

```html
<link type="text/css" rel="stylesheet" href="https://cdn.jsdelivr.net/gh/marcop135/bullframe.css/bullframe-darkmode.min.css">
```

And this, enables a dark mode only if the user prefers it, in browsers that support the <code>prefers-color-scheme</code> media query.<br>
Read more [on MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-color-scheme).

```html
<link type="text/css" rel="stylesheet" href="https://cdn.jsdelivr.net/gh/marcop135/bullframe.css/bullframe-darkmode-prefers.min.css">
```


## Browser support

Tested and compatible in:

Desktop browsers

- IE 8+
- Latest Stable: Firefox, Chrome, Safari, Opera
 
Mobile browsers

- Latest Stable: Firefox, Chrome and Opera
- Android browser v5+
- IE Mobile 9-10
- Mobile Safari iOS 4+
- Opera Mini (no responsive-table support barrow.io/overflow-scrolling)

## Tested on real browsers

This project is tested in a wide range of browsers using [BrowserStack](http://browserstack.com/) live, thanks to the BrowserStack Open Source initiative.

![BrowserStack Logo](./docs/img/browserstack-logo.png)

## Contributors

[@englishextra](https://github.com/englishextra) the project is still live thanks to you!

## Become a sponsor

[Sponsor me](https://github.com/sponsors/marcop135) and support my front-end efforts and open source!

## Acknowledgements

bullframe.css incorporates some of the styles found on:

- Normalize.css - [https://github.com/necolas/normalize.css](https://github.com/necolas/normalize.css)
- Bootstrap - [https://github.com/twbs/bootstrap](https://github.com/twbs/bootstrap)
- HTML5 Boilerplate - [https://github.com/h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate)
- 320 and up - [https://github.com/malarkey/320andup](https://github.com/malarkey/320andup)
- Formalize - [https://github.com/nathansmith/formalize](https://github.com/nathansmith/formalize)
- Inuit CSS - [https://github.com/csswizardry/inuit.css](https://github.com/csswizardry/inuit.css)
- YUI3 CSS Grids - [http://yuilibrary.com/yui/docs/cssgrids/](http://yuilibrary.com/yui/docs/cssgrids/)

## License

The MIT License (MIT) - [http://opensource.org/licenses/MIT](http://opensource.org/licenses/MIT "The MIT License")
