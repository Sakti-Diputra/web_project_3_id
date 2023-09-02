# Dari Tanah Air ke Tanah Air
Proyek ini merupakan proyek website yang menampilkan kampung halaman beberapa karyawan TripleTen, yang tamplanya disajikan secara responsif dalam tiga ukuran media yang berbeda (1280px untuk dextop, 768px untuk tablet, dan 320px untuk mobile)

**Tujuan membuat proyek ini, untuk melatih para student menggunakan :**
-Tata Letak Grid
-Media Query

### Tata Letak Grid
Digunaka untuk mengatur elemen di sepanjang sumbu x dan y secara bersamaan dalam sebuah blok.
untuk menerapkannya kita perlu mengubah suatu elemen menjadi kontainr grid,dengan menggunakan deklarasi ```display: grid;``` ke dalamnya.
Contoh dalam proyek ini :
```javascript
.places {
    display: grid;
}
```

### Media Query
Kueri media (media query) digunakan untuk membuat situs web yang responsif karena memungkinkan kita untuk menentukan tampilan elemen yang bergantung pada ukuran jendela browser.
contoh penerapan media query pada proyek ini :
```javascript
@media screen and (min-width: 320px) and (max-width: 767px) {
    .lead__title {
        width: 70%;
        font-size: 40px;
        line-height: 44px;
        margin: 50px auto 0;
    }

    .lead__subtitle {
        width: 90%;
        font-size: 16px;
        line-height: 20px;
    }

    .image {
        width: 100%;
        margin: 20px auto 0;
    }
}
```

**Tautan Ke GitHub Pages Saya**
https://sakti-diputra.github.io/web_project_3_id/
