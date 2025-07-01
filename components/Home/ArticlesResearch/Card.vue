<template>

        <!-- Articles Research Card  -->
            <div class="col-lg-6">
                            <div class="card h-100 border-1 shadow-sm">
                                <div class="card-body p-4">
                                    <div class="d-flex align-items-center mb-3">
                                            <i :class="icon"></i>

                                        <h3 class="card-title fw-bold"> {{ cardTitle }}</h3>
                                    </div>
                                    
                                    <p class="card-text  mb-4">
                                        {{ cardText }}
                                    </p>
                                    
                                    <a :href="buttonLink" class="btn btn-link p-0 text-dark fw-semibold text-decoration-none d-flex align-items-center">
                                        {{ buttonText }}
                                        <i class="fas fa-arrow-right ms-2"></i>
                                    </a>
                                </div>
                            </div>
                        </div>

</template>

<script setup lang="ts">

// const { imageSrc } = defineProps( [imageSrc] )

interface Props {
  cardTitle: string,  // camelCase in script
  cardText: string,
  buttonText: string,
  buttonLink: string,
  icon: string
}

const props = defineProps<Props>()

</script>

<style scoped>

</style>