<template>
  <v-container fluid
    ><v-row class="bg-color">
      <!-- First Coloum ------------------- -->
      <v-col cols="12" lg="2" md="6" sm="12">
        <div class="mt-6 text-center">
          <div>
            <v-icon color="black" large>mdi-account-cowboy-hat</v-icon>
          </div>
          <div class="font-weight-black"><h2>SOLARIUS</h2></div>
        </div>
        <div class="ma-6">
          <dir class="hover-efect pa-4 d-flex">
            <div>
              <v-icon color="black">mdi-alien-outline</v-icon>
            </div>
            <div class="font-weight-bold ms-2">Dashboard</div>
          </dir>
          <dir class="hover-efect pa-4 d-flex">
            <div>
              <v-icon color="black">mdi-baby-face-outline</v-icon>
            </div>
            <div class="font-weight-bold ms-2">Education</div>
          </dir>

          <dir class="hover-efect pa-4">
            <div class="float-left">
              <div class="d-flex">
                <div>
                  <v-icon color="black">mdi-biohazard</v-icon>
                </div>
                <div class="font-weight-bold ms-2">Resources</div>
              </div>
            </div>
            <div class="float-right">
              <v-icon color="black">mdi-arrow-down-drop-circle-outline</v-icon>
            </div>
          </dir>

          <dir class="hover-efect pa-4 d-flex mt-4">
            <div>
              <v-icon color="black">mdi-alert-decagram</v-icon>
            </div>
            <div class="font-weight-bold ms-2">Setting</div>
          </dir>
        </div>
        <dir class="pa-4 d-flex">
          <div>
            <v-icon large color="black">mdi-chess-rook</v-icon>
          </div>
          <div class="font-weight-bold ms-2"><h3>Logout</h3></div>
        </dir>
      </v-col>
      <!-- Seconde Coloum ------------------- -->
      <v-col cols="12" lg="4" md="6" sm="12" class="white mt-2 mb-2">
        <div class="ma-6">
          <div class="float-left">
            <dir><h3>Today's Plan</h3></dir>
            <div class="font-weight-light">June 14th, 2022</div>
          </div>
          <div class="float-right">
            <v-icon large color="black">mdi-compass-off</v-icon>
          </div>
          <div class="mt-6 mb-6 float-end">
            <h2>Sustainable development goals and health innovations</h2>
          </div>
          <div class="mt-5">
            <div class="float-left">
              <v-avatar size="45">
                <v-img src="../assets/images/1.jpg"></v-img>
              </v-avatar>
              <v-avatar size="45" style="postion: absolute; left: -15%">
                <v-img src="../assets/images/2.jpg"></v-img>
              </v-avatar>
              <v-avatar size="45" style="postion: absolute; left: -25%">
                <v-img src="../assets/images/3.jpg"></v-img>
              </v-avatar>
              <v-avatar size="45" style="postion: absolute; left: -35%">
                <v-img src="../assets/images/4.jpg"></v-img>
              </v-avatar>
            </div>
            <div class="float-right">
              <div class="font-weight-medium">Medi team meeting</div>
              <div>13:30 - 14:50</div>
            </div>
          </div>
          <v-container class="lighten-5 float-end">
            <v-row no-gutters>
              <v-col cols="12">
                <v-card class="pa-2 purple height_card ma-2" outlined tile>
                </v-card>
              </v-col>
              <v-col cols="6">
                <v-card class="pa-2 blue height_card ma-1" outlined tile>
                </v-card>
              </v-col>
              <v-col cols="6">
                <v-card class="pa-2 green height_card ma-1" outlined tile>
                </v-card>
              </v-col>
            </v-row>
          </v-container>
        </div>
      </v-col>
      <!-- Thired Coloum ------------------- -->
      <v-col cols="12" lg="4" md="6" sm="12">
        <v-container>
          <v-row>
            <v-col cols="12">
              <div class="ma-6">
                <div class="float-left"><h3>Monthly Pin</h3></div>
                <div class="font-weight-light float-right">view all</div>
              </div>
            </v-col>
          </v-row>
          <v-row>
            <v-col
              cols="12"
              style="border: 2px solid grey"
              class="font-weight-light mb-2"
            >
              <div class="ms-6 me-6">
                <v-row>
                  <v-col cols="10">
                    <div class="">Next-gen immuno</div>
                  </v-col>
                  <v-col cols="2"><div class="float-right">5d</div> </v-col>
                  <v-col cols="12"
                    ><h4>Multispecific liquid specalict</h4></v-col
                  >
                  <v-col cols="12"
                    ><dir class="d-flex">
                      <div>
                        <v-icon color="black">mdi-all-inclusive</v-icon>
                      </div>
                      <div class="ms-2">New feedback</div>
                    </dir></v-col
                  >
                </v-row>
              </div>
            </v-col>
            <v-col
              cols="12"
              style="border: 2px solid grey"
              class="font-weight-light mb-2"
            >
              <div class="ms-6 me-6">
                <v-row>
                  <v-col cols="10">
                    <div class="">Next-gen immuno</div>
                  </v-col>
                  <v-col cols="2"><div class="float-right">5d</div> </v-col>
                  <v-col cols="12"
                    ><h4>Multispecific liquid specalict</h4></v-col
                  >
                  <v-col cols="12"
                    ><dir class="d-flex">
                      <div>
                        <v-icon color="black">mdi-all-inclusive</v-icon>
                      </div>
                      <div class="ms-2">New feedback</div>
                    </dir></v-col
                  >
                </v-row>
              </div>
            </v-col>
            <v-col
              cols="12"
              style="border: 2px solid grey"
              class="font-weight-light"
            >
              <div class="ms-6 me-6">
                <v-row>
                  <v-col cols="10">
                    <div class="">Next-gen immuno</div>
                  </v-col>
                  <v-col cols="2"><div class="float-right">5d</div> </v-col>
                  <v-col cols="12"
                    ><h4>Multispecific liquid specalict</h4></v-col
                  >
                  <v-col cols="12"
                    ><dir class="d-flex">
                      <div>
                        <v-icon color="black">mdi-all-inclusive</v-icon>
                      </div>
                      <div class="ms-2">New feedback</div>
                    </dir></v-col
                  >
                </v-row>
              </div>
            </v-col>
            <v-row>
              <v-col cols="12">
                <div class="ma-6">
                  <div class="float-left"><h3>My learnings</h3></div>
                  <div class="font-weight-light float-right">***</div>
                </div>
              </v-col>
              <v-col cols="12" class="ms-6"
                ><p class="">Lorem ipsum dolor sit amet.</p>
              </v-col>
            </v-row>
            <v-row>
              <v-col cols="6">
                <div class="d-flex ms-6">
                  <div>
                    <v-avatar size="45"
                      ><img src="../assets/images/1.jpg" alt=""
                    /></v-avatar>
                  </div>
                  <div class="ms-2">
                    <h4>Virus</h4>
                    <p>94% progress</p>
                  </div>
                </div>
              </v-col>
              <v-col cols="6">
                <div class="d-flex ms-6">
                  <div>
                    <v-avatar size="45"
                      ><img src="../assets/images/2.jpg" alt=""
                    /></v-avatar>
                  </div>
                  <div class="ms-2">
                    <h4>Virus</h4>
                    <p>94% progress</p>
                  </div>
                </div>
              </v-col>
              <v-col cols="6">
                <div class="d-flex ms-6">
                  <div>
                    <v-avatar size="45"
                      ><img src="../assets/images/3.jpg" alt=""
                    /></v-avatar>
                  </div>
                  <div class="ms-2">
                    <h4>Virus</h4>
                    <p>94% progress</p>
                  </div>
                </div>
              </v-col>
              <v-col cols="6">
                <div class="d-flex ms-6">
                  <div>
                    <v-avatar size="45"
                      ><img src="../assets/images/4.jpg" alt=""
                    /></v-avatar>
                  </div>
                  <div class="ms-2">
                    <h4>Virus</h4>
                    <p>94% progress</p>
                  </div>
                </div>
              </v-col>
            </v-row>
          </v-row>
        </v-container>
      </v-col>
      <!-- Fourth Coloum ------------------- -->
      <v-col cols="12" lg="2" md="6" sm="12">
        <div class="py-5 text-center">
          <v-badge
            bordered
            bottom
            color="deep-purple accent-4"
            dot
            offset-x="10"
            offset-y="10"
          >
            <v-avatar size="70">
              <v-img src="../assets/images/2.jpg"></v-img>
            </v-avatar>
          </v-badge>
          <h3 class="mt-3">Dr. Riddle</h3>
          <p>Scientist</p>
        </div>

        <div class="text-center">
          <div>
            <v-icon large color="black" class="ma-2"
              >mdi-fountain-pen-tip</v-icon
            >
          </div>
          <div>
            <v-icon large color="black" class="ma-2"
              >mdi-message-processing-outline
            </v-icon>
          </div>
          <div>
            <v-icon large color="black" class="ma-2"
              >mdi-alpha-g-circle-outline</v-icon
            >
          </div>
        </div>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "HelloWorld",
  data: () => ({}),
};
</script>
<style scope>
.bg-color {
  background-color: #fbf7f4;
}

.height_card {
  height: 200px;
}
.hover-efect:hover {
  background-color: #ccc1be;
}
</style>
