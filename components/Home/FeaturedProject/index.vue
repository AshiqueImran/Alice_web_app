<template>
    <div>
            <section class="py-5 bg-white">
                <div class="container">
                    <!-- Section Header -->
                    <div class="row mb-5">
                        <div class="col-12">
                            <div class="d-flex align-items-center mb-4">
                                    <i class=" me-3 fas fa-palette fa-thin icon-color fs-3"></i>
                                <h2 class="fw-bold mb-0">Featured Projects</h2>
                            </div>
                        </div>
                    </div>
                    
                    <!-- Expertise Cards -->
                    <div class="row g-4">
                        <!-- AI/ML Technologies -->
                         <HomeFeaturedProjectCard 
                         card-title="AI/ML Technologies" 
                         card-content="Multi-modal Learning, LLM Integration, Video Understanding, Transformer Architectures, Emotion Recognition" 
                         />

                        <!-- Development & Tools -->
                         
                         <HomeFeaturedProjectCard 
                         card-title="Development & Tools" 
                         card-content="Multi-modal Learning, LLM Integration, Video Understanding, Transformer Architectures, Emotion Recognition" 
                         />

                         
                         <!-- Product Strategy -->
                         <HomeFeaturedProjectCard 
                         card-title="Product Strategy" 
                         card-content="Agile Methodologies (PMI-ACP), Product Lifecycle Management, Platform Thinking, Stakeholder Collaboration" 
                         />

                    </div>
                </div>
            </section>
    </div>
    </template>