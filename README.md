# tachyons-grid-layout 0.1.0

CSS Grid module for Tachyons

### Stats

1583 | 239 | 267
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev tachyons-grid-layout
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/bobek-balinek/tachyons-grid-layout
```

ssh:
```
git clone git@github.com:bobek-balinek/tachyons-grid-layout.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "tachyons-grid-layout";
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
<link rel="stylesheet" href="http://unpkg.com/tachyons-grid-layout@0.1.0/css/tachyons-grid-layout.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/tachyons-grid-layout">
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

  GAP

  Base
    g = gap

  Modifiers
    a = all
    c = column
    r = row

    0 = none
    1 = 1st step in spacing scale
    2 = 2nd step in spacing scale
    3 = 3rd step in spacing scale
    4 = 4th step in spacing scale
    5 = 5th step in spacing scale
    6 = 6th step in spacing scale
    7 = 7th step in spacing scale

  Media Query Extensions:
    -ns = not-small
    -m  = medium
    -l  = large

*/
.ga0 { gap: 0; }
.ga1 { gap: .25rem; }
.ga2 { gap: .5rem; }
.ga3 { gap: 1rem; }
.ga4 { gap: 2rem; }
.ga5 { gap: 4rem; }
.ga6 { gap: 8rem; }
.gc0 { -webkit-column-gap: 0; column-gap: 0; }
.gc1 { -webkit-column-gap: .25rem; column-gap: .25rem; }
.gc2 { -webkit-column-gap: .5rem; column-gap: .5rem; }
.gc3 { -webkit-column-gap: 1rem; column-gap: 1rem; }
.gc4 { -webkit-column-gap: 2rem; column-gap: 2rem; }
.gc5 { -webkit-column-gap: 4rem; column-gap: 4rem; }
.gc6 { -webkit-column-gap: 8rem; column-gap: 8rem; }
.gr0 { row-gap: 0; }
.gr1 { row-gap: .25rem; }
.gr2 { row-gap: .5rem; }
.gr3 { row-gap: 1rem; }
.gr4 { row-gap: 2rem; }
.gr5 { row-gap: 4rem; }
.gr6 { row-gap: 8rem; }
/*

  GRID COLUMNS

  Base
    g = gap

  Modifiers
    1 = 1 column
    c = column
    r = row

    0 = none
    1 = 1st step in spacing scale
    2 = 2nd step in spacing scale
    3 = 3rd step in spacing scale
    4 = 4th step in spacing scale
    5 = 5th step in spacing scale
    6 = 6th step in spacing scale
    7 = 7th step in spacing scale

  Media Query Extensions:
    -ns = not-small
    -m  = medium
    -l  = large

*/
.ga0 { gap: 0; }
.ga1 { gap: .25rem; }
  GRID COLUMNS
.ga3 { gap: 1rem; }
.ga4 { gap: 2rem; }
.ga5 { gap: 4rem; }
.ga6 { gap: 8rem; }
.gc0 { -webkit-column-gap: 0; column-gap: 0; }
    1 = 1 row
.gc2 { -webkit-column-gap: .5rem; column-gap: .5rem; }
.gc3 { -webkit-column-gap: 1rem; column-gap: 1rem; }
.gc4 { -webkit-column-gap: 2rem; column-gap: 2rem; }
.gc5 { -webkit-column-gap: 4rem; column-gap: 4rem; }
.gc6 { -webkit-column-gap: 8rem; column-gap: 8rem; }
.gr0 { row-gap: 0; }
.gr1 { row-gap: .25rem; }
.gr2 { row-gap: .5rem; }
.gr3 { row-gap: 1rem; }
.gr4 { row-gap: 2rem; }
.gr5 { row-gap: 4rem; }
.gr6 { row-gap: 8rem; }
/*

  GRID COLUMNS

  Base
    g = gap

  Modifiers
  COLUMN START
    c = column
    r = row

    0 = none
    1 = 1st step in spacing scale
    2 = 2nd step in spacing scale
    3 = 3rd step in spacing scale
    4 = 4th step in spacing scale
    5 = 5th step in spacing scale
    6 = 6th step in spacing scale
    7 = 7th step in spacing scale
    7 = 7th line

  Media Query Extensions:
    -ns = not-small
    -m  = medium
    -l  = large

*/
.ga0 { gap: 0; }
.ga1 { gap: .25rem; }
  GRID COLUMNS
.ga3 { gap: 1rem; }
.ga4 { gap: 2rem; }
.ga5 { gap: 4rem; }
.column-start-7 { grid-column-start: 7; }
.ga6 { gap: 8rem; }
.gc0 { -webkit-column-gap: 0; column-gap: 0; }
  COLUMN END
.gc2 { -webkit-column-gap: .5rem; column-gap: .5rem; }
.gc3 { -webkit-column-gap: 1rem; column-gap: 1rem; }
.gc4 { -webkit-column-gap: 2rem; column-gap: 2rem; }
.gc5 { -webkit-column-gap: 4rem; column-gap: 4rem; }
.gc6 { -webkit-column-gap: 8rem; column-gap: 8rem; }
.gr0 { row-gap: 0; }
.gr1 { row-gap: .25rem; }
.gr2 { row-gap: .5rem; }
.gr3 { row-gap: 1rem; }
.gr4 { row-gap: 2rem; }
.gr5 { row-gap: 4rem; }
    7 = 7th line
.gr6 { row-gap: 8rem; }
/*

  GRID COLUMNS

  Base:
    grid-columns = grid-template-columns

  Modifiers
  COLUMN START
    2 = 2 columns
    3 = 3 columns
    4 = 4 columns
.column-end-7 { grid-column-end: 7; }
    5 = 5 columns
    6 = 6 columns
  ROW START
  Media Query Extensions:
    -ns = not-small
    -m  = medium
    -l  = large

    7 = 7th line
*/
.grid-columns-1 { grid-template-columns: 1fr; }
.grid-columns-2 { grid-template-columns: 1fr 1fr; }
.grid-columns-3 { grid-template-columns: 1fr 1fr 1fr; }
.grid-columns-4 { grid-template-columns: 1fr 1fr 1fr 1fr; }
    7 = 7th line
.grid-columns-5 { grid-template-columns: 1fr 1fr 1fr 1fr 1fr; }
.grid-columns-6 { grid-template-columns: 1fr 1fr 1fr 1fr 1fr 1fr; }
/*

  GRID COLUMNS

  Base:
    grid-rows = grid-template-rows
.column-start-7 { grid-column-start: 7; }

  Modifiers
  COLUMN END
    2 = 2 rows
    3 = 3 rows
    4 = 4 rows
  ROW END
    6 = 6 rows

  Media Query Extensions:
    -ns = not-small
    -m  = medium
    -l  = large

    7 = 7th line
*/
.grid-rows-1 { grid-template-rows: 1fr; }
.grid-rows-2 { grid-template-rows: 1fr 1fr; }
    7 = 7th line
.grid-rows-3 { grid-template-rows: 1fr 1fr 1fr; }
.grid-rows-4 { grid-template-rows: 1fr 1fr 1fr 1fr; }
.grid-rows-5 { grid-template-rows: 1fr 1fr 1fr 1fr 1fr; }
.grid-rows-6 { grid-template-rows: 1fr 1fr 1fr 1fr 1fr 1fr; }
/*

  COLUMN START

  Base:
    column-start = grid-column-start
.column-end-7 { grid-column-end: 7; }

  Modifiers
  ROW START
    2 = 2nd line
    3 = 3rd line
    4 = 4th line
    5 = 5th line
 .ga0-ns { gap: 0; }
 .ga1-ns { gap: .25rem; }
 .ga2-ns { gap: .5rem; }
 .ga3-ns { gap: 1rem; }
 .ga4-ns { gap: 2rem; }
 .ga5-ns { gap: 4rem; }
 .ga6-ns { gap: 8rem; }
 .gc0-ns { -webkit-column-gap: 0; column-gap: 0; }
 .gc1-ns { -webkit-column-gap: .25rem; column-gap: .25rem; }
 .gc2-ns { -webkit-column-gap: .5rem; column-gap: .5rem; }
 .gc3-ns { -webkit-column-gap: 1rem; column-gap: 1rem; }
 .gc4-ns { -webkit-column-gap: 2rem; column-gap: 2rem; }
 .gc5-ns { -webkit-column-gap: 4rem; column-gap: 4rem; }
 .gc6-ns { -webkit-column-gap: 8rem; column-gap: 8rem; }
 .gr0-ns { row-gap: 0; }
 .gr1-ns { row-gap: .25rem; }
 .gr2-ns { row-gap: .5rem; }
 .gr3-ns { row-gap: 1rem; }
 .gr4-ns { row-gap: 2rem; }
 .gr5-ns { row-gap: 4rem; }
 .gr6-ns { row-gap: 8rem; }
    6 = 6th line
    7 = 7th line

  Media Query Extensions:
    -ns = not-small
    -m  = medium
    -l  = large
    7 = 7th line

*/
.column-start-1 { grid-column-start: 1; }
.column-start-2 { grid-column-start: 2; }
.column-start-3 { grid-column-start: 3; }
.column-start-4 { grid-column-start: 4; }
.column-start-5 { grid-column-start: 5; }
.column-start-6 { grid-column-start: 6; }
.column-start-7 { grid-column-start: 7; }
/*
 .column-start-7-ns { grid-column-start: 7; }

  COLUMN END

  Base:
    column-end = grid-column-end
  ROW END
 .column-end-7-ns { grid-column-end: 7; }
  Modifiers
    1 = 1st line
    2 = 2nd line
    3 = 3rd line
    4 = 4th line
    5 = 5th line
    6 = 6th line
    7 = 7th line

  Media Query Extensions:
    -ns = not-small
    7 = 7th line
    -m  = medium
    -l  = large

 .ga0-m { gap: 0; }
 .ga1-m { gap: .25rem; }
 .ga2-m { gap: .5rem; }
 .ga3-m { gap: 1rem; }
 .ga4-m { gap: 2rem; }
 .ga5-m { gap: 4rem; }
 .ga6-m { gap: 8rem; }
 .gc0-m { -webkit-column-gap: 0; column-gap: 0; }
 .gc1-m { -webkit-column-gap: .25rem; column-gap: .25rem; }
 .gc2-m { -webkit-column-gap: .5rem; column-gap: .5rem; }
 .gc3-m { -webkit-column-gap: 1rem; column-gap: 1rem; }
 .gc4-m { -webkit-column-gap: 2rem; column-gap: 2rem; }
 .gc5-m { -webkit-column-gap: 4rem; column-gap: 4rem; }
 .gc6-m { -webkit-column-gap: 8rem; column-gap: 8rem; }
 .gr0-m { row-gap: 0; }
 .gr1-m { row-gap: .25rem; }
 .gr2-m { row-gap: .5rem; }
 .gr3-m { row-gap: 1rem; }
 .gr4-m { row-gap: 2rem; }
 .gr5-m { row-gap: 4rem; }
 .gr6-m { row-gap: 8rem; }
*/
.column-end-1 { grid-column-end: 1; }
.column-end-2 { grid-column-end: 2; }
.column-end-3 { grid-column-end: 3; }
.column-end-4 { grid-column-end: 4; }
.column-end-5 { grid-column-end: 5; }
.column-end-6 { grid-column-end: 6; }
.column-end-7 { grid-column-end: 7; }
/*

  ROW START

  Base:
    row-start = grid-row-start

 .ga0-ns { gap: 0; }
 .ga1-ns { gap: .25rem; }
 .ga2-ns { gap: .5rem; }
 .ga3-ns { gap: 1rem; }
 .ga4-ns { gap: 2rem; }
 .ga5-ns { gap: 4rem; }
 .ga6-ns { gap: 8rem; }
 .gc0-ns { -webkit-column-gap: 0; column-gap: 0; }
 .gc1-ns { -webkit-column-gap: .25rem; column-gap: .25rem; }
 .column-end-7-m { grid-column-end: 7; }
 .gc2-ns { -webkit-column-gap: .5rem; column-gap: .5rem; }
 .gc3-ns { -webkit-column-gap: 1rem; column-gap: 1rem; }
 .gc4-ns { -webkit-column-gap: 2rem; column-gap: 2rem; }
 .gc5-ns { -webkit-column-gap: 4rem; column-gap: 4rem; }
 .gc6-ns { -webkit-column-gap: 8rem; column-gap: 8rem; }
 .gr0-ns { row-gap: 0; }
 .gr1-ns { row-gap: .25rem; }
 .gr2-ns { row-gap: .5rem; }
 .gr3-ns { row-gap: 1rem; }
 .gr4-ns { row-gap: 2rem; }
 .gr5-ns { row-gap: 4rem; }
 .gr6-ns { row-gap: 8rem; }
  Modifiers
    1 = 1st line
    2 = 2nd line
 .ga0-l { gap: 0; }
 .ga1-l { gap: .25rem; }
 .ga2-l { gap: .5rem; }
 .ga3-l { gap: 1rem; }
 .ga4-l { gap: 2rem; }
 .ga5-l { gap: 4rem; }
 .ga6-l { gap: 8rem; }
 .gc0-l { -webkit-column-gap: 0; column-gap: 0; }
 .gc1-l { -webkit-column-gap: .25rem; column-gap: .25rem; }
 .gc2-l { -webkit-column-gap: .5rem; column-gap: .5rem; }
 .gc3-l { -webkit-column-gap: 1rem; column-gap: 1rem; }
 .gc4-l { -webkit-column-gap: 2rem; column-gap: 2rem; }
 .gc5-l { -webkit-column-gap: 4rem; column-gap: 4rem; }
 .gc6-l { -webkit-column-gap: 8rem; column-gap: 8rem; }
 .gr0-l { row-gap: 0; }
 .gr1-l { row-gap: .25rem; }
 .gr2-l { row-gap: .5rem; }
 .gr3-l { row-gap: 1rem; }
 .gr4-l { row-gap: 2rem; }
 .gr5-l { row-gap: 4rem; }
 .gr6-l { row-gap: 8rem; }
    3 = 3rd line
    4 = 4th line
    5 = 5th line
    6 = 6th line
    7 = 7th line

  Media Query Extensions:
    -ns = not-small
    -m  = medium
    -l  = large

*/
.row-start-1 { grid-row-start: 1; }
.row-start-2 { grid-row-start: 2; }
.row-start-3 { grid-row-start: 3; }
 .column-start-7-ns { grid-column-start: 7; }
.row-start-4 { grid-row-start: 4; }
.row-start-5 { grid-row-start: 5; }
 .column-start-7-l { grid-column-start: 7; }
.row-start-6 { grid-row-start: 6; }
/*

  ROW END
 .column-end-7-ns { grid-column-end: 7; }

 .column-end-7-l { grid-column-end: 7; }
  Base:
    row-end = grid-row-end

  Modifiers
    1 = 1st line
    2 = 2nd line
    3 = 3rd line
    4 = 4th line
    5 = 5th line
    6 = 6th line
    7 = 7th line

  Media Query Extensions:
    -ns = not-small
 .ga0-m { gap: 0; }
 .ga1-m { gap: .25rem; }
 .ga2-m { gap: .5rem; }
 .ga3-m { gap: 1rem; }
 .ga4-m { gap: 2rem; }
 .ga5-m { gap: 4rem; }
 .ga6-m { gap: 8rem; }
 .gc0-m { -webkit-column-gap: 0; column-gap: 0; }
 .gc1-m { -webkit-column-gap: .25rem; column-gap: .25rem; }
 .gc2-m { -webkit-column-gap: .5rem; column-gap: .5rem; }
 .gc3-m { -webkit-column-gap: 1rem; column-gap: 1rem; }
 .gc4-m { -webkit-column-gap: 2rem; column-gap: 2rem; }
 .gc5-m { -webkit-column-gap: 4rem; column-gap: 4rem; }
 .gc6-m { -webkit-column-gap: 8rem; column-gap: 8rem; }
 .gr0-m { row-gap: 0; }
 .gr1-m { row-gap: .25rem; }
 .gr2-m { row-gap: .5rem; }
 .gr3-m { row-gap: 1rem; }
 .gr4-m { row-gap: 2rem; }
 .gr5-m { row-gap: 4rem; }
 .gr6-m { row-gap: 8rem; }
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
 .ga0-ns { gap: 0; }
 .ga1-ns { gap: .25rem; }
 .ga2-ns { gap: .5rem; }
 .ga3-ns { gap: 1rem; }
 .ga4-ns { gap: 2rem; }
 .ga5-ns { gap: 4rem; }
 .ga6-ns { gap: 8rem; }
 .gc0-ns { -webkit-column-gap: 0; column-gap: 0; }
 .gc1-ns { -webkit-column-gap: .25rem; column-gap: .25rem; }
 .column-end-7-m { grid-column-end: 7; }
 .gc2-ns { -webkit-column-gap: .5rem; column-gap: .5rem; }
 .gc3-ns { -webkit-column-gap: 1rem; column-gap: 1rem; }
 .gc4-ns { -webkit-column-gap: 2rem; column-gap: 2rem; }
 .gc5-ns { -webkit-column-gap: 4rem; column-gap: 4rem; }
 .gc6-ns { -webkit-column-gap: 8rem; column-gap: 8rem; }
 .gr0-ns { row-gap: 0; }
 .gr1-ns { row-gap: .25rem; }
 .gr2-ns { row-gap: .5rem; }
 .gr3-ns { row-gap: 1rem; }
 .gr4-ns { row-gap: 2rem; }
 .gr5-ns { row-gap: 4rem; }
 .gr6-ns { row-gap: 8rem; }
 .grid-columns-1-ns { grid-template-columns: 1fr; }
 .grid-columns-2-ns { grid-template-columns: 1fr 1fr; }
 .grid-columns-3-ns { grid-template-columns: 1fr 1fr 1fr; }
 .ga0-l { gap: 0; }
 .ga1-l { gap: .25rem; }
 .ga2-l { gap: .5rem; }
 .ga3-l { gap: 1rem; }
 .ga4-l { gap: 2rem; }
 .ga5-l { gap: 4rem; }
 .ga6-l { gap: 8rem; }
 .gc0-l { -webkit-column-gap: 0; column-gap: 0; }
 .gc1-l { -webkit-column-gap: .25rem; column-gap: .25rem; }
 .gc2-l { -webkit-column-gap: .5rem; column-gap: .5rem; }
 .gc3-l { -webkit-column-gap: 1rem; column-gap: 1rem; }
 .gc4-l { -webkit-column-gap: 2rem; column-gap: 2rem; }
 .gc5-l { -webkit-column-gap: 4rem; column-gap: 4rem; }
 .gc6-l { -webkit-column-gap: 8rem; column-gap: 8rem; }
 .gr0-l { row-gap: 0; }
 .gr1-l { row-gap: .25rem; }
 .gr2-l { row-gap: .5rem; }
 .gr3-l { row-gap: 1rem; }
 .gr4-l { row-gap: 2rem; }
 .gr5-l { row-gap: 4rem; }
 .gr6-l { row-gap: 8rem; }
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
 .column-start-7-ns { grid-column-start: 7; }
 .column-end-1-ns { grid-column-end: 1; }
 .column-end-2-ns { grid-column-end: 2; }
 .column-start-7-l { grid-column-start: 7; }
 .column-end-3-ns { grid-column-end: 3; }
 .column-end-4-ns { grid-column-end: 4; }
 .column-end-5-ns { grid-column-end: 5; }
 .column-end-6-ns { grid-column-end: 6; }
 .column-end-7-ns { grid-column-end: 7; }
 .row-start-1-ns { grid-row-start: 1; }
 .column-end-7-l { grid-column-end: 7; }
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
 .ga0-m { gap: 0; }
 .ga1-m { gap: .25rem; }
 .ga2-m { gap: .5rem; }
 .ga3-m { gap: 1rem; }
 .ga4-m { gap: 2rem; }
 .ga5-m { gap: 4rem; }
 .ga6-m { gap: 8rem; }
 .gc0-m { -webkit-column-gap: 0; column-gap: 0; }
 .gc1-m { -webkit-column-gap: .25rem; column-gap: .25rem; }
 .gc2-m { -webkit-column-gap: .5rem; column-gap: .5rem; }
 .gc3-m { -webkit-column-gap: 1rem; column-gap: 1rem; }
 .gc4-m { -webkit-column-gap: 2rem; column-gap: 2rem; }
 .gc5-m { -webkit-column-gap: 4rem; column-gap: 4rem; }
 .gc6-m { -webkit-column-gap: 8rem; column-gap: 8rem; }
 .gr0-m { row-gap: 0; }
 .gr1-m { row-gap: .25rem; }
 .gr2-m { row-gap: .5rem; }
 .gr3-m { row-gap: 1rem; }
 .gr4-m { row-gap: 2rem; }
 .gr5-m { row-gap: 4rem; }
 .gr6-m { row-gap: 8rem; }
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
 .column-end-7-m { grid-column-end: 7; }
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
 .ga0-l { gap: 0; }
 .ga1-l { gap: .25rem; }
 .ga2-l { gap: .5rem; }
 .ga3-l { gap: 1rem; }
 .ga4-l { gap: 2rem; }
 .ga5-l { gap: 4rem; }
 .ga6-l { gap: 8rem; }
 .gc0-l { -webkit-column-gap: 0; column-gap: 0; }
 .gc1-l { -webkit-column-gap: .25rem; column-gap: .25rem; }
 .gc2-l { -webkit-column-gap: .5rem; column-gap: .5rem; }
 .gc3-l { -webkit-column-gap: 1rem; column-gap: 1rem; }
 .gc4-l { -webkit-column-gap: 2rem; column-gap: 2rem; }
 .gc5-l { -webkit-column-gap: 4rem; column-gap: 4rem; }
 .gc6-l { -webkit-column-gap: 8rem; column-gap: 8rem; }
 .gr0-l { row-gap: 0; }
 .gr1-l { row-gap: .25rem; }
 .gr2-l { row-gap: .5rem; }
 .gr3-l { row-gap: 1rem; }
 .gr4-l { row-gap: 2rem; }
 .gr5-l { row-gap: 4rem; }
 .gr6-l { row-gap: 8rem; }
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
 .column-start-7-l { grid-column-start: 7; }
 .column-end-1-l { grid-column-end: 1; }
 .column-end-2-l { grid-column-end: 2; }
 .column-end-3-l { grid-column-end: 3; }
 .column-end-4-l { grid-column-end: 4; }
 .column-end-5-l { grid-column-end: 5; }
 .column-end-6-l { grid-column-end: 6; }
 .column-end-7-l { grid-column-end: 7; }
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
