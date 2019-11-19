<template>
    <section id="partners">
        <div class="container">
             <div class="partners-group">
                <div class="co-presenter">
                    <h3>Presented by</h3>
                    <div class="partner-logo d-flex mb-4 mt-3 align-items-center flex-wrap">
                        <img src="../assets/img/gdg-jakarta-logo.svg" class="gdg">
                    </div>
                </div>
                <div class="community-partner">
                    <h3>Partners</h3>
                    <h6>Venue Partner</h6>
                    <div class="partner-logo d-flex mb-4 mt-3 align-items-center flex-wrap">
                        <img src="../assets/img/partners/upperroom.svg" class="upperroom">
                    </div>
                    <h6>Community Partners</h6>
                     <div class="partner-logo d-flex mb-4 mt-3 align-items-center flex-wrap">
                        <img src="../assets/img/partners/wtm.svg" class="wtm">
                        <img src="../assets/img/partners/dsc.svg" class="dsc">
                    </div>
                </div>
                <div class="media-partner">
                    <h6>Media Partners</h6>
                    <div class="partner-logo d-flex d-flex mb-4 mt-3 align-items-center flex-wrap">
                        <img src="../assets/img/partners/teknoevent.png"  class="teknoevent">
                        <img src="../assets/img/partners/chromplex.png"  class="chromplex">
                    </div>
                </div>
             </div>
        </div>
    </section>
</template>

<style lang="sass" scoped>
    @import "./node_modules/bootstrap/scss/bootstrap"

    #partners
        .partners-group
            padding: 70px 0
        .co-presenter
            .gdg
                height: 40px
            .wtm
                height: 40px
            .uii
                height: 80px
            img
                height: 90px
                margin: 10px 40px 0 0
        .community-partner
            margin-top: 5px
            .dsc
                height: 40px
            .upperroom
                height: 80px
            .jogjajs
                height: 40px
            .yac
                height: 70px
            img
                height: 50px
                margin: 10px 40px 10px 0
        .media-partner
            .teknoevent
                margin-right: 40px
            .chromplex
                height: 45px
            img
                height: 60px

    @include media-breakpoint-down(md)
        #partners
            text-align: center
            .partner-logo
                justify-content: center
                img
                    margin: 15px 10px
</style>