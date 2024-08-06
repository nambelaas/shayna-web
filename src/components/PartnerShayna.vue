<script setup>
import { Carousel, Slide } from 'vue3-carousel';
</script>
<template>
    <!-- Partner Logo Section Begin -->
    <div class="partner-logo">
        <div class="container">
            <Carousel class="logo-carousel" :wrap-around="true" :autoplay="3500" :items-to-show="5">
                <template #slides>
                    <Slide :index="0">
                        <div class="logo-item">
                            <div class="tablecell-inner">
                                <img src="/img/logo-carousel/logo-1.png" alt="" />
                            </div>
                        </div>
                    </Slide>
                    <Slide :index="1">
                        <div class="logo-item">
                            <div class="tablecell-inner">
                                <img src="/img/logo-carousel/logo-2.png" alt="" />
                            </div>
                        </div>
                    </Slide>
                    <Slide :index="2">
                        <div class="logo-item">
                            <div class="tablecell-inner">
                                <img src="/img/logo-carousel/logo-3.png" alt="" />
                            </div>
                        </div>
                    </Slide>
                    <Slide :index="3">
                        <div class="logo-item">
                            <div class="tablecell-inner">
                                <img src="/img/logo-carousel/logo-4.png" alt="" />
                            </div>
                        </div>
                    </Slide>
                    <Slide :index="4">
                        <div class="logo-item">
                            <div class="tablecell-inner">
                                <img src="/img/logo-carousel/logo-5.png" alt="" />
                            </div>
                        </div>
                    </Slide>
                </template>
            </Carousel>
        </div>
    </div>
    <!-- Partner Logo Section End -->
</template>