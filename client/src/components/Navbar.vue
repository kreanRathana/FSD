<template>
  <div>
    <v-app-bar
      app
      color="#3B506F"
      dark
      height="80"
    >
      <div class="d-flex align-center">
        <v-avatar
            class="profile ml-12"
            color="white"
            size="90"
          >
            <v-img  
            alt="Vuetify Logo"
            class="shrink"
          src="../assets/nvna_logo.jpg"
          transition="scale-transition"
          width="100">
            </v-img>
          </v-avatar>

        <v-img
          alt="Vuetify Name"
          class="shrink mt-1 hidden-sm-and-down"
          contain
          min-width="100"
          src="https://cdn.vuetifyjs.com/images/logos/vuetify-name-dark.png"
          width="200"
        />
      </div>  
      <v-text-field 
            hide-details 
            label="Filled" 
            placeholder="Search" 
            filled 
            rounded 
            dense
            solo-inverted 
            single-line 
            append-icon="mdi-magnify" class="shrink">
      </v-text-field>  
        <v-btn 
        outlined 
        class="ml-4">Search</v-btn>
        <v-spacer></v-spacer>

      <v-btn
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
        target="_blank"
        text
      >
        <span class="mr-2">Latest Release</span>
        <v-icon>mdi-open-in-new</v-icon>
      </v-btn>
    </v-app-bar>
  </div>
</template>
<script>
export default {
    
}
</script>