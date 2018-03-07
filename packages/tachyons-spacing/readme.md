# tachyons 5.0.0-1

Functional CSS for humans

### Stats

1907 | 336 | 432
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev tachyons
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/tachyons
```

ssh:
```
git clone git@github.com:tachyons-css/tachyons.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "tachyons";
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
<link rel="stylesheet" href="http://unpkg.com/tachyons@5.0.0-1/css/tachyons.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/tachyons">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*!!!

  # SPACING

  An eight step powers of two scale ranging from 0 to 16rem.

  ### Docs

  http://tachyons.io/docs/layout/spacing/

  ### Base

  - p = padding
  - m = margin

  ### Modifiers

  - a = all
  - h = horizontal
  - v = vertical
  - t = top
  - r = right
  - b = bottom
  - l = left

  - 0 = none
  - 1 = 1st step in spacing scale
  - 2 = 2nd step in spacing scale
  - 3 = 3rd step in spacing scale
  - 4 = 4th step in spacing scale
  - 5 = 5th step in spacing scale
  - 6 = 6th step in spacing scale
  - 7 = 7th step in spacing scale

  ### Media Query Extensions

  - `-m` = medium
  - `-l` = large
*/
/* Variables */
.pa0 { padding: 0; }
.pa1 { padding: .25rem; }
.pa2 { padding: .5rem; }
.pa3 { padding: 1rem; }
.pa4 { padding: 2rem; }
.pa5 { padding: 4rem; }
.pa6 { padding: 8rem; }
.pa7 { padding: 16rem; }
.pl0 { padding-left: 0; }
.pl1 { padding-left: .25rem; }
.pl2 { padding-left: .5rem; }
.pl3 { padding-left: 1rem; }
.pl4 { padding-left: 2rem; }
.pl5 { padding-left: 4rem; }
.pl6 { padding-left: 8rem; }
.pl7 { padding-left: 16rem; }
.pr0 { padding-right: 0; }
.pr1 { padding-right: .25rem; }
.pr2 { padding-right: .5rem; }
.pr3 { padding-right: 1rem; }
.pr4 { padding-right: 2rem; }
.pr5 { padding-right: 4rem; }
.pr6 { padding-right: 8rem; }
.pr7 { padding-right: 16rem; }
.pb0 { padding-bottom: 0; }
.pb1 { padding-bottom: .25rem; }
.pb2 { padding-bottom: .5rem; }
.pb3 { padding-bottom: 1rem; }
.pb4 { padding-bottom: 2rem; }
.pb5 { padding-bottom: 4rem; }
.pb6 { padding-bottom: 8rem; }
.pb7 { padding-bottom: 16rem; }
.pt0 { padding-top: 0; }
.pt1 { padding-top: .25rem; }
.pt2 { padding-top: .5rem; }
.pt3 { padding-top: 1rem; }
.pt4 { padding-top: 2rem; }
.pt5 { padding-top: 4rem; }
.pt6 { padding-top: 8rem; }
.pt7 { padding-top: 16rem; }
.pv0 { padding-top: 0; padding-bottom: 0; }
.pv1 { padding-top: .25rem; padding-bottom: .25rem; }
.pv2 { padding-top: .5rem; padding-bottom: .5rem; }
.pv3 { padding-top: 1rem; padding-bottom: 1rem; }
.pv4 { padding-top: 2rem; padding-bottom: 2rem; }
.pv5 { padding-top: 4rem; padding-bottom: 4rem; }
.pv6 { padding-top: 8rem; padding-bottom: 8rem; }
.pv7 { padding-top: 16rem; padding-bottom: 16rem; }
.ph0 { padding-left: 0; padding-right: 0; }
.ph1 { padding-left: .25rem; padding-right: .25rem; }
.ph2 { padding-left: .5rem; padding-right: .5rem; }
.ph3 { padding-left: 1rem; padding-right: 1rem; }
.ph4 { padding-left: 2rem; padding-right: 2rem; }
.ph5 { padding-left: 4rem; padding-right: 4rem; }
.ph6 { padding-left: 8rem; padding-right: 8rem; }
.ph7 { padding-left: 16rem; padding-right: 16rem; }
.ma0 { margin: 0; }
.ma1 { margin: .25rem; }
.ma2 { margin: .5rem; }
.ma3 { margin: 1rem; }
.ma4 { margin: 2rem; }
.ma5 { margin: 4rem; }
.ma6 { margin: 8rem; }
.ma7 { margin: 16rem; }
.ml0 { margin-left: 0; }
.ml1 { margin-left: .25rem; }
.ml2 { margin-left: .5rem; }
.ml3 { margin-left: 1rem; }
.ml4 { margin-left: 2rem; }
.ml5 { margin-left: 4rem; }
.ml6 { margin-left: 8rem; }
.ml7 { margin-left: 16rem; }
.mr0 { margin-right: 0; }
.mr1 { margin-right: .25rem; }
.mr2 { margin-right: .5rem; }
.mr3 { margin-right: 1rem; }
.mr4 { margin-right: 2rem; }
.mr5 { margin-right: 4rem; }
.mr6 { margin-right: 8rem; }
.mr7 { margin-right: 16rem; }
.mb0 { margin-bottom: 0; }
.mb1 { margin-bottom: .25rem; }
.mb2 { margin-bottom: .5rem; }
.mb3 { margin-bottom: 1rem; }
.mb4 { margin-bottom: 2rem; }
.mb5 { margin-bottom: 4rem; }
.mb6 { margin-bottom: 8rem; }
.mb7 { margin-bottom: 16rem; }
.mt0 { margin-top: 0; }
.mt1 { margin-top: .25rem; }
.mt2 { margin-top: .5rem; }
.mt3 { margin-top: 1rem; }
.mt4 { margin-top: 2rem; }
.mt5 { margin-top: 4rem; }
.mt6 { margin-top: 8rem; }
.mt7 { margin-top: 16rem; }
.mv0 { margin-top: 0; margin-bottom: 0; }
.mv1 { margin-top: .25rem; margin-bottom: .25rem; }
.mv2 { margin-top: .5rem; margin-bottom: .5rem; }
.mv3 { margin-top: 1rem; margin-bottom: 1rem; }
.mv4 { margin-top: 2rem; margin-bottom: 2rem; }
.mv5 { margin-top: 4rem; margin-bottom: 4rem; }
.mv6 { margin-top: 8rem; margin-bottom: 8rem; }
.mv7 { margin-top: 16rem; margin-bottom: 16rem; }
.mh0 { margin-left: 0; margin-right: 0; }
.mh1 { margin-left: .25rem; margin-right: .25rem; }
.mh2 { margin-left: .5rem; margin-right: .5rem; }
.mh3 { margin-left: 1rem; margin-right: 1rem; }
.mh4 { margin-left: 2rem; margin-right: 2rem; }
.mh5 { margin-left: 4rem; margin-right: 4rem; }
.mh6 { margin-left: 8rem; margin-right: 8rem; }
.mh7 { margin-left: 16rem; margin-right: 16rem; }
@media screen and (min-width: 30em) {
 .pa0-m { padding: 0; }
 .pa1-m { padding: .25rem; }
 .pa2-m { padding: .5rem; }
 .pa3-m { padding: 1rem; }
 .pa4-m { padding: 2rem; }
 .pa5-m { padding: 4rem; }
 .pa6-m { padding: 8rem; }
 .pa7-m { padding: 16rem; }
 .pl0-m { padding-left: 0; }
 .pl1-m { padding-left: .25rem; }
 .pl2-m { padding-left: .5rem; }
 .pl3-m { padding-left: 1rem; }
 .pl4-m { padding-left: 2rem; }
 .pl5-m { padding-left: 4rem; }
 .pl6-m { padding-left: 8rem; }
 .pl7-m { padding-left: 16rem; }
 .pr0-m { padding-right: 0; }
 .pr1-m { padding-right: .25rem; }
 .pr2-m { padding-right: .5rem; }
 .pr3-m { padding-right: 1rem; }
 .pr4-m { padding-right: 2rem; }
 .pr5-m { padding-right: 4rem; }
 .pr6-m { padding-right: 8rem; }
 .pr7-m { padding-right: 16rem; }
 .pb0-m { padding-bottom: 0; }
 .pb1-m { padding-bottom: .25rem; }
 .pb2-m { padding-bottom: .5rem; }
 .pb3-m { padding-bottom: 1rem; }
 .pb4-m { padding-bottom: 2rem; }
 .pb5-m { padding-bottom: 4rem; }
 .pb6-m { padding-bottom: 8rem; }
 .pb7-m { padding-bottom: 16rem; }
 .pt0-m { padding-top: 0; }
 .pt1-m { padding-top: .25rem; }
 .pt2-m { padding-top: .5rem; }
 .pt3-m { padding-top: 1rem; }
 .pt4-m { padding-top: 2rem; }
 .pt5-m { padding-top: 4rem; }
 .pt6-m { padding-top: 8rem; }
 .pt7-m { padding-top: 16rem; }
 .pv0-m { padding-top: 0; padding-bottom: 0; }
 .pv1-m { padding-top: .25rem; padding-bottom: .25rem; }
 .pv2-m { padding-top: .5rem; padding-bottom: .5rem; }
 .pv3-m { padding-top: 1rem; padding-bottom: 1rem; }
 .pv4-m { padding-top: 2rem; padding-bottom: 2rem; }
 .pv5-m { padding-top: 4rem; padding-bottom: 4rem; }
 .pv6-m { padding-top: 8rem; padding-bottom: 8rem; }
 .pv7-m { padding-top: 16rem; padding-bottom: 16rem; }
 .ph0-m { padding-left: 0; padding-right: 0; }
 .ph1-m { padding-left: .25rem; padding-right: .25rem; }
 .ph2-m { padding-left: .5rem; padding-right: .5rem; }
 .ph3-m { padding-left: 1rem; padding-right: 1rem; }
 .ph4-m { padding-left: 2rem; padding-right: 2rem; }
 .ph5-m { padding-left: 4rem; padding-right: 4rem; }
 .ph6-m { padding-left: 8rem; padding-right: 8rem; }
 .ph7-m { padding-left: 16rem; padding-right: 16rem; }
 .ma0-m { margin: 0; }
 .ma1-m { margin: .25rem; }
 .ma2-m { margin: .5rem; }
 .ma3-m { margin: 1rem; }
 .ma4-m { margin: 2rem; }
 .ma5-m { margin: 4rem; }
 .ma6-m { margin: 8rem; }
 .ma7-m { margin: 16rem; }
 .ml0-m { margin-left: 0; }
 .ml1-m { margin-left: .25rem; }
 .ml2-m { margin-left: .5rem; }
 .ml3-m { margin-left: 1rem; }
 .ml4-m { margin-left: 2rem; }
 .ml5-m { margin-left: 4rem; }
 .ml6-m { margin-left: 8rem; }
 .ml7-m { margin-left: 16rem; }
 .mr0-m { margin-right: 0; }
 .mr1-m { margin-right: .25rem; }
 .mr2-m { margin-right: .5rem; }
 .mr3-m { margin-right: 1rem; }
 .mr4-m { margin-right: 2rem; }
 .mr5-m { margin-right: 4rem; }
 .mr6-m { margin-right: 8rem; }
 .mr7-m { margin-right: 16rem; }
 .mb0-m { margin-bottom: 0; }
 .mb1-m { margin-bottom: .25rem; }
 .mb2-m { margin-bottom: .5rem; }
 .mb3-m { margin-bottom: 1rem; }
 .mb4-m { margin-bottom: 2rem; }
 .mb5-m { margin-bottom: 4rem; }
 .mb6-m { margin-bottom: 8rem; }
 .mb7-m { margin-bottom: 16rem; }
 .mt0-m { margin-top: 0; }
 .mt1-m { margin-top: .25rem; }
 .mt2-m { margin-top: .5rem; }
 .mt3-m { margin-top: 1rem; }
 .mt4-m { margin-top: 2rem; }
 .mt5-m { margin-top: 4rem; }
 .mt6-m { margin-top: 8rem; }
 .mt7-m { margin-top: 16rem; }
 .mv0-m { margin-top: 0; margin-bottom: 0; }
 .mv1-m { margin-top: .25rem; margin-bottom: .25rem; }
 .mv2-m { margin-top: .5rem; margin-bottom: .5rem; }
 .mv3-m { margin-top: 1rem; margin-bottom: 1rem; }
 .mv4-m { margin-top: 2rem; margin-bottom: 2rem; }
 .mv5-m { margin-top: 4rem; margin-bottom: 4rem; }
 .mv6-m { margin-top: 8rem; margin-bottom: 8rem; }
 .mv7-m { margin-top: 16rem; margin-bottom: 16rem; }
 .mh0-m { margin-left: 0; margin-right: 0; }
 .mh1-m { margin-left: .25rem; margin-right: .25rem; }
 .mh2-m { margin-left: .5rem; margin-right: .5rem; }
 .mh3-m { margin-left: 1rem; margin-right: 1rem; }
 .mh4-m { margin-left: 2rem; margin-right: 2rem; }
 .mh5-m { margin-left: 4rem; margin-right: 4rem; }
 .mh6-m { margin-left: 8rem; margin-right: 8rem; }
 .mh7-m { margin-left: 16rem; margin-right: 16rem; }
}
@media screen and (min-width: 60em) {
 .pa0-l { padding: 0; }
 .pa1-l { padding: .25rem; }
 .pa2-l { padding: .5rem; }
 .pa3-l { padding: 1rem; }
 .pa4-l { padding: 2rem; }
 .pa5-l { padding: 4rem; }
 .pa6-l { padding: 8rem; }
 .pa7-l { padding: 16rem; }
 .pl0-l { padding-left: 0; }
 .pl1-l { padding-left: .25rem; }
 .pl2-l { padding-left: .5rem; }
 .pl3-l { padding-left: 1rem; }
 .pl4-l { padding-left: 2rem; }
 .pl5-l { padding-left: 4rem; }
 .pl6-l { padding-left: 8rem; }
 .pl7-l { padding-left: 16rem; }
 .pr0-l { padding-right: 0; }
 .pr1-l { padding-right: .25rem; }
 .pr2-l { padding-right: .5rem; }
 .pr3-l { padding-right: 1rem; }
 .pr4-l { padding-right: 2rem; }
 .pr5-l { padding-right: 4rem; }
 .pr6-l { padding-right: 8rem; }
 .pr7-l { padding-right: 16rem; }
 .pb0-l { padding-bottom: 0; }
 .pb1-l { padding-bottom: .25rem; }
 .pb2-l { padding-bottom: .5rem; }
 .pb3-l { padding-bottom: 1rem; }
 .pb4-l { padding-bottom: 2rem; }
 .pb5-l { padding-bottom: 4rem; }
 .pb6-l { padding-bottom: 8rem; }
 .pb7-l { padding-bottom: 16rem; }
 .pt0-l { padding-top: 0; }
 .pt1-l { padding-top: .25rem; }
 .pt2-l { padding-top: .5rem; }
 .pt3-l { padding-top: 1rem; }
 .pt4-l { padding-top: 2rem; }
 .pt5-l { padding-top: 4rem; }
 .pt6-l { padding-top: 8rem; }
 .pt7-l { padding-top: 16rem; }
 .pv0-l { padding-top: 0; padding-bottom: 0; }
 .pv1-l { padding-top: .25rem; padding-bottom: .25rem; }
 .pv2-l { padding-top: .5rem; padding-bottom: .5rem; }
 .pv3-l { padding-top: 1rem; padding-bottom: 1rem; }
 .pv4-l { padding-top: 2rem; padding-bottom: 2rem; }
 .pv5-l { padding-top: 4rem; padding-bottom: 4rem; }
 .pv6-l { padding-top: 8rem; padding-bottom: 8rem; }
 .pv7-l { padding-top: 16rem; padding-bottom: 16rem; }
 .ph0-l { padding-left: 0; padding-right: 0; }
 .ph1-l { padding-left: .25rem; padding-right: .25rem; }
 .ph2-l { padding-left: .5rem; padding-right: .5rem; }
 .ph3-l { padding-left: 1rem; padding-right: 1rem; }
 .ph4-l { padding-left: 2rem; padding-right: 2rem; }
 .ph5-l { padding-left: 4rem; padding-right: 4rem; }
 .ph6-l { padding-left: 8rem; padding-right: 8rem; }
 .ph7-l { padding-left: 16rem; padding-right: 16rem; }
 .ma0-l { margin: 0; }
 .ma1-l { margin: .25rem; }
 .ma2-l { margin: .5rem; }
 .ma3-l { margin: 1rem; }
 .ma4-l { margin: 2rem; }
 .ma5-l { margin: 4rem; }
 .ma6-l { margin: 8rem; }
 .ma7-l { margin: 16rem; }
 .ml0-l { margin-left: 0; }
 .ml1-l { margin-left: .25rem; }
 .ml2-l { margin-left: .5rem; }
 .ml3-l { margin-left: 1rem; }
 .ml4-l { margin-left: 2rem; }
 .ml5-l { margin-left: 4rem; }
 .ml6-l { margin-left: 8rem; }
 .ml7-l { margin-left: 16rem; }
 .mr0-l { margin-right: 0; }
 .mr1-l { margin-right: .25rem; }
 .mr2-l { margin-right: .5rem; }
 .mr3-l { margin-right: 1rem; }
 .mr4-l { margin-right: 2rem; }
 .mr5-l { margin-right: 4rem; }
 .mr6-l { margin-right: 8rem; }
 .mr7-l { margin-right: 16rem; }
 .mb0-l { margin-bottom: 0; }
 .mb1-l { margin-bottom: .25rem; }
 .mb2-l { margin-bottom: .5rem; }
 .mb3-l { margin-bottom: 1rem; }
 .mb4-l { margin-bottom: 2rem; }
 .mb5-l { margin-bottom: 4rem; }
 .mb6-l { margin-bottom: 8rem; }
 .mb7-l { margin-bottom: 16rem; }
 .mt0-l { margin-top: 0; }
 .mt1-l { margin-top: .25rem; }
 .mt2-l { margin-top: .5rem; }
 .mt3-l { margin-top: 1rem; }
 .mt4-l { margin-top: 2rem; }
 .mt5-l { margin-top: 4rem; }
 .mt6-l { margin-top: 8rem; }
 .mt7-l { margin-top: 16rem; }
 .mv0-l { margin-top: 0; margin-bottom: 0; }
 .mv1-l { margin-top: .25rem; margin-bottom: .25rem; }
 .mv2-l { margin-top: .5rem; margin-bottom: .5rem; }
 .mv3-l { margin-top: 1rem; margin-bottom: 1rem; }
 .mv4-l { margin-top: 2rem; margin-bottom: 2rem; }
 .mv5-l { margin-top: 4rem; margin-bottom: 4rem; }
 .mv6-l { margin-top: 8rem; margin-bottom: 8rem; }
 .mv7-l { margin-top: 16rem; margin-bottom: 16rem; }
 .mh0-l { margin-left: 0; margin-right: 0; }
 .mh1-l { margin-left: .25rem; margin-right: .25rem; }
 .mh2-l { margin-left: .5rem; margin-right: .5rem; }
 .mh3-l { margin-left: 1rem; margin-right: 1rem; }
 .mh4-l { margin-left: 2rem; margin-right: 2rem; }
 .mh5-l { margin-left: 4rem; margin-right: 4rem; }
 .mh6-l { margin-left: 8rem; margin-right: 8rem; }
 .mh7-l { margin-left: 16rem; margin-right: 16rem; }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

ISC
