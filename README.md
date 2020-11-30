# display-flex-utility

A suite of flexbox utilities

## Installation

```
npm i display-flex-utility
```

## Usage

```scss
// example.scss

// Import scss
@import '~display-flex-utility';
```

```html
<!-- example.html -->
<div class="flex-cb flex-row-reverse">
  <div></div>
  <div></div>
</div>
```

## Custom

For example you want use `x` instead of `flex` as the prefix:

```scss
$display-flex-prefix: x;

// Import scss
@import '~display-flex-utility';
```

Also you could custom the short name map.

### All variables and default value

```scss
$display-flex-prefix: flex !default;

$flex-align-items-types: (
  s: flex-start,
  e: flex-end,
  c: center,
  l: baseline,
  h: stretch,
) !default;

$flex-justify-content-types: (
  s: flex-start,
  e: flex-end,
  c: center,
  b: space-between,
  a: space-around,
  v: space-evenly,
) !default;

$flex-align-content-types: (
  s: flex-start,
  e: flex-end,
  c: center,
  b: space-between,
  a: space-around,
  h: stretch,
) !default;
```

## Build to css

```bash
# output file is css/index.css
npm run build
```

### `index.css`

```css
.flex-hv,
.flex-ha,
.flex-hb,
.flex-hc,
.flex-he,
.flex-hs,
.flex-lv,
.flex-la,
.flex-lb,
.flex-lc,
.flex-le,
.flex-ls,
.flex-cv,
.flex-ca,
.flex-cb,
.flex-cc,
.flex-ce,
.flex-cs,
.flex-ev,
.flex-ea,
.flex-eb,
.flex-ec,
.flex-ee,
.flex-es,
.flex-sv,
.flex-sa,
.flex-sb,
.flex-sc,
.flex-se,
.flex-ss,
.flex {
  display: flex;
}
.flex-ss {
  align-items: flex-start;
  justify-content: flex-start;
}
.flex-se {
  align-items: flex-start;
  justify-content: flex-end;
}
.flex-sc {
  align-items: flex-start;
  justify-content: center;
}
.flex-sb {
  align-items: flex-start;
  justify-content: space-between;
}
.flex-sa {
  align-items: flex-start;
  justify-content: space-around;
}
.flex-sv {
  align-items: flex-start;
  justify-content: space-evenly;
}
.flex-es {
  align-items: flex-end;
  justify-content: flex-start;
}
.flex-ee {
  align-items: flex-end;
  justify-content: flex-end;
}
.flex-ec {
  align-items: flex-end;
  justify-content: center;
}
.flex-eb {
  align-items: flex-end;
  justify-content: space-between;
}
.flex-ea {
  align-items: flex-end;
  justify-content: space-around;
}
.flex-ev {
  align-items: flex-end;
  justify-content: space-evenly;
}
.flex-cs {
  align-items: center;
  justify-content: flex-start;
}
.flex-ce {
  align-items: center;
  justify-content: flex-end;
}
.flex-cc {
  align-items: center;
  justify-content: center;
}
.flex-cb {
  align-items: center;
  justify-content: space-between;
}
.flex-ca {
  align-items: center;
  justify-content: space-around;
}
.flex-cv {
  align-items: center;
  justify-content: space-evenly;
}
.flex-ls {
  align-items: baseline;
  justify-content: flex-start;
}
.flex-le {
  align-items: baseline;
  justify-content: flex-end;
}
.flex-lc {
  align-items: baseline;
  justify-content: center;
}
.flex-lb {
  align-items: baseline;
  justify-content: space-between;
}
.flex-la {
  align-items: baseline;
  justify-content: space-around;
}
.flex-lv {
  align-items: baseline;
  justify-content: space-evenly;
}
.flex-hs {
  align-items: stretch;
  justify-content: flex-start;
}
.flex-he {
  align-items: stretch;
  justify-content: flex-end;
}
.flex-hc {
  align-items: stretch;
  justify-content: center;
}
.flex-hb {
  align-items: stretch;
  justify-content: space-between;
}
.flex-ha {
  align-items: stretch;
  justify-content: space-around;
}
.flex-hv {
  align-items: stretch;
  justify-content: space-evenly;
}
.flex-ac-s {
  align-content: flex-start;
}
.flex-ac-e {
  align-content: flex-end;
}
.flex-ac-c {
  align-content: center;
}
.flex-ac-b {
  align-content: space-between;
}
.flex-ac-a {
  align-content: space-around;
}
.flex-ac-h {
  align-content: stretch;
}
.flex-wrap {
  flex-wrap: wrap;
}
.flex-nowrap {
  flex-wrap: nowrap;
}
.flex-wrap-reverse {
  flex-wrap: wrap-reverse;
}
.flex-row {
  flex-direction: row;
}
.flex-row-reverse {
  flex-direction: row-reverse;
}
.flex-column {
  flex-direction: column;
}
.flex-column-reverse {
  flex-direction: column-reverse;
}
```
