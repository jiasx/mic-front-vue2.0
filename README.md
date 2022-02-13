<!--
 * @Author: jiashuangxi
 * @Date: 2022-02-13 20:58:56
 * @LastEditors: jiashuangxi
 * @LastEditTime: 2022-02-13 21:09:08
 * @Describe: 
-->
# mic-front-vue2.0

*将普通的项目改造成 qiankun 主应用基座，需要进行三步操作： 
1、创建微应用容器 - 用于承载微应用，渲染显示微应用 
2、注册微应用 - 设置微应用激活条件，微应用地址等等； 
3、启动 qiankun； 
扩展：主应用不限技术栈，只需要提供一个容器 DOM，然后注册微应用并 start 即可。

主应用(基座)配置 react 2.6.10  
子应用配置 vue 2.6.10  
子应用配置 react 17.0.2