<template>
  <v-app-bar flat>
    <v-app-bar-title>
<!---      <v-img :width="300" aspect-ratio="1:1" src="../../assets/shuttle-zone-logo.png"></v-img> -->
      Shuttle zone
    </v-app-bar-title>
    <v-container>
    <v-btn-toggle v-model="text"
          rounded="0"
          color="deep-purple-accent-3"
          group>
          <v-btn href="/Tournaments">
            Tournaments
          </v-btn>

          <v-btn href="/Players">
            Players
          </v-btn>

    </v-btn-toggle>
  </v-container> 
  </v-app-bar>
</template>

<script lang="ts" setup>
  //
</script>
