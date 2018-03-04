# vue-console

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).


#启动
1.npm start  所占用的端口号是localhost:8585;
2.
````shell
文件简介:
1.总文件夹名字叫:JeeSite
2.下面包含5个文件夹
3.config文件夹下面是webpack的跨域处理
  index.js中 proxyTable:{} 下配置,
  以/api代替http://localhost:8080/ibus-console,
4.src文件夹下面是所有的页面和共有js文件
5.assets是公共文件
  5.1 auth.js+http.js是关于token权限处理文件
6.components文件夹是所有页面的文件夹
7.router文件夹下面的Index.js文件夹是路由导航




