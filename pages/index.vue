<template>
  <div>
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

    <el-container style="background: #fafafa">
      <el-row>
        <el-col span="12">
          <el-main>
            <h2>AdvertKit</h2>
            <p style="margin-top: 20px">
              A powerful alternative to Facebook Ads Manager. Manage, monitor and optimize
              you ads on Facebook Ads platform from a single place. User can create split ads
              with the intuitive and powerful interface. Track the progress of an ad using goals,
              group similar campaing into campaign groups. Use advanced rules engine to automate
              boring and manual tasks.
            </p>
            <h5 style="margin-top: 15px">Technology</h5>
            <p style="margin-top: 15px">
              AdvertKit is built using Ruby on Rails as the backend, Postgresql as the database
              and React.js on the
              frontend. It makes use of Bootstrap as the CSS framework. The site is designed
              to be responsive on different mobile devices. It integrates very closly with Facebook
              API. It is deployed on Heroku
            </p>
          </el-main>
        </el-col>
        <el-col span="12">
        </el-col>
      </el-row>
    </el-container>
  </div>
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
