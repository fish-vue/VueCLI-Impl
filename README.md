# vue-cli
vue-cli 能让我们快速的搭建vue开发环境

## 基本使用

``` bash
# 创建名称为vue-cli的项目
$ vue create vue-cli

# 安装依赖
$ npm install

# 开启调试环境
$ npm run serve

# 打包构建
$ npm run build
# vue-cli-service build --modern
# 这个参数可以让编译中不再兼容太不支持es2015的浏览器。提高了性能

# 开始测试
$ npm run test

# 代码风格测试
npm run lint
```


## 安装
``` bash
# 全局安装脚手架
$ npm install -g @vue/cli
$ sudo npm install -g @vue/cli

# 查看安装版本
$ vue -V
3.3.0
$ vue --version
3.3.0
# 本项目基于3.3.0测试的

# 这个模块可以让我们调试单个vue组件
$ npm install -g @vue/cli-service-global
$ vue serve ./src/App.vue
```
