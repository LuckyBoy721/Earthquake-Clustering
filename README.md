# Analisis Clustering Spasial Gempa Bumi di Indonesia

> Di bawah permadani kepulauan ini, bumi tak pernah benar-benar terlelap. Ia meregang, bergeser, dan sesekali melepaskan energinya dalam getaran. Proyek ini adalah upaya untuk mendengar bisikan itu—menerjemahkan bahasa sunyi lempeng tektonik menjadi peta waspada.

## Misi: Memetakan Denyut Seismik Nusantara

Kami tidak sekadar mengolah angka. Misi kami adalah sebuah ekspedisi digital untuk menyingkap pola tersembunyi dari aktivitas seismik Indonesia. Tujuannya adalah untuk:

* **Memburu Episentrum**: Melacak jejak-jejak gempa lampau untuk menemukan di mana energi bumi paling sering terkonsentrasi.
* **Merajut Peta Kewaspadaan**: Mengubah titik-titik data yang dingin menjadi visualisasi panas yang intuitif, menunjukkan "urat nadi" seismik kepulauan ini.
* **Menafsirkan Pola Provinsi**: Membedah temuan pada skala provinsi, memberikan konteks lokal pada fenomena geologis yang masif.
* **Membuka Dialog**: Menyajikan wawasan yang memantik diskusi tentang risiko, resiliensi, dan hubungan kita dengan bumi yang kita pijak.

## Jejak Digital & Alkimia Algoritma

Perjalanan ini dimungkinkan oleh jejak digital yang ditinggalkan setiap getaran dan "alkimia" dari algoritma modern.

1.  **Ekstraksi Jejak**: Jejak berupa data historis gempa (koordinat, magnitudo, kedalaman) diekstraksi dari arsip publik **BMKG** atau **USGS**. Ini adalah bahan mentah kami.
2.  **Pemurnian Esensi**: Data mentah dimurnikan. Riak-riak yang tidak relevan disaring, hanya menyisakan esensi getaran dalam batas geografis Nusantara.
3.  **Sihir Clustering**: Di sinilah keajaiban terjadi. Kami memanggil **DBSCAN**, sebuah algoritma cerdas yang mampu melihat "kerumunan" (cluster) dalam data spasial. Ia secara mandiri menemukan di mana episentrum gempa saling berdekatan, dan memisahkannya dari getaran-getaran yang menyendiri (*noise*).
4.  **Manifestasi Visual**: Temuan algoritma kemudian dimanifestasikan ke dalam kanvas digital. **Heatmap** melukiskan bara api seismik, sementara **peta cluster interaktif** menandai jantung-jantung aktivitas gempa dengan presisi.

## Arsenal Digital

Ekspedisi ini dipersenjatai dengan perangkat lunak canggih:

* **Penerjemah Bahasa Data**: `Python`
* **Pahat & Palu Data**: `Pandas`, `NumPy`, `GeoPandas`
* **Kompas Ajaib (Clustering)**: `Scikit-learn`
* **Kuas & Kanvas Visual**: `Matplotlib`, `Seaborn`, `Folium`

## Temuan di Garis Depan

Tirai data tersingkap, memperlihatkan panggung utama aktivitas seismik Indonesia. Konsentrasi energi tertinggi tampak membara di sepanjang jalur subduksi, membentuk sabuk api yang melingkari:

* Punggung barat **Sumatra**.
* Busur selatan **Jawa hingga Nusa Tenggara**.
* Persimpangan lempeng di **Maluku** dan sekitarnya.
* Kawasan utara dan barat **Papua**.

Peta ini bukan sekadar gambar, melainkan cerminan dari kekuatan dahsyat yang terus membentuk tanah air kita.

## Mulai Ekspedisi Anda

Ingin menelusuri jejak ini sendiri?

1.  **Ambil Peta & Kompas (Clone Repo):**
    ```bash
    git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)
    cd your-repository-name
    ```
2.  **Siapkan Perbekalan (Install Dependencies):**
    ```bash
    pip install -r requirements.txt
    ```
3.  **Selami Jurnal Lapangan (Run Notebook):**
    ```bash
    jupyter notebook notebooks/earthquake_spatial_analysis.ipynb
    ```

## Menjadi Bagian dari Cerita

Setiap baris kode, setiap visualisasi, setiap analisis baru adalah bab tambahan dalam cerita ini. Jika Anda memiliki ide, koreksi, atau ingin memperkaya narasi ini, kontribusi Anda lebih dari sekadar diterima—ia dinantikan.

## Prasasti Digital (Lisensi)

Karya ini dibagikan secara bebas di bawah naungan **Lisensi MIT**. Gunakan, modifikasi, dan sebarkan pengetahuan ini.
