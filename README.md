Nama: Imam Muzakki

NIM: H1D022060

Shift Baru: D

# Tugas Pertemuan 7

![Tampilan aplikasi](pertemuan_6/src/assets/docs/Screen%20Shot%202024-10-30%20at%2014.30.05.png)

Komponen yang ditambahkan adalah list beserta dengan item. Berikut adalah cara menambahkannya:

1. Kunjungi https://ionicframework.com/docs/api/list
2. Copy kode dari segment `Basic Usage` ke container di file `folder.page.html`
3. Kustomisasi hingga didapatkan kode yang diinginkan
```
<div id="list">
    <ion-list [inset]="true">
        <ion-item color="dark">
            <ion-label>Imam Muzakki</ion-label>
        </ion-item>
        <ion-item color="dark">
            <ion-label>H1D022060</ion-label>
        </ion-item>
    </ion-list>
</div>
```