<template>
  <div id="profile">
    <div id="todo-card">
        <div class="container">
            <div class="alert alert-primary" role="alert">
                <h1>{{ msg6 }}</h1>
            </div>
        </div>
    </div>

    <section class="w-100 px-4 py-5" style="background-color: #F8EDE3; border-radius: .5rem .5rem 0 0;">
        <div class="row d-flex justify-content-center">
            <div class="col col-md-9 col-lg-7 col-xl-6">
                <div class="card" style="border-radius: 15px;">
                    <div class="card-body p-4">
                    <div class="d-flex align-items-center">
                        <div class="flex-shrink-0">
                        <img src="../assets/wel.jpg"
                            alt="Generic placeholder image" class="img-fluid" style="width: 180px; border-radius: 10px;">
                        </div>
                        <div class="flex-grow-1 ms-3">
                        <h5 class="mb-1"><span>Reuel Christian Sundiam</span></h5>
                        <p class="mb-2 pb-1">Holy Angel University</p>
                        <div class="rounded-3 p-2 mb-2 bg-body-tertiary" style="text-align: left;">
                            <p class=""><span>Objective:</span> I want to expand my knowledge even further regarding Web Development.</p>
                            <p class=""><span>Course:</span> Bachelor of Science in Information Technology</p>
                            <p class=""><span>Specialization:</span> Web Development</p>
                        </div>
                        <div class="d-flex pt-1">
                            <button type="button" data-mdb-button-init data-mdb-ripple-init class="btn btn-outline-primary me-1 flex-grow-1">Chat</button>
                            <button type="button" data-mdb-button-init data-mdb-ripple-init class="btn btn-primary flex-grow-1">Follow</button>
                        </div>
                        </div>
                    </div>
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
        name: 'about-us',
        data(){
            return{
                msg6: 'This is the Profile Component'
            }
        }
    }
</script>
