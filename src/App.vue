<template>
  <IonApp>
    <Menu />
    <IonRouterOutlet :animated="false" />
  </IonApp>
</template>

<script setup lang="ts">
import { IonApp, IonRouterOutlet } from "@ionic/vue";
import Menu from "@/components/Menu.vue";
</script>
