# 📦 like-effects

[![License](https://img.shields.io/npm/l/oclif.svg)](https://github.com/oclif/oclif/blob/main/package.json)
<br><br>
Text and SVG icon effects preview.
<br>

![avatar](https://github.com/skayi/like-effects/blob/main/like-text.gif)
![avatar](https://github.com/skayi/like-effects/blob/main/like-svg.gif)

<br />

# 🗒 Description

Button `"Like"` or `"Heart"` click effects.
<br />
`Web component`.

<br />

# ✨ Features

1. Text effects
2. SVG icon effects
3. Custom width and slots
4. default checked

<br />

# 🔨 Installation

```
npm install like-effects --save
or
yarn add like-effects
```

## Import

Install the component :

```javascript
import 'like-effects'
or
require('like-effects')

DOM: <like-effects></like-effects>
```

<br/>

# 🏗 Usage

default :

```javascript
<like-effects></like-effects>
```

custom :

```javascript
<like-effects width="40px" checked="true|false">
  <span slot="unchecked" style="color: gray">
    like
  </span>
  <span slot="checked" style="color: orange">
    like
  </span>
</like-effects>
```
