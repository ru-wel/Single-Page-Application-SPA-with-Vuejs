<template>
  <div id="about-us">
    <br>
    <div id="todo-card">
        <div class="container">
            <div class="alert alert-primary" role="alert">
                <h1>{{ msg6 }}</h1>
            </div>
        </div>
    </div>

    <div class="container px-4 " id="featured-3" style="background-color: #F8EDE3;">
      <br>
      <div class="row g-4 py-5 row-cols-1 row-cols-lg-3">
        <div class="feature col">
          <h3 class="fs-2 text-body-emphasis">I am</h3>
        </div>
        <div class="feature col">
          <h3 class="fs-2 text-body-emphasis">a 3rd Year</h3>
        </div>
        <div class="feature col">
          <h3 class="fs-2 text-body-emphasis">Web Dev Student</h3>
        </div>
      </div>
    </div>
    <br>
  </div>
</template>

<script>
    export default {
        name: 'about-us',
        data(){
            return{
                msg6: 'This is the About component'
            }
        }
    }
</script>
