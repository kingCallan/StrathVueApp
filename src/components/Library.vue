<template>
    <div id = 'Library'>
        <v-container>
                <v-layout column>
                    <v-carousel>
                        <v-carousel-item
                            src="https://images.unsplash.com/photo-1519389950473-47ba0277781c?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
                            cover
                        ></v-carousel-item>

                        <v-carousel-item
                            src="https://images.unsplash.com/photo-1607859928694-44744cf8b230?q=80&w=1886&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
                            cover
                        ></v-carousel-item>

                        <v-carousel-item
                            src="https://media.istockphoto.com/id/1044823920/photo/journalism.jpg?s=1024x1024&w=is&k=20&c=rmQReFUJT2-dyuUSFjN4qb9qxgsWvRXXv7NFSYFhFN0="
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
                                title="Digital Resources"
                                subtitle="E-books, online databases, digital archives, and other electronic resources accessible through computers or mobile devices."
                                text="Embark on a Digital Odyssey: Journey through Our Extensive Repository of Digital Resources, Where the Infinite Expanse of Information Awaits at Your Fingertips. Delve into a Multitude of Virtual Archives, E-Books, Online Databases, and Interactive Learning Platforms, Each Offering a Gateway to Discovery and Enrichment. From Historical Archives to Cutting-Edge Research, Our Digital Library Empowers Users to Explore, Learn, and Connect with the World's Collective Knowledge, Anytime, Anywhere. Join Us in Embracing the Future of Learning, Where the Possibilities are Limitless and the Adventure Knows No Bounds."
                                ></v-card>

                                <div class="mt-4 text-subtitle-2">With slots</div>

                                <v-card width="400">
                                <template v-slot:title>
                                    Audiovisual materials
                                </template>

                                <template v-slot:subtitle>
                                    DVDs, Blu-rays, CDs, and other media formats, including movies, music, audiobooks, and educational videos.
                                </template>

                                <template v-slot:text>
                                    Dive into a Multisensory Universe: Explore Our Diverse Audiovisual Collection, Where Visual Splendor and Auditory Delight Await. From the Cinematic Grandeur of Classic Films to the Melodic Symphony of Musical Masterpieces, Our Collection Transports You to Worlds Beyond Imagination. Whether You're Seeking Entertainment, Enlightenment, or Inspiration, Our Array of DVDs, Blu-rays, CDs, and Streaming Services Offers a Cornucopia of Cultural Riches to Enrich Your Senses and Expand Your Horizons. Join Us in the Journey of Discovery, Where Every Frame Tells a Story and Every Note Resonates with Meaning.
                                </template>
                                </v-card>

                                <div class="mt-4 text-subtitle-2">With markup</div>

                                <v-card width="400">
                                <v-card-item>
                                    <v-card-title>Periodicals</v-card-title>

                                    <v-card-subtitle>Magazines, journals, newspapers, and other serial publications covering specific topics or areas of interest.</v-card-subtitle>
                                </v-card-item>

                                <v-card-text>
                                    Step into the World of Periodicals: A Treasure Trove of Knowledge, Insight, and Inspiration Awaits. From the Pages of Esteemed Journals to the Vibrant Palette of Glossy Magazines, Our Collection Spans the Spectrum of Human Thought and Creativity. Whether You're Seeking the Latest Scientific Breakthroughs, Cultural Commentary, or Practical How-Tos, Our Periodicals Offer a Window into the World's Most Pressing Issues and Timeless Curiosities. Immerse Yourself in the Rich Tapestry of Ideas, Perspectives, and Stories that Define Our Ever-Evolving Human Experience. Discover, Explore, and Engage with the Infinite Possibilities Within the Pages of Our Periodicals.
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