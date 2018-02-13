# gl-react-hue-rotate ![](https://img.shields.io/npm/v/gl-react-hue-rotate.svg) ![](https://img.shields.io/badge/gl--react-3-05F561.svg) ![](https://img.shields.io/badge/gl--react-dom%20%7C%20native-f90.svg)

[Universal](https://projectseptemberinc.gitbooks.io/gl-react/content/docs/universal.html) gl-react **Hue Rotate effect**

## Props

* `children` **(required)**: the content to hue-rotate.
* `hue` **(required)**: the hue rotation in radian.

## Usage Examples

```js
var HueRotate = require("gl-react-hue-rotate").HueRotate;
// or
import { HueRotate } from "gl-react-hue-rotate";
```

```html
<HueRotate hue={Math.PI}>...</HueRotate>
```
