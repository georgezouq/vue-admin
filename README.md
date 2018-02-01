# Vue Admin

This is a vue admin start kit with ElementUI base on [taylorchen709's template](https://github.com/taylorchen709/vue-admin). We change the style and do some optimize.

### Getting start

``` bash
npm install
npm run dev
```

and then, open http://localhost:8081 at your browser

### Build as production

```bash
npm run build
```

##  Folder structure

* build - webpack config files
* config - webpack config files
* dist - build
* src -your app
    * api
    * assets
    * common
    * components - your vue components
    * mock
    * styles
    * views - your pages
    * vuex
    * App.vue
    * main.js - main file
    * routes.js
* static - static assets

# Theme

You can change theme by 
1. Generate theme packages by [https://elementui.github.io/theme-preview/#/](https://elementui.github.io/theme-preview/#/)
2. Put theme packages in src/assets/theme/
3. Edit src/main.js 
``` bash
   import 'element-ui/lib/theme-default/index.css'
   to
   import './assets/theme/your-theme/index.css'
```
4. Edit src/styles/vars.scss

![theme-blue](https://raw.githubusercontent.com/taylorchen709/markdown-images/master/vueadmin/rec-demo.gif)
![theme-green](https://raw.githubusercontent.com/taylorchen709/markdown-images/master/vueadmin/theme-green.png)

# Browser support

Modern browsers and IE 10+.

# License
[MIT](http://opensource.org/licenses/MIT)
