# Proyek 4: Dari Tanah Air ke Tanah Air
Proyek ini merupakan proyek website yang menampilkan kampung halaman beberapa karyawan TripleTen, yang tampilanya dapat dilihat secara responsif dalam ukuran display yang secara umum digunakan pada saat ini.

**Tujuan membuat proyek ini, untuk melatih para student menggunakan :**
-Tata Letak Grid
-Media Query
-Figma

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
    .lead {
      margin: 0;
    }
  
    .lead__title {
      padding: 0 16;
      font-size: 40px;
      line-height: 110%;
    }
  
    .lead__subtitle {
      padding: 0 16px;
      font-size: 16px;
      line-height: 125%;
    }
  }  
```
### Figma
Dalam proyek ini digunakan untuk:
- [Menautkan ke proyek di Figma](https://www.figma.com/file/1zCYcflj6BJx5VqOvXU9nb/Sprint-3-From-Homeland-to-Homeland-desktop-mobile?node-id=0%3A1)
- Mengekspor gambar langsung dari Figma — disarankan melakukan itu untuk berlatih lebih banyak. Jangan lupa mengoptimalkannya [di sini] (https://tinypng.com/), sehingga proyek dapat dimuat lebih cepat.


**Tautan Ke GitHub Pages Saya**
https://sakti-diputra.github.io/web_project_3_id/
