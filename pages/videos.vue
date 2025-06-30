<template>
    <div>
        <!-- YouTube Videos Section -->
    <section class="my-5 py-5 ">
        <div class="container">
            <!-- Section Header -->
            <div class="row mb-5">
                <div class="col-12 text-center">
                    <h2 class="fw-bold mb-3">YouTube Videos</h2>
                    <p class="text-muted mx-auto" style="max-width: 500px;">
                        Visual content exploring the intersection of creativity and technology.
                    </p>
                </div>
            </div>
            
            <!-- Filter Tabs -->
            <div class="row mb-4 ">
                <div class="col-12 ">
                    <div class="d-flex justify-content-center ">
                        <ul class="nav nav-pills video-filters p-1" id="videoTabs" role="tablist">
                            <li class="nav-item" role="presentation">
                                <button class="nav-link active" id="all-videos-tab" data-bs-toggle="pill" data-bs-target="#all-videos" type="button" role="tab">
                                    All Videos
                                </button>
                            </li>
                            <li class="nav-item" role="presentation">
                                <button class="nav-link" id="tutorials-tab" data-bs-toggle="pill" data-bs-target="#tutorials" type="button" role="tab">
                                    Tutorials
                                </button>
                            </li>
                            <li class="nav-item" role="presentation">
                                <button class="nav-link" id="behind-scenes-tab" data-bs-toggle="pill" data-bs-target="#behind-scenes" type="button" role="tab">
                                    Behind the Scenes
                                </button>
                            </li>
                            <li class="nav-item" role="presentation">
                                <button class="nav-link" id="tech-tab" data-bs-toggle="pill" data-bs-target="#tech" type="button" role="tab">
                                    Tech
                                </button>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
            
            <!-- Video Content -->
            <div class="tab-content" id="videoTabsContent">
                <!-- All Videos Tab -->
                <div class="tab-pane fade show active" id="all-videos" role="tabpanel">
                    <div class="row g-4">
                        <!-- Video 1 -->
                        <div class="col-lg-6">
                            <div class="video-card">
                                <div class="video-thumbnail">
                                    <div class="placeholder-video d-flex align-items-center justify-content-center">
                                        <i class="fab fa-youtube text-danger fs-1"></i>
                                    </div>
                                    <div class="video-duration">15:24</div>
                                    <div class="play-overlay">
                                        <i class="fas fa-play"></i>
                                    </div>
                                </div>
                                <div class="video-info">
                                    <h4 class="video-title">Creative Production Techniques for Beginners</h4>
                                    <p class="video-description text-muted">
                                        Learn the fundamentals of creative production in this comprehensive tutorial.
                                    </p>
                                </div>
                            </div>
                        </div>
                        
                        <!-- Video 2 -->
                        <div class="col-lg-6">
                            <div class="video-card">
                                <div class="video-thumbnail">
                                    <div class="placeholder-video d-flex align-items-center justify-content-center">
                                        <i class="fab fa-youtube text-danger fs-1"></i>
                                    </div>
                                    <div class="video-duration">8:37</div>
                                    <div class="play-overlay">
                                        <i class="fas fa-play"></i>
                                    </div>
                                </div>
                                <div class="video-info">
                                    <h4 class="video-title">Behind the Scenes: My Creative Process</h4>
                                    <p class="video-description text-muted">
                                        A detailed walkthrough of how I approach creative projects from concept to completion.
                                    </p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                
                <!-- Other tab contents (hidden by default) -->
                <div class="tab-pane fade" id="tutorials" role="tabpanel">
                    <div class="row g-4">
                        <div class="col-12 text-center">
                            <p class="text-muted">Tutorial videos will be displayed here.</p>
                        </div>
                    </div>
                </div>
                
                <div class="tab-pane fade" id="behind-scenes" role="tabpanel">
                    <div class="row g-4">
                        <div class="col-12 text-center">
                            <p class="text-muted">Behind the scenes videos will be displayed here.</p>
                        </div>
                    </div>
                </div>
                
                <div class="tab-pane fade" id="tech" role="tabpanel">
                    <div class="row g-4">
                        <div class="col-12 text-center">
                            <p class="text-muted">Tech videos will be displayed here.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    </div>
</template>

<script setup lang="ts">

</script>

<style scoped>

</style>