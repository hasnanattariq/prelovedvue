<template>
    <div>
    <!-- Women Banner Section Begin -->
    <section class="women-banner spad">
        <div class="container-fluid">
            <div class="row">
                <div class="col-lg-12 mt-5">
                    <carousel class="product-slider" :items="3" :nav="false" :dots="false" :autoplay="true">
                        <div class="product-item">
                            <div class="pi-pic">
                                <img src="img/shoes/nike-air270-1.jpg" alt="" />
                                <ul>
                                    <li class="w-icon active">
                                        <a href="#"><i class="icon_bag_alt"></i></a>
                                    </li>
                                    <li class="quick-view"><a href="product.html">+ Quick View</a></li>
                                </ul>
                            </div>
                            <div class="pi-text">
                                <div class="catagory-name">Nike</div>
                                <a href="#">
                                    <h5>Air Max 270</h5>
                                </a>
                                <div class="product-price">
                                    $128.00
                                    <span>$150.00</span>
                                </div>
                            </div>
                        </div>
                        <div class="product-item">
                            <div class="pi-pic">
                                <img src="img/shoes/af1.jpg" alt="" />
                                <ul>
                                    <li class="w-icon active">
                                        <a href="#"><i class="icon_bag_alt"></i></a>
                                    </li>
                                    <li class="quick-view"><router-link to="/product">+ Quick View</router-link></li>
                                </ul>
                            </div>
                            <div class="pi-text">
                                <div class="catagory-name">Nike</div>
                                <router-link to="/product">
                                    <h5>Air Force 1 Mid '07</h5>
                                </router-link>
                                <div class="product-price">
                                    $95.00
                                </div>
                            </div>
                        </div>
                        <div class="product-item">
                            <div class="pi-pic">
                                <img src="img/shoes/puma1.jpg" alt="" />
                                <ul>
                                    <li class="w-icon active">
                                        <a href="#"><i class="icon_bag_alt"></i></a>
                                    </li>
                                    <li class="quick-view"><a href="#">+ Quick View</a></li>
                                </ul>
                            </div>
                            <div class="pi-text">
                                <div class="catagory-name">Puma</div>
                                <a href="#">
                                    <h5>RS-Fast Sneakers</h5>
                                </a>
                                <div class="product-price">
                                    $110.00
                                </div>
                            </div>
                        </div>
                        <div class="product-item">
                            <div class="pi-pic">
                                <img src="img/shoes/ultraboost1.jpg" alt="" />
                                <ul>
                                    <li class="w-icon active">
                                        <a href="#"><i class="icon_bag_alt"></i></a>
                                    </li>
                                    <li class="quick-view"><a href="#">+ Quick View</a></li>
                                    <li class="w-icon">
                                        <a href="#"><i class="fa fa-random"></i></a>
                                    </li>
                                </ul>
                            </div>
                            <div class="pi-text">
                                <div class="catagory-name">Adidas</div>
                                <a href="#">
                                    <h5>Terrex Two Ultra Primeblue Trail</h5>
                                </a>
                                <div class="product-price">
                                    $180.00
                                </div>
                            </div>
                        </div>
                    </carousel>
                </div>
            </div>
        </div>
    </section>
    <!-- Women Banner Section End -->

    </div>
</template>

<script>
import carousel from 'vue-owl-carousel'

export default {
    name: 'BannerPreloved',
    components: {
        carousel
    }
}
</script>

<style scoped>
    .product-item {
        margin-right: 25px;
    }

    .product-item .pi-pic img {
        height: 778px;
    }
</style>