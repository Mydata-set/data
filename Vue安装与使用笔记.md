### 1 安装脚手架		-g 安装全局的 平常都安装局部的
## npm install vue-cli	2.x的版本
## npm install @vue/cli 	3.x的版本

### 2 安装脚手架 2.x
## npm install vue-cli	 	1、（下载完毕

### 3使用Vue创建一个基础工程
## vue init webpack demo	2、（初始化完毕
#初始化一个工程webpack，工程的名称自己设置 {demo} 模板名称webpack
# 然后在脚手架页面 {buid} 打开工程{端口} npm run dev

### 讲解目录结构
## build -- 构建		打包配置
# webpack.base.config.js 基础的webpack配置
# webpack.dev.config.js  devlef开发时候的配置
# webpack.prod.config.js 最终生成产品时候的配置

## config -- 打包环境的配置
## node_modules -- 所有依赖包存放的文件夹
## src -- 源代码
#  assets -- 资源
#  components -- 组件
#  router -- 路由表
#  App.vue -- 根组件
#  main.js -- 入口js文件
#  static -- 静态存储文件
.gitkeep -- 让空文件夹可以上传到远程代码存放库里github

## test -- 测试
# e2e -- 测试驱动开发
# unit -- 单元测试

## .babelrc -- 翻译ES6、7、8...的配置文件
## .editorconfig -- 编辑者的配置 indent_				size = 2  一个Tab键两个空格
## .eslintrc.js -- 约束代码配置
## .gitignore -- 忽略哪些代码不被上传提交

##### package -- 包工程管理文件
###   scripts -- 脚本里面有一个 start
# 	  start 就是执行 dev 里面的内容

##### 开始写代码
### 在component文件下的vue文件里写代码
## 在Vscode安装工具内 安装一个插件ESlint 来约束代码 {语法空格很严格}

##### 然后在file > Preferences > Settings > User Settings > Edit in settings.json里面加上一段数据
#	"eslint.autoFixOnSave": true,
    "eslint.validate": [
        "javascript",{
            "language": "vue",
            "autoFix": true
        },"html",
        "vue"
    ],
    "window.zoomLevel": 0,
<!-- ------------------------------ -->

### 组件之间的链接