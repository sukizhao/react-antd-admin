## 基于React+antd实现后台模板
自己利用业余时间，基于React+antd写了一个后台管理模板。主要是熟悉antd组件和React，页面主要还是展示页面,比较简单不涉及后台交互。

github地址：[基于React+antd实现后台模板](https://github.com/sukizhao/react-antd-admin.git)  


启动项目：npm start 




### 技术栈

 - react
 - antd
 - react-router
 - mobx
 - canvas
 - ES6
 - cookie

自己参考了其他优秀的插件，比如[动态打字效果](https://blog.csdn.net/qq_37860930/article/details/80859473)、背景粒子效果、[shuffle（洗牌）](https://github.com/Vestride/Shuffle)，[全屏插件](https://github.com/sindresorhus/screenfull.js)等，自己对有些插件封装成类使用

所有路由都需要登录才可进入，自己封装了PrivateRoute组件来实现路由认证，登录信息保存在cookie中，原本是保存在store中，但是刷新页面后登录状态丢失，所以就保存在cookie中
登录背景图太大，使用了[TinyPNG](https://tinypng.com/)进行压缩，并编写了一个loading效果
<br/>

### 项目目录结构

<img src="https://github.com/zhangZhiHao1996/image-store/blob/master/react-admin-master/111.png?raw=true"/>
assets----存储静态图片资源和共用icon图标<br/>
components----存储共用组件<br/>
routes----业务页面入口和常用模板<br/> 
store----状态管理<br/>
utils----工具函数<br/>
<br/>





<br/>

`觉得不错的给个star鼓励支持！^_^`
