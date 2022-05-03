<template>
<v-app id="home" :style="{background: $vuetify.theme.themes.dark.background}">
<navbar />
<v-container fluid>
   <v-row>
     <v-col cols="6">
       <v-img src="IMG-20220502-WA0002-removebg-preview.png" contain max-height="700"></v-img>
     </v-col>
     <v-col cols="6">
       <h4 class=" black--text text-darden-4 top"> olá meu nome é willian diaz</h4>
       <h1 class="w3-dark-gray--text">desenvolvedor FullStack</h1>
       <p>“Há apenas uma maneira de evitar críticas: não fazer, não falar e simplesmente ser nada.” – Aristóteles</p>
       <v-btn tile color="#a7121d" dark> mina historia</v-btn>

     </v-col>
    <v-col cols="12" class="padd">
      <div class="first" id="parject">
        <v-row>
          <v-col cols="12">
            <div class="child bgColor1">
              <v-icon color="#A7121D" x-large class="ml-3">
                mdi-palette-swatch
              </v-icon>
              <h3 class="white--text ml-3 mt-4">tener idea</h3>
              <p class="grey--text ml-3 mt-6">
                tener una idea<br />texto de idea
              </p>
              <v-btn color="#A7121D" dark text>
                saber mais
                <v-icon right>mdi-arrow-right </v-icon>
              </v-btn>

            </div>
          </v-col>
        </v-row>

      </div>
    </v-col>

   </v-row>  
</v-container>
</v-app>
 
</template>

<script>

import Navbar from '../components/Navbar'

export default {
  name: 'Home',

  components: {
    
    Navbar,
  },
}
</script>
<style scoped>
.top{
  margin-top: 180px;
}
.topInverse{
  margin: -250px;
}
.topTolbar{
  margin: 100px;
  text-align: center;
}
.first{
  width: 100%;
  height: 610%;
  background: linear-gradient(
    to right,
    #181818,
    #181818 50%,
    #111111 50%,
    #111111 50%
  );
  text-align: center;
  padding: 2rem 2rem;
}
.second{
  width: 100%;
  height: 400px;
  background: #181818;
  text-align: center;
  padding: 2rem 2rem;
}
.secondchild1{
  display: inline-block;
  background-color: #1e1e1e;
  padding: 2rem 2rem;
  vertical-align:  middle;
  text-align: left;
  margin: 250px;
}
.child {
  display: inline-block;
  padding: 2rem 2rem;
  vertical-align: middle;
  text-align: left;
  margin: 8px;
}
.bgColor1 {
  background-color: #1e1e1e ;
}
.bgColor2 {
  background: #ce1d2a;
}
.child1 {
  display: inline-block;
  padding: 2rem 2rem;
  vertical-align: middle;
  margin-right: 5px;
  width: 240px;

}
.child2 {
  display: inline-block;
  width: 245px;
  vertical-align: middle;
}
.mRight {
  margin-right: 8px;
}
.mButton {
  margin-bottom: 8px;
}
.padding {
  padding: 8px 0px;

}
.col-12.padd {
  padding: 12px 0 !important;
}
.col-12.childco1 {
  padding: o !important;
}
h1.number {
  font-size: 50px;
  font-weight: bold;
}


</style>
