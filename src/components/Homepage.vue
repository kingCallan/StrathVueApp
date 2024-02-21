<template>
    <div id = 'homepage'>
        <v-container>
                <v-layout column>
                    <v-carousel>
                        <v-carousel-item
                            src="https://media.istockphoto.com/id/1452684770/photo/group-of-smiling-young-colleagues-walking-and-talking-in-modern-office.jpg?s=1024x1024&w=is&k=20&c=4QC8MREWrD_kWlWOGVNS5NMh7KQ2CiWVobnrlGgrSLA="
                            cover
                        ></v-carousel-item>

                        <v-carousel-item
                            src="https://media.istockphoto.com/id/1351718103/photo/we-start-living-together.jpg?s=1024x1024&w=is&k=20&c=t6wKh8rSOUf5DjP3-aJQSbA09oMoEylrQgBgTSVclE8="
                            cover
                        ></v-carousel-item>

                        <v-carousel-item
                            src="https://media.istockphoto.com/id/1829008488/photo/team-of-young-female-soccer-players-cheering-on-field-after-a-match.jpg?s=1024x1024&w=is&k=20&c=1aEh6u5PSWuxunzt8lstqKVLUs3pHA_-5G3NUeXaUEg="
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
                                title="Student Life"
                                subtitle="This is my experience so far"
                                text="Embarking on the journey of student life has been a whirlwind of experiences, from the excitement of new friendships and intellectual exploration to the daunting challenges of exams and deadlines. Amidst the endless sea of textbooks and late-night study sessions fueled by coffee, there have been moments of pure inspiration and revelation that remind me why I embarked on this path in the first place. Each day brings its own set of trials and triumphs, shaping me into a more resilient and determined individual. Through it all, I am learning, growing, and embracing the adventure of higher education with open arms."
                                ></v-card>

                                <div class="mt-4 text-subtitle-2">With slots</div>

                                <v-card width="400">
                                <template v-slot:title>
                                    Accommodation
                                </template>

                                <template v-slot:subtitle>
                                    Living Alone
                                </template>

                                <template v-slot:text>
                                    In the sanctuary of accommodation living alone, I've found a haven for self-discovery, independence, and the pursuit of personal growth. Amidst the bustling rhythms of student life, this space offers moments of quiet reflection, where I can delve into my studies, explore my passions, and nurture my individuality. From decorating my own space to mastering the art of budgeting and meal prep, every aspect of solo living has become a lesson in resilience and self-sufficiency. Through the ups and downs, I've come to appreciate the freedom and autonomy that comes with this lifestyle, cherishing the opportunity to carve out my own path and create a home that reflects my unique identity.
                                </template>
                                </v-card>

                                <div class="mt-4 text-subtitle-2">With markup</div>

                                <v-card width="400">
                                <v-card-item>
                                    <v-card-title>Sports</v-card-title>

                                    <v-card-subtitle>Extracurricular</v-card-subtitle>
                                </v-card-item>

                                <v-card-text>
                                    Stepping onto the field, court, or track, I enter a realm where passion meets perseverance, and every movement is a testament to dedication. In the world of sports, there's a symphony of effort and strategy, where athletes push their limits, both physically and mentally, striving for excellence. From the adrenaline rush of competition to the camaraderie forged through teamwork, every game, match, or race is a journey of growth and self-discovery. Whether it's the thrill of victory or the lessons learned in defeat, sports teach us resilience, discipline, and the power of relentless pursuit. In this arena, we transcend boundaries, unite communities, and celebrate the boundless potential of the human spirit.
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