# GIS

# Pemetaan Jalan di Sekitar Sarijadi, Bandung
## 🗺️ Deskripsi Proyek

Proyek ini berisi data **GeoJSON** yang memetakan jaringan jalan di sebuah area di Kelurahan Sarijadi, Bandung. Secara spesifik, area yang dipetakan adalah lingkungan di sekitar tempat tinggal (kost) saya. Data ini mencakup jalan utama, jalan perumahan, hingga gang-gang kecil.

Tujuan dari proyek ini adalah untuk membuat representasi digital dari lingkungan sekitar sebagai bahan latihan dalam pengolahan data geospasial. Data ini diekstraksi dari **OpenStreetMap (OSM)** dan dapat digunakan untuk berbagai keperluan analisis atau visualisasi.

---

##  sadržaj Konten Data

[cite_start]File `sarijadi_coba.geojson` merupakan sebuah `FeatureCollection` yang berisi kumpulan `Feature` dengan tipe geometri `LineString`[cite: 8, 31, 35]. Setiap *feature* merepresentasikan satu ruas jalan.

Setiap ruas jalan memiliki properti yang mendeskripsikannya, antara lain:
* [cite_start]`name`: Nama jalan, contohnya "Jalan Sarimanah 2"[cite: 1].
* [cite_start]`highway`: Tipe jalan, seperti `residential` [cite: 1][cite_start], `living_street` [cite: 37][cite_start], atau `service`[cite: 48].
* [cite_start]`surface`: Jenis permukaan jalan, misalnya `asphalt` [cite: 17] [cite_start]atau `concrete`[cite: 20].
* [cite_start]`lanes`: Jumlah lajur jalan[cite: 1].
* [cite_start]`width`: Lebar jalan dalam meter[cite: 2, 25].

[cite_start]Data ini dihasilkan menggunakan **Overpass Turbo** dari database OpenStreetMap pada tanggal 20 Oktober 2025[cite: 1].

---

## 🚀 Cara Menggunakan

Anda dapat dengan mudah memvisualisasikan data ini:

1.  **Gunakan Web Viewer**:
    * Buka situs seperti [geojson.io](https://geojson.io/).
    * Hapus data contoh yang ada.
    * Salin seluruh isi file `sarijadi_coba.geojson` dan tempelkan ke dalam editor teks di situs tersebut.
    * Anda akan langsung melihat visualisasi petanya, sama seperti gambar di atas.

2.  **Gunakan di Proyek Anda**:
    * File GeoJSON ini dapat diintegrasikan dengan mudah ke dalam aplikasi web menggunakan *library* pemetaan seperti **Leaflet.js**, **Mapbox GL JS**, atau **OpenLayers**.
    * Anda juga bisa menggunakannya untuk analisis geospasial lebih lanjut dengan *software* seperti QGIS atau dengan *library* Python seperti GeoPandas.

---

## 🎯 Tujuan & Potensi Pengembangan

* **Tujuan Awal**: Proyek ini dibuat sebagai latihan pribadi untuk memahami struktur data GeoJSON dan alur kerja untuk mendapatkan data dari OpenStreetMap.
* **Potensi Pengembangan**:
    * Menambahkan data Points of Interest (POI) seperti warung, masjid, atau fasilitas umum lainnya.
    * Melakukan analisis jaringan jalan, misalnya untuk mencari rute terpendek.
    * Mengintegrasikan data ini ke dalam sebuah aplikasi web interaktif sederhana.

Jangan ragu untuk menggunakan data ini untuk keperluan belajar atau proyek Anda sendiri!
