<template>
  <IonPage id="main">
    <IonHeader>
      <IonToolbar>
        <IonButtons slot="start">
          <IonMenuButton />
        </IonButtons>
        <IonTitle>Settings</IonTitle>
      </IonToolbar>
    </IonHeader>
    <IonContent class="ion-padding">
      <div class="container">
        <IonCard>
          <IonCardHeader>
            <IonCardTitle>Welcome to Ionic Vue</IonCardTitle>
          </IonCardHeader>
          <IonCardContent>
            <p>
              This is a blank starter project for Ionic Vue. To get started, you
              can edit this content in <code>src/views/Home.vue</code>.
            </p>
          </IonCardContent>
        </IonCard>
      </div>
    </IonContent>
  </IonPage>
</template>

<script setup lang="ts">
import {
  IonPage,
  IonHeader,
  IonToolbar,
  IonTitle,
  IonContent,
  IonCard,
  IonCardHeader,
  IonCardTitle,
  IonCardContent,
  IonButtons,
  IonMenuButton,
} from "@ionic/vue";
</script>
