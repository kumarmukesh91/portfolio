<template>
  <div>
    <!-- hero section -->
    <el-container class="content bg-white hero">
      <el-row class="hero-row">
        <el-col :md="{span: 18, offset: 3}" :sm="{span: 24, offset: 0}">
          <el-row :gutter="20">
            <el-col class="border-right large-fonts" :md="{span: 12}" :sm="24">
              <el-main>
                <h1>Ankit Singhaniya</h1>
                <h4>Full Stack Developer</h4>
                <div class="social">
                  <a target="_blank" href="//github.com/ankitsinghaniyaz" class="no-link-style">
                    <i class="icon-github"></i>
                  </a>
                  <a target="_blank" href="//twitter.com/aks0510" class="no-link-style">
                    <i class="icon-twitter"></i>
                  </a>
                  <a target="_blank" href="//linkedin.com/in/ankitsinghaniyaz" class="no-link-style">
                    <i class="icon-linkedin"></i>
                  </a>
                  <a target="_blank" href="http://classandobjects.com" class="no-link-style">
                    <i class="icon-globe"></i>
                  </a>
                </div>
              </el-main>
            </el-col>
            <el-col :md="{span: 12}" :sm="24" >
              <el-main class="m-t-10">
                <p>
                  Most of the times you will find me dabbling with some idea unless I am working hard to earn a livelihood.
                  To me, coding is an art, editor my canvas and keywords are my brush.
                  When inspiration strikes, I sit down to paint algorithms, which shall be maintained, extended and tested for the ages to come.
                </p>
              </el-main>
            </el-col>
          </el-row>
        </el-col>
      </el-row>
    </el-container>

    <!-- project 1 - advertkit -->
    <el-container class="content bg-light">
      <el-row>
        <el-col :md="{span: 18, offset: 3}" :sm="{span: 24, offset: 0}">
          <el-row :gutter="20">
            <el-col :md="{span: 12, push: 12}" :sm="24">
              <el-carousel class="m-t-30">
                <el-carousel-item>
                  <img class="carousal" src="~/assets/ak1.png" alt="">
                </el-carousel-item>
                <el-carousel-item>
                  <img class="carousal" src="~/assets/ak2.png" alt="">
                </el-carousel-item>
              </el-carousel>
            </el-col>
            <el-col :md="{span: 12, pull: 12}" :sm="24" >
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
                  <img class="logo-image" src="~/assets/rails_logo.png" alt="Ruby on Rails" title="Ruby on Rails" height="50">
                  <img class="logo-image" src="~/assets/react_logo.svg" alt="React.js" title="React.js" height="50">
                  <img class="logo-image" src="~/assets/bootstrap_logo.png" alt="Bootstrap CSS" title="Bootstrap CSS" height="45">
                  <img class="logo-image" src="~/assets/facebook_ads_logo.png" alt="Facebook API" title="Facebook API" height="50">
                  <img class="logo-image" src="~/assets/elasticsearch_logo.png" alt="Elasticsearch" title="Elasticsearch" height="50">
                  <img class="logo-image" src="~/assets/aws_logo.png" alt="AWS" title="AWS" height="50">
                </p>
              </el-main>
            </el-col>
          </el-row>
          <el-row type="flex" justify="center" class="m-t-10">
            <el-col :span="4">
              <a href="//www.advertkit.com" target="_blank">
                <el-button type="primary"> Go To The App </el-button>
              </a>
            </el-col>
          </el-row>
        </el-col>
      </el-row>
    </el-container>

    <!-- project 2 - formester -->
    <el-container class="content bg-white">
      <el-row>
        <el-col :md="{span: 18, offset: 3}" :sm="{span: 24, offset: 0}">
          <el-row :gutter="20">
            <el-col :md="{span: 12}" :sm="24">
              <el-carousel class="m-t-30">
                <el-carousel-item>
                  <img class="carousal" src="~/assets/fms1.png" alt="">
                </el-carousel-item>
                <el-carousel-item>
                  <img class="carousal" src="~/assets/fms2.png" alt="">
                </el-carousel-item>
                <el-carousel-item>
                  <img class="carousal" src="~/assets/fms3.png" alt="">
                </el-carousel-item>
              </el-carousel>
            </el-col>
            <el-col :md="{span: 12}" :sm="24" >
              <el-main>
                <h2>Formester</h2>
                <p style="margin-top: 20px">
                  A form backend as a service. It makes creating form endpoints for
                  websites very easy. It requires zero programming knowledge. The user
                  has the full control over the look and feel of the form. In Formester
                  validation, spam protection and integration with different CRMs are few clicks
                  away.
                </p>
                <h5 style="margin-top: 15px">Technology</h5>
                <p style="margin-top: 15px">
                  Formester is built using Ruby on Rails as the backend and powerful Vue.js
                  on the frontend. The database is powered by Postgresql. It integrates with Zapier
                  to provide different integrations. Formester makes use of
                  Google recaptcha to provide spam protection.
                </p>
                <p style="margin-top: 15px">
                  <img class="logo-image" title="Ruby on Rails" src="~/assets/rails_logo.png" alt="" height="50">
                  <img class="logo-image" title="Vue js" src="~/assets/vuejs_logo.png" alt="" height="50">
                  <img class="logo-image" title="Heroku" src="~/assets/heroku_logo.svg" alt="" height="50">
                  <img class="logo-image" title="Zapier integrations" src="~/assets/zapier_logo.svg" alt="" height="50">
                  <img class="logo-image" title="Google recaptcha" src="~/assets/recaptcha_logo.png" alt="" height="50">
                  <img class="logo-image" title="Bootstrap css framework" src="~/assets/bootstrap_logo.png" alt="" height="45">
                </p>
              </el-main>
            </el-col>
          </el-row>
          <el-row type="flex" justify="center" class="m-t-10">
            <el-col :span="4">
              <a href="https://alternativeto.net/software/formester/" target="_blank">
                <el-button type="primary"> Know More </el-button>
              </a>
            </el-col>
          </el-row>
        </el-col>
      </el-row>
    </el-container>

    <!-- project 3 - shareito -->
    <el-container class="content bg-light">
      <el-row>
        <el-col :md="{span: 18, offset: 3}" :sm="{span: 24, offset: 0}">
          <el-row :gutter="20">
            <el-col :md="{span: 12, push: 12}" :sm="24">
              <el-carousel class="m-t-30">
                <el-carousel-item>
                  <img class="carousal" src="~/assets/sto1.png" alt="">
                </el-carousel-item>
                <el-carousel-item>
                  <img class="carousal" src="~/assets/sto2.png" alt="">
                </el-carousel-item>
              </el-carousel>
            </el-col>
            <el-col :md="{span: 12, pull: 12}" :sm="24" >
              <el-main>
                <h2>Shareito</h2>
                <p style="margin-top: 20px">
                  Organizations today rely on multiple software running in the cloud.
                  Sharing access to contributors and stakeholders can be very challenging.
                  Shareito provides a central place to manage this.
                  It helps keep track of suspicious activities, ensures strong password usage and optional 2-factor authentication.
                </p>
                <h5 style="margin-top: 15px">Technology</h5>
                <p style="margin-top: 15px">
                  Shareito uses Rails for RESTful API, Vue.js for user interfaces and Postgresql for the database.
                  It integrates with 10+ 3rd party APIs currently. Hundred more to come soon.
                </p>
                <p style="margin-top: 15px">
                  <img class="logo-image" title="Ruby on Rails" src="~/assets/rails_logo.png" alt="" height="50">
                  <img class="logo-image" title="Vue js" src="~/assets/vuejs_logo.png" alt="" height="50">
                  <img class="logo-image" title="Heroku" src="~/assets/heroku_logo.svg" alt="" height="50">
                  <img class="logo-image" title="Postgresql" src="~/assets/postgres_logo.png" alt="" height="60">
                </p>
              </el-main>
            </el-col>
          </el-row>
          <el-row type="flex" justify="center" class="m-t-10">
            <el-col :span="4">
              <a href="https://beta.shareito.com/" target="_blank">
                <el-button type="primary">Know More</el-button>
              </a>
            </el-col>
          </el-row>
        </el-col>
      </el-row>
    </el-container>

    <!-- More Projects -->
    <el-container class="content bg-white">
      <el-row>
        <el-col :md="{span: 18, offset: 3}" :sm="{span: 24, offset: 0}">
          <el-row>
            <el-col :md="12" :sm="24">
              <el-main>
                <div class="title">
                  <h2 class="text">
                    Selectom
                  </h2>
                  <img class="logo-image" src="~/assets/selectom_logo.png" title="Android application" alt="Android" height="50">
                </div>
                <p style="margin-top: 20px">
                  Selectom is a smart marketing platform that connects growing businesses with top marketers.
                  It helps the business choose the right marketing agency or freelancer based on their past performance.
                  Making data-driven decision making a reality.
                </p>
                <h5 style="margin-top: 15px">Technology</h5>
                <p style="margin-top: 15px">
                  Selectom has a micro-service architecture and uses home brewed Python micro-service framework.
                  MySQL and Redis are used as the persistence layer.
                  It relies heavily on automated BDD testing via Cucumber.
                </p>
                <p style="margin-top: 15px">
                  <img class="logo-image" src="~/assets/python_logo.png" title="Python" alt="Python" height="45">
                  <img class="logo-image" src="~/assets/redis_logo.svg" title="Redis" alt="Redis" height="50">
                  <img class="logo-image" src="~/assets/mysql_logo.png" title="MySql" alt="MySql" height="50">
                  <img class="logo-image" src="~/assets/cucumber_logo.svg" title="Cucumber" alt="Cucumber" height="50">
                </p>

                <el-row>
                  <el-col class="center" style="margin-top: 25px">
                    <a href="http://www.selectom.com/" target="_blank">
                      <el-button type="primary"> Go To The App </el-button>
                    </a>
                  </el-col>
                </el-row>
              </el-main>
            </el-col>
            <el-col :md="12" :sm="24">
              <el-main>
                <div class="title">
                  <h2 class="text">
                    Organized Effort
                  </h2>
                  <img class="logo-image" src="~/assets/oe_logo.svg" title="Android application" alt="Android" height="50">
                </div>
                <p style="margin-top: 20px">
                  Organized Effort makes collaboration on open projects easy.
                  It allows organizers to easily create, share and track work.
                  Step by step onboarding for contributors and a lot more.
                  Provides an iOS and a progressive web application for other devices.
                </p>
                <h5 style="margin-top: 15px">Technology</h5>
                <p style="margin-top: 15px">
                  The progressive web application made using Vue.js
                  It makes use of Vuex for state management and Vue-Router for routing.
                  It uses Vuetify as the CSS framework, which provides material design capabilities.
                </p>
                <p style="margin-top: 15px">
                  <img class="logo-image" src="~/assets/vuejs_logo.png" title="Android application" alt="Android" height="50">
                  <img class="logo-image" src="~/assets/aws_logo.png" alt="" height="50">
                  <img class="logo-image" src="~/assets/webpack_logo.svg" title="Webpack" alt="Webpack" height="60">
                  <img class="logo-image" src="~/assets/vuetify_logo.png" title="Vuetify" alt="Vuetify" height="60">
                </p>

                <el-row>
                  <el-col class="center" style="margin-top: 25px">
                    <a href="https://app.organizedeffort.com" target="_blank">
                      <el-button type="primary"> Go To The App </el-button>
                    </a>
                  </el-col>
                </el-row>
              </el-main>
            </el-col>
          </el-row>
        </el-col>
      </el-row>
    </el-container>
    <el-container class="content bg-light">
      <el-row>
        <el-col :md="{span: 18, offset: 3}" :sm="{span: 24, offset: 0}">
          <el-row>
            <el-col :md="12" :sm="24">
              <el-main>
                <div class="title">
                  <h2 class="text">
                    Cognisight
                  </h2>
                  <img class="logo-image" src="~/assets/cognisight_logo.svg" title="Android application" alt="Android" height="50">
                </div>
                <p style="margin-top: 20px">
                  Cognisight is transforming the way we access and analyze the business data.
                  It makes of machine learning and artificial intelligence to provide a natural language interface for exploring business data.
                  The consumer can use natural English sentences to search deeply correlated data, which is a lot of manual SQL when done ad-hoc.
                </p>
                <h5 style="margin-top: 15px">Technology</h5>
                <p style="margin-top: 15px">
                  Quotes scrapper was built using Python. Then I built the native Android app using Java.
                  The free stock images served through AWS S3. The application is hosted on Android
                  Play Store.
                </p>
                <p style="margin-top: 15px">
                  <img class="logo-image" src="~/assets/react_logo.svg" title="React" alt="React" height="50">
                  <img class="logo-image" src="~/assets/redux_logo.png" title="Redux" alt="Redux" height="50">
                </p>

                <el-row>
                  <el-col class="center" style="margin-top: 25px">
                    <a href="https://www.cognisight.io/" target="_blank">
                      <el-button type="primary"> Know More </el-button>
                    </a>
                  </el-col>
                </el-row>
              </el-main>
            </el-col>
            <el-col :md="12" :sm="24">
              <el-main>
                <div class="title">
                  <h2 class="text">
                    Quoted
                  </h2>
                  <img class="logo-image" src="~/assets/quoted_logo.png" title="Android application" alt="Android" height="50">
                </div>
                <p style="margin-top: 20px">
                  There are many quotes app on the store but none of them where good enough for my need.
                  So I set out to build an app which will be easy to use and customizable. The main
                  goal was to explore new quotes and inspirations from great minds around the globe. It has
                  around 15k+ downloads today on the play store.
                </p>
                <h5 style="margin-top: 15px">Technology</h5>
                <p style="margin-top: 15px">
                  Quotes scrapper was built using Python. Then I built the native Android app using Java.
                  The free stock images served through AWS S3. The application is hosted on Android
                  Play Store.
                </p>
                <p style="margin-top: 15px">
                  <img class="logo-image" src="~/assets/android_logo.png" title="Android application" alt="Android" height="50">
                  <img class="logo-image" src="~/assets/java_logo.svg" title="Java" alt="Java" height="50">
                  <img class="logo-image" src="~/assets/python_logo.png" title="Python" alt="Python" height="45">
                  <img class="logo-image" src="~/assets/aws_logo.png" alt="" height="50">
                </p>

                <el-row>
                  <el-col class="center" style="margin-top: 25px">
                    <a href="https://play.google.com/store/apps/details?id=com.classandobjects.quoted" target="_blank">
                      <el-button type="primary"> Go To The App </el-button>
                    </a>
                  </el-col>
                </el-row>
              </el-main>
            </el-col>
          </el-row>
        </el-col>
      </el-row>
    </el-container>

    <!-- recent posts -->
    <el-container class="content bg-white">
      <el-row>
        <el-col :md="{span: 18, offset: 3}" :sm="{span: 24, offset: 0}">
          <el-main>
            <el-row>
              <el-col>
                  <h2>Most Viewed Posts</h2>
              </el-col>
            </el-row>
            <el-row :gutter="20" class="m-t-20">
              <el-col :md="8" :sm="12" :xs="24">
                <el-card class="post-card">
                  <h4>Problem With React Single Page App</h4>
                  <p class="m-t-10">
                    React is awesome, but the choices to create a single page app with react has challenges.
                    Here I share the issues I faced when creating a react SPA.
                  </p>
                  <a href="http://classandobjects.com/tutorial/problems_with_react_single_page_app/">
                    <el-button type="text">
                      Read More
                    </el-button>
                  </a>
                </el-card>
              </el-col>
              <el-col :md="8" :sm="12" :xs="24">
                <el-card class="post-card">
                  <h4>Create Bottom Toolbar Like Google Plus Android</h4>
                  <p class="m-t-10">
                    Creating an Android toolbar can be sometimes challenging.
                    Create a bottom toolbar like google plus with button feedback, touch effects and lot more.
                  </p>
                  <a href="http://classandobjects.com/tutorial/create_google_plus_like_toolbar_android/">
                    <el-button type="text">
                      Read More
                    </el-button>
                  </a>
                </el-card>
              </el-col>
              <el-col :md="8" :sm="12" :xs="24">
                <el-card class="post-card">
                  <h4>The Zen of Form Validation</h4>
                  <p class="m-t-10">
                    There are so many ways to validate form and inputs. What is the right way to do it?
                    Validation gets even more complicated with React js, here is what I do
                  </p>
                  <a href="http://classandobjects.com/right_form_validation_in_react/">
                    <el-button type="text">
                      Read More
                    </el-button>
                  </a>
                </el-card>
              </el-col>
            </el-row>
            <el-row type="flex" justify="center" class="m-t-30">
              <el-col :span="4">
                <a href="//classandobjects.com" target="_blank">
                  <el-button type="primary"> See All Posts </el-button>
                </a>
              </el-col>
            </el-row>
          </el-main>
        </el-col>
      </el-row>
    </el-container>

    <!-- contact section -->
    <el-container class="content bg-light center">
      <el-row>
        <el-col :span="24">
          <p>
            <h3>I'm available for work, get in touch</h3>
          </p>
          <p class="m-t-20" style="">
            <strong>
              ankit.singhaniyaz @ gmail
            </strong>
          </p>
        </el-col>
      </el-row>
    </el-container>
  </div>
</template>

<script>
import Vue from 'vue'
import ElementUI from 'element-ui'
// import 'element-ui/lib/theme-chalk/index.css'

import Logo from '~/components/Logo.vue'

Vue.use(ElementUI)

export default {
  components: {
    Logo
  }
}
</script>

<style>
p {
  line-height: 1.5;
  color: #696969;
}

.description {
  font-size: 1.5em;
  margin-left: 10px;
  padding: 20px 0;
}

.center {
  text-align: center;
  justify-content: center;
}

.hero {
  /* height: 100vh; */
  /* min-height: ; */
  margin: 50px 0;
  width: 100%;
}

.large-fonts {
  font-size: 1.5em;
}

.hero-row {
  width: 100%;
}

.border-right {
  border-right: #eee 1px solid;
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

.content {
  padding: 20px 0;
  /* margin: 10px; */
}

.post-card {
  margin-top: 10px;
  min-height: 250px;
}

.m-t-30 {
  margin-top: 30px;
}

.m-t-20 {
  margin-top: 20px;
}

.m-t-10 {
  margin-top: 10px;
}

.center {
  text-align: center;
  margin: auto;
}

.carousal {
  width: 100%;
  height: 100%;
}

.hero-image {
  border-radius: 50%;
  width: 250px;
  height: 250px;
}

.no-link-style {
  text-decoration: inherit;
  color: inherit;
  padding-right: 15px;
}

.social {
  margin-top: 10px;
}

.title {
  display: flex;
  align-items: center;
}

.title .text {
  padding-top: 20px
}
</style>
