# alurapic

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```

For detailed explanation on how things work, consult the [docs for vue-loader](http://vuejs.github.io/vue-loader).

# Notes

```
npm install vue-cli -g
vue --version
vue init webpack-simple alurapic
cd alurapic
npm install
npm run dev
```

`Babel` = ECMAScript transpiler  
`Webpack` = Module bundler

`Interpolation`
- unidirectional data binding
- Not allow in tags attributes, like `src="{{ myData }}"`, instead we must use `v-bind:src="myData"` or `:src="myData"` with the data

Directives
 - v-for
 - v-bind

### API
```
cd api
npm start
```
http://localhost:3000/v1/fotos

No root
```
npm install vue-resource --save
```

https://vuejs.org/v2/api/#Options-Lifecycle-Hooks