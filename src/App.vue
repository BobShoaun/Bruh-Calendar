<template>
  <ion-app>
    <ion-router-outlet/>
  </ion-app>
</template>

<script lang="ts">

import {IonApp, IonRouterOutlet} from '@ionic/vue';
import {defineComponent} from 'vue';
import "vue-cal";

export default defineComponent({
  name: 'App',
  components: {
    IonApp,
    IonRouterOutlet
  }
});
</script>

<style>
.no-scroll {
  --overflow: hidden;
}

.vertical-align {
  padding-top: 15px;
  text-align: center;
}

.align-help {
  padding-top: 10px;
}
</style>