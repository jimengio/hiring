
### 产品线

* 桌面端(管理后台, 数据分析)
* 移动端(工厂数据采集录入)
* 工控电脑(生产线数据采集)

### 开发环境

* TypeScript(VS Code)
* Webpack
* Jest
* Prettier

### 基础组件库

* React
* Immer
* Emotion(CSS)
* antd
* ECharts
* Lodash
* Momentjs/dayjs
* FontAwesome

部分业务用到 Threejs, qrcoder, ckeditor.

### 内部基础库和工具

* [Jasmin UI](https://github.com/jimengio/jasmin-ui) - 桌面端 UI
* [Mescal UI](https://github.com/jimengio/mescal-ui) - 采集端 UI
* [Meson Form](https://github.com/jimengio/meson-form) - 基于 Immer 定制的 Form 方案
* [Rex](https://github.com/jimengio/rex) - 数据层方案, 替代 Redux
* [ruled-router](https://github.com/jimengio/ruled-router) - 定制的深度嵌套路由方案
* [Jimo Icons](https://github.com/jimengio/jimo-icons/) - 图标库

项目基础选型大致可以看 [ts-workflow](https://github.com/jimengio/ts-workflow).

### 废弃中的技术

* mobx, mobx-state-tree, Redux(改用 Hooks)
* SASS(改用 Emotion)
* antd form(改用 meson-form)
