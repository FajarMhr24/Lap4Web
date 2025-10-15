# PENJELASAN

![foto](https://github.com/FajarMhr24/foto/blob/97372beb1fc9608fa328516aa008bd8dcac3c947/Screenshot%202025-10-16%20002013.png)

`<header>` Menampilkan judul utama “Layout Sederhana”.

`<nav>` Menu navigasi ke halaman lain (Home, Artikel, About, Kontak).

`<section id="hero">` Bagian pengenalan berisi teks Hello World! dan tombol “Learn more”.

`<aside id="sidebar">` Sidebar berisi widget tautan dan teks tambahan.

`<section id="main">` Bagian utama berisi tiga kotak (box) dengan gambar dan tombol View detail.

`<article class="entry">` Artikel tambahan dengan gambar dan teks deskripsi.

`<footer>` Bagian bawah halaman menampilkan hak cipta “© 2021 - Universitas Pelita Bangsa”

# PENJELASAAN CSS

### 1. IMPORT FONT

```CSS
@import url("https://fonts.googleapis.com/css2?family=Open+Sans...");
@import url("https://fonts.googleapis.com/css2?family=Open+Sans+Condensed...");
```

Mengambil font dari Google Fonts agar tampilan teks lebih modern.

### 2. RESET CSS

```CSS
* { margin: 0; padding: 0; }
```

Menghapus jarak bawaan (default margin & padding) semua elemen agar desain lebih konsisten.

### 3. BODY

```CSS
body {
  font-family: "Open Sans", sans-serif;
  color: #5a5a5a;
}
```

Mengatur font utama dan warna teks seluruh halaman.

### 4. CONTAINER

```CSS
#container {
  width: 980px;
  margin: 0 auto;
  box-shadow: 0 0 1em #cccccc;
}
```

Membungkus seluruh konten di tengah halaman dengan lebar tetap dan efek bayangan.

### 5. HEADER

```CSS
header {
  padding: 20px;
}
header h1 {
  color: #b5b5b5;
}
```

Memberi ruang dan warna abu-abu lembut pada judul utama.


### 6. NAVIGASI

```CSS
nav {
  background-color: #1f5faa;
}
nav a {
  color: #fff;
  padding: 15px 30px;
}
nav a.active,
nav a:hover {
  background-color: #2b83ea;
}
```

Membuat menu navigasi berwarna biru tua, teks putih, dan berubah warna saat kursor diarahkan (hover).

### 7. HERO SECTION

```CSS
#hero {
  background-color: #e4e4e5;
  padding: 50px 20px;
}
```

Bagian pengantar (hero) dengan latar abu-abu muda dan jarak luas agar menonjol.

### 8. WIDGET SIDEBAR

```CSS
.widget-box {
  border: 1px solid #eee;
}
.widget-box .title {
  background-color: #428bca;
  color: #fff;
}
```

Kotak kecil di sidebar (widget) dengan judul biru dan isi berisi link atau teks.

### 9. BOX (KONTEN UTAMA)

```CSS
.box {
  float: left;
  width: 33.33%;
  text-align: center;
}
.image-circle {
  border-radius: 50%;
}
```

Tiga kolom sejajar di bagian utama dengan gambar berbentuk lingkaran.

### 10. ENTRY

```CSS
.entry img {
  float: left;
  border-radius: 5px;
  margin-right: 15px;
}
.entry .right-img {
  float: right;
}
```

Mengatur gambar dan teks di artikel agar sejajar kiri atau kanan dengan jarak rapi

### 11. DIVIDER

```CSS
.divider {
  border-top: 1px solid #eeeeee;
  margin: 40px 0;
}
```

Garis pemisah antar bagian untuk memperjelas struktur halaman.

## ARTIKEL

![FOTO](https://github.com/FajarMhr24/foto/blob/63a7cf6faeaabf0bd3d02c7ee11f2fe55854d24d/Screenshot%202025-10-16%20010717.png)

```HTML
<footer>
  <p>&copy; 2025 - Universitas Pelita Bangsa</p>
</footer>
```

Bagian bawah halaman, berisi hak cipta atau identitas situs.

# ABOUT 

![FOTO](https://github.com/FajarMhr24/foto/blob/173b0559adca3616bcfa37bc63c2ff4e5baefd5e/Screenshot%202025-10-16%20012220.png)

# KONTAK

![FOTO](https://github.com/FajarMhr24/foto/blob/59562ff74c6ab5bf77e902c97a25084dfde49793/Screenshot%202025-10-16%20012000.png)

`<header>` berisi judul dan menu navigasi.

`<main>` berisi form (formulir kontak).

`<footer>` berisi teks hak cipta di bawah halaman.

## BAGIAN CSS

### 1. BODY

```CSS
body {
  font-family: "Segoe UI", Arial, sans-serif;
  background: linear-gradient(135deg, #eaf4ff, #f9fcff);
}
```

Mengatur font agar rapi dan memberi warna gradient lembut dari biru muda ke putih kebiruan supaya tidak polos.

### 2. CONTAINER

```CSS
.container {
  max-width: 600px;
  background: #fff;
  padding: 30px;
  border-radius: 12px;
  box-shadow: 0 6px 15px rgba(0,0,0,0.1);
}
```

Membuat kotak putih di tengah halaman agar isi form terlihat rapi dan modern (pakai shadow agar tampak mengambang).

### 3. HEADER DAN APLIKASI

```CSS
header h1 {
  color: #007acc;
  text-align: center;
}
nav a {
  color: #007acc;
  font-weight: bold;
}
nav a:hover {
  color: #005fa3;
  text-decoration: underline;
}
```

Judul dan link menu berwarna biru; saat diarahkan kursor, warnanya jadi lebih gelap dan muncul garis bawah (hover effect).

### 4. FORMULIR

```CSS
input, textarea {
  border: 1px solid #ccc;
  border-radius: 5px;
  padding: 10px;
  transition: 0.3s;
}
input:focus, textarea:focus {
  border-color: #007acc;
  box-shadow: 0 0 6px rgba(0,122,204,0.3);
}
```

Kolom input rapi dengan border lembut.
Saat diklik, muncul efek cahaya biru di pinggir — tanda fokus.

### TOMBOL

```CSS
button {
  background: linear-gradient(90deg, #007acc, #0096ff);
  color: #fff;
  border-radius: 5px;
  transition: 0.3s;
}
button:hover {
  background: linear-gradient(90deg, #005fa3, #007acc);
  transform: scale(1.05);
}
```

Warna tombol biru dengan gradient.
Saat diarahkan kursor, warnanya berubah dan sedikit membesar — efek animasi halus.


### FOOTER
```CSS
footer {
  text-align: center;
  color: #666;
}
```
Teks di bawah halaman dibuat kecil dan berwarna abu-abu lembut.




