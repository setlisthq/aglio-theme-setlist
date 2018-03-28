# Aglio Setlist Theme

[![NPM version](http://img.shields.io/npm/v/aglio-theme-setlist.svg)](https://www.npmjs.org/package/aglio-theme-setlist) [![License](http://img.shields.io/npm/l/aglio-theme-setlist.svg)](https://www.npmjs.org/package/aglio-theme-setlist)

This is the Setlist theme engine for [Aglio](https://github.com/danielgtaylor/aglio). It is based off of the style of Apiary docs and forked from the default Aglio theme, Olio.

Example use:

```bash
$ npm install aglio-theme-setlist
$ aglio -i blueprint.apib -t setlist -o MyAPI.html
```

## Theme Options

The theme comes with a handful of configurable theme options. These are set via the `--theme-XXX` parameter, where `XXX` is one of the following:

Name           | Description
-------------- | ------------------
`condense-nav` | Whether to condense nagivation for resources with only a single action (default is `true`).
`full-width`   | Whether to use the full page width or a responsive layout (default is responsive).
`style`        | LESS or CSS to control the layout and style of the document using the variables from below. Can be a path to your own file or one of the following presets: `default`. May be an array of paths and/or presets.
`template`     | Jade template to render HTML. Can be a path to your own file or one of the following presets: `default`.
`variables`    | LESS variables that control theme colors, fonts, and spacing. Can be a path to your own file or one of the following presets: `default`, `flatly`, `slate`, `cyborg`. May be an array of paths and/or presets.

**Note**: When using this theme programmatically, these options are cased like you would expect in Javascript: `--theme-full-width` becomes `options.themeFullWidth`.

License
=======
Copyright &copy; 2016 Daniel G. Taylor

http://dgt.mit-license.org/
