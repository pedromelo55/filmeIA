<template>
    <div>
        <header class="shadow-sm">
            <nav class="container mx-auto p-4 flex justify-between">
                <NuxtLink to="/" class="font-bold">FilmesIA</NuxtLink>
                <ul class="flex gap-4">
                    <li><NuxtLink to="/">Home</NuxtLink></li>
                    <li><NuxtLink to="/about">About</NuxtLink></li>
                    <li><NuxtLink to="/products" class="btn">Filmes</NuxtLink></li>
                </ul>
            </nav>
        </header>
        <!--output the page content-->
        <div class="container mx-auto p-4">
            <slot />
        </div>
    </div>

    <footer>
        <hr>
        <img src="" alt="Logo da SECTI" class="px-5 py-5 ml-5 ">
    </footer>

</template>

<style scoped>
    .router-link-exact-active {
        color: #fb923c ;
    }
</style>

