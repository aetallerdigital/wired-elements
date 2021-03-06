[![Published on Vaadin  Directory](https://img.shields.io/badge/Vaadin%20Directory-published-00b4f0.svg)](https://vaadin.com/directory/search?keyword=wiredjs)

# wired-elements 👉 [wiredjs.com](https://wiredjs.com)
Wired Elements is a series of basic UI Elements that have a hand drawn look. These can be used for wireframes, mockups, or just the fun hand-drawn look. 

![alt Preview](https://i.imgur.com/qttPllg.png)

The elements are drawn with enough randomness that no two renderings will be exactly the same - just like two separate hand drawn shapes. 

## Try now
Play with wired-elements on CodeSandbox:

[Wired Elements](https://codesandbox.io/s/p77jkn13nq)

#### Try it with a framework

[Wired Elements in React](https://codesandbox.io/embed/xrll5wyl8w)

[Wired Elements in Vue](https://codesandbox.io/embed/vj389y9375)


## Install

The package (wired-elements) exports all components in the **_wired_** category. List of all wired elements can be found [here](https://github.com/wiredjs/wired-elements/tree/master/packages).

Add wired-elements to your project:
```
npm i wired-elements
```
or individual controls
```
npm i wired-button
```

## Usage

Import into your module script:
```javascript
import { WiredButton, WiredInput } from "wired-elements"
```

Alternatively, load a bundled version from the [dist folder](https://github.com/wiredjs/wired-elements/tree/master/packages/all/dist) or from CDN:

```html
<script src="https://unpkg.com/wired-elements@latest/dist/wired-elements.bundled.min.js"></script>
```

#### Use it in your web page:
```html
<wired-input placeholder="Enter name"></wired-input>
<wired-button>Click Me</wired-button>
```

Learn about web components [here](https://www.webcomponents.org/introduction).

### Demo

Demo of all components is available at [wiredjs.com](https://wiredjs.com/showcase.html).

## Dev Environment

View the [Dev environment page](https://github.com/wiredjs/wired-elements/wiki/Dev-Environment) for instructions.

## License
[MIT License](https://github.com/wiredjs/wired-elements/blob/master/LICENSE) (c) [Preet Shihn](https://twitter.com/preetster)
