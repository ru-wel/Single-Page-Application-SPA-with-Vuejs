<template>
  <div id="app">
    <img src="./assets/oikawa.png">
    <h1>{{ msg }}</h1>
    <about-us></about-us>
    <profile></profile>
    <education></education>
    <skills></skills>
  </div>
</template>

<script>

import AboutUs from './components/AboutUs.vue';
import profile from './components/profile.vue';
import education from './components/education.vue';
import skills from './components/skills.vue';

export default {
  name: 'app',
  components: {
    AboutUs,
    profile,
    education,
    skills
  },
  data () {
    return {
      msg: "This is Reuel's SPA for Vue.js"
    }
  }
}

</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}

#profile span{
  font-weight: bolder;
}

.resume .resume-title {
  font-size: 26px;
  font-weight: 400;
  margin-top: 20px;
  margin-bottom: 20px;
  color: #222222;
}

.resume .resume-item {
  padding: 0 0 20px 20px;
  margin-top: -2px;
  border-left: 2px solid #34b7a7;
  position: relative;
  text-align: left;
}

.resume .resume-item h4 {
  line-height: 18px;
  font-size: 18px;
  font-weight: 600;
  font-family: "Poppins", sans-serif;
  color: #1d685f;
  margin-bottom: 10px;
}

.resume .resume-item h5 {
  font-size: 16px;
  background: #effbf9;
  padding: 5px 15px;
  display: inline-block;
  font-weight: 600;
  margin-bottom: 10px;
  color: #34b7a7;
}

.resume .resume-item ul {
  padding-left: 20px;
}

.resume .resume-item ul li {
  padding-bottom: 10px;
}

.resume .resume-item:last-child {
  padding-bottom: 0;
}

.resume .resume-item::before {
  content: "";
  position: absolute;
  width: 16px;
  height: 16px;
  border-radius: 50px;
  left: -9px;
  top: 0;
  background: #fff;
  border: 2px solid #34b7a7;
}
</style>
