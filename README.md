# tachyons-grid 0.0.1

Flexbox CSS module for Tachyons

### Stats

1046 | 148 | 148
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev tachyons-grid
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/tachyons-grid
```

ssh:
```
git clone git@github.com:tachyons-css/tachyons-grid.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "tachyons-grid";
```

Then process the css using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons path/to/css-file.css > dist/t.css
```

#### Using the css

##### CDN
The easiest and most simple way to use the css is to use the cdn hosted version. Include it in the head of your html with:

```
<link rel="stylesheet" href="http://unpkg.com/tachyons-grid@0.0.1/css/tachyons-grid.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/tachyons-grid">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*

  GRID

  Media Query Extensions:
    -ns = not-small
    -m  = medium
    -l  = large

*/
.grid { display: grid; }
/*

  GRID TEMPLATE COLUMNS

  Base:
    grid-columns = grid-template-columns

  Modifiers
    1 = 1 columns
    2 = 2 columns
    3 = 3 columns
    4 = 4 columns
    5 = 5 columns
    6 = 6 columns

  Media Query Extensions:
    -ns = not-small
    -m  = medium
    -l  = large

*/
.grid-columns-1 { grid-template-columns: 1fr; }
.grid-columns-2 { grid-template-columns: 1fr 1fr; }
.grid-columns-3 { grid-template-columns: 1fr 1fr 1fr; }
.grid-columns-4 { grid-template-columns: 1fr 1fr 1fr 1fr; }
.grid-columns-5 { grid-template-columns: 1fr 1fr 1fr 1fr 1fr; }
.grid-columns-6 { grid-template-columns: 1fr 1fr 1fr 1fr 1fr 1fr; }
/*

  GRID TEMPLATE COLUMNS

  Base:
    grid-rows = grid-template-rows

  Modifiers
    1 = 1 rows
    2 = 2 rows
    3 = 3 rows
    4 = 4 rows
    5 = 5 rows
    6 = 6 rows

  Media Query Extensions:
    -ns = not-small
    -m  = medium
    -l  = large

*/
.grid-rows-1 { grid-template-rows: 1fr; }
.grid-rows-2 { grid-template-rows: 1fr 1fr; }
.grid-rows-3 { grid-template-rows: 1fr 1fr 1fr; }
.grid-rows-4 { grid-template-rows: 1fr 1fr 1fr 1fr; }
.grid-rows-5 { grid-template-rows: 1fr 1fr 1fr 1fr 1fr; }
.grid-rows-6 { grid-template-rows: 1fr 1fr 1fr 1fr 1fr 1fr; }
/*

  GRID COLUMN START

  Base:
    column-start = grid-column-start

  Modifiers
    1 = 1st line
    2 = 2nd line
    3 = 3rd line
    4 = 4th line
    5 = 5th line
    6 = 6th line

  Media Query Extensions:
    -ns = not-small
    -m  = medium
    -l  = large

*/
.column-start-1 { grid-column-start: 1; }
.column-start-2 { grid-column-start: 2; }
.column-start-3 { grid-column-start: 3; }
.column-start-4 { grid-column-start: 4; }
.column-start-5 { grid-column-start: 5; }
.column-start-6 { grid-column-start: 6; }
/*

  GRID COLUMN END

  Base:
    column-end = grid-column-end

  Modifiers
    1 = 1st line
    2 = 2nd line
    3 = 3rd line
    4 = 4th line
    5 = 5th line
    6 = 6th line

  Media Query Extensions:
    -ns = not-small
    -m  = medium
    -l  = large

*/
.column-end-1 { grid-column-end: 1; }
.column-end-2 { grid-column-end: 2; }
.column-end-3 { grid-column-end: 3; }
.column-end-4 { grid-column-end: 4; }
.column-end-5 { grid-column-end: 5; }
.column-end-6 { grid-column-end: 6; }
/*

  GRID ROW START

  Base:
    row-start = grid-row-start

  Modifiers
    1 = 1st line
    2 = 2nd line
    3 = 3rd line
    4 = 4th line
    5 = 5th line
    6 = 6th line

  Media Query Extensions:
    -ns = not-small
    -m  = medium
    -l  = large

*/
.row-start-1 { grid-row-start: 1; }
.row-start-2 { grid-row-start: 2; }
.row-start-3 { grid-row-start: 3; }
.row-start-4 { grid-row-start: 4; }
.row-start-5 { grid-row-start: 5; }
.row-start-6 { grid-row-start: 6; }
/*

  GRID ROW START

  Base:
    row-end = grid-row-end

  Modifiers
    1 = 1st line
    2 = 2nd line
    3 = 3rd line
    4 = 4th line
    5 = 5th line
    6 = 6th line

  Media Query Extensions:
    -ns = not-small
    -m  = medium
    -l  = large

*/
.row-end-1 { grid-row-end: 1; }
.row-end-2 { grid-row-end: 2; }
.row-end-3 { grid-row-end: 3; }
.row-end-4 { grid-row-end: 4; }
.row-end-5 { grid-row-end: 5; }
.row-end-6 { grid-row-end: 6; }
/*
    VARIABLES
*/
@media screen and (min-width: 30em) {
 .grid-ns { display: grid; }
 .grid-columns-1-ns { grid-template-columns: 1fr; }
 .grid-columns-2-ns { grid-template-columns: 1fr 1fr; }
 .grid-columns-3-ns { grid-template-columns: 1fr 1fr 1fr; }
 .grid-columns-4-ns { grid-template-columns: 1fr 1fr 1fr 1fr; }
 .grid-columns-5-ns { grid-template-columns: 1fr 1fr 1fr 1fr 1fr; }
 .grid-columns-6-ns { grid-template-columns: 1fr 1fr 1fr 1fr 1fr 1fr; }
 .grid-rows-1-ns { grid-template-rows: 1fr; }
 .grid-rows-2-ns { grid-template-rows: 1fr 1fr; }
 .grid-rows-3-ns { grid-template-rows: 1fr 1fr 1fr; }
 .grid-rows-4-ns { grid-template-rows: 1fr 1fr 1fr 1fr; }
 .grid-rows-5-ns { grid-template-rows: 1fr 1fr 1fr 1fr 1fr; }
 .grid-rows-6-ns { grid-template-rows: 1fr 1fr 1fr 1fr 1fr 1fr; }
 .column-start-1-ns { grid-column-start: 1; }
 .column-start-2-ns { grid-column-start: 2; }
 .column-start-3-ns { grid-column-start: 3; }
 .column-start-4-ns { grid-column-start: 4; }
 .column-start-5-ns { grid-column-start: 5; }
 .column-start-6-ns { grid-column-start: 6; }
 .column-end-1-ns { grid-column-end: 1; }
 .column-end-2-ns { grid-column-end: 2; }
 .column-end-3-ns { grid-column-end: 3; }
 .column-end-4-ns { grid-column-end: 4; }
 .column-end-5-ns { grid-column-end: 5; }
 .column-end-6-ns { grid-column-end: 6; }
 .row-start-1-ns { grid-row-start: 1; }
 .row-start-2-ns { grid-row-start: 2; }
 .row-start-3-ns { grid-row-start: 3; }
 .row-start-4-ns { grid-row-start: 4; }
 .row-start-5-ns { grid-row-start: 5; }
 .row-start-6-ns { grid-row-start: 6; }
 .row-end-1-ns { grid-row-end: 1; }
 .row-end-2-ns { grid-row-end: 2; }
 .row-end-3-ns { grid-row-end: 3; }
 .row-end-4-ns { grid-row-end: 4; }
 .row-end-5-ns { grid-row-end: 5; }
 .row-end-6-ns { grid-row-end: 6; }
}
@media screen and (min-width: 30em) and (max-width: 60em) {
 .grid-m { display: grid; }
 .grid-columns-1-m { grid-template-columns: 1fr; }
 .grid-columns-2-m { grid-template-columns: 1fr 1fr; }
 .grid-columns-3-m { grid-template-columns: 1fr 1fr 1fr; }
 .grid-columns-4-m { grid-template-columns: 1fr 1fr 1fr 1fr; }
 .grid-columns-5-m { grid-template-columns: 1fr 1fr 1fr 1fr 1fr; }
 .grid-columns-6-m { grid-template-columns: 1fr 1fr 1fr 1fr 1fr 1fr; }
 .grid-rows-1-m { grid-template-rows: 1fr; }
 .grid-rows-2-m { grid-template-rows: 1fr 1fr; }
 .grid-rows-3-m { grid-template-rows: 1fr 1fr 1fr; }
 .grid-rows-4-m { grid-template-rows: 1fr 1fr 1fr 1fr; }
 .grid-rows-5-m { grid-template-rows: 1fr 1fr 1fr 1fr 1fr; }
 .grid-rows-6-m { grid-template-rows: 1fr 1fr 1fr 1fr 1fr 1fr; }
 .column-start-1-m { grid-column-start: 1; }
 .column-start-2-m { grid-column-start: 2; }
 .column-start-3-m { grid-column-start: 3; }
 .column-start-4-m { grid-column-start: 4; }
 .column-start-5-m { grid-column-start: 5; }
 .column-start-6-m { grid-column-start: 6; }
 .column-end-1-m { grid-column-end: 1; }
 .column-end-2-m { grid-column-end: 2; }
 .column-end-3-m { grid-column-end: 3; }
 .column-end-4-m { grid-column-end: 4; }
 .column-end-5-m { grid-column-end: 5; }
 .column-end-6-m { grid-column-end: 6; }
 .row-start-1-m { grid-row-start: 1; }
 .row-start-2-m { grid-row-start: 2; }
 .row-start-3-m { grid-row-start: 3; }
 .row-start-4-m { grid-row-start: 4; }
 .row-start-5-m { grid-row-start: 5; }
 .row-start-6-m { grid-row-start: 6; }
 .row-end-1-m { grid-row-end: 1; }
 .row-end-2-m { grid-row-end: 2; }
 .row-end-3-m { grid-row-end: 3; }
 .row-end-4-m { grid-row-end: 4; }
 .row-end-5-m { grid-row-end: 5; }
 .row-end-6-m { grid-row-end: 6; }
}
@media screen and (min-width: 60em) {
 .grid-l { display: grid; }
 .grid-columns-1-l { grid-template-columns: 1fr; }
 .grid-columns-2-l { grid-template-columns: 1fr 1fr; }
 .grid-columns-3-l { grid-template-columns: 1fr 1fr 1fr; }
 .grid-columns-4-l { grid-template-columns: 1fr 1fr 1fr 1fr; }
 .grid-columns-5-l { grid-template-columns: 1fr 1fr 1fr 1fr 1fr; }
 .grid-columns-6-l { grid-template-columns: 1fr 1fr 1fr 1fr 1fr 1fr; }
 .grid-rows-1-l { grid-template-rows: 1fr; }
 .grid-rows-2-l { grid-template-rows: 1fr 1fr; }
 .grid-rows-3-l { grid-template-rows: 1fr 1fr 1fr; }
 .grid-rows-4-l { grid-template-rows: 1fr 1fr 1fr 1fr; }
 .grid-rows-5-l { grid-template-rows: 1fr 1fr 1fr 1fr 1fr; }
 .grid-rows-6-l { grid-template-rows: 1fr 1fr 1fr 1fr 1fr 1fr; }
 .column-start-1-l { grid-column-start: 1; }
 .column-start-2-l { grid-column-start: 2; }
 .column-start-3-l { grid-column-start: 3; }
 .column-start-4-l { grid-column-start: 4; }
 .column-start-5-l { grid-column-start: 5; }
 .column-start-6-l { grid-column-start: 6; }
 .column-end-1-l { grid-column-end: 1; }
 .column-end-2-l { grid-column-end: 2; }
 .column-end-3-l { grid-column-end: 3; }
 .column-end-4-l { grid-column-end: 4; }
 .column-end-5-l { grid-column-end: 5; }
 .column-end-6-l { grid-column-end: 6; }
 .row-start-1-l { grid-row-start: 1; }
 .row-start-2-l { grid-row-start: 2; }
 .row-start-3-l { grid-row-start: 3; }
 .row-start-4-l { grid-row-start: 4; }
 .row-start-5-l { grid-row-start: 5; }
 .row-start-6-l { grid-row-start: 6; }
 .row-end-1-l { grid-row-end: 1; }
 .row-end-2-l { grid-row-end: 2; }
 .row-end-3-l { grid-row-end: 3; }
 .row-end-4-l { grid-row-end: 4; }
 .row-end-5-l { grid-row-end: 5; }
 .row-end-6-l { grid-row-end: 6; }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [bobek-balinek](https://github.com/bobek-balinek)

## License

ISC
