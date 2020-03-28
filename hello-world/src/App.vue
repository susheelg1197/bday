<template>
<div id="app">
     <v-app>
        <app-navigation></app-navigation>

        <v-content transition="slide-x-transition">
            <router-view></router-view>
        </v-content>
    </v-app>
  <Firework :boxHeight="'100%'" :boxWidth="'100%'"/>
    </div>
</template>

<script>
import AppNavigation from '@/components/AppNavigation';
import Firework from './components/fireworks.vue'

export default {
    name: 'App',
    components: {
        AppNavigation,
        Firework
    }
};
</script>

<style>
</style>