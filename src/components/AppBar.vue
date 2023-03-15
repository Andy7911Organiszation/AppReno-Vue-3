<template>
    <v-app-bar app :elevation="7" rounded style="background-color : #18A0FB">


        <v-btn>  </v-btn>

        <v-app-bar-title>Renovation</v-app-bar-title>

        <v-btn>Home</v-btn>
        <v-btn>About Us</v-btn>
        <v-btn>How it works</v-btn>

        <v-spacer></v-spacer>

        <!-- <template v-slot:append>
          <v-btn icon="mdi:mdi-dots-vertical">Login</v-btn>

        </template> -->

        <v-btn>Sign Up</v-btn>
        <v-btn>Login In</v-btn>
    </v-app-bar>
</template>


<script lang="ts">
import { defineComponent } from "vue"



export default defineComponent({
    name: 'AppBar'
});
</script>


<style scoped>
/* v-app-bar {
    background-color : #18A0FB;
} */
</style>