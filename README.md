1. Instalasi Git
2. Download Git, buka website resminya Git (git-scm.com).
3. Kemudian unduh Git sesuai dengan arsitektur komputer kita. Kalau
4. menggunakan 64bit, unduh yang 64bit. Begitu juga kalau menggunakan 32bit.
![downloadgit](https://user-images.githubusercontent.com/57305570/68079180-2aaa8800-fe18-11e9-8bb4-a4143c793432.png)
5.Selamat, Git sudah terinstal di Windows. Untuk mencobanya,silahkan buka CMD atau PowerShell, kemudian
 
6. Menambahkan Global Config,Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi user.name dan user.email
7.konfigurasi ini bisa dilakukan untuk global repostiry atau individual repository. apabila belum dilakukan konfigurasi akan terjadi
8.kegagalan saat menjalankan perintah *git commit Config Global Repository
 
9. Perintah Dasar Git,Buka direktory aktif, misal: d:\latihan1 (buka menggunakan Windows Explorer) klik kanan pada direktory
10.	aktif tersebut, dan pilih menu Git Bash,
11.sehingga muncul git bash commad  
12. Buat direktory project praktikum pertama dengan nama --latihan1--
13. Sehingga terbentuk satu direktori baru dibawahnya, selanjutnya masuk kedalam direktori tersebut dengan perintah cd direktory
aktif menjadi: d:\latihan1 
14. Membuat Repository Local Jalankan perintah git init, untuk membuat repository local Repository baru berhasil di inisialisasi,
15.dengan terbentuknya satu direktori hidden dengan nama .git  
16. Pada direktori tersebut, semua perubahan pada working directoryakan disimpan. Menambahkan File baru pada repositor untuk membuat
17. file dapat menggunakan text editor, lalu menyimpan filenya pada direktori aktif (repository disini kita akan coba buat satu file
bernama README.md (text file)
 
18. File README.md berhasil dibuat.Menambahkan File baru pada repository Untuk menambahkan file yang baru saja dibuat tersebut
19.	gunakan perintah git add. File README.md berhasil ditambahkan.   Commit (Menyimpan perubahan ke database)
20. Untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah git commit -m “komentar commit”
21. Perubahan berhasil disimpan. $ git commit -m “File pertama"
 
22. Membuat repository server, server reopsitory yang akan kita gunakan adalah http://github.com
23. Anda harus membuat akun terlebih dahulu.Pada laman github, klik tombol start a project, atau Dari menu (icon +) klik New
Repository
