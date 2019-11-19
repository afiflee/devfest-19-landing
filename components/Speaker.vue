<template>
    <section id="speaker">
        <div class="container">
            <h2>Speakers</h2>
            <div class="row">
                <div class="col-6 col-lg-3 text-center">
                    <img src="../assets/img/speakers/anbita.jpeg" alt="">
                    <div>
                        <h5>Anbita Nadine Siregar</h5>
                        <p>Founder <br>of Generation Girl</p>
                    </div>
                </div>
                <div class="col-6 col-lg-3 text-center">
                    <img src="../assets/img/speakers/denny.jpeg" alt="">
                    <div>
                        <h5>Denny Muktar</h5>
                        <p>Cloud Customer Consultant <br> at Google</p>
                    </div>
                </div>
                <div class="col-6 col-lg-3 text-center">
                    <img src="../assets/img/speakers/ivan.jpg" alt="">
                    <div>
                        <h5>Ivan Kristianto</h5>
                            <p>Google Developer Expert <br> of Web Technologies</p>
                    </div>
                </div>
                <div class="col-6 col-lg-3 text-center">
                    <img src="../assets/img/speakers/sonja.jpg" alt="">
                    <div>
                        <h5>Sonja Johar</h5>
                        <p>CTO <br> of Halosis</p>
                    </div>
                </div>
            </div>
            <div class="more-speaker">
                <a href="/speakers">View All Speakers <i class="icon-arrow-right"></i></a>
            </div>
        </div>
    </section>
</template>

<style lang="sass" scoped>
    #speaker
        padding: 50px 0
        img
            max-width: 170px
            width: 100%
            border-radius: 50%
            margin: 15px 0
        .more-speaker
            a
                color: #007bff
                text-decoration: none
                .icon-arrow-right:before
                    transition: 0.3s
            a:hover
                .icon-arrow-right:before
                    transform: translateX(10px)
                    transition: 0.3s
</style>