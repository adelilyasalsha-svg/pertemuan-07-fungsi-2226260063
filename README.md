**Nama:** Adelilya Salsha  
**NIM:** 2225250063  
**Kelas:** 3B

## Tujuan

Menggunakan fungsi, parameter, return value, dan scope untuk membuat program modular.

## Cara Menjalankan

Jalankan file latihan melalui terminal VS Code dengan perintah berikut:

```bash
python latihan/01_salam.py
python latihan/02_luas_persegi_panjang.py
python latihan/03_jumlah_n.py
python latihan/04_statistik_sederhana.py
python latihan/05_scope.py
python praktik/utilitas_matematika.py
```

Pastikan terminal berada di folder utama proyek `pertemuan-07-fungsi-2225250063`.

## Struktur Fungsi

Pada folder `latihan`, terdapat lima program untuk mempelajari salam menggunakan fungsi, menghitung luas persegi panjang, menjumlahkan bilangan sampai n, menghitung statistik sederhana, dan memahami scope variabel.

Pada file `praktik/utilitas_matematika.py`, terdapat fungsi-fungsi berikut:

- `luas_persegi_panjang(p, l)`: menerima panjang dan lebar, lalu mengembalikan hasil perkalian keduanya.
- `luas_segitiga(a, t)`: menerima alas dan tinggi, lalu mengembalikan hasil perhitungan luas segitiga.
- `jumlah_n(n)`: menjumlahkan bilangan dari 1 sampai n dan mengembalikan totalnya.
- `faktorial(n)`: menghitung faktorial n dan mengembalikan hasilnya.
- `tampilkan_menu()`: menampilkan pilihan menu program.

## Hasil Pengujian

| Pengujian | Input | Hasil yang diharapkan |
|---|---|---|
| Luas persegi panjang | panjang = 8, lebar = 5 | 40 |
| Luas segitiga | alas = 10, tinggi = 6 | 30.0 |
| Jumlah 1 sampai n | n = 10 | 55 |
| Faktorial | n = 5 | 120 |
| Faktorial nol | n = 0 | 1 |

**Hasil aktual:** Isi setelah setiap pengujian dijalankan di VS Code.  
**Status:** Isi dengan Berhasil jika hasil aktual sesuai dengan hasil yang diharapkan.

## Refleksi

Dengan memisahkan perhitungan ke dalam fungsi, program menjadi lebih terstruktur dan mudah dibaca. Setiap fungsi memiliki tugas tertentu sehingga kode dapat digunakan kembali dan lebih mudah diuji maupun diperbaiki.
#
