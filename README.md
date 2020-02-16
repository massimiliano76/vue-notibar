<h1 align="center">Vue Notibar (Notification bar)</h1>

<p align="center">
	<a href="https://ci.appveyor.com/project/b-maslennikov/vue-notibar"><img alt="AppVeyor Build Status" src="https://img.shields.io/appveyor/build/b-maslennikov/vue-notibar/master?style=flat-square" /></a> 
	<a href="https://ci.appveyor.com/project/b-maslennikov/vue-notibar/build/tests"><img alt="AppVeyor Tests" src="https://img.shields.io/appveyor/tests/b-maslennikov/vue-notibar/master?style=flat-square" /></a>
	<a href="https://unpkg.com/vue-notibar/dist/vue-notibar.min.js"><img alt="Minimized fiel size" src="https://img.shields.io/github/size/b-maslennikov/vue-notibar/dist/vue-notibar.min.js?style=flat-square"></a>
	<a href="https://www.npmjs.com/package/vue-notibar"><img alt="Downloads per month" src="https://img.shields.io/npm/dm/vue-notibar?style=flat-square"></a>
	<a href="https://www.npmjs.com/package/vue-notibar"><img alt="Latest version" src="https://img.shields.io/npm/v/vue-notibar?style=flat-square"></a>
	<a href="https://www.npmjs.com/package/vue-notibar"><img alt="License" src="https://img.shields.io/npm/l/vue-notibar?style=flat-square"></a>
</p>

# Installation
Using npm
```shell
$ npm i vue-notibar
```

or CDN
```html
<script src="https://unpkg.com/vue/dist/vue.js"></script>
<script src="https://unpkg.com/vue-notibar/dist/vue-notibar.js"></script>
```

# Usage
```javascript
import Vue from 'vue'
import VueNotibar from 'vue-notibar'

Vue.use(VueNotibar, options)
```

## Default options
```javascript
{
	textColor: '#FFFFFF',
	backgroundColor: '#323232',
	time: 5000,
	position: 'center'
}
```

# Live demo
<a href="https://jsfiddle.net/tattdogg/gmnfqz98/" target="_blank">JSFiddle</a>