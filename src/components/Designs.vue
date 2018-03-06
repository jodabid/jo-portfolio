<template>
<v-container fluid grid-list-lg >
  <v-layout >
    <v-flex xs12 sm6 md4>
      <v-card >
        <v-card-media src="require('@/assets/logo.jpg')" height="200px" width="200px">
        </v-card-media>
        <v-card-title primary-title>
          <div>
            <h3 class="headline mb-0">The Eating Game</h3>
             </div>
        </v-card-title>
      </v-card>
    </v-flex>
    
    <v-flex xs12 sm6 md4 >
      <v-card >
        <v-card-media src="/static/src/assets/logo.png" height="200px" >
        </v-card-media>
        <v-card-title primary-title>
          <div>
            <h3 class="headline mb-0">The Eating Game</h3>
              </div>
        </v-card-title>
      </v-card>
    </v-flex>
  </v-layout>
  <v-layout align-center >
    <v-flex xs12 sm6 md4 >
      <v-card >
        <v-card-media src='@/assets/logo.png' height="200px" >
        </v-card-media>
        <v-card-title primary-title>
          <div>
            <h3 class="headline mb-0">The Eating Game</h3>
              </div>
        </v-card-title>
      </v-card>
    </v-flex>
    <v-flex xs12 sm6 md4>
      <v-card >
        <v-card-media src='@/assets/logo.png' height="200px" >
        </v-card-media>
        <v-card-title primary-title>
          <div>
            <h3 class="headline mb-0">The Eating Game</h3>
              </div>
        </v-card-title>
      </v-card>
    </v-flex>
    </v-layout>
    </v-container>


    
</template>



<script>
  export default {
    data () {
      return {
        card_text: 'Test test test'}
    }
  }
  style: {
  background: `url(${this.src}) center center / ${this.contain ? 'contain' : 'cover'} no-repeat`
}
</script>