<!--
 * @Author: jiashuangxi
 * @Date: 2020-12-23 09:48:24
 * @LastEditors: jiashuangxi
 * @LastEditTime: 2021-12-22 20:27:35
 * @Describe: 
-->
<template>
  <div>
  <el-menu :router="true" mode="horizontal">
      <!--基座中可以放自己的路由-->
      <el-menu-item index="/">Home</el-menu-item> 
       <!--引用其他子应用-->
      <el-menu-item index="/vue">vue应用</el-menu-item>
      <el-menu-item index="/react">react应用</el-menu-item>
  </el-menu>
    <router-view ></router-view>
    <div id="vue"></div>
    <div id="react"></div>
  </div>
</template>
