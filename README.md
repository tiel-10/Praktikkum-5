Soal :
Buat program sederhana untuk menambahkan data kedalam sebuah list dengan rincian sebagai berikut:
- Progam meminta memasukkan data sebanyak-banyaknya(gunakanperulangan)
- Tampilkan pertanyaan untuk menambah data (y/t?), apabilajawabant (Tidak), maka program akan menampilkan daftar datanya. 
- Nilai Akhir diambil dari perhitungan 3 komponen nilai (tugas: 30%,uts: 35%, uas: 35%)
- Buat flowchart dan penjelasan programnya pada README.md. 
- Commit dan push repository ke github.

Flowchart :
![Praktikum4 flowchart](https://github.com/user-attachments/assets/0b0dc552-d150-4569-95aa-67b07b4d7700)

Jawaban :
Flowchart ini menggambarkan proses pengolahan data nilai mahasiswa dengan langkah-langkah sebagai berikut:

1. Inisialisasi:
   - Program dimulai dengan menginisialisasi list kosong bernama "data" untuk menyimpan data mahasiswa.

2. Input Data Mahasiswa:
   - Program akan terus meminta input data mahasiswa berupa Nama, NIM, Nilai Tugas, Nilai UTS, dan Nilai UAS.
   - Setiap data yang diinput akan disimpan dalam bentuk list ke dalam variabel "data".

3. Perhitungan Nilai Akhir:
   - Setelah semua data diinput, program akan menghitung Nilai Akhir mahasiswa menggunakan rumus:
     - Nilai Akhir = (Nilai Tugas × 30%) + (Nilai UTS × 35%) + (Nilai UAS × 35%)
   - Nilai Akhir yang telah dihitung juga akan disimpan dalam list "data".

4. Pertanyaan Tambah Data:
   - Setelah data mahasiswa dan nilai akhir disimpan, program akan menanyakan kepada pengguna apakah ingin menambah data lagi.
   - Jika pengguna memilih "y", maka program akan kembali ke proses input data.
   - Jika pengguna memilih "t", maka program akan lanjut ke proses output.

5. Output Data:
   - Program akan mencetak garis pembatas sepanjang 50 karakter.
   - Kemudian mencetak header tabel yang berisi: No, Nama, NIM, Tugas, UTS, UAS, Akhir.
   - Selanjutnya, program akan melakukan loop pada list "data" dan mencetak setiap baris data dengan format:
     - Nomor urut (i+1), Nama, NIM, Nilai Tugas, Nilai UTS, Nilai UAS, Nilai Akhir (2 angka di belakang koma).
   - Setelah semua data dicetak, program akan mencetak kembali garis pembatas.

6. Selesai:
   - Setelah semua proses selesai, program akan berakhir.

Secara keseluruhan, flowchart ini menggambarkan alur program yang memungkinkan pengguna untuk melakukan input data mahasiswa, menghitung nilai akhir, dan mencetak hasil dalam bentuk tabel. Program akan berjalan secara berulang hingga pengguna memilih untuk berhenti menambah data.
