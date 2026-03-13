# 📘 MATA KULIAH STRUKTUR DATA

| Nama | NIM | Kelas |
|-----|-----|-----|
| I Kadek Cri Bhaskara Wirawan Sutha | 2501010052 | A |
---
# Sistem Pengelolaan Nilai Mahasiswa

## Deskripsi Program
Program ini dibuat menggunakan Python untuk mengelola data nilai mahasiswa menggunakan konsep **array (list)**. Program akan menerima input nilai mahasiswa, kemudian melakukan beberapa proses seperti mencari nilai tertinggi, nilai terendah, menghitung rata-rata, serta menentukan jumlah mahasiswa yang lulus dan tidak lulus. Selain itu, program juga menampilkan grafik untuk memvisualisasikan data nilai.

---

# Penjelasan Konsep Array
Array adalah salah satu **struktur data dasar dalam ilmu komputer** yang digunakan untuk menyimpan sekumpulan elemen data dalam satu variabel. Setiap elemen dalam array biasanya memiliki **tipe data yang sama** dan dapat diakses menggunakan **indeks** yang menunjukkan posisi elemen tersebut dalam array.

Menurut Encyclopaedia Britannica, struktur data merupakan cara penyimpanan dan pengorganisasian data agar dapat diakses dan diproses secara efisien. Salah satu bentuk struktur data yang paling sederhana adalah **array linear**, di mana elemen-elemen data disimpan secara berurutan dan diakses menggunakan nomor indeks.

Array banyak digunakan dalam pemrograman karena memungkinkan penyimpanan banyak data dalam satu variabel serta memudahkan proses pengolahan data menggunakan perulangan atau operasi lainnya.

Dalam bahasa pemrograman Python, konsep array biasanya diimplementasikan menggunakan **list**, yang dapat menyimpan banyak nilai dalam satu variabel dan diakses menggunakan indeks.

Contoh penggunaan array pada program:

```python
nilai_mahasiswa = []
```

Pada program tugas ini, array digunakan untuk:

* Menyimpan nilai mahasiswa
* Menghitung nilai tertinggi dan terendah
* Menghitung rata-rata nilai
* Menentukan jumlah mahasiswa yang lulus dan tidak lulus


---

# Screenshot Hasil Eksekusi

Berikut contoh hasil eksekusi program:


<img width="611" height="447" alt="image" src="https://github.com/user-attachments/assets/8fd0a1d9-9bb2-4eb9-8494-19529eef8808" />

<img width="611" height="447" alt="image" src="https://github.com/user-attachments/assets/f6cfbec7-3516-4f11-b2ae-bb61b3060695" />
<img width="611" height="447" alt="image" src="https://github.com/user-attachments/assets/5c178714-94a6-434b-928b-6b67e5f55464" />
<img width="611" height="447" alt="image" src="https://github.com/user-attachments/assets/3b04b50e-2f61-435b-937c-98f4f1465c34" />


---

# Analisis Kompleksitas

1. **Input Nilai Mahasiswa**
   Program melakukan perulangan untuk memasukkan nilai mahasiswa ke dalam array.
   Kompleksitas waktu: **O(n)**

2. **Mencari Nilai Tertinggi dan Terendah**
   Program memeriksa seluruh data nilai untuk menentukan nilai maksimum dan minimum.
   Kompleksitas waktu: **O(n)**

3. **Menghitung Rata-rata Nilai**
   Seluruh nilai dijumlahkan kemudian dibagi dengan jumlah data.
   Kompleksitas waktu: **O(n)**

4. **Menghitung Jumlah Mahasiswa Lulus**
   Program memeriksa setiap nilai untuk menentukan apakah memenuhi kriteria kelulusan.
   Kompleksitas waktu: **O(n)**

5. **Menampilkan Grafik**
   Grafik dibuat berdasarkan data nilai yang tersedia.
   Kompleksitas waktu: **O(n)**

Sebagian besar operasi dalam program ini memiliki kompleksitas **O(n)** karena setiap proses harus memeriksa seluruh data nilai mahasiswa.

---

# Refleksi Pembelajaran

Melalui tugas ini, saya belajar bagaimana menggunakan struktur data array (list) dalam Python untuk menyimpan dan mengolah data. Saya juga memahami cara melakukan perulangan untuk memproses data, menghitung nilai statistik seperti rata-rata, serta membuat visualisasi data menggunakan library **matplotlib**.

Selain itu, saya juga belajar mengenai konsep **analisis kompleksitas algoritma**, yang membantu memahami seberapa efisien suatu program ketika jumlah data semakin besar.

