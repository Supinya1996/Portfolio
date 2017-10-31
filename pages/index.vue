<template>
  <v-content>
    <section>
            <v-parallax src="/Home.jpg" height="500">
              <v-layout column align-center justify-center class="white--text" >
                <v-avatar size="250px">
                  <img
                    class="img-circle elevation-7 mb-1"
                    src="/profile.jpg"
                  >
                </v-avatar>
                <h1 class="white--text" >Portfolio</h1>
                <h4 class="white--text">Supinya Chankate</h4>
              </v-layout>
            </v-parallax>
    </section>

    <section >
          <v-layout
            column
            wrap
            class="my-5"
            align-center
          >
            <v-flex xs12>
              <v-container grid-list-xl>
                <v-layout row wrap align-center>
                  <v-flex xs12 md4>
                    <v-card class="elevation-0 transparent">
                      <v-card-text class="text-xs-center">
                        <v-icon x-large class="blue--text text--lighten-2">assignment_ind</v-icon>
                      </v-card-text>
                      <v-card-title primary-title class="layout justify-center">
                        <div class="headline text-xs-center">About Me</div>
                      </v-card-title>
                      <v-card-text class="text-xs-left">
                        <h6>ชื่อ : ศุภิณญา จันทร์เกตุ</h6>
                        <h6>ชื่อเล่น : เจมส์</h6>
                        <h6>วันเดือนปีเกิด : 31 พฤษภาคม 2539</h6>
                        <h6>สัญชาติ : ไทย  เชื้อชาติ : ไทย  ศาสนา : พุทธ</h6>
                        <h6>ที่อยู่ : 17/3 ถ.ราชบุตร ต.เวียง อ.เมือง จ.พะเยา 56000</h6>
                      </v-card-text>
                    </v-card>
                  </v-flex>
                  <v-flex xs12 md4>
                    <v-card class="elevation-0 transparent">
                      <v-card-text class="text-xs-center">
                        <v-icon x-large class="blue--text text--lighten-2">accessibility</v-icon>
                      </v-card-text>
                      <v-card-title primary-title class="layout justify-center">
                        <div class="headline">Family</div>
                      </v-card-title>
                      <v-card-text class="text-xs-left">
                        <h6>ชื่อมารดา : พยอม จันทร์เกตุ </h6>
                        <h6>อายุ : 51 ปี  อาชีพ : ค้าขาย </h6>
                        <h6>ชื่อบิดา : ธัญญา จันทร์เกตุ (เสียชีวิต)</h6>
                        <h6 class="hidden-xs-only">&nbsp;</h6>
                        <h6 class="hidden-xs-only">&nbsp;</h6>
                        <h6 class="hidden-xs-only">&nbsp;</h6>
                      </v-card-text>
                    </v-card>
                  </v-flex>
                  <v-flex xs12 md4>
                    <v-card class="elevation-0 transparent">
                      <v-card-text class="text-xs-center">
                        <v-icon x-large class="blue--text text--lighten-2">code</v-icon>
                      </v-card-text>
                      <v-card-title primary-title class="layout justify-center">
                        <div class="headline text-xs-center">Skill</div>
                      </v-card-title>
                      <v-card-text>
                            <div>
                              <v-progress-circular
                                v-bind:size="100"
                                v-bind:width="15"
                                v-bind:rotate="270"
                                v-bind:value="80"
                                color="pink"
                              >
                                Java
                              </v-progress-circular>
                              &nbsp;
                              <v-progress-circular
                                v-bind:size="100"
                                v-bind:width="15"
                                v-bind:rotate="270"
                                v-bind:value="35"
                                color="cyan"
                              >
                                Python
                              </v-progress-circular>
                              &nbsp;
                              <v-progress-circular
                                v-bind:size="100"
                                v-bind:width="15"
                                v-bind:rotate="270"
                                v-bind:value="40"
                                color="deep-orange"
                              >
                                PHP
                              </v-progress-circular>
                            </div>

                            <div>
                              <v-progress-circular
                                v-bind:size="100"
                                v-bind:width="15"
                                v-bind:rotate="270"
                                v-bind:value="50"
                                color="indigo"
                              >
                                HTML
                              </v-progress-circular>
                              &nbsp;
                              <v-progress-circular
                                v-bind:size="100"
                                v-bind:width="15"
                                v-bind:rotate="270"
                                v-bind:value="55"
                                color="red"
                              >
                                Photoshop
                              </v-progress-circular>
                              &nbsp;
                              <v-progress-circular
                                v-bind:size="100"
                                v-bind:width="15"
                                v-bind:rotate="270"
                                v-bind:value="45"
                                color="deep-purple"
                              >
                                illustrator
                              </v-progress-circular>
                            </div>
                      </v-card-text>
                    </v-card>
                  </v-flex>
                </v-layout>
              </v-container>
            </v-flex>
          </v-layout>
        </section>

    <section>
            <v-parallax src="/contacts.jpg" height="500">
              <v-layout column align-center justify-center class="white--text" >
                <v-icon style="font-size: 200px" class="yellow--text text--lighten-3" >contacts</v-icon>
                <h3 class="white--text" >Contacts</h3>
                <h4 class="white--text">Phone : 0900537801 , 0942519882</h4>
                <h4 class="white--text">Email : jame_kiki@icloud.com</h4>
                <h4 class="white--text">Line : jame_kiki</h4>
              </v-layout>
            </v-parallax>
    </section>

  </v-content>
</template>

<style>
   @import url('https://fonts.googleapis.com/css?family=Itim');

    #app {
      font-family: 'Itim', Helvetica, Arial, sans-serif;
      -webkit-font-smoothing: antialiased;
      -moz-osx-font-smoothing: grayscale;
      text-align: center;
      margin-top: 1px;
    }


 </style>