# praktikum5.py

Nama : muflih salda maulana <p>
NIM : 312410527 <p>
Kelas : TI.24.A.5 <p>
Mata kuliah : Bahasa Pemrograman <p>

# program input nilai
flowcahrt

![flowchart](https://github.com/user-attachments/assets/d5fe20aa-c731-4f25-9f4f-ac4f15651803)

# penjelasan perogram
1. judul perogram

![judul perogram](https://github.com/user-attachments/assets/df1886ea-40f0-4edc-84d5-7735b804fc9f)

Baris ini mencetak judul program dan garis pemisah untuk memberikan konteks kepada pengguna.

2. Kelas Student

![class student](https://github.com/user-attachments/assets/38e6df2a-6784-4834-9ae4-72301280c378)

Kelas Student: Kelas ini digunakan untuk merepresentasikan seorang mahasiswa
__init__ Method: Ini adalah konstruktor yang dipanggil saat objek Student dibuat. Ini menerima NIM, nama, nilai tugas, UTS, dan UAS sebagai parameter. Nilai akhir dihitung dengan memanggil metode calculate_final_grade.

![bagian class student 2](https://github.com/user-attachments/assets/d12ce765-b99b-4d61-965c-9059a661a431)

calculate_final_grade Method: Metode ini menghitung nilai akhir berdasarkan bobot yang ditentukan untuk tugas, UTS, dan UAS, kemudian membulatkannya hingga dua desimal.

3.fungsi display_menu

![desplay menu](https://github.com/user-attachments/assets/f97ca246-89d6-4d54-bf79-f789153e0a47)

Fungsi ini menampilkan menu pilihan kepada pengguna untuk melihat, menambah, mengubah, menghapus, atau mencari data mahasiswa.

4.Fungsi display_students

![display student](https://github.com/user-attachments/assets/b17fadf2-b79f-4e3c-8160-8afa2222313b)

Fungsi ini menampilkan daftar mahasiswa dalam format tabel. Jika tidak ada mahasiswa, akan menampilkan pesan "TIDAK ADA DATA".

5. Fungsi find_student_index

![find student index](https://github.com/user-attachments/assets/87f83a42-537e-489f-a9e9-29d63162af9c)

Fungsi ini mencari indeks mahasiswa berdasarkan NIM. Jika ditemukan, mengembalikan indeksnya; jika tidak, mengembalikan None

6. Fungsi main

![fungsi main](https://github.com/user-attachments/assets/84b81da9-306f-471b-ac97-4f4d1cdace15)

Fungsi main adalah titik masuk program. Ini menginisialisasi daftar mahasiswa dan memasuki loop untuk menerima input dari pengguna.

Menangani Pilihan Pengguna
Tambah Mahasiswa ('t'):

Meminta input NIM, nama, dan nilai, kemudian menambahkan objek Student ke dalam daftar students.
Lihat Mahasiswa ('l'):

Memanggil fungsi display_students untuk menampilkan daftar mahasiswa.
Ubah Mahasiswa ('u'):

Menampilkan daftar mahasiswa, meminta NIM mahasiswa yang ingin diubah, dan jika ditemukan, meminta input baru dan memperbarui data mahasiswa.
Hapus Mahasiswa ('h'):

Menampilkan daftar mahasiswa, meminta NIM mahasiswa yang ingin dihapus, dan jika ditemukan, menghapus data mahasiswa dari daftar.
Cari Mahasiswa ('c'):

Meminta NIM mahasiswa yang dicari dan menampilkan detailnya jika ditemukan.
Keluar ('k'):

Menghentikan loop dan keluar dari program.
Pilihan Tidak Valid:

Jika pilihan tidak dikenali, menampilkan pesan bahwa pilihan tidak valid.

7. Menjalankan Program

![menjalankan perogram](https://github.com/user-attachments/assets/0d5ae079-b362-413e-aaa9-d1c1cff536ff)

 Baris ini memastikan bahwa fungsi main hanya akan dijalankan jika file ini dieksekusi sebagai program utama, bukan jika diimpor sebagai modul.

# hasil perogram
1. Menjalankan Program Setelah menjalankan program, Anda akan melihat output awal seperti ini:


![hasil 1](https://github.com/user-attachments/assets/18a44cdf-ef9d-480d-9cb3-a24f1c1e6d16)

2. Menampilkan Menu Program akan menampilkan menu pilihan:

![menampilkan menu](https://github.com/user-attachments/assets/9fdc938a-9a3d-4b30-a613-2af026754118)

3. Menambah Mahasiswa Jika Anda memilih untuk menambah mahasiswa dengan memasukkan 'T', program akan meminta Anda untuk memasukkan data:

![menambahkan data](https://github.com/user-attachments/assets/d1d5ca97-8d80-402c-94cc-1cb8379ec9fb)

   
5. Melihat Daftar Mahasiswa Jika Anda memilih 'L', program akan menampilkan daftar mahasiswa:

![lihat daftar nama](https://github.com/user-attachments/assets/326f7816-c0c7-4815-974d-f2f86557cb67)

   
6. Mengubah Data Mahasiswa Jika Anda memilih 'U' dan memasukkan NIM mahasiswa yang ingin diubah:

![mengubah data mahasiswa](https://github.com/user-attachments/assets/630a0c4f-8685-40e3-921e-b9b4fdcdd0d6)

 
7. Melihat Daftar Mahasiswa Setelah Diubah Memilih 'L' lagi untuk melihat daftar mahasiswa setelah perubahan:

![lihat daftar nilai yang di ubah](https://github.com/user-attachments/assets/1b9e448f-2def-4a97-a647-f01bdb62ca48)


8. Menghapus Mahasiswa Jika Anda memilih 'H' untuk menghapus mahasiswa:

![menghapus dari daftar nilai](https://github.com/user-attachments/assets/68000fe2-8b54-4fad-b496-89426d53e301)


9. Mencari Mahasiswa Jika Anda memilih 'C' untuk mencari mahasiswa:

![mencari data mahasiswa](https://github.com/user-attachments/assets/0d06ed6e-1c6c-4dc9-8861-06761a65b617)


10. Keluar dari Program Jika Anda memilih 'K', program akan berhenti:

![keluar dari perogram](https://github.com/user-attachments/assets/2d9a1fc3-cd85-4dca-a3cd-afb0708da91e)
