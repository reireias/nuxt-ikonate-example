<template>
  <v-layout column justify-center align-center>
    <v-flex xs12 sm8 md6>
      <div class="text-xs-center">
        <h1>Nuxt.js + ikonate example</h1>

        <img
          svg-inline
          svg-sprite
          class="ikonate ikonate-red"
          width="24px"
          height="24px"
          src="ikonate/icons/activity.svg"
        />
        <p>24px</p>

        <img
          svg-inline
          svg-sprite
          class="ikonate ikonate-green"
          width="32px"
          height="32px"
          src="ikonate/icons/chart.svg"
        />
        <p>32px</p>

        <img
          svg-inline
          svg-sprite
          class="ikonate ikonate-blue"
          width="48px"
          height="48px"
          src="ikonate/icons/camera.svg"
        />
        <p>48px</p>
      </div>
    </v-flex>
  </v-layout>
</template>

<style>
.ikonate {
  fill: none;
}
.ikonate-red {
  stroke: red;
}
.ikonate-green {
  stroke: green;
}
.ikonate-blue {
  stroke: blue;
}
</style>
