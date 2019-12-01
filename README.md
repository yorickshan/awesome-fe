# awesome-fe
awesome things related to frontend develop

## 工具选择

### Animation
- [velocity.js](https://github.com/julianshapiro/velocity)
- [animate.css](https://github.com/daneden/animate.css)
- [GSAP](https://github.com/greensock/GSAP)

### CSS
- [stylelint](https://stylelint.io/)
- [postcss](https://postcss.org/)
- [sass(scss)](https://sass-lang.com/)

### EScript
- [eslint](https://eslint.org/)
- [babel](https://babeljs.io/)
- [typescript](http://typescriptlang.org/)

### 代码风格
- husky
- prettier

### JS 压缩
- TerserJS

### CSS 压缩
- cssnano
  
### 静态文档
- docz
  
### 微前端
- qiankun

### 图表库
- antv
- echarts

### Enterprise Boilerplate
- [vue-enterprise-boilerplate](https://github.com/chrisvfritz/vue-enterprise-boilerplate)
- nuxt.js
- [umi](https://github.com/umijs/umi)
- next.js

### 国际化
- vue-i18n
- react-intl

### Node
- koa
- nest
- egg
- midway

### You-Dont-Need

- [You-Dont-Need-JavaScript](https://github.com/you-dont-need/You-Dont-Need-JavaScript)
- [You-Dont-Need-Lodash-Underscore](https://github.com/you-dont-need/You-Dont-Need-Lodash-Underscore)
- [You-Dont-Need-jQuery](https://github.com/nefe/You-Dont-Need-jQuery) & [youmightnotneedjquery](http://youmightnotneedjquery.com/)

- [You-Dont-Need-GUI](https://github.com/you-dont-need/You-Dont-Need-GUI)

### Unit Test
- [jest]
- enzyme
- puppteer
- jsdom

### Components & Libraries
- [swiper](https://github.com/nolimits4web/swiper)
- [vue-awesome-swiper](https://github.com/surmon-china/vue-awesome-swiper)
- [draggable](https://github.com/Shopify/draggable)
- [Vue.Draggable](https://github.com/SortableJS/Vue.Draggable)

## 技术栈选型

### 固定化
- React框架
- Typescript语言
- Less+Css Modules
- Eslint+Prettier+固定配置
- 固定数据流方案dva
- 固定babel插件
- Jest+Enzyme
- 框架版本不允许锁定，^前缀必须有
- 主要依赖不允许自定义依赖版本

### 配置化
- 不仅是框架功能，还有UI界面
- 路由，布局，菜单，导航，面包屑，权限，请求，埋点，错误处理
- 只管写Page页面就可以了

### 编译态配置
- 给node.js使用，比如webpack，babel相关配置，静态路由配置

### 运行态配置
- 给浏览器用，比如渲染逻辑，动态修改路由，获取用户信息

### 约定化
- 国际化
- 数据流
- MOCK
- 目录结构
- 404
- 权限策略
- Service
- 配置文件