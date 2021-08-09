<template>
    <ion-page>
        <ion-header>
            <ion-toolbar>
                <ion-title>Pretty Sweat, Sweat Pretty</ion-title>
            </ion-toolbar>
            
        </ion-header>
        <ion-content>
            <p class="ion-padding-start">Workout Record</p>
            <ion-list>
                <ion-item class="ion-text-nowrap">2021.08.08 &nbsp; 20:40</ion-item>
                <ion-item>2021.08.09 &nbsp; 08:09</ion-item>
                <ion-item>2021.08.10 &nbsp; 10:30</ion-item>
                <ion-item>2021.08.12 &nbsp; 21:02</ion-item>
            </ion-list>
        </ion-content>
    </ion-page>
</template>

<script>
import { IonPage, IonHeader, IonTitle, IonContent, IonToolbar, IonList, IonItem } from '@ionic/vue';

export default {
    components: {
        IonPage, 
        IonHeader, 
        IonTitle, 
        IonContent,
        IonToolbar,
        IonList, 
        IonItem,
    }
}
</script>
