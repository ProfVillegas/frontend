<template>
    <span>
        <v-app-bar color="deep-purple" dark>
            <v-app-bar-nav-icon 
            class="hidden-md-and-up"
            @click="drawer= !drawer"
            ></v-app-bar-nav-icon>
            <v-toolbar-title>Sys.Dev</v-toolbar-title>
            <v-spacer class="hidden-md-and-up"></v-spacer>
            <v-btn to="/" flat class="hidden-md-and-up">Home</v-btn>
            <v-spacer class="hidden-md-and-up"></v-spacer>
            <v-btn to="/about" flat class="hidden-md-and-up">About</v-btn>
        </v-app-bar>
    </span>
</template>
<script>
export default {
    name:"AppNavigation",
    data(){
        return{
            drawer:false
        }
    }
}
</script>