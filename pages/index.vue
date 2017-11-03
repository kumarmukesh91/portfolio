<template>
  <div>
    <el-container>
      <el-row class="hero" justify="center" align="middle"  type="flex">
        <el-col span="12">
          <el-row>
            <el-col :md="8">
              <logo></logo>
            </el-col>
            <el-col :md="16">
              <div class="description">
                <h1 class="h1">Ankit Singhaniya</h1>
                <h3>Full Stack Developer</h3>
                <h6>
                  <a href="classandobjects.com">
                    classandobjects.com
                  </a>
                </h6>
              </div>
            </el-col>
          </el-row>

        </el-col>
      </el-row>
    </el-container>

    <el-container class="bg-light">
      <el-row>
        <el-col :md="{span: 18, offset: 3}" :sm="{span: 24, offset: 0}">
          <el-row>
            <el-col :md="12" :sm="24" >
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
                <p style="margin-top: 15px">
                  <img class="logo-image" src="~/assets/rails_logo.png" alt="" height="50">
                  <img class="logo-image" src="~/assets/react_logo.svg" alt="" height="50">
                  <img class="logo-image" src="~/assets/bootstrap_logo.png" alt="" height="45">
                  <img class="logo-image" src="~/assets/facebook_ads_logo.png" alt="" height="50">
                  <img class="logo-image" src="~/assets/elasticsearch_logo.png" alt="" height="50">
                  <img class="logo-image" src="~/assets/aws_logo.png" alt="" height="50">
                </p>
              </el-main>
            </el-col>
            <el-col :md="12" :sm="24">
              <el-carousel>
              </el-carousel>
            </el-col>
          </el-row>
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
  margin-left: 10px;
  padding: 20px;
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

.bg-light {
  background: #fafafa;
}

.bg-white {
  background: #fff;
}

.logo-image {
  margin-left: 20px;
  margin-top: 20px;
}
</style>
