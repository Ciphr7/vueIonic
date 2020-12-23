<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>All Memories</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content>
      <ion-list>
          <ion-item>Gil</ion-item>
           <ion-item>Yvett</ion-item>
            <ion-item>Jason</ion-item>
             <ion-item>Alex</ion-item>
              <ion-item>Heysie</ion-item>
               <ion-item>Aaron</ion-item>
      </ion-list>
    </ion-content>
  </ion-page>
</template>

<script>
import {
  IonPage,
  IonHeader,
  IonTitle,
  IonToolbar,
  IonContent,
  IonList,
  IonItem,
} from "@ionic/vue";
export default {
  components: {
    IonPage,
    IonHeader,
    IonTitle,
    IonToolbar,
    IonContent,
    IonList,
    IonItem,
  },
};
</script>
