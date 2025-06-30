<template>
    <div>
        <!-- nav goes here -->
        <nav class="navbar navbar-expand-lg navbar-custom fixed-top">
                <div class="container">

                    <NuxtLink class="navbar-brand" to="/">Alice Ding</NuxtLink>
                    
                    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                        <span class="navbar-toggler-icon"></span>
                    </button>
                    
                    <div class="collapse navbar-collapse" id="navbarNav">
                        <ul class="navbar-nav ms-auto">
                            <li class="nav-item">
                                <NuxtLink class="nav-link text-sm " to="/">Home</NuxtLink>
                            </li>
                            <li class="nav-item">
                                <NuxtLink class="nav-link text-sm " to="/articles">Articles</NuxtLink>
                            </li>
                            <li class="nav-item">
                                <NuxtLink class="nav-link text-sm " to="/videos">Videos</NuxtLink>
                            </li>
                            <li class="nav-item">
                                <NuxtLink class="nav-link text-sm " to="/about">About</NuxtLink>
                            </li>
                        </ul>
                        
                        <div class="d-flex ms-3">
                            <a href="#" class="icon-btn">
                                <i class="fas fa-external-link-alt"></i>
                            </a>
                            <a href="#" class="icon-btn">
                                <i class="fab fa-github"></i>
                            </a>
                            <a href="#" class="icon-btn">
                                <i class="fas fa-palette"></i>
                            </a>
                        </div>
                    </div>
                </div>
            </nav>
    </div>
</template>

<script setup>

</script>

<style scoped>

.router-link-exact-active{
    color: var(--primary-color) !important;
}

</style>