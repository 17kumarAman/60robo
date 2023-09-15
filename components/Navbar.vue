
import { NuxtLink } from '#build/components';
<script setup lang="ts">

</script>

<template>
    <div class="mt-10 ml-40 mr-40 flex text-center  w-auto ">
        <NuxtLink to="/"><img src="https://www.64robots.com/_nuxt/logo.c0e378ba.svg?inline" class="h-6"
                alt="Discover Nuxt 3" /></NuxtLink>

        <nav class="ml-10 pl-5">
            <ul class="flex  mb-5 ml-80 pl-40">
                <NuxtLink to="about">
                    <li class="ml-10 hover:border-b-2 hover:border-red-500  hover:text-red-500  ">About</li>
                </NuxtLink>
                <NuxtLink to="/">
                    <li class="ml-10 hover:border-b-2 hover:border-red-500  hover:text-red-500  ">Work</li>
                </NuxtLink>
                <NuxtLink to="about">
                    <li class="ml-10 hover:border-b-2 hover:border-red-500  hover:text-red-500  ">Team</li>
                </NuxtLink>
                <NuxtLink to="/">
                    <li class="ml-10 hover:border-b-2 hover:border-red-500  hover:text-red-500  ">WorkHere</li>
                </NuxtLink>
                <NuxtLink to="about">
                <li class="ml-10 bg-sky-600 rounded-2xl w-[100px] h-19 text-white hover:bg-slate-600  pb-1 text-center">
                    Contact Us</li>
            </NuxtLink>
        </ul>
    </nav>
</div></template>

<style lang="scss" scoped></style>