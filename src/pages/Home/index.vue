/*
 * Desc: 首页
 * File Created: Tuesday, 25th February 2020 2:55:02 pm
 * Author: huangfuchangyu (changyu.huangfu@tcl.com)
 */

<template>
  <div>
    <Header />
    <Menu />
    <section class="main-content">content   <el-button type="success">成功按钮</el-button></section>
  </div>
</template>

<script>
import Header from "../../components/Header";
import Menu from "../../components/Menu";

export default {
  name: "Home",
  components: {
    Header,
    Menu
  }
};
</script>

<style lang="scss" scoped>
@import "./index.scss";
</style>