<template>
  <div>
    <v-layout>

      <v-app-bar 
        title="Application Bar"
        color="black"
        flat
        >
      </v-app-bar>


      <!-- <v-navigation-drawer
          class="bg-deep-purple"
          permanent
      >
        <v-list>
          <v-list-item title="Navigation drawer"></v-list-item>
        </v-list>
      </v-navigation-drawer> -->

      <v-main style="min-height: 300px;">
        <!-- <h1>Hello</h1> -->
        <NuxtPage />

      </v-main>

    </v-layout>
  </div>
</template>
