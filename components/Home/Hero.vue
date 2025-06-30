<template>
    <div>

        <!-- Hero Section Intro-->
    <section class="hero-section" id="home">
        <div class="container">
            <div class="row align-items-center pt-5">
                <div class="col-lg-4 order-lg-1 text-center mb-5 mb-lg-0">
                    <img  :src="imageSrc"
                         alt="Alice Ding" 
                         class="profile-image">
                </div>
                
                <div class="col-lg-8 order-lg-2 text-lg-start text-sm-center">
                    <h1 class="main-title">
                        Hello, I'm <span class="name-highlight">Alice Ding</span>
                    </h1>
                    
                    <div class="mb-4">
                        <span class="badge badge-custom text-sm ">AI Product Manager</span>
                        <span class="badge badge-custom text-sm ">PMI-ACP</span>
                        <span class="badge badge-custom text-sm ">Multi-modal AI</span>
                        <span class="badge badge-custom text-sm ">LLM Integration</span>
                    </div>
                    
                    <p class="description">
                        AI-focused product manager with 8 years of cross-functional leadership 
                        and a platform-oriented mindset. Currently conducting advanced research 
                        in multi-modal learning and LLM-based systems with applications in 
                        context-aware video understanding.
                    </p>
                    
                    <div class="d-flex flex-wrap justify-content-lg-start justify-content-sm-center gap-2 ">
                        <NuxtLink class="btn btn-primary-custom btn-sm" to="/about">More About Me</NuxtLink>
                        
                        <!-- <button class="btn btn-primary-custom btn-sm">
                            More About Me
                        </button> -->
                        <NuxtLink class="btn btn-outline-custom btn-sm" to="/articles">Read My Articles</NuxtLink>
                        <!-- <button class="btn btn-outline-custom btn-sm">
                            Read My Articles
                        </button> -->
                    </div>
                </div>
            </div>
        </div>
    </section>

    </div>
</template>

<script setup lang="ts">

// const { imageSrc } = defineProps( [imageSrc] )

interface Props {
  imageSrc: string  // camelCase in script
}

const props = defineProps<Props>()

</script>

<style scoped>

</style>