<template>
    <!-- featured projects card -->
    <div class="col-lg-4 col-md-6">
        <div class="expertise-card h-100">
            <h4 class="expertise-title"> {{cardTitle}}</h4>
            <p class="expertise-content">
                {{cardContent}}
            </p>
        </div>
    </div>
</template>

<script setup lang="ts">

// const { imageSrc } = defineProps( [imageSrc] )

interface Props {
  cardTitle: string , // camelCase in script
  cardContent:string
}

const props = defineProps<Props>()

</script>

<style scoped>

</style>