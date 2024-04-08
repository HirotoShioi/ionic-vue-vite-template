<template>
  <IonMenu side="start" content-id="main">
    <IonHeader>
      <IonToolbar>
        <IonTitle>App Title</IonTitle>
      </IonToolbar>
    </IonHeader>
    <IonContent>
      <IonList>
        <IonMenuToggle :auto-hide="false">
          <IonItem routerLink="/" button lines="full">
            <IonLabel>Home</IonLabel>
          </IonItem>
        </IonMenuToggle>
        <IonMenuToggle :auto-hide="false">
          <IonItem routerLink="/settings" button lines="full">
            <IonLabel>Settings</IonLabel>
          </IonItem>
        </IonMenuToggle>
      </IonList>
    </IonContent>
  </IonMenu>
</template>

<script setup lang="ts">
import {
  IonMenu,
  IonHeader,
  IonToolbar,
  IonTitle,
  IonContent,
  IonList,
  IonMenuToggle,
  IonItem,
  IonLabel,
} from "@ionic/vue";
</script>
