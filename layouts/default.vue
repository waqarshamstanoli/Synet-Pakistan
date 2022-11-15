<template>
  <v-app light>
    <v-app-bar elevation="0" fixed color="transparent">
      <v-toolbar-title>
        <img
          :src="require('../assets/logo (2).svg')"
          width="150"
          class="mt-2 ml-5"
          lazy-load
        />
      </v-toolbar-title>
<v-spacer></v-spacer>
      <v-toolbar class="hidden-sm-and-down elevation-0" color="transparent">
        <v-toolbar-items class="hidden-sm-and-down">
          <v-btn class="white--text headerFont text-capitalize" text>
            Home
            
          </v-btn>

          <v-btn class="white--text text-capitalize headerFont" text>
            Expertise
            <!-- <v-icon right> -->
              <img
          :src="require('../assets/arrowDown.svg')"
          class="ml-2"
          lazy-load
        />
      <!-- </v-icon> -->
          </v-btn>

          <v-btn text class="mx-5 white--text headerFont text-capitalize"
            >About Us
            <img
          :src="require('../assets/arrowDown.svg')"
          class="ml-2"
          lazy-load
        />
            </v-btn>

          <v-btn text class="white--text headerFont mx-5 text-capitalize">industries</v-btn>
          <v-btn text class="white--text headerFont mx-5 text-capitalize"
            >capital structure
            <img
          :src="require('../assets/arrowDown.svg')"
          class="ml-2"
          lazy-load
        />
        </v-btn>
          <v-btn text class="white--text headerFont mx-5 text-capitalize">people</v-btn>
          <v-btn text class="white--text headerFont mx-5 text-capitalize">careers</v-btn>
          <v-btn text class="white--text headerFont mx-5 text-capitalize">about us</v-btn>
          <v-btn text class="white--text headerFont mx-5 text-capitalize">contact us</v-btn>
          <v-spacer></v-spacer>
          <div class="d-flex mt-5">
            
<v-avatar size="25">
  <v-img
            :src="require('../assets/flag.webp')"
            lazy-load
           ></v-img>
</v-avatar>
<v-img
          :src="require('../assets/arrowDown.svg')"
          class="ml-2"
          lazy-load
        > </v-img>
</div>
        </v-toolbar-items>
      </v-toolbar>
    </v-app-bar>

    <v-main>
      <v-container fluid class="pa-0">
        <Nuxt />
      </v-container>
    </v-main>
    <v-section style="background-color: #000">
      <v-container fluid style="border-bottom: 1px dotted white">
        <v-row>
          <v-col cols="12" lg="3" md="12" sm="12">
            <v-toolbar-title class="pl-0 ml-15 mt-10">
              <v-img
                :src="require('../assets/logo (2).svg')"
                width="160"
                class="mt-4"
                lazy-load
              ></v-img>
            </v-toolbar-title>
            <v-list dense color="transparent" class="white--text ml-13 mt-5">
              <v-list-item>
                <v-list-item-icon>
                  <v-img
                    :src="require('../assets/tel.svg')"
                    width="20"
                    lazy-load
                  ></v-img
                ></v-list-item-icon>
                <v-list-item-title class="white--text"
                  >(126) 123 1234</v-list-item-title
                >
              </v-list-item>
              <v-list-item>
                <v-list-item-icon class="">
                  <img
                    :src="require('../assets/mail.svg')"
                    width="20"
                    lazy-load
                /></v-list-item-icon>
                <v-list-item-title class="white--text"
                  >info@example.com</v-list-item-title
                >
              </v-list-item>
            </v-list>
            <div class="d-flex mt-2 ml-16 mt-5">
              <img
                :src="require('../assets/f_1_.svg')"
                width="10px"
                lazy-load
              />
              <img
                :src="require('../assets/insta.svg')"
                class="ml-5"
                width="20px"
                lazy-load
              />
              <img
                :src="require('../assets/_x30_4.Twitter.svg')"
                class="ml-5"
                width="20px"
                lazy-load
              />

              <img
                :src="require('../assets/linkedin-black 1.svg')"
                class="ml-5"
                width="20px"
                lazy-load
              />
              <img
                :src="require('../assets/youtube-black 1.svg')"
                class="ml-5"
                width="20px"
                lazy-load
              />
              <img
                :src="require('../assets/pinterest.svg')"
                class="ml-5"
                width="20px"
                lazy-load
              />
            </div>
            <v-text-field
              outlined
              dense
              label="Type Email"
              class="borderRadius mt-5"
            >
            </v-text-field>
          </v-col>
          <v-col cols="12" lg="3" md="6" sm="6">
            <h3 class="mt-16 font-weight-medium white--text">Expertise</h3>
            <ul>
              <li class="white--text">Strategic Planning</li>
              <li class="white--text">Performance Improvement</li>
              <li class="white--text">Digital Transformation</li>
              <li class="white--text">Data & Analytics</li>

              <li class="white--text">Innovation</li>
              <li class="white--text">Technology Services & Cloud</li>
            </ul>
          </v-col>

          <v-col cols="12" lg="3" md="12" sm="12">
            <h3 class="mt-16 font-weight-medium ml-4 white--text">
              Capital Structure
            </h3>
            <ul>
              <li class="white--text">Public Companies</li>
              <li class="white--text">Private Equity</li>
              <li class="white--text">Venture Capital</li>

              <li class="white--text">Federal & State Government</li>
              <li class="white--text">Academia & Non-Profits</li>
            </ul>
          </v-col>
          <v-col cols="12" lg="3" md="12" sm="12">
            <div class="d-flex">
              <div> 
            <h3 class="mt-16 font-weight-medium ml-4 white--text">
              Useful Links
            </h3>
            <ul>
              <li class="white--text">About Us</li>
              <li class="white--text">Careers</li>
              <li class="white--text">terms & conditions</li>
              <li class="white--text">Careers</li>

              <li class="white--text">Careers</li>
            </ul>
          </div>
            <img :src="require('../assets/Group 124.svg')" width="200" class="ml-10" lazy-load/>
          </div>
          </v-col>
        </v-row>
      </v-container>
      <div class="white--text my-5 text-center"
        >
        <p>
        Copyright &copy; {{ new Date().getFullYear() }} All Rights
        Reserved
      </p></div
      >
    </v-section>
    
  </v-app>
</template>

<script>
import lazyLoad from "vue-lazyload";
export default {
  target: "static",
  components: { lazyLoad },
  name: "DefaultLayout",
  data() {
    return {
      clipped: false,
      drawer: false,
      fixed: false,
      src: "",
      right: true,
      rightDrawer: false,

      items: [
        {
          title: "(126) 123 1234",
          to: "/cross-platform-appDevelopment",
        },

        {
          title: "info@example.com",
          to: "/innovation-product-development",
        },
      ],
    };
  },
  methods: {},
};
</script>
<style >
li {
  font-family: "Raleway";
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  margin-top: 40px;
}
.headerFont {
  font-family: "Raleway";
  font-size: 16px;
  font-weight: 500;
}
@font-face {
  font-family: "Raleway";
  src: url(../assets/font/Raleway-Regular.ttf);
}
</style>
