<template>
 <v-footer id="social" dark padless>
    <v-card class="black white--text py-5 px-5 text-center" width="100%" flat tile >
        <v-row>
            <v-col cols="12" sm="4">
                <v-card-text class="white--text pt2">
                    <v-btn icon>
                        <v-icon color="orange accent-4"> apple</v-icon>
                    </v-btn>
                </v-card-text>
            </v-col>
            <v-col cols="12" sm="4">
                <v-card-text class="pt-2">
                    <v-btn class="mx-1 white--text" icon v-for="icon in icons" :key="icon">
                        <v-icon size="24px">{{icon}}</v-icon>
                    </v-btn>
                </v-card-text>
            </v-col>
            <v-col cols="12" sm="4">
                <v-card-text class="pt-2">
                    <v-btn class="mx-1 white--text" icon>
                        <v-icon color="orange accent-4">mdi-heart</v-icon>
                    </v-btn>
                    Created by MudWebDev
                </v-card-text>
            </v-col>
        </v-row>
    </v-card>
 </v-footer>
</template>

<script>
export default {
data: () => ({
    icons: [
        "mdi-facebook", "mdi-twitter", "mdi-linkedin", "mdi-instagram"
    ]
})
}
</script>

<style>

</style>