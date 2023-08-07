<template>
    <header class="flex items-center" style="height: 70px">
        <div style="height: 48px" class="pr-5">
            <img src="/favicon.ico" alt="logo" class="h-full">
        </div>
        <ul class="text-white text-base flex items-center ml-auto">
            <li>
                <nuxt-link class="px-4 py-3 hover:underline" to="#">Home</nuxt-link>
            </li>
            <li>
                <nuxt-link class="px-4 py-3 hover:underline" to="#">About</nuxt-link>
            </li>
            <li>
                <nuxt-link class="px-4 py-3 hover:underline" to="#">Projects</nuxt-link>
            </li>
            <li>
                <nuxt-link class="px-4 py-3 hover:underline" to="#">Blog</nuxt-link>
            </li>
            <li>
                <nuxt-link class="px-4 py-3 hover:underline" to="#">Contact</nuxt-link>
            </li>
        </ul>
    </header>
</template>