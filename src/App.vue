
<template>
    <div>
        <app-header></app-header>
    <section>
         <v-parallax :src="require('@/assets/bg.jpg')" height="600">
          <v-layout
            column
            align-center
            justify-center
          >
            <img src='@/assets/White.png' alt="Due design" height="300">
            <br>
            <h2 class="white--text">Applying thoughts</h2>                   
          </v-layout>
        </v-parallax>
        </section>
        
        
        <app-main></app-main>
        <app-footer></app-footer>
    </div>
</template>

<script>
// Imports
import Header from './components/Header.vue';
import Footer from './components/Footer.vue';
import HelloWorld from './components/HelloWorld.vue';
import Designs from './components/Designs.vue';
export default {
    components: {
        'app-header': Header,
        'app-footer': Footer,
        'app-main': HelloWorld,
        'app-designs': Designs
    },
    data () {
        return {
        }
    }
}
</script>

<style>
body{
    margin: 0;
    font-family: 'Simplifica';
}
header{
    margin: 0;
    font-family: 'Simplifica';
}
</style>

