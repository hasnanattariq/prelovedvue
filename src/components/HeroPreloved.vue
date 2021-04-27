<template>
        <!-- Hero Section Begin -->
        <section class="hero-section">
            <carousel class="hero-items" :items="1" :nav="false" :autoplay="true">
                <div class="single-hero-items set-bg" style="background-image: url('/img/group-1.png')">
                    <div class="container">
                        <div class="row">
                            <div class="col-lg-5">
                                <span>Lifestyle</span>
                                <h1>Summer Sale</h1>
                                <p>
                                    Air Jordan Max 200 discount up to 40% off!
                                </p>
                                <a href="#" class="primary-btn">Shop Now</a>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="single-hero-items set-bg" style="background-image: url('/img/group-2.png')">
                    <div class="container">
                        <div class="row">
                            <div class="col-lg-5">
                                <span>Sportswear</span>
                                <h1>Black friday</h1>
                                <p>
                                    Luxury fashion brands at exceptional prices, checkout now!
                                </p>
                                <a href="#" class="primary-btn">Shop Now</a>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="single-hero-items set-bg" style="background-image: url('/img/group-3.png')">
                    <div class="container">
                        <div class="row">
                            <div class="col-lg-5">
                                <span>Lifestyle.Running</span>
                                <h1>Black friday</h1>
                                <p>
                                    Adidas UltraBoost 19
                                </p>
                                <a href="#" class="primary-btn">Shop Now</a>
                            </div>
                        </div>
                    </div>
                </div>
            </carousel>
        </section>
        <!-- Hero Section End -->
</template>

<script>
import carousel from 'vue-owl-carousel'

export default {
    name: 'HeroPreloved',
    components: {
        carousel
    }
}
</script>