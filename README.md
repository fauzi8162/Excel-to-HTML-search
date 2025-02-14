# Excel-to-HTML-search
Membuat halaman web sederhana yang dapat mengonversi file Excel menjadi tabel di browser, serta memiliki fitur pencarian. Kode ini menggunakan HTML, CSS, dan JavaScript dengan bantuan library SheetJS untuk membaca file Excel.

# Penjelasan Kode
### HTML Structure :
```
Input file untuk memilih file Excel.
Kotak pencarian untuk mencari data dalam tabel.
Kontainer tabel untuk menampilkan hasil konversi.
```
### CSS Styling :
```
Desain responsif dengan tampilan bersih dan modern.
Efek bayangan pada kontainer untuk meningkatkan estetika.
```
### JavaScript Logic :
```
Menggunakan library SheetJS untuk membaca file Excel.
File Excel dikonversi menjadi array JSON, lalu dirender ke dalam tabel HTML.
Fitur pencarian bekerja dengan menyaring baris berdasarkan teks yang dimasukkan.
```
### Fitur Pencarian :
```
Saat pengguna mengetik di kotak pencarian, baris tabel yang tidak sesuai dengan query akan disembunyikan.
```

# Cara Menggunakan
```
Unggah file Excel (.xlsx atau .xls).
Tabel akan ditampilkan secara otomatis.
Gunakan kotak pencarian untuk mencari data dalam tabel.
```
