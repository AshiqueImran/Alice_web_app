<template>
    <div >
        <!-- About Section -->
        <section class="about-section ">
            <div class="container">
                <div class="row g-4">
                    <!-- Profile Card -->
                    <div class="col-lg-4">
                        <div class="profile-card">
                            <img src="/img/photo.jpeg" 
                            alt="Alice Ding" 
                            class="profile-image-about">

                            <h1 class="profile-name">Alice Ding</h1>
                            <p class="profile-title">AI Product Manager & Researcher</p>

                            <div class="my-4 text-lg-start">
                                <span class="badge badge-custom text-sm ">AI Product Manager</span>
                                <span class="badge badge-custom text-sm ">PMI-ACP</span>
                                <span class="badge badge-custom text-sm ">Multi-modal AI</span>
                                <span class="badge badge-custom text-sm ">LLM Integration</span>
                            </div>
                        </div>


                    </div>

                    <!-- Content Card -->
                    <div class="col-lg-8">
                        <div class="content-card " >
                            <!-- Tabs Navigation -->
                            <ul class="nav nav-tabs nav-tabs-custom" id="aboutTabs" role="tablist">
                                <li class="nav-item" role="presentation">
                                    <button class="nav-link active" id="bio-tab" data-bs-toggle="tab" data-bs-target="#bio" type="button" role="tab">
                                        Bio
                                    </button>
                                </li>
                                <li class="nav-item" role="presentation">
                                    <button class="nav-link" id="experience-tab" data-bs-toggle="tab" data-bs-target="#experience" type="button" role="tab">
                                        Experience
                                    </button>
                                </li>
                                <li class="nav-item" role="presentation">
                                    <button class="nav-link" id="research-tab" data-bs-toggle="tab" data-bs-target="#research" type="button" role="tab">
                                        Research
                                    </button>
                                </li>

                                <li class="nav-item" role="presentation">
                                    <button class="nav-link" id="education-tab" data-bs-toggle="tab" data-bs-target="#education" type="button" role="tab">
                                        Education
                                    </button>
                                </li>
                            </ul>

                            <!-- Tab Content -->
                            <div class="tab-content tab-content-custom" id="aboutTabsContent">

                                <!-- Bio Tab -->
                                <div class="tab-pane fade show active" id="bio" role="tabpanel">
                                    <h2 class="content-title">Professional Summary</h2>

                                    <p class="content-text">
                                        I'm an AI-focused product manager with 8 years of cross-functional leadership 
                                        experience and a platform-oriented mindset. Currently conducting advanced 
                                        research in multi-modal learning and LLM-based systems with applications in 
                                        context-aware video understanding.
                                    </p>

                                    <p class="content-text">
                                        My expertise lies in translating complex business needs into scalable AI-enabled 
                                        tools across education, media, and consulting sectors. I'm passionate about 
                                        delivering structured yet adaptable product strategies in high-growth, AI-driven 
                                        organizations.
                                    </p>

                                    <p class="content-text">
                                        With a strong background in both technical implementation and strategic 
                                        product management, I bridge the gap between cutting-edge AI research and 
                                        practical business applications.
                                    </p>

                                    <section class="py-1 bg-white">
                                        <div class="container">
                                            <!-- Section Header -->
                                            <div class="row ">
                                                <div class="col-12">
                                                    <div class="d-flex align-items-center mb-4">
                                                        <h3 class="fw-bold mb-0">Technical Skills</h3>
                                                    </div>
                                                </div>
                                            </div>

                                            <!-- Expertise Cards -->
                                            <div class="row g-4">
                                                <!-- AI/ML Technologies -->
                                                <div class="col-md-6">
                                                    <div class="expertise-card h-100">
                                                        <div class="d-flex align-items-center mb-4">
                                                            <i class=" me-3 fas fa-brain fa-thin icon-color fs-5"></i>
                                                            <h5 class="expertise-title">AI/ML Technologies</h5>
                                                        </div>
                                                        <div class="expertise-content">
                                                            Multi-modal Learning, LLM Integration, Video Understanding, Transformer Architectures, Emotion Recognition
                                                        </div>
                                                    </div>
                                                </div>

                                                <!-- Development & Tools -->
                                                <div class="col-md-6">
                                                    <div class="expertise-card h-100">
                                                        <div class="d-flex align-items-center mb-4">
                                                            <i class=" me-3 fas fa-database fa-thin icon-color fs-5"></i>
                                                            <h5 class="expertise-title">Development & Tools</h5>
                                                        </div>
                                                        <p class="expertise-content">
                                                            Python, SQL, Java, Cursor, Zoho Projects, Notion, NotebookLM, Custom CRM Development
                                                        </p>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </section>
                                </div>

                                <!-- Experience Tab -->
                                <div class="tab-pane fade" id="experience" role="tabpanel">
                                    <h2 class="content-title ms-1">Professional Experience</h2>
                                    <div class="content-text">

                                        <div class="job-item">
                                            <div class="job-header">
                                                <div class="job-icon">
                                                    <i class="fas fa-briefcase  fs-5"></i>
                                                </div>
                                                <div class="job-details">
                                                    <h3>Agentic AI Consultant</h3>
                                                    <p class="job-company ms-1">Maurel Solutions Inc. • April 2025 - Present</p>
                                                </div>
                                            </div>
                                            <ul class="ms-5 job-responsibilities">
                                                <li>Designed AI integration playbooks for boutique firms (revenue $2M-$10M)</li>
                                                <li>Led discovery sessions with founders to translate business goals into technical LLM-based solutions</li>
                                                <li>Built internal knowledge management tools using LLMs for enhanced decision-making</li>
                                                <li>Delivered training for cross-functional teams to accelerate AI adoption and system integration</li>
                                            </ul>
                                        </div>

                                        <div class="job-item">
                                            <div class="job-header">
                                                <div class="job-icon">
                                                    <i class="fas fa-briefcase  fs-5"></i>
                                                </div>
                                                <div class="job-details">
                                                    <h3>Agentic AI Consultant</h3>
                                                    <p class="job-company ms-1">Maurel Solutions Inc. • April 2025 - Present</p>
                                                </div>
                                            </div>
                                            <ul class="ms-5 job-responsibilities">
                                                <li>Designed AI integration playbooks for boutique firms (revenue $2M-$10M)</li>
                                                <li>Led discovery sessions with founders to translate business goals into technical LLM-based solutions</li>
                                                <li>Built internal knowledge management tools using LLMs for enhanced decision-making</li>
                                                <li>Delivered training for cross-functional teams to accelerate AI adoption and system integration</li>
                                            </ul>
                                        </div>

                                        <div class="job-item">
                                            <div class="job-header">
                                                <div class="job-icon">
                                                    <i class="fas fa-briefcase  fs-5"></i>
                                                </div>
                                                <div class="job-details">
                                                    <h3>Agentic AI Consultant</h3>
                                                    <p class="job-company ms-1">Maurel Solutions Inc. • April 2025 - Present</p>
                                                </div>
                                            </div>
                                            <ul class="ms-5 job-responsibilities">
                                                <li>Designed AI integration playbooks for boutique firms (revenue $2M-$10M)</li>
                                                <li>Led discovery sessions with founders to translate business goals into technical LLM-based solutions</li>
                                                <li>Built internal knowledge management tools using LLMs for enhanced decision-making</li>
                                                <li>Delivered training for cross-functional teams to accelerate AI adoption and system integration</li>
                                            </ul>
                                        </div>

                                        <div class="job-item">
                                            <div class="job-header">
                                                <div class="job-icon">
                                                    <i class="fas fa-briefcase  fs-5"></i>
                                                </div>
                                                <div class="job-details">
                                                    <h3>Agentic AI Consultant</h3>
                                                    <p class="job-company ms-1">Maurel Solutions Inc. • April 2025 - Present</p>
                                                </div>
                                            </div>
                                            <ul class="ms-5 job-responsibilities">
                                                <li>Designed AI integration playbooks for boutique firms (revenue $2M-$10M)</li>
                                                <li>Led discovery sessions with founders to translate business goals into technical LLM-based solutions</li>
                                                <li>Built internal knowledge management tools using LLMs for enhanced decision-making</li>
                                                <li>Delivered training for cross-functional teams to accelerate AI adoption and system integration</li>
                                            </ul>
                                        </div>

                                    </div>
                                </div>


                                <!-- Research Tab -->
<!--                         <div class="tab-pane fade" id="research" role="tabpanel">
                            <h2 class="content-title">Educational Background</h2>

                            <div class="content-text">
                                ghjhg
                            </div>

                        </div> -->

                        <div class="tab-pane fade" id="research" role="tabpanel">
                            <h2 class="content-title">Multi-Modal AI Research</h2>

                            <div class="content-text">


                                <div class="col-md-12 my-3">
                                    <div class="expertise-card h-100 ">
                                        <div class="d-flex align-items-center mb-4">
                                            <i class=" me-3 fas fa-brain fa-thin icon-color fs-5"></i>
                                            <h5 class="expertise-title">Video Understanding & Captioning</h5>
                                        </div>
                                        <p class="expertise-content">
                                            <ul>
                                                <li>Researching transformer-based architectures for multi-modal video captioning</li>
                                                <li> Developing intent-aware captioning models using visual, audio, and subtitle fusion</li>
                                                <li>Implementing shot boundary detection (SBD) to enhance narrative understanding</li>
                                            </ul>

                                        </p>
                                    </div>
                                </div>


                                <div class="col-md-12 my-3">
                                    <div class="expertise-card h-100">
                                        <div class="d-flex align-items-center mb-4">
                                            <i class=" me-3 fas fa-heart fa-thin icon-color fs-5"></i>
                                            <h5 class="expertise-title">Emotion Recognition & Narrative Analysis</h5>
                                        </div>
                                        <p class="expertise-content">
                                            <ul>
                                                <li>Exploring emotion recognition for richer content modeling</li>
                                                <li> Developing narrative progression analysis for enhanced storytelling</li>
                                                <li>Integrating contextual understanding for improved AI-human interaction</li>
                                            </ul>
                                        </p>
                                    </div>
                                </div>

                            </div>
                        </div>




                        <!-- Education Tab -->
                        <div class="tab-pane fade" id="education" role="tabpanel">
                            <h2 class="content-title">Educational Background</h2>

                            <div class="content-text">

                                <div class="job-item">
                                    <div class="job-header">
                                        <div class="edu-icon">
                                            <i class="fas fa-graduation-cap  fs-5"></i>
                                        </div>
                                        <div class="job-details">
                                            <h3>B.A. in Applied Computer Science</h3>
                                            <p class="job-company ms-1">The University of Winnipeg • Expected May 2026</p>
                                        </div>
                                    </div>
                                    <p class="ms-5 job-responsibilities">
                                        Currently pursuing advanced studies in computer science with focus on AI and machine learning applications.
                                    </p>
                                </div>

                                <div class="job-item">
                                    <div class="job-header">
                                        <div class="edu-icon">
                                            <i class="fas fa-graduation-cap fs-5"></i>
                                        </div>
                                        <div class="job-details">
                                            <h3>M.A. in Social Sciences</h3>
                                            <p class="job-company ms-1">University of Chicago • September 2014 - December 2015</p>
                                        </div>
                                    </div>
                                    <p class="ms-5 job-responsibilities">
                                        Currently pursuing advanced studies in computer science with focus on AI and machine learning applications.
                                    </p>
                                <!-- </ul> -->
                            </div>

                            <div class="job-item">
                                <div class="job-header">
                                    <div class="edu-icon">
                                        <i class="fas fa-graduation-cap  fs-5"></i>
                                    </div>
                                    <div class="job-details">
                                        <h3>B.A. in Economics</h3>
                                        <p class="job-company ms-1">New York University • September 2010 - May 2014</p>
                                    </div>
                                </div>
                                <p class="ms-5 job-responsibilities">
                                    Currently pursuing advanced studies in computer science with focus on AI and machine learning applications.
                                </p>
                            </div>

                            <div class="job-item">
                                <div class="job-header">
                                    <div class="edu-icon">
                                        <i class="fas fa-award  fs-5"></i>
                                    </div>
                                    <div class="job-details">
                                        <h3>Professional Certifications</h3>
                                        <p class="job-company ms-1">Maurel Solutions Inc. • April 2025 - Present</p>
                                    </div>
                                </div>
                                <ul class="ms-5 job-responsibilities">
                                    <li>PMI Agile Certified Practitioner (PMI-ACP) - Project Management Institute</li>
                                    <li>Supervised Machine Learning - Stanford University</li>
                                </ul>
                            </div>

                        </div>
                    </div>


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