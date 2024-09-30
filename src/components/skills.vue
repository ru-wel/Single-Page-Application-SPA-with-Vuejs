<template>
    <div id="skills">
        <div id="todo-card">
            <div class="container">
                <div class="alert alert-primary" role="alert">
                    <h1>{{ msg6 }}</h1>
                </div>
            </div>
        </div>

        <section id="resume" class="resume" style="padding-bottom: 20px;">
            <div class="container">
                <div class="row d-flex justify-content-center">
                    <div class="col-lg-6">
                        <h3 class="resume-title">Certifications</h3>
                        <br>
                        <div class="resume-item">
                            <h4>Comptia ITF+</h4>
                            <h5>2023</h5>
                        </div>
                        <div class="resume-item">
                            <h4>Cisco Certification in Introduction to Networks</h4>
                            <h5>2024</h5>
                        </div>
                        <div class="resume-item">
                            <h4>Cisco Certification in Cybersecurity Essentials</h4>
                            <h5>2024</h5>
                        </div>
                    </div>

                    <div class="col-lg-6">
                        <h3 class="resume-title">Programming Languages</h3>
                        <br>
                        <div class="resume-item">
                            <h4>Python</h4>
                        </div>
                        <div class="resume-item">
                            <h4>Java</h4>
                        </div>
                        <div class="resume-item">
                            <h4>HTML, CSS, JS</h4> 
                        </div>
                        <div class="resume-item">
                            <h4>Node.js, Express.js, Vue.js</h4> 
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </div>


</template>

<script>
    export default {
        name: 'skills',
        data(){
            return{
                msg6: 'This is the Skills Component'
            }
        }
    }
</script>
