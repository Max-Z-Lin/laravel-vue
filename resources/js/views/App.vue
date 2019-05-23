<template>
    <v-app>
        <v-navigation-drawer app></v-navigation-drawer>
        <v-toolbar app></v-toolbar>
        <v-content>
            <v-container fluid >
                <router-link tag="li" style="color:black;" to="/" >home</router-link>
                <router-link tag="li" to="/about">about</router-link>

                <router-view></router-view>
            </v-container>
        </v-content>
        <v-footer app></v-footer>
    </v-app>
</template>

<script>
    export default {}
</script>
