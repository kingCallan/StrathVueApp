<template>
    <div id = 'Events'>
        <v-container>
                <v-layout column>
                    <v-carousel>
                        <v-carousel-item
                            src="https://media.istockphoto.com/id/941328776/photo/artists-collection-at-showroom.jpg?s=1024x1024&w=is&k=20&c=s7cZ4idRGdgrORk9VIXSP_mK2yb04f64fiZAsxfmjD4="
                            cover
                        ></v-carousel-item>

                        <v-carousel-item
                            src="https://media.istockphoto.com/id/957689782/photo/business-people-having-a-meeting.jpg?s=1024x1024&w=is&k=20&c=fqH3Qr1MPWEW-UCEV6zlJe-Tn-RHohFXVlwyWytvrR0="
                            cover
                        ></v-carousel-item>

                        <v-carousel-item
                            src="https://media.istockphoto.com/id/469711926/photo/audience-in-the-lecture-hall.jpg?s=1024x1024&w=is&k=20&c=sIHRV8ofQS44UAG-q3eJoKI5qYT3_3UNzYAYfltCY_s="
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
                                title="What is happening?"
                                subtitle="Arts and Culture Expo"
                                text="Celebrate Diversity, Creativity, and Expression at Our Annual Arts and Culture Expo! Immerse Yourself in a Vibrant Tapestry of Talent, Where Every Brushstroke Tells a Story and Every Note Sings of Passion. From Captivating Art Exhibits to Enchanting Musical Performances, Dance Spectacles, and Cultural Showcases, Our Expo Promises to Transport You on a Journey of Inspiration and Discovery. Come Witness the Beauty of Human Expression and Unleash Your Own Creative Spirit! Join Us for a Day of Artistic Exploration and Cultural Celebration Like No Other!"
                                ></v-card>

                                <div class="mt-4 text-subtitle-2">With slots</div>

                                <v-card width="400">
                                <template v-slot:title>
                                    What will be happening?
                                </template>

                                <template v-slot:subtitle>
                                    Technology and Innovation Exhibit
                                </template>

                                <template v-slot:text>
                                    Step Into Tomorrow: Explore the Boundless Horizons of Innovation at Our Technology and Innovation Exhibit! From Cutting-Edge Robotics to Revolutionary AI, Virtual Reality Adventures, and Sustainable Solutions, Embark on a Journey Through the Technological Frontier. Engage with the Creators, Test the Latest Gadgets, and Witness the Future Unfold Before Your Eyes. Join Us in Igniting Curiosity, Fostering Creativity, and Embracing the Possibilities of Tomorrow. Dare to Dream, Dare to Innovate – Welcome to the Future!
                                </template>
                                </v-card>

                                <div class="mt-4 text-subtitle-2">With markup</div>

                                <v-card width="400">
                                <v-card-item>
                                    <v-card-title>What already happened?</v-card-title>

                                    <v-card-subtitle>Educational Workshop/Seminar</v-card-subtitle>
                                </v-card-item>

                                <v-card-text>
                                    Empowerment Through Education: Enrich Your Mind and Expand Your Horizons at Our Educational Workshop/Seminar! Unlock the Tools for Success, Discover Strategies for Lifelong Learning, and Forge Pathways to Achievement. Join Expert Speakers, Engage in Interactive Sessions, and Equip Yourself with Valuable Insights and Skills. Whether You're Navigating Academia, Pursuing Personal Growth, or Planning Your Future, Our Workshop/Seminar Offers the Knowledge and Support You Need to Thrive. Invest in Yourself Today for a Brighter Tomorrow!
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