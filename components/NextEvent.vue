<template>
    <section id="speaker">
    <div class="container">
        <h3 class="pb-2">#GDGJakarta Next Event</h3>
            <div class="row">
                <div class="col-6 col-lg-6">
                    <div class="card">
                        <div class="card-image">
                            <img src="../assets/img/speakers/anbita.jpeg" alt="" class="w-100">
                        </div>
                        <div class="card-title">
                            <h5>Anbita Nadine Siregar</h5>
                            <p>Founder <br> of Generation Girl</p>
                            <ul>
                                <div class="text-center">
                                    <a href="http://bit.ly/jkt-devfest-19" target="_blank">
                                        <button class="btn btn-primary btn-lg">Register here</button>
                                    </a> 
                                </div>
                            </ul>
                        </div>
                    </div>
                </div>
                <div class="col-6 col-lg-6">
                    <div class="card">
                        <div class="card-image">
                            <img src="../assets/img/speakers/andrew.jpg" alt="" class="w-100">
                        </div>
                        <div class="card-title">
                            <h5>Andrew Kurniadi</h5>
                            <p>Google Developer Expert <br> of Android</p>
                            <ul>
                                <li><a href="https://www.linkedin.com/in/anbitasiregar" target="_blank"><i class="icon-linkedin"></i></a></li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
    </div>
    </section>
</template>

<style lang="sass" scoped>
    #speaker
        background-color: #F5F5F5
        padding: 50px 0
        .card
            padding: 20px
            transition: 0.3s
            text-align: center
            margin: 15px 0
            .card-image
                img
                    max-width: 150px
                    border-radius: 50%
                    margin-left: auto
                    margin-right: auto
            .card-title
                padding: 10px 0
                margin-bottom: 0
                p
                    margin: 0
                ul
                    list-style: none
                    padding: 0
                    margin: 20px 0 0 0
                    li
                        display: inline-block
                        padding: 3px
        .card:hover
            transition: 0.3s
            box-shadow: 0 4px 5px 0 rgba(0,0,0,0.14), 0 1px 10px 0 rgba(0,0,0,0.12), 0 2px 4px -1px rgba(0,0,0,0.2)
        .updating
            margin-top: 50px
</style>