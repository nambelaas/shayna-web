<script setup>
import { Carousel, Slide } from 'vue3-carousel';
</script>

<template>
    <!-- Women Banner Section Begin -->
    <section class="women-banner spad">
        <div class="container-fluid">
            <div class="row">
                <div class="col-lg-12 mt-5">
                    <Carousel class="product-slider" :items-to-show="4.5" :wrap-around="true" :autoplay="2500"
                        :transition="800">
                        <template #slides>
                            <Slide :index="0">
                                <div class="product-item">
                                    <div class="pi-pic">
                                        <img src="/img/mickey1.jpg" alt="" />
                                        <ul>
                                            <li class="w-icon active">
                                                <a href="#"><i class="icon_bag_alt"></i></a>
                                            </li>
                                            <li class="quick-view"><a href="product.html">+ Quick View</a></li>
                                        </ul>
                                    </div>
                                    <div class="pi-text">
                                        <div class="catagory-name">Coat</div>
                                        <a href="#">
                                            <h5>Mickey Baggy</h5>
                                        </a>
                                        <div class="product-price">
                                            $14.00
                                            <span>$35.00</span>
                                        </div>
                                    </div>
                                </div>
                            </Slide>
                            <Slide :index="1">
                                <div class="product-item">
                                    <div class="pi-pic">
                                        <img src="/img/products/women-2.jpg" alt="" />
                                        <ul>
                                            <li class="w-icon active">
                                                <a href="#"><i class="icon_bag_alt"></i></a>
                                            </li>
                                            <li class="quick-view"><a href="#">+ Quick View</a></li>
                                        </ul>
                                    </div>
                                    <div class="pi-text">
                                        <div class="catagory-name">Shoes</div>
                                        <a href="#">
                                            <h5>Guangzhou sweater</h5>
                                        </a>
                                        <div class="product-price">
                                            $13.00
                                        </div>
                                    </div>
                                </div>
                            </Slide>
                            <Slide :index="2">
                                <div class="product-item">
                                    <div class="pi-pic">
                                        <img src="/img/products/women-3.jpg" alt="" />
                                        <ul>
                                            <li class="w-icon active">
                                                <a href="#"><i class="icon_bag_alt"></i></a>
                                            </li>
                                            <li class="quick-view"><a href="#">+ Quick View</a></li>
                                        </ul>
                                    </div>
                                    <div class="pi-text">
                                        <div class="catagory-name">Towel</div>
                                        <a href="#">
                                            <h5>Pure Pineapple</h5>
                                        </a>
                                        <div class="product-price">
                                            $34.00
                                        </div>
                                    </div>
                                </div>
                            </Slide>
                            <Slide :index="3">
                                <div class="product-item">
                                    <div class="pi-pic">
                                        <img src="/img/products/women-4.jpg" alt="" />
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
                                        <div class="catagory-name">Towel</div>
                                        <a href="#">
                                            <h5>Converse Shoes</h5>
                                        </a>
                                        <div class="product-price">
                                            $34.00
                                        </div>
                                    </div>
                                </div>
                            </Slide>
                        </template>
                    </Carousel>
                </div>
            </div>
        </div>
    </section>
    <!-- Women Banner Section End -->
</template>