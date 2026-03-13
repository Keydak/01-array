
# Sistem Pengelolaan Nilai Mahasiswa

## Deskripsi Program
Program ini dibuat menggunakan Python untuk mengelola data nilai mahasiswa menggunakan konsep **array (list)**. Program akan menerima input nilai mahasiswa, kemudian melakukan beberapa proses seperti mencari nilai tertinggi, nilai terendah, menghitung rata-rata, serta menentukan jumlah mahasiswa yang lulus dan tidak lulus. Selain itu, program juga menampilkan grafik untuk memvisualisasikan data nilai.

---

# Penjelasan Konsep Array
Array adalah struktur data yang digunakan untuk menyimpan beberapa data dengan tipe yang sama dalam satu variabel.  

Dalam Python, array biasanya direpresentasikan menggunakan **list**. List memungkinkan kita menyimpan banyak nilai dalam satu variabel dan mengaksesnya menggunakan indeks.

Pada program ini, array digunakan untuk:
- Menyimpan 10 nilai mahasiswa
- Mengolah data nilai untuk mencari nilai maksimum dan minimum
- Menghitung rata-rata nilai
- Menentukan jumlah mahasiswa yang lulus dan tidak lulus

Contoh penggunaan array pada program:

```python
nilai_mahasiswa = []
````

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

