<template>
<v-app id="home" :style="{background: $vuetify.theme.themes.dark.background}">
<navbar />
<v-container fluid>
   <v-row>
     <v-col cols="6">
       <v-img src="IMG_20200620_172933309_PORTRAIT_2-removebg-preview.png" contain max-height="700"></v-img>
     </v-col>
     <v-col cols="6">
       <h4 class=" black--text text-darden-4 top"> Olá meu nome é Willian Diaz</h4>
       <h1 class="w3-dark-gray--text">Desenvolvedor FullStack</h1>
       <p>“Às vezes, quando você inova, comete erros. É melhor admiti-los rapidamente e continuar a melhorar suas outras inovações.” Steve Jobs</p>
       <v-btn tile color="#A7121D" dark> mina historia</v-btn>

     </v-col>
    <v-col cols="12" class="padd">
      <div class="first" id="parject">
        <v-row>
          <v-col cols="12">
            <div class="child bgColor1">
              <v-icon color="#CFD8DC" x-large class="ml-3">
                 fa-solid fa-computer
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
            <div class="child bgColor1">
              <v-icon x-large class="ml-3" color="#CFD8DC">mdi-shopping</v-icon>
              <h3 class="white--text ml-3 mt-4">en construccion!</h3>
              <p class="grey--text ml-3 mt-6">
                vamos a ver que pudeo <br /> poner en este lugar
                ok.
              </p>
              <v-btn color="#A7121D" white text>construindo!
                <v-icon>mdi-arrow-right</v-icon>
              </v-btn>
              </div>
              <div class="child bgColor1">
                <v-icon color="#CFD8DC" x-large class="ml-3">mdi-book-open-page-variant</v-icon>
                <h3 class="white--text ml-3 mt-4">tener una idea</h3>
                <p class="grey--text ml-3 mt-6">
                  haciendo la estructura <br />vamos a 
                  ver que sale
                </p>
                <v-btn color="#A7121D" dark text>
                saber mais
                <v-icon right>mdi-arrow-right </v-icon>
              </v-btn>
              </div>
          </v-col>
          <v-col cols="12" class="mt-10">
            <div class=" child1">
              <h1 class="red--text text-darken-4 mt-4 number">3</h1>
              <h3 class="white-text mt-4">anos de expca</h3>
            </div>
            <div class="child2 mRight">
              <v-row>
                <v-col cols="12" class="childco1">
                  <div class="child2 mButton padding bgColor1">
                    <h1 class="red--text text--darken-4">00</h1>
                    <p class="grey--text">idea!</p>
                  </div>
                </v-col>
                <v-col cols="12" class="childco1">
                  <div class="child2 padding bgColor1">
                    <h1 class="red--text text--darken-4">00</h1>
                    <p class="grey--text">en construccion</p>
                  </div>
                </v-col>
              </v-row>
            </div>
            <div class="child2 ">
              <v-row>
                <v-col cols="12" class="childco1">
                  <div class="child2 mButton padding bgColor1">
                    <h1 class="red--text text--darken-4">00</h1>
                    <p class="grey--text">anos de experiencia!</p>
                  </div>
                </v-col>
                <v-col cols="12" class="childco1">
                  <div class="child2 padding bgColor1">
                    <h1 class="red--text text--darken-4">00</h1>
                    <p class="grey--text">en construccion</p>
                  </div>
                </v-col>
              </v-row>
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
    #000000,
    #CFD8DC 50%,
    #000000 50%,
    #CFD8DC 50%
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
  background-color: #000000 ;
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
