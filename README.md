# Tugas-3--SISTEM-OPERASI-SK3B-SATRIO_JORONGGUR_MAHENDRA_09011282328092
Nama   :Satrio Joronggur Mahendra
Kelas  : SK3B
NIM    : 09011282328092


1. Lihat peralatan I/O, character device, yang ada pada system komputer.

![1 1](https://github.com/user-attachments/assets/928fad3d-06aa-4c41-8ea6-b03fe4002b6f)
![1 2](https://github.com/user-attachments/assets/1db2b4f4-572b-4798-a465-e7d5e0c30bd2)
![1 3](https://github.com/user-attachments/assets/af547747-937e-449b-aeb5-69b8658153e5)
![1 4](https://github.com/user-attachments/assets/dd0d9aa7-bf4c-4efb-95d2-41a16880bfc5)



2. Buatlah sub direktori januari, februari dan maret sekaligus pada direktori latihan5.
membuat direktori latihan5 dengan mkdir lalu membuat direktori lagi didalam direktori latihan5 dengan nama januari, februari, maret.

pertama-tama kita buat dulu direktori utama yang bernama latihan5 untuk menampung direktori Januari, Februari dan Maret. Untuk membuat direktori kita gunakan command "mkdir Latihan5" setelah itu masuk ke direktori nya dengan menggunakan command "cd \Latihan5", kemudian kita buat direktori januari, februari dan maret nya menggunakan command yang sama yaitu "mkdir Januari && mkdir Februari && mkdir Maret" bisa juga di buat satu persatu kalo cara ini eror

![2](https://github.com/user-attachments/assets/5cb947df-ab3a-47f7-91a9-74f75d1d8d89)


3. Buatlah file dataku yang berisi nama, nim dan alamat anda pada sub direktori januari
dan copy-kan file tersebut ke sub direktori februari dan maret.

lalu saya membuat file bernama dataku.txt dengan command touch, lalu saya menggunakan nano unntuk mengisi teks di file tersebut, lalu saya copykan file teersebu dengan command cp dan saya masukan didirektori februari dan maret


![3](https://github.com/user-attachments/assets/1dfeb489-f11d-434b-8974-36dc555dff78)
![3 1](https://github.com/user-attachments/assets/72d3eacf-0083-406d-88dd-ed49355d385f)
![3 2](https://github.com/user-attachments/assets/25d81859-0db5-45b7-88b3-039b16007a5b)




4. Ubahlah ijin akses file dataku pada sub direktori januari sehingga group dan others
dapat melakukan write.

Pertama kita masuk ke sub direktori januari terlebih dahulu, kemudian kita ingin mengubah ijin akses file dataku.txt agar group dan others dapat melakukan write. Caranya adalah menggunakan command chmod. Caranya yaitu ketik chmod g=w dan o=ww, yang dimana g dan o itu berarti group dan others, w adalah write, itu artinya group dan others bisa melakukan write file tersebut. Setelah mengetik chmod tersebut, kita ketik nama file yang ingin diganti ijin aksesnya 

![4](https://github.com/user-attachments/assets/1a511e65-36ef-4b24-8f12-7dc0a61e6782)




5. Ubahlah ijin akses file dataku pada sub direktori pebruari sehingga user dapat
melakukan baik write, read maupun execute, tetapi group dan others hanya bisa read
dan execute.
 ketik chmod 755. 7 berarti user bisa melakukan read, write dan execute. 5 berarti group hanya bisa melakukan read dan execute. 5 berarti others hanya bisa melakukan read dan execute. Kemudian kita ketik nama filenya, lalu kita bisa mengecek ls -l maka akan tampil --rwxr-xr-x yang berarti rwx itu user bisa melakukan read,write dan execute, lalu r-x untuk group dan others yang berari cuman bisa read dan execute saj
![5](https://github.com/user-attachments/assets/4a9a2128-8bc5-4055-a0db-6fb331a95875)


6. Ubahlah ijin akses file dataku pada sub direktori maret sehingga semua dapat melakukan write, read dan execute.
disini saya menygetik chmod 777 yang berarti user, others, group dapat melakukan akses dalam bentuk read, write , dan excute

![6](https://github.com/user-attachments/assets/f168aef4-4d91-44c8-a9fd-103abe47a215)



7. Hapuslah direktori maret.

menghapus diretori bisa dengan rm -r lalu lokasi direktorinya
![7](https://github.com/user-attachments/assets/246ce434-aa97-4a6d-bbbe-9aede6ffe2b7)



8. Ubahkan kepemilikan sub direktori februari sehingga user dan group hanya dapat melakukan read, dan cobalah untuk membuat direktori baru haha pada sub direktori februari.

Kita ubah izin akses direktori februari menggunakan command "chmod 444 (lokasi direktori yang ingin diubah)" kemudian coba lah untuk membuat direktori baru di dalam direktori februari atau coba masuk ke dalam direktori februari, jika permission denied maka kita sudah berhasil mengubah izin akses direktori nya

![8](https://github.com/user-attachments/assets/88c53e70-1e9b-46f5-902d-1f5a3287d93f)



9. Modifikasi umask dari file dataku pada sub direktori januari menjadi 027 dan berapaka nilai default-nya ?

![9](https://github.com/user-attachments/assets/58c370fd-f3e7-4e8e-9391-7daff32236a1)



10. Buatlah link dari file dataku ke file dataku.ini dan file dataku.juga dan dengan perintah
list perhatikan berapa link yang terjadi ?


membuat link dari file Dataku.txt ke .juga dan .ini kita gunakan perintah "ln (lokasi file dataku contoh : /home/satriojr25/Desktop/Latihan5/Januari/Dataku.txt kemudian spasi dan ketikkan lokasi yang sama hanya saja ubah Dataku.txt menjadi Dataku.ini begitupun juga dengan Dataku.juga) langkah selanjutnya adalah mengecek berapa link yang terjadi dengan command : ls -l (jika kalian berada di direktori Januari, jika tidak ikutin yang seperti di gambar)
![10 2](https://github.com/user-attachments/assets/04e089f6-cfbd-464e-850f-b09ffc47b47b)
![10 1](https://github.com/user-attachments/assets/02f54983-5c43-4146-9ca1-9378fdf98100)
