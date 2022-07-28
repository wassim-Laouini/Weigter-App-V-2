<template>
  <v-app-bar app color="white" flat>
    <v-badge color="#D5F0DB" dot>
      
      <v-img src="1.png" contain width="30"></v-img>
    </v-badge>

    <v-toolbar-title class="ml-4">
      <span class="green--text">e</span><strong>Restau name </strong>
    </v-toolbar-title>

    <v-spacer></v-spacer>
    <v-badge color="#FF6D59" overlap content="2" class="mr-2 mt-1">
      <v-avatar color="#FFF0EE" size="40">
        <v-icon x-small color="#FF6D59">far fa-heart</v-icon>
      </v-avatar>
    </v-badge>
    <v-badge color="#41AB55" overlap content="3" class="mr-2 mt-1">
      <v-avatar color="#ECF7EE" size="40">
        <v-icon x-small color="#41AB55">fas fa-shopping-cart</v-icon>
      </v-avatar>
    </v-badge>
   
   
   
  </v-app-bar>
</template>

<script>
export default {};
</script>

<style>
.v-toolbar__title {
  font-size: 1rem !important;
}
</style>