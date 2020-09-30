<template>
  <v-app id="inspire">
    <v-app-bar
      app
      shrink-on-scroll
    >
      <v-app-bar-nav-icon></v-app-bar-nav-icon>

      <v-toolbar-title>Application</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-btn icon>
        <v-icon>mdi-dots-vertical</v-icon>
      </v-btn>
    </v-app-bar>

    <v-main>
      <v-container>
        <v-row>
          <v-col cols="12">
            <v-card height="300">
                  <v-row no-gutters>
                    <!-- image -->
                     <v-col cols="4">
                        <v-card
                           class="pa-2">
                              <v-img
                                :src="require('../assets/Angkor Wat.png')"
                                height="250"
                                width="400"
                                class="grey darken-4">
                            </v-img>
                      </v-card>
                      </v-col>
                <v-col cols="6">
                  <v-container
                    class="pa-2"
                    
                  >
                    <h1>Angkor Wat template</h1>
                    <div>
                      <p style="color:gray;font-family: 'Lucida Console', Courier, monospace;">Siem Reap, Cambodia</p>
                    </div>
                  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatum aliquam commodi quas consequuntur 
                    eligendi? Facilis illo odio sed sapiente aspernatur soluta,Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatum aliquam commodi quas consequuntur 
                    eligendi? Facilis illo odio sed sapiente aspernatur soluta</p>
                  </v-container>
                </v-col>
              </v-row>
            </v-card>
          </v-col>
        </v-row>
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
  export default {
    //
  }
</script>