# Vuestic 분석
 - No jQuery
 - Reactive(Page)
 - CSS : bootstrap4
 - table : vuetable-2
   -. paging / filtering / sorting 등
 - form
   -. React와 달리 form validator 가 제공되지 않는다고 함
    -> vee-validate 플러그인이 설치되어 있음
 
 * 기타
 - docker 확장이 가능하도록 되어 있음
 - express 가 설치되어 있음
 - chat플랫폼(Drift) 설치되어 있음

# json Server

- 설치

```bash
$ npm install -g json-server
```
- 실행
```bash
$ json-server --watch db.json --middlewares singular.js
```
# Vuestic Admin Dashboard

Responsive admin dashboard template built with [Vue.js](https://vuejs.org) and [Bootstrap 4](https://v4-alpha.getbootstrap.com). Developed by [Epicmax](https://epicmax.co). Designed by [Vasili Savitski](https://xxsavitski.myportfolio.com/)

Subscribe to our [newsletter](https://epicmax.co/newsletter) to get Vuestic updates, our team's stories and Vue.js materials hand-picked by Epicmax.

git [url](https://github.com/epicmaxco/vuestic-admin)

## Demo
Check it out [live](https://vuestic.epicmax.co)!

## Prerequisites:

- [Node.js](https://nodejs.org/en/) (at least 4.x, 8.x recommended)
- npm version 3+ and [Git](https://git-scm.com/).
- [vuestic-installer](https://github.com/epicmaxco/vuestic-installer) `npm install vuestic-installer -g`.

## Browser Support
* Latest Chrome, Firefox, Safari, Edge, IE11+

## Installation

vue-cli3 has to be installed globally. If it's not, do:

```bash
$ npm install -g @vue/cli
# OR
$ yarn global add @vue/cli
```

You can create vuestic project via installer:

``` bash
# create new project via vuestic-installer command.
$ vuestic myproject

```

or just by cloning repo:  

```

# clone the repo
$ git clone https://github.com/epicmaxco/vuestic-admin.git myproject

# go into app's directory and install dependencies:
$ cd myproject
$ npm install

# serve with hot reload at localhost:8080.
$ npm run serve

# build for production with minification
$ npm run build

# build for production and view the bundle analyzer report.
$ npm run build --report
```

## Documentation

Got stuck? Check out our [documentation](https://github.com/epicmaxco/vuestic-admin/wiki) 🤓

## Features
* Vue.js
* Bootstrap 4
* Webpack
* Responsive layout
* Charts (Chart.js)
* Maps (Google, Leaflet, amMap)
* Progress bars
* Material forms with beautiful validation
* 4 Form wizard types
* Static tables and datatables
* Login/signup pages templates
* Medium editor
* Toasts, tooltips, popovers,
* i18n
* and many more!


## How can I support developers?
- Star our GitHub repo :star:
- Create pull requests, submit bugs, suggest new features or documentation updates :wrench:
- Follow us on [Twitter](https://twitter.com/epicmaxco) :feet:
- Like our page on [Facebook](https://www.facebook.com/epicmaxco) :thumbsup:
- Subscribe to our [newsletter](https://epicmax.co/newsletter) :postbox:

## Can I hire you guys?
Yes!  Visit [our homepage](https://epicmax.co/) or simply leave us a message to [hello@epicmax.co](mailto:hello@epicmax.co). We will be happy to work with you!

## License
[MIT](https://github.com/epicmaxco/vuestic-admin/blob/master/LICENSE) license.