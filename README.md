# Cara Membuat Repository dalam Github
Disini saya akan mencoba membahas sedikit tentang bagaimana cara membuat Repository dalam Github menggunakan sistem operasi Windows.
## 1. Download dan Instalasi
Silakan Anda download dan install aplikasi git dalam website resminya Git (git-scm.com) sesuai dengan arsitektur komputer kita.
## 2. Membuat akun Github
Langkah selanjutnya, kita akan membuat akun Github terlebih dahulu. Silakan klik dan kunjungi website resminya Github, dan akan muncul tampilan seperti di bawah ini:

![img daftar repo](https://github.com/kameliacindy/LatihanVCS/blob/master/gambar/img%20daftar%20repo.jpeg)

Setelah itu, klik **"Sign up for Github"**, lalu akan muncul seperti ini :

![sign up](https://github.com/kameliacindy/LatihanVCS/blob/master/gambar/Img_4.png)

Pada langkah ini, Anda harus mengisi sesuai dengan perintahnya untuk membuat akun Github pada Step 1 dan mengikuti sampai selesai pada Step 3.
## 3. Membuat Repository Baru
Lihat pada pojok kanan atas halaman lalu klik ikon **"+"** dan klik **"New Repository"** 

![img new repo](https://github.com/kameliacindy/LatihanVCS/blob/master/gambar/img%20new%20repo.jpeg)

Lalu, akan muncul tampilan seperti di bawah ini :

![img sign up]

Dan kita akan mengisi kolom **"Repository name"** dengan nama **"Latihan1"**. Lalu, klik **"Create Repository"**.
## 4. Menghubungkan dengan Git
Silakan Anda buka aplikasi git yang sudah Anda install, yaitu **"Git Bash"** dengan cara klik kanan pada desktop atau klik **"Menu Start"** lalu ketik Git Bash.

Pertama kali silakan Anda ketikkan kode di bawah ini untuk memperkenalkan diri Anda dengan cara menuliskan username dan password :

```
$ git config --global user.name “nama_ku”
```
```
$ git config --global user.email emailku
```

Contoh :

```
$ git config --global user.name “nama_ku”
```
```
$ git config --global user.email namaku@gmail.com
```

Kemudian kita cek lokasi direktori kita saat ini :

```
$ pwd 
```
Selanjutnya, kita akan membuat folder di dalam di **disk "D"** dengan nama folder **"Latihan1"** :

```
$ cd d:
$ mkdir Latihan1
$ cd Latihan1
```
Lalu, masukkan perintah berikut untuk file **"README.md"** 

```
$ echo "# Latihan1" >> README.md
$ git init 
$ git add README.md
$ git commit -m "File pertama saya"
$ git remote add origin [Url_Repository_anda]
$ git push -u origin master
```

Untuk mendapatkan **"Url_Repository_anda"** ,silakan buka Repository yang sudah Anda buat dengan nama **"Latihan1"** pada akun github Anda, lalu pilih **"Clone or download"** dan salin url yang tertera.

Contoh kode perintah yang akan anda masukan :

```
$ git remote add origin https://github.com/kameliacindy/latihan1.git
```

Setelah anda memasukan semua kode perintah, anda akan diminta memasukan **"Username"** dan **"Password"** github anda.

## 5. Finally
Silahkan refresh browser anda untuk melihat hasil yang sudah anda kerjakan tadi.
Dan selamat! Anda telah berhasil membuat file repository dalam Github dengan nama **"Latihan1"** yang berisi file **"README.md"**



Semoga bermanfaat...