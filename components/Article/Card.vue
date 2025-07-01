<template>
       <div class="col-lg-4 col-md-6">
                    <div class="article-card h-100">
                        <div class="article-image">
                            <div class="placeholder-image d-flex align-items-center justify-content-center">
                                <i class="fas fa-image text-muted fs-1"></i>
                            </div>
                        </div>
                        <div class="article-content">
                            <div class="article-meta mb-3">
                                <span class="meta-item">
                                    <i class="fas fa-calendar-alt me-1"></i>
                                   {{cardDate}}
                                </span>
                                <span class="meta-item">
                                    <i class="fas fa-clock me-1"></i>
                                    {{readingTime}}
                                </span>
                            </div>
                            
                            <h4 class="article-title">
                                {{cardTitle}}
                            </h4>
                            
                            <p class="article-excerpt">
                                {{cardExcerpt}}
                            </p>
                            
                            <div class="d-flex justify-content-between align-items-center">
                                <small class="text-muted">Source: {{sourceName}}</small>
                                <a :href="readMoreLink" class="read-more-btn">
                                    Read More
                                    <i class="fas fa-arrow-right ms-1"></i>
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
</template>

<script setup lang="ts">

// const { imageSrc } = defineProps( [imageSrc] )

interface Props {
    cardDate:string,
    readingTime:string,
    cardTitle:string,
    cardExcerpt:string,
    sourceName:string,
    readMoreLink: string,  // camelCase in script

}

const props = defineProps<Props>()

</script>

<style scoped>

</style>