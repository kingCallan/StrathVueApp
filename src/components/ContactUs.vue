<template>
    <div id = 'ContactUs'>
        <v-container>
                <v-layout column>
                    <v-carousel>
                        <v-carousel-item
                            src="https://media.istockphoto.com/id/1129113667/photo/got-a-problem-contact-us.jpg?s=1024x1024&w=is&k=20&c=wqidxdGPkidrJy1kLjGg5l_fffRXZETKTwOtGfPNqvU="
                            cover
                        ></v-carousel-item>

                        <v-carousel-item
                            src="https://media.istockphoto.com/id/461064709/photo/blue-contact-us-button-on-a-white-keyboard.jpg?s=1024x1024&w=is&k=20&c=VB8XdOpwr7qfrCllWyBIhrAsoVjoM8ssGCnalHx8GEA="
                            cover
                        ></v-carousel-item>

                        <v-carousel-item
                            src="https://media.istockphoto.com/id/885731084/photo/woman-hand-using-smart-phone-contact-us-connection-concept.jpg?s=1024x1024&w=is&k=20&c=vEsIhgYvSDiZ-x2VvnBZ2siMl7577X9o0ljZON4daxI="
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
                                title="Curious about us?"
                                subtitle="Reach out!"
                                text="Connect, Collaborate, Create: Reach Out to Us and Let's Make Magic Together! Whether You Have Questions, Ideas, or Just Want to Say Hello, We're Here and Ready to Hear from You. Your Voice Matters, Your Input Counts, and Together, We Can Achieve Greatness. Reach Out Today and Let's Start Building Something Extraordinary!"
                                ></v-card>

                                <div class="mt-4 text-subtitle-2">With slots</div>

                                <v-card width="400">
                                <template v-slot:title>
                                    Here's our contact information
                                </template>

                                <template v-slot:subtitle>
                                    Reach out at your convenience!
                                </template>

                                <template v-slot:text>
                                    Main Switchboard: +1 (555) 123-4567
Admissions Office: +1 (555) 987-6543
Registrar's Office: +1 (555) 789-0123
                                </template>
                                </v-card>

                                <div class="mt-4 text-subtitle-2">With markup</div>

                                <v-card width="400">
                                <v-card-item>
                                    <v-card-title>Here's our email information</v-card-title>

                                    <v-card-subtitle>Write to us at your convenience</v-card-subtitle>
                                </v-card-item>

                                <v-card-text>
                                    General Inquiries: info@callanuniversity.edu
Admissions Office: admissions@callanuniversity.edu
Registrar's Office: registrar@callanuniversity.edu
Financial Aid Office: financialaid@callanuniversity.edu
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