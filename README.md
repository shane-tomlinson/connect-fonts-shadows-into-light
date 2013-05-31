# connect-fonts-shadows-into-light

Shadows Into Light fontpack for [connect-fonts](https://github.com/shane-tomlinson/connect-fonts).

## Usage

1. Include [connect-fonts](https://github.com/shane-tomlinson/connect-fonts) in a node module.
```js
const font_middleware = require("connect-fonts");
```

2. Include the font packs that you want to serve.
```js
const font_pack  = require("connect-fonts-shadows-into-light");
```

3. Add a middleware by calling the `setup` function.
```js
    app.use(font_middleware.setup({
      fonts: [ font_pack ],
      allow_origin: "https://exampledomain.com"
    }));
```

4. Add a link tag to include the font CSS.
```html
<link href="/shadows-into-light/fonts.css" type="text/css" rel="stylesheet"/ >
```


Available fonts:
* shadows-into-light

Locale-optimised font sets can be served by specifying the locale in the fonts.css URL.
```html
<link href="/latin/shadowsintolight/fonts.css" type="text/css" rel="stylesheet"/ >
```

Available subsets:
* latin

5. Set your CSS up to use the new font by using the "Shadows Into Light" font-family.
```
    body {
      font-family: 'Shadows Into Light', 'sans-serif', 'serif';
    }
```

## Font Info
Shadows Into Light

* Description: Copyright (c) 2010, Kimberly Geswein (kimberlygeswein.com)
* Copyright: Copyright (c) 2010, Kimberly Geswein (kimberlygeswein.com)
* Designer: Kimberly Geswein
* Designer URL: http://kimberlygeswein.com
* Vendor: Kimberly Geswein

## Development Info
* Homepage: https://github.com/shane-tomlinson/connect-fonts-shadows-into-light
* Repo: https://github.com/shane-tomlinson/connect-fonts-shadows-into-light

## Author
* Shane Tomlinson
* shane@shanetomlinson.com
* stomlinson@mozilla.com
* set117@yahoo.com
* https://shanetomlinson.com
* https://github.com/shane-tomlinson
* https://github.com/stomlinson
* @shane_tomlinson


## License

Software: Licenced under version 2.0 of the MPL

  https://www.mozilla.org/MPL/

Fonts: Licensed under version 1.1 of the SIL Open Font License

  http://scripts.sil.org/OFL

