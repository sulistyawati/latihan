# Instalasi Git
* Download Git, buka website resminya Git [git-scm.com](https://git-scm.com "sulis Cans").
* Kemudian unduh Git sesuai dengan arsitektur komputer kita. Kalau
* Menggunakan 64bit, unduh yang 64bit. Begitu juga kalau menggunakan 32bit.
![downloadgit](https://user-images.githubusercontent.com/57305570/68079180-2aaa8800-fe18-11e9-8bb4-a4143c793432.png)
* Selamat, Git sudah terinstal di Windows. Untuk mencobanya,silahkan buka CMD atau PowerShell, kemudian
 ![cmd](https://user-images.githubusercontent.com/57305570/68079564-31d49480-fe1e-11e9-9e6a-121199694ceb.png)
# Menambahkan Global Config
* Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi user.name dan user.email
* Konfigurasi ini bisa dilakukan untuk global repostiry atau individual repository. apabila belum dilakukan konfigurasi akan terjadi
* Kegagalan saat menjalankan perintah *git commit Config Global Repository
 ![git config](https://user-images.githubusercontent.com/57305570/68079580-5af52500-fe1e-11e9-849e-759fd5a61a9b.png)
# Perintah Dasar Git
* Buka direktory aktif, misal: d:\latihan1 (buka menggunakan Windows Explorer) klik kanan pada direktory
* Aktif tersebut, dan pilih menu Git Bash,
* Sehingga muncul git bash commad  
# Membuat Reposiory Local
* Buat direktory project praktikum pertama dengan nama --latihan1--
![mkdir](https://user-images.githubusercontent.com/57305570/68079586-76f8c680-fe1e-11e9-928b-b66d0b3787fe.png)

* Sehingga terbentuk satu direktori baru dibawahnya, selanjutnya masuk kedalam direktori tersebut dengan perintah cd direktory
aktif menjadi: d:\latihan1 
# Membuat Repository Local
* Jalankan perintah git init, untuk membuat repository local Repository baru berhasil di inisialisasi,
![gitinit](https://user-images.githubusercontent.com/57305570/68079648-6432c180-fe1f-11e9-8186-275ed629c92c.png)
* Dengan terbentuknya satu direktori hidden dengan nama .git  
* Pada direktori tersebut, semua perubahan pada working directoryakan disimpan. Menambahkan File baru pada repositor untuk membuat
* File dapat menggunakan text editor, lalu menyimpan filenya pada direktori aktif (repository disini kita akan coba buat satu file
bernama README.md (text file)
![echolatihan 1](https://user-images.githubusercontent.com/57305570/68079632-233aad00-fe1f-11e9-9207-c14f2e5e3d32.png)
 
* File README.md berhasil dibuat.Menambahkan File baru pada repository Untuk menambahkan file yang baru saja dibuat tersebut
* Gunakan perintah git add. File README.md berhasil ditambahkan.   Commit (Menyimpan perubahan ke database)
* Untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah git commit -m “komentar commit”
* Perubahan berhasil disimpan. $ git commit -m “File pertama"
 ![git commit](https://user-images.githubusercontent.com/57305570/68079874-6dbe2880-fe23-11e9-875d-6006f409846d.png)

# Membuat repository server
* server reopsitory yang akan kita gunakan adalah http://github.com
* Anda harus membuat akun terlebih dahulu.Pada laman github, klik tombol start a project, atau Dari menu (icon +) klik New
Repository
![newrepository](https://user-images.githubusercontent.com/57305570/68079455-65aeba80-fe1c-11e9-80a3-7b3d3a5cac86.png)

* Isi nama repositorynya, misal: latihan. lalu klik tombol Create repository
![create a new repository](https://user-images.githubusercontent.com/57305570/68079725-a8729180-fe20-11e9-9149-15a566ac5da3.png)

* Menambahkan Remote Repository, Remote Repository merupakan repository server yang akan digunakan untuk menyimpan setiap
* Perubahan pada local repository, sehingga dapat diakses oleh banyak user.
* Untuk menambahkan remote repository server, gunakan perintah git remote add origin https://github.com/sulistyawati/latihan 
 
# Push (Mengirim perubahan ke server) Untuk mengirim perubahan pada local repository ke server gunakan perintah git push.
* Perintah ini akan meminta memasukkan username dan password pada akun github.com
 
* Melihat hasilnya pada server repository buka laman github.com,arahkan pada repositorinya.
* Maka perubahan akan terlihat pada laman tersebut. 
# Clone repository
* Pada dasarnya adalah meng-copy repository server dan secara otomatis membuat satu direktory sesuai dengan nama
* Repositorynya (working directory).Untuk melakukan cloning, gunakan perintah git cloneh(url)
 
# Kegunaan file README.md
* Apabila kita menggunakan github, untuk memberikan penjelasan awal pada project yang kita buat, maka
* Dapat menggunakan sebuah file yang bernama README.md Pada file tersebut kita dapat membuat dokumentasi awal dari setiap projec
* Yang kita buat untuk memberikan penjelasan atau sekedar cara penggunaan dari aplikasi yang kita kembangkan.
* Penulisan file README.md berbasis teks, dan untuk pemformatannya menggunakan Markdown format.
* Untuk lebih jelasnya, dapat anda pelajari cara penggunaan markdown pada url berikut: https://guides.github.com/features/masteringmarkdown/.
