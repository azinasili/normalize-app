# normalize-app
Normalize-app builds on [normalize.css](https://necolas.github.io/normalize.css/) with small
tweaks made specifically for webapps in mind. Normalize-app  offers a small
set of settings to make consistent heading typography. For more documentation
checkout the original project, [normalize.css](https://necolas.github.io/normalize.css/)

## Install
With [NPM](https://www.npmjs.com/package/normalize-app):

```bash
npm install normalize-app --save
```

With [Bower](https://bower.io/):

```bash
bower install normalize-app --save
```

Or download and include normalize-app directly:

```scss
@import '/path/to/normalize-app/normalize-app';
```

## Settings
Normalize-app does come with some settings to manage typography. However the options map
must come before importing normalize.app. Here is all the settings and default values for normalize-app:

```scss
$normalize: (
  'font-family': sans-serif,
  'normalize-headings': false,
  'headings': (
    'h1': 2em,
    'h2': 1.5em,
    'h3': 1.17em,
    'h4': 1em,
    'h5': .83em,
    'h6': .75em,
  ),
);
```

## Acknowledgements
Normalize.css is a project by [Nicolas Gallagher](https://github.com/necolas),
co-created with [Jonathan Neal](https://github.com/jonathantneal).
