<template>
    <v-container fluid fill-height class="home-hero">
        <v-layout justify-center align-center column pa-5>
            <div class="display-4 font-weight-black black--text text-xs-center">A Very Happy Bday</div>
            <div class="display-4 font-weight-black black--text text-xs-center mb-3">To The Love Of My Life</div>
            <!-- <v-btn raised primary @click="here" fab class="mt-5 brown darken-4"> -->
                 <v-btn class="ma-2" color="primary"
      @click="here()"
    >
      Click Here To play A game for gift
    </v-btn>
            <!-- <v-icon large color="white">Click Here to Start a Game</v-icon> -->
            </v-btn>
        </v-layout>
    </v-container>
</template>

<script>
export default {
    name: 'HomeHero',
    methods:{
        here(){
            console.log("here")
        }
        
        
    }
    
};
</script>
<style scoped>
.home-hero {
    background: url('~@/assets/bdaypics/waterpk2.png');
    background-size: cover;
    width: 100%;
    height: 100%;
}

</style>