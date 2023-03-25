<template>
    <v-container class="container">
    
       <v-row class="estilocompleto" >
       
        <v-bottom-navigation
  :value="value"
  color="teal"
  width="100%"
  max-height="60px"
  background-color="#f6f2f2"
  style="margin-left:-18px; margin-bottom: -2.6%; border-radius: 20px;"
  
>
      <div style="margin-left:-200px; margin-top:1%; margin-right:10px;">
      <v-icon 
      color="blue"
      size="300%"
      left="true"
      >
      mdi-book-account</v-icon>
    </div>
     <h1>Fisica</h1>
      
    <v-avatar
          color="red"
          size="30"
          style="float:right;margin-right:-200px;margin-left:80px;margin-top:10px; position:right;"
        >
          <button @click="vuelveInicio()" class="white--text text-h5">X</button>
        </v-avatar>
  
</v-bottom-navigation>
        
            <v-row >
              <v-col cols="12" sm="8">
              <v-card class="elevation-12 mt-10" color="transparent">
                <v-row style="max-width: 600px; margin-left: 20px; padding-top: 40px;">
                  <h2 class="leta">La cedula y sus funciones</h2>
                </v-row>
                <v-row style=" margin-left: 20px; margin-top:20px">
                    <h6 style="font-weight: bold;">Objetivos:</h6>
                  </v-row>
                <v-row style="max-width: 500px; margin-left: 20px;font-size:20px ">
                  <ul>
                    <li>
                        conocer las celila y sus funiones 
                    </li>
                    <li>
                        conocer las celila y sus funiones 
                    </li>
                    <li>
                        conocer las celila y sus funiones 
                    </li>
                  </ul>
                 </v-row>
                 <v-row style=" margin-left: 20px; margin-top:20px">
                    <h6 style="font-weight: bold;">Descripcion:</h6>
                  </v-row>
                <v-row style="max-width: 500px; margin-left: 20px; ">
                  <h5>a celila es un mecanismo estraño que nos permite extrañar la extrañancion hbc  nh wcw chw rh re f cwh whwrh h</h5>
               </v-row>
               <v-row style=" margin-left: 20px; margin-top:20px">
                <h6 style="font-weight: bold;">Recursos:</h6>
              </v-row>
               <v-row style="max-width: 500px; margin-left: 25px; ">
                <div class="input-group mb-2"  >
                    <v-carousel
                    height="320"
                    hide-delimiter-background
                    show-arrows="hover"
                  >
                    <v-carousel-item
                      v-for="(slide, i) in slides"
                      :key="i"
                    >
                      <v-sheet
                        height="100%"
                      >
                        <div class="d-flex fill-height justify-center align-center">
                          <div class="text-h2">
                            <iframe width="500" style="border-radius: 40px;" height="315" :src="slide" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
                    
                          </div>
                        </div>
                      </v-sheet>
                    </v-carousel-item>
                  </v-carousel>
                </div>
                
               
              </v-row>
              <v-row  style="max-width: 500px; margin-left: 20px; ">
               <ul style="font-weight: bold;color:blue;text-decoration: underline;font-size:20px">
              <li>  <b-icon color="red"  icon="file-earmark-pdf-fill" font-scale="1"></b-icon> aqui saldrian los pdf 1</li>
              <li>  <b-icon color="red"  icon="file-earmark-pdf-fill" font-scale="1"></b-icon> aqui saldrian los pdf 2</li>
              <li>  <b-icon color="red"  icon="file-earmark-pdf-fill" font-scale="1"></b-icon> aqui saldrian los pdf 3</li>
              <li>  <b-icon color="red"  icon="file-earmark-pdf-fill" font-scale="1"></b-icon> aqui saldrian los pdf 4</li>
            </ul>
             </v-row>

                  
              </v-card>
              
            </v-col>
            <v-col cols="12" sm="4">
              <v-card class="elevation-12 mt-10" color="transparent">
                <v-row style=" margin-left: 20px;  padding-top: 10px;" >
                    <label class="leta">Ejercicios</label>
                  </v-row>
                  <v-row  style="max-width: 500px; margin-left: 20px; ">
                    <ul style="font-weight: bold;color:blue;text-decoration: underline;font-size:20px">
                   <li>  <b-icon color="green"  icon="pencil-square" font-scale="1"></b-icon> aqui los ejercicios 1</li>
                   <li>  <b-icon color="green"  icon="pencil-square" font-scale="1"></b-icon> aqui los ejercicios 2</li>
                   <li>  <b-icon color="green"  icon="pencil-square" font-scale="1"></b-icon> aqui los ejercicios 3</li>
                   <li>  <b-icon color="green"  icon="pencil-square" font-scale="1"></b-icon> aqui los ejercicios 4</li>
                 </ul>
                  </v-row>
                <v-row>
                      <vs-button style="margin-left:40%">
                         GUARDAR
                        </vs-button>
                        
                  </v-row>
                  
                          <br>
              </v-card>
            </v-col>
            </v-row>
           <!-- <div>
                    <h2 class="text-center mb-3">Vue Get Full Date and Time Example</h2>
                    <ul class="list-group">
                      <li class="list-group-item" v-show="timestamp"><strong>Timestamp:</strong> {{ timestamp }}</li>
                      <li class="list-group-item" v-show="date1"><strong>Date:</strong> {{ date1 }}</li>
                      <li class="list-group-item" v-show="time"><strong>Time:</strong> {{ time }}</li>
                      <li class="list-group-item" v-show="year"><strong>Current Year:</strong> {{ year }}</li>
                      <li class="list-group-item" v-show="fulldatetime"><strong>Full Date:</strong> {{ fulldatetime }}</li>
                    </ul>
                </div>  -->
               
        </v-row>

        
     <!-- 
  <v-snackbar
      v-model="hasSaved"
      :timeout="5000"
      absolute
      bottom
      left
      color="green"
    >
      {{msg}}
      
    </v-snackbar>
      <v-dialog v-model="hasSaved" persistent max-width="500">
        
        <v-card :style="colo">
          <v-card-title class="text-h5 justify-center">
            {{msg}}
          </v-card-title>
          <v-card-actions>
            <v-spacer></v-spacer>
            <v-btn color="black darken-1" text @click="limpiar()"
                    style=" background-color:#05AFF2;"             >
            OK
            </v-btn>
          </v-card-actions>
        </v-card>
      </v-dialog>-->
   
     
    </v-container>
    
  </template>
<script>
export default{
data() {
  return {
    slides:['https://www.youtube.com/embed/FU-7mHUTJKk','https://www.youtube.com/embed/Xl5FV2Etpg4','https://www.youtube.com/embed/Lz6d1ZlEdPU'],
    nombre:'',
    objetivos:'',
    descripcion:'',
    video:'',
    videos:[],
    pdf:null,
    pdfs:[],
    h5p:[],
  }
},
methods: {
  agregarPdf(){
    let pd = new Object();
    pd.pdf=this.pdf;
    this.pdfs.push(pd);
    this.pdf=null;
    alert('pdf agregado')
  },
  agregarVideo(){
    let vide = new Object();
    vide.url=this.video;
    this.videos.push(vide);
    this.video='';
    alert('video agregado')
  },
},
}
</script>
<style scoped>
  .v-application .rounded-bl-xl {
      border-bottom-left-radius: 300px !important;
  }
  .v-application .rounded-br-xl {
      border-bottom-right-radius: 300px !important;
  }
  .image-col{
    background-image: url("../../assets/imgCrear/actividad.svg");
    background-size: 80vh 50vw;
    background-repeat: no-repeat;
  }

  .container{
    display: flex;
    margin-bottom: 50px;
    
  }
  .estado-tarea{
    width: 240px;
    height: 10px;
  }

   .estado-tarea__buttons{
    background-color: #f6f2f2;
    border-radius: 20px;
    border: 1px solid #C3C3C5;
    height: auto;
    margin-top: auto;
    margin-bottom: auto;
    margin-left: auto;
    margin-right: auto;
  }

  .estado-tarea .estado-tarea__buttons:hover{
    border: 1px solid black;
  }


  .adjuntar{
    background-color: #f6f2f2;
    border-radius: 20px;
    border: 1px solid #C3C3C5;
    width: 300px;
    
    
    padding: 2%;
  }

  .adjuntar:hover{
    border: 1px solid black;
  }

  h4{
    color: black;
    font-weight: 300;
  }

  .save{
    margin-left: 90px;
  }

  .divNew{
    position: absolute;
    background-color: #b99f9f;
    width: 78%;
    background-position-x: center;
    border-radius: 10px;
   
  }

  h1{
    font-size: 36px;
    font-weight: 800;
    color: #0F5C8c;
    display: inline;
    margin-right: 70%;
    margin-top: auto;
  }
  .leta{
    margin-left: 30px;
    font-size: 25px;
    font-weight: 800;
    color: #0F5C8c;
    display: inline;
    
  }
  .estilocompleto{
    margin-left: 50px;
    margin-right: 50px;
    margin-block: 10px;
    
  }
  
  </style>