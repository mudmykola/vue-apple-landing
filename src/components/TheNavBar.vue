<template>
    <v-app-bar app color="#0c0c0d" dark flat class="px-8">
        <v-btn icon>
            <v-icon color="white"> apple</v-icon>
        </v-btn>
        <v-spacer></v-spacer>
        <v-btn text @click="scroll('the-home')">iPhone</v-btn>
        <v-btn text @click="scroll('mac')">Mac</v-btn>
        <v-btn text @click="scroll('airpods')">Airpods</v-btn>
        <v-btn text @click="scroll('contact')">Contact</v-btn>
        <v-btn text @click="scroll('social')">Social</v-btn>
        
    </v-app-bar>
</template>

<script>
export default {
    methods: {
        scroll(refName) {
            const element = document.getElementById(refName);
            element.scrollIntoView({ behavior: "smooth" });
        }
    }
}
</script>

<style>
</style>