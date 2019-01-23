**TUTORIAL PENGGUNAAN GIT**
1) Download Git, link (git-scm.com)

2) Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi
user.name dan user.email
 Config Global Repository
{$ git config --global user.name “nama_user”
$ git config --global user.email “nama_user” }

3) Buat direktory project praktikum pertama dengan nama latihan1
{ $ mkdir latihan1
$ cd latihan1 }

4) Membuat Reposiory Local
{ $ git init }

5) Menambahkan File Baru Pada Repository
{ $ echo "#latihan1" >> README.md 
$ git add README.md  }

6) Simpan Perubahan Ke Dalam Database
{ $git commit -m "File Pertama Saya" }

7) Membuat Repository Server
{ Server reopsitory yang akan kita gunakan adalah 
http://github.com
• Anda harus membuat akun terlebih dahulu. • Pada laman 
github, klik tombol start a project, atau
• Dari menu (icon +) klik New Repository
• Isi nama repositorynya, misal: labpy1.

8) Menambahkan Remote repository
{ $ git remote add origin [URL]

9) Push (Mengirim perubahan ke server)
{ $ git push -u origin master }

10) Lihat Hasilnya pada Server repository
