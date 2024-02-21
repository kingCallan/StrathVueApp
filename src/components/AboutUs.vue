<template>
    <div id = 'AboutUs'>
        <v-container>
                <v-layout column>
                    <v-carousel>
                        <v-carousel-item
                            src="https://media.istockphoto.com/id/1170204144/photo/vision-mission-values-text-on-sticky-notes-isolated-on-black-desk-mechanism-strategy-concept.jpg?s=1024x1024&w=is&k=20&c=kHSEsEAr8_GTXd6wFK82zC6SF2HqaaL0IoKu9v77zdc="
                            cover
                        ></v-carousel-item>

                        <v-carousel-item
                            src="https://images.unsplash.com/photo-1447069387593-a5de0862481e?q=80&w=2069&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
                            cover
                        ></v-carousel-item>

                        <v-carousel-item
                            src="https://media.istockphoto.com/id/1383796215/photo/silhouette-of-man-holding-binoculars-on-mountain-peak-against-bright-sunlight-sky-background.jpg?s=1024x1024&w=is&k=20&c=QUKKZc4Xmh30nhFFAaZc2S6pOpoGcMVuc1cas4TgJbc="
                            cover
                        ></v-carousel-item>
                    </v-carousel>
                    </v-layout>
                    <v-layout>
                    <v-container>
                        <v-row align="center" justify="center">
                            <div class="d-flex align-center flex-column">
                                <div class="text-subtitle-2">With props</div>

                                <v-card
                                width="400"
                                title="Mission Statement"
                                subtitle="What are our core values and our purpose?"
                                text="Empowering Minds, Transforming Futures: Our University's Commitment to Excellence in Education and Innovation."
                                ></v-card>

                                <div class="mt-4 text-subtitle-2">With slots</div>

                                <v-card width="400">
                                <template v-slot:title>
                                    History
                                </template>

                                <template v-slot:subtitle>
                                    Our founders,Our milestones: Our history!
                                </template>

                                <template v-slot:text>
                                    Embark on a Journey Through the Rich Tapestry of Our University's History, Unfolding From Its Modest Origins to Its Current Position of Prominence in the Educational Landscape. Discover the Pioneering Visionaries, the Milestones of Progress, and the Challenges Overcome, All Weaving Together to Shape the Vibrant Story of Our Institution. Join Us in Celebrating a Legacy of Academic Achievement, Innovation, and Community Impact, Spanning Generations and Inspiring Futures Yet to Come.
                                </template>
                                </v-card>

                                <div class="mt-4 text-subtitle-2">With markup</div>

                                <v-card width="400">
                                <v-card-item>
                                    <v-card-title>Our vision for the future</v-card-title>

                                    <v-card-subtitle>Our goals&Aspirations</v-card-subtitle>
                                </v-card-item>

                                <v-card-text>
                                    Envisioning Tomorrow's Horizons: Our University's Goals and Aspirations Resonate with Ambition, Guiding Every Endeavor Towards the Pursuit of Academic Excellence, Innovation, and Societal Impact. With a Firm Commitment to Empowering Learners, Advancing Knowledge Frontiers, and Fostering Global Citizenship, We Aim to Forge a Future Where Boundaries Fade, Possibilities Flourish, and Transformational Change Shapes the World We Inhabit. Join Us as We Aspire to Inspire, Embarking Together on a Journey of Endless Discovery and Purposeful Achievement.
                                </v-card-text>
                                </v-card>
                            </div>
                        </v-row>
                    </v-container>
                </v-layout>
            </v-container>
    </div>
</template>
<script setup>
  const variants = ['elevated', 'flat', 'tonal', 'outlined']
</script>