# React Progress Bar Plus

Progress bar component for ReactJS.

[<img src="./screen-shot.png" width="100%"/>](http://vn38minhtran.github.io/react-progress-bar-plus)

## Installation

```bash
npm install --save react-progress-bar-plus
```

## Usage

### JS

```js
var ProgressBar = require('react-progress-bar-plus');

var percent = 0;

<ProgressBar percent={10}/>
```

### CSS

**Webpack:**

```js
require('react-progress-bar-plus/lib/progress-bar.css');
```

**Without Webpack:**

```html
<link rel="stylesheet" type="text/css" href="path/to/react-progress-bar-plus/lib/progress-bar.css">
```

## Props
| Name | Type | Default | Description |
|------|------|---------|-------------|
| percent | number | -1 | Progress percent |
| onTop | bool | false | Progrees bar will ontop & height 100% |
| autoIncrement | bool | false | if `true` percent will auto increment `Math.random() + 1 - Math.random()`% in `intervalTime` ms. |
| intervalTime | number | 200 | Interval time for auto increment. |

## Example

View [demo](http://vn38minhtran.github.io/react-progress-bar-plus) or example folder.
