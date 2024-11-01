# 📚 Laporan Pratikum Pemrograman Berorientasi Objek

Selamat datang di laporan pratikum **Pemrograman Berorientasi Objek**! 🎉😄

## 📖 Deskripsi

Laporan ini membuat aplikasi menggunakan Java Swing untuk menampilkan dan mengelola datamata kuliah dalam bentuk tabel  yang berisi Kode Mk, SKS, Nama mata kuliah dan Semester ajar dengan melakukan operasi CRUD  (Create, Read, Update, Delete) sekaligus Laporan ini membahas penggunaan Report untuk mencetak laporan Data Mata Kuliah. Aplikasi ini dibangun menggunakan Java dan memanfaatkan library seperti JasperReports untuk menghasilkan laporan yang terformat dengan baik.💻✨

🔗 Langkah - langkah :

1.	Menginstall plugin kedalam java
   ![image](https://github.com/user-attachments/assets/0ac712ea-9f7e-4137-b328-58b70eb1c41e)

   ![image](https://github.com/user-attachments/assets/50a05ad6-f516-41d0-b78c-73fc807af52d)


2.	Menginstall Ireport pada java
 ![image](https://github.com/user-attachments/assets/eb38eaad-e4dd-4df5-a6f4-4dd4ef9c1aa2)


3.	Menambahkan libraray
 ![image](https://github.com/user-attachments/assets/29b5488d-af33-4be9-83db-1a46b57f5e97)


4.	Menambahkan report untuk membuat template laporan
 ![image](https://github.com/user-attachments/assets/a24f90c1-fb9c-4d98-be3c-5da8d540ccf2)

 

5.	Memilih template laporan pada report
 ![image](https://github.com/user-attachments/assets/9c5005c7-f7e5-4152-bf6e-687081f28d35)


6.	Menentukan nama file (MataKuliah.jrxml) dan lokasi penyimpanan template laporan dalam proyek NetBeans (src/UTS)
    ![image](https://github.com/user-attachments/assets/c6358eba-2504-4684-909c-77c7d35bf892)


 
7.	  Menyisipkan Query SQL pada postgres untuk mengambil semua data dari tabel "MataKuliah" yang disimpan di database
    ![image](https://github.com/user-attachments/assets/e613cf6c-8abe-49b5-8e80-9933ceb95bb9)


8.  Memindahkan field seperti kodemk, sks, namamk, dan semesterajar agar tercetak kedalam laporan
   ![image](https://github.com/user-attachments/assets/f90f47dd-1642-466e-a974-0679e945dd48)


9. finish 
   ![image](https://github.com/user-attachments/assets/7b95cd35-8eea-4be1-baf4-081c90cc4e74)


10. Melakukan konfigurasi Project Properties
   ![image](https://github.com/user-attachments/assets/5a8b3e4c-5566-49af-ac70-170890ab4fd4)


11. pilih opsi run dan menambahkan VM option untuk mengatasi akses server pada Java
   ![image](https://github.com/user-attachments/assets/7cce9e5f-83b1-4746-9ed7-b02fd0907602)


12. menambahkan botton cetak pada java swing 
    ![image](https://github.com/user-attachments/assets/75f9c72e-f1a9-4676-911d-6dca46fe9e8c)



13. Pada botton `Cetak` digunakan untuk memuat, mengisi, dan menampilkan laporan ke dalam jendela baru menggunakan JasperReports
   ![image](https://github.com/user-attachments/assets/25743a18-c783-482a-b883-33601df51485)


Hasil :
![image](https://github.com/user-attachments/assets/66eceaf6-a64c-4e7b-a792-62eab7642cdc)


