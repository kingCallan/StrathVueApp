<template>
    <div id = 'Partnerships'>
        <v-container>
                <v-layout column>
                    <v-carousel>
                        <v-carousel-item
                            src="https://media.istockphoto.com/id/1443245439/photo/business-meeting-businesswoman-woman-office-portrait-job-career-happy-businessman-teamwork.jpg?s=1024x1024&w=is&k=20&c=NPqjCnSKcneHXR85l-2ZV5SAe0a32eoTkIy5G0sZtgc="
                            cover
                        ></v-carousel-item>

                        <v-carousel-item
                            src="https://media.istockphoto.com/id/1189913170/photo/engineer-and-businessman-handshake-at-construction-site.jpg?s=1024x1024&w=is&k=20&c=oKuIFud_wUJhDW7rK5MFVKQsiHnQR7bZKe8bZ9x1Ojk="
                            cover
                        ></v-carousel-item>

                        <v-carousel-item
                            src="https://media.istockphoto.com/id/1196912174/photo/group-of-people-and-communication-network-concept-human-resources-teamwork-of-business.jpg?s=1024x1024&w=is&k=20&c=R7V_HR7RzaykRUBHohFCZjBBb5MC5hinm3UaOLI-5ow="
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
                                title="Academic Partnerships"
                                subtitle="Collaborations between educational institutions to enhance research, exchange knowledge, and facilitate student mobility programs."
                                text="Building Bridges of Knowledge: Academic Partnerships that Inspire Innovation and Transform Education. At the Heart of Our Commitment to Excellence Lies a Tapestry of Collaborative Endeavors, Where Institutions Unite to Forge New Frontiers in Research, Teaching, and Learning. Through Strategic Alliances with Universities, Colleges, and Research Institutes, We Embrace a Culture of Curiosity, Exchange, and Mutual Enrichment. Together, We Empower Minds, Expand Horizons, and Cultivate the Leaders and Innovators of Tomorrow. Join Us in the Pursuit of Academic Excellence, Where Boundaries Fade and Possibilities Flourish in the Spirit of Collaboration."
                                ></v-card>

                                <div class="mt-4 text-subtitle-2">With slots</div>

                                <v-card width="400">
                                <template v-slot:title>
                                    Industry Partnerships
                                </template>

                                <template v-slot:subtitle>
                                    Alliances with businesses and corporations to drive innovation, develop new technologies, and provide internship or job opportunities for students.
                                </template>

                                <template v-slot:text>
                                    Empowering Innovation Through Strategic Industry Partnerships: Together, We Shape the Future of Technology, Commerce, and Society. Anchored in a Shared Vision of Progress and Excellence, Our Collaborations with Leading Companies and Industry Giants Propel us to New Heights of Discovery and Achievement. By Leveraging Collective Expertise, Resources, and Networks, We Catalyze Innovation, Drive Economic Growth, and Bring Breakthrough Solutions to Market. Join us in the Thrilling Journey of Co-Creation, Where the Boundaries Between Academia and Industry Blur, and Together, We Pioneer the Next Frontier of Possibility.
                                </template>
                                </v-card>

                                <div class="mt-4 text-subtitle-2">With markup</div>

                                <v-card width="400">
                                <v-card-item>
                                    <v-card-title>Government Partnerships</v-card-title>

                                    <v-card-subtitle>Partnerships with governmental agencies or entities to collaborate on research projects, policy development, or community outreach programs.</v-card-subtitle>
                                </v-card-item>

                                <v-card-text>
                                    Charting a Course for Progress: Government Partnerships That Shape Policy, Foster Innovation, and Empower Communities. Rooted in a Shared Commitment to Public Service and Societal Betterment, Our Collaborations with Government Agencies and Entities Drive Meaningful Change and Lasting Impact. Together, We Tackle Complex Challenges, Develop Forward-Thinking Policies, and Implement Initiatives That Strengthen Infrastructure, Promote Economic Development, and Enhance Quality of Life for All. Join Us in the Pursuit of a Brighter Future, Where Government and Civil Society Work Hand in Hand to Build Resilient, Inclusive, and Thriving Communities.
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