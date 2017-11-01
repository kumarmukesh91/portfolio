<template>
  <el-container>
    <el-row class="hero" justify="center" align="middle"  type="flex">
      <div class="logo">
        <logo></logo>
        <img src="#"/>
      </div>
      <div class="description">
        <h1 class="h1">Ankit Singhaniya</h1>
        <h3>Full Stack Developer</h3>
        <h6>
          <a href="classandobjects.com">
            classandobjects.com
          </a>
        </h6>
      </div>
    </el-row>
  </el-container>
</template>

<script>
import Vue from 'vue'

import ElementUI from 'element-ui'
import 'element-ui/lib/theme-chalk/index.css'

import Logo from '~/components/Logo.vue'

Vue.use(ElementUI)

export default {
  components: {
    Logo
  }
}
</script>

<style>
.description {
  font-size: 2em;
  margin-left: 20px;
}

.center {
  text-align: center;
  justify-content: center;
}

.hero {
  height: 100vh;
  min-height: 500px;
  width: 100%; 
}
</style>
