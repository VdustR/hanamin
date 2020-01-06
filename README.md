# 花園フォント

A webfont repository for Hanamin.

- Original font: <https://fonts.jp/hanazono/>

- Split with [font-splitter](https://github.com/VdustR/font-splitter)

- Minify with [clean-css-cli](https://github.com/jakubpawlowicz/clean-css-cli)

  ```bash
  cleancss --source-map -o HanaMin.min.css HanaMin.css
  ```

## Online Demo

<https://codesandbox.io/embed/hanamin-demo-uo5ez>

## Usage

```css
body {
  font-family: HanaMin;
}
```

### With Pre-processor

Install `hanamin`:

```sh
npm i hanamin
# or install it with yarn
yarn add hanamin
```

And import it in js:

```js
import "hanamin";
```

or in css:

```css
@import "~hanamin";
```

### With CDN

jsDelivr npm:

```html
<link
  rel="stylesheet"
  type="text/css"
  href="https://cdn.jsdelivr.net/npm/hanamin/HanaMin.min.css"
/>
```

jsDelivr GitHub:

```html
<link
  rel="stylesheet"
  type="text/css"
  href="https://cdn.jsdelivr.net/gh/vdustr/hanamin/HanaMin.min.css"
/>
```

UNPKG:

```html
<link rel="stylesheet" type="text/css" href="https://unpkg.com/hanamin" />
```
