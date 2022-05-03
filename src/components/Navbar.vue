<template>
  <v-app-bar app color="#000000" dark flat class="px-8">
      
      <v-btn icon>
            <v-icon color="#CFD8DC"> fa-solid fa-laptop-code </v-icon>
            <v-icon color="#CFD8DC"> fa-solid fa-computer </v-icon>
            
      </v-btn>
      <v-spacer></v-spacer>
      <v-btn text @click="scroll('home')" elevation="2" color="#CFD8DC" large rounded x-large >home</v-btn>
      <v-btn text @click="scroll('projetos')" elevation="2" color="#CFD8DC" large rounded x-large>projetos</v-btn>
      <v-btn text @click="scroll('skill')" elevation="2" color="#CFD8DC" large rounded x-large>skill</v-btn>
      <v-btn text @click="scroll('biografia')" elevation="2" color="#CFD8DC" large rounded x-large>biografia</v-btn>
 </v-app-bar>
</template>

<script>
export default {
      methods: {
            scroll(refName) {
                  const element = document.getElementById(refName);
                  element.scrollIntoView({behavior: "smooth"});
            }
      }

}
</script>

<style>

</style>