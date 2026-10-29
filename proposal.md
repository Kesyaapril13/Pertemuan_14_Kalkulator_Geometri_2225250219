# PROPOSAL PROYEK PERTEMUAN 14
# RANCANGAN KALKULATOR GEOMETRI BANGUN DATAR BERBASIS PYTHON

## 1. Identitas Proyek

- Nama: Kesya Nur Aprilliani
- NIM: 2225250219
- Kelas: 3E
- Program Studi: Pendidikan Matematika
- Mata Kuliah: Algoritma dan Pemrograman
- Pertemuan: 14

## 2. Judul Proyek

Rancangan Program Kalkulator Geometri Bangun Datar Berbasis Python.

## 3. Latar Belakang

Matematika merupakan ilmu yang memiliki banyak penerapan dalam kehidupan sehari-hari. Salah satu materi matematika yang sering digunakan adalah geometri, khususnya materi bangun datar. Dalam pembelajaran geometri, peserta didik mempelajari berbagai bentuk bangun datar serta cara menghitung luas dan kelilingnya.

Namun, dalam melakukan perhitungan, diperlukan pemahaman terhadap rumus dan ketelitian dalam memasukkan nilai. Oleh karena itu, diperlukan sebuah rancangan program sederhana yang dapat membantu proses perhitungan luas dan keliling bangun datar.

Berdasarkan hal tersebut, dirancang sebuah program Kalkulator Geometri Bangun Datar menggunakan bahasa pemrograman Python. Program ini direncanakan dapat menghitung luas dan keliling persegi, persegi panjang, segitiga, dan lingkaran.

## 4. Identifikasi Masalah

1. Pengguna perlu memahami berbagai rumus luas dan keliling bangun datar.
2. Perhitungan manual membutuhkan ketelitian.
3. Kesalahan memasukkan nilai dapat menyebabkan hasil perhitungan tidak tepat.
4. Diperlukan penerapan teknologi untuk membantu proses pembelajaran matematika.

## 5. Rumusan Masalah

1. Bagaimana merancang program kalkulator geometri menggunakan Python?
2. Bagaimana menerapkan rumus luas dan keliling bangun datar ke dalam algoritma pemrograman?
3. Bagaimana merancang program yang mudah digunakan oleh pengguna?
4. Bagaimana merancang validasi input agar program dapat menangani masukan yang tidak sesuai?

## 6. Tujuan Proyek

1. Merancang program perhitungan luas dan keliling bangun datar.
2. Menerapkan konsep matematika dalam pemrograman Python.
3. Menyusun algoritma dan pseudocode program.
4. Merancang struktur program yang sistematis.
5. Menentukan rencana pengujian program sebelum tahap implementasi.

## 7. Manfaat Proyek

1. Membantu pengguna melakukan perhitungan geometri.
2. Menjadi sarana penerapan konsep matematika dalam teknologi.
3. Melatih kemampuan menyusun algoritma.
4. Meningkatkan pemahaman penggunaan bahasa pemrograman Python.

## 8. Fitur yang Direncanakan

Program direncanakan memiliki fitur berikut:

1. Menghitung luas dan keliling persegi.
2. Menghitung luas dan keliling persegi panjang.
3. Menghitung luas dan keliling segitiga.
4. Menghitung luas dan keliling lingkaran.
5. Memvalidasi masukan pengguna.
6. Menampilkan hasil perhitungan.
7. Menyediakan pilihan untuk mengulangi atau mengakhiri perhitungan.

## 9. Rumus Matematika yang Digunakan

### A. Persegi
Luas = sisi × sisi

Keliling = 4 × sisi

### B. Persegi Panjang
Luas = panjang × lebar

Keliling = 2 × (panjang + lebar)

### C. Segitiga
Luas = ½ × alas × tinggi

Keliling = sisi a + sisi b + sisi c

### D. Lingkaran
Luas = π × r²

Keliling = 2 × π × r

Keterangan:
- π = 3,14 atau 22/7.
- r = jari-jari lingkaran.

## 10. Analisis Input, Proses, dan Output (IPO)

### A. Input
1. Pilihan jenis bangun datar.
2. Panjang sisi persegi.
3. Panjang dan lebar persegi panjang.
4. Alas, tinggi, serta tiga sisi segitiga.
5. Jari-jari lingkaran.

### B. Proses
1. Menerima pilihan bangun datar.
2. Meminta nilai sesuai jenis bangun datar.
3. Memeriksa validitas nilai masukan.
4. Menghitung luas dan keliling menggunakan rumus matematika.
5. Menyiapkan hasil perhitungan.

### C. Output
1. Nama bangun datar.
2. Hasil perhitungan luas.
3. Hasil perhitungan keliling.
4. Pesan kesalahan apabila input tidak sesuai.

## 11. Algoritma Program

1. Mulai.
2. Menampilkan menu pilihan bangun datar.
3. Meminta pengguna memilih jenis bangun datar.
4. Memeriksa pilihan pengguna.
5. Meminta nilai yang diperlukan.
6. Memvalidasi nilai masukan.
7. Menghitung luas dan keliling berdasarkan rumus.
8. Menampilkan hasil perhitungan.
9. Menawarkan pilihan untuk mengulangi perhitungan.
10. Selesai apabila pengguna memilih keluar.

## 12. Pseudocode

```text
START

REPEAT
    Tampilkan menu bangun datar
    Input pilihan

    IF pilihan = 1 THEN
        Input sisi
        Hitung luas persegi
        Hitung keliling persegi

    ELSE IF pilihan = 2 THEN
        Input panjang dan lebar
        Hitung luas persegi panjang
        Hitung keliling persegi panjang

    ELSE IF pilihan = 3 THEN
        Input alas, tinggi, dan tiga sisi
        Hitung luas segitiga
        Hitung keliling segitiga

    ELSE IF pilihan = 4 THEN
        Input jari-jari
        Hitung luas lingkaran
        Hitung keliling lingkaran

    ELSE
        Tampilkan pesan pilihan tidak valid
    END IF

    Tampilkan hasil perhitungan jika input valid

    Tanya apakah ingin mengulangi perhitungan

UNTIL pengguna memilih keluar

END
```

## 13. Rancangan Struktur Program

```text
Proyek_Matematika_2225250219/
│
├── README.md
├── proposal.md
├── main.py
│
├── src/
│   └── kalkulator_geometri.py
│
└── tests/
    └── test_case.md
```

Keterangan:
- README.md: dokumentasi proyek.
- proposal.md: rancangan proyek.
- main.py: rancangan program utama.
- src/kalkulator_geometri.py: rancangan modul perhitungan.
- tests/test_case.md: dokumentasi rencana pengujian.

## 14. Rencana Pengujian

| No. | Jenis Pengujian | Tujuan |
|---|---|---|
| 1 | Perhitungan persegi | Memeriksa ketepatan rumus |
| 2 | Perhitungan persegi panjang | Memeriksa ketepatan rumus |
| 3 | Perhitungan segitiga | Memeriksa ketepatan rumus |
| 4 | Perhitungan lingkaran | Memeriksa ketepatan rumus |
| 5 | Input negatif | Menguji validasi nilai |
| 6 | Pilihan menu tidak valid | Menguji penanganan kesalahan |

## 15. Penutup

Rancangan proyek Kalkulator Geometri Bangun Datar dibuat sebagai bentuk penerapan konsep matematika ke dalam pemrograman Python. Melalui rancangan ini, diharapkan proses implementasi program pada tahap berikutnya dapat dilakukan secara lebih terarah.

Rancangan ini mencakup identifikasi masalah, tujuan, fitur, analisis input-proses-output, algoritma, pseudocode, struktur program, serta rencana pengujian sebagai dasar pengembangan program pada Pertemuan 15.
