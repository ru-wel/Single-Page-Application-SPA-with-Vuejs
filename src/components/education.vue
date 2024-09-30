<template>
  <div id="education">
    <div id="todo-card">
        <div class="container">
            <div class="alert alert-primary" role="alert">
                <h1>{{ msg6 }}</h1>
            </div>
        </div>
    </div>

    <section id="resume" class="resume">
      <div class="container">
        <div class="row d-flex justify-content-center">
          <div class="col-lg-6">
            <h3 class="resume-title">Education</h3>
            <br>
            <div class="resume-item">
              <h4>Holy Family Academy</h4>
              <p><em>Elementary</em></p>
              <h5>2010 - 2016</h5>
              <p>Sto. Rosario Street, Angeles City, Philippines</p>
            </div>
            <div class="resume-item">
              <h4>Information and Communication Technology High School</h4>
              <p><em>Junior & Senior High School</em></p>
              <h5>2016 - 2022</h5>
              <p>Sindalan, MacArthur Hwy, San Fernando, Pampanga</p>
            </div>
            <div class="resume-item">
              <h4>Holy Angel University</h4>
              <p><em>College</em></p>
              <h5>2022 - Present</h5>
              <p>#1 Holy Angel St, Angeles City, Pampanga</p>
            </div>
          </div>
        </div>
      </div>
    </section>
    <br>
  </div>

  
</template>

<script>
    export default {
        name: 'education',
        data(){
            return{
                msg6: 'This is the Education Component'
            }
        }
    }
</script>
