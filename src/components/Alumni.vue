<template>
    <div id = 'Alumni'>
        <v-container>
                <v-layout column>
                    <v-carousel>
                        <v-carousel-item
                            src="https://media.istockphoto.com/id/1496191790/photo/portrait-of-young-graduates-embracing-their-parents-on-graduation.jpg?s=1024x1024&w=is&k=20&c=95-EFoGDEnDS5WjhS2_8ORvG6oIiskE_otEY5-X6K3s="
                            cover
                        ></v-carousel-item>

                        <v-carousel-item
                            src="https://media.istockphoto.com/id/1519542517/photo/convocation-ceremony-rear-view-asian-graduation-university-students-together-with-dean.jpg?s=1024x1024&w=is&k=20&c=SCjB3VsvbrJ3fiQyiByUirflXJuDbBLZr28G2HyuV3k="
                            cover
                        ></v-carousel-item>

                        <v-carousel-item
                            src="https://media.istockphoto.com/id/1789172414/photo/woman-finger-touch-job-search-hologram-with-diverse-business-icons.jpg?s=1024x1024&w=is&k=20&c=CEaZ3IlYHKupv2GbMBTUtsOe5IFczw6R3znO_aSzAlc="
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
                                title="Alumni Relations"
                                subtitle="Activities and programs aimed at fostering a sense of community among former students, including alumni networking events, reunions, and communication channels."
                                text="Strengthening Bonds, Creating Legacies: Our Alumni Relations Program Embodies the Spirit of Connection and Continuity, Nurturing Lifelong Relationships Beyond Graduation. Through a Tapestry of Engagement Opportunities, from Reunions to Networking Events, Mentorship Programs to Volunteer Initiatives, We Cultivate a Vibrant Community Where Alumni Thrive, Share, and Inspire. Together, We Honor the Past, Celebrate the Present, and Shape the Future of Our Alma Mater, Forging a Legacy of Excellence that Endures Across Generations."
                                ></v-card>

                                <div class="mt-4 text-subtitle-2">With slots</div>

                                <v-card width="400">
                                <template v-slot:title>
                                    Alumni Associations
                                </template>

                                <template v-slot:subtitle>
                                    Formal organizations established to connect graduates of a particular institution or program, often providing networking opportunities, career services, and social events.
                                </template>

                                <template v-slot:text>
                                    Forging Everlasting Bonds: Our Alumni Associations Stand as Pillars of Unity and Support, Enriching the Lives of Graduates Far and Wide. With a Legacy of Tradition and Pride, We Extend a Warm Welcome to All Who Have Walked Our Hallowed Halls, Providing a Home Away from Home Where Memories are Cherished, Friendships Flourish, and Opportunities Abound. Through a Spectrum of Activities, from Reunions to Networking Events, Mentorship Programs to Volunteer Initiatives, We Foster a Spirit of Camaraderie and Giving Back, Empowering Alumni to Make a Lasting Impact in Their Communities and Beyond. Together, We Honor the Past, Celebrate the Present, and Shape the Future of Our Alma Mater, Forging a Legacy of Excellence that Transcends Time.
                                </template>
                                </v-card>

                                <div class="mt-4 text-subtitle-2">With markup</div>

                                <v-card width="400">
                                <v-card-item>
                                    <v-card-title>Alumni Career Services</v-card-title>

                                    <v-card-subtitle>Resources and support for alumni in career advancement, job search, and professional development, including job boards, resume assistance, and networking opportunities.</v-card-subtitle>
                                </v-card-item>

                                <v-card-text>
                                    Charting Paths to Success: Our Comprehensive Alumni Career Services Program is More Than Just a Resource - It's a Lifeline for Graduates Navigating the Complexities of the Professional World. With a Commitment to Lifelong Learning and Growth, We Provide a Spectrum of Tailored Services and Support, from Personalized Career Counseling and Resume Assistance to Networking Events, Job Fairs, and Professional Development Workshops. Whether Alumni are Seeking to Advance in Their Current Career, Transition to a New Field, or Explore Entrepreneurial Ventures, Our Program Equips Them with the Tools, Connections, and Confidence Needed to Thrive. Join Us in Empowering Alumni to Fulfill Their Potential, Realize Their Dreams, and Make Meaningful Contributions to Their Communities and Beyond.
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