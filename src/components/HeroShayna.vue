<script setup>
import { Carousel, Slide, Navigation, Pagination } from 'vue3-carousel';
</script>
<template>
    <!-- Hero Section Begin -->
    <section class="hero-section">
        <Carousel class="hero-items" :items-to-show="1" :wrap-around="true" :autoplay="5000" :transition="800">
            <template #slides>
                <Slide :index="0" class="single-hero-items set-bg" style="background-image: url('./img/hero-1.jpg');">
                    <div class="container">
                        <div class="row">
                            <div class="col-lg-5">
                                <span>Bag,kids</span>
                                <h1>Black friday</h1>
                                <p>
                                    Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor
                                    incididunt ut
                                    labore
                                    et dolore
                                </p>
                                <a href="#" class="primary-btn">Shop Now</a>
                            </div>
                        </div>
                    </div>
                </Slide>
                <Slide :index="1" class="single-hero-items set-bg" style="background-image: url('./img/hero-2.jpg');">
                    <div class="container">
                        <div class="row">
                            <div class="col-lg-5">
                                <span>Bag,kids</span>
                                <h1>Black friday</h1>
                                <p>
                                    Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor
                                    incididunt ut
                                    labore
                                    et dolore
                                </p>
                                <a href="#" class="primary-btn">Shop Now</a>
                            </div>
                        </div>
                    </div>
                </Slide>
            </template>
            <template #addons>
                <Navigation />
                <Pagination />
            </template>
        </Carousel>
    </section>
    <!-- Hero Section End -->
</template>