**Hi nama saya Ihsan Hadimulya. Disini saya akan menjelaskan cara penggunaan Git yang kita perlukan adalah**  *Applikasi git , akun git*. Sebelum itu saya akan kasih tutorial cara penginstalan **GIT**.
## Cara penginstalan GIT

  - Pertama anda harus mendownload Aplikasi  Git, buka website resminya Git  di **git-scm.com** .
  
  ![Screenshot (10)](https://user-images.githubusercontent.com/115678077/196750441-6043fbb1-77bb-4278-867c-f4a37905174c.png)
 *Download lah sesuai dengan bit (32 bit atau 64 bit)laptop anda agar support. Setelah selesai download klik instal*
- Lalu klik next simpan file lokasi instal di C:\ProgramFiles\Git(sesuai keinginan anda) , lalu di next saja semua sampai ke step install, TUNGGU SAMPAI SELESAI.

  ![image](https://user-images.githubusercontent.com/56957725/67549597-d8d67380-f72e-11e9-9387-456db6ca1fb8.png)

- Setelah melakukan penginstalan, buka git cmd untuk mengetahui apakah sudah bisa melakukan proses atau belum jika muncul git version berarti sudah siap melakukan proses. Untuk mengetahui versinya ketikan perintah **git --version.**  Saya memakai versi 2.38.0.windows.1

![Screenshot (3)](https://user-images.githubusercontent.com/115678077/196098603-4565e65d-ec03-44ab-8a5d-09eb6542b99d.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### _Cara membuat akun git_
- Disini anda harus membuat akun git terlebih dahulu  untuk membuat repository server bukalah link tersebut *http://github.com*

![Screenshot (4)](https://user-images.githubusercontent.com/115678077/196099581-83e9648a-733b-4db9-ad2e-f79e025f89bc.png)

- Pada langka selanjutnya anda boleh langsung diskip saja.
   
  ### _Membuat repositori baru_

- Ini adalah tampilan pertama setelah kalian selesai membuat akun git

![Screenshot (12)](https://user-images.githubusercontent.com/115678077/196752012-fd382d90-0613-4c04-a3ac-6196d0469aa3.png)

- Langkah selanjutnya nanti anda akan dialihkan ke tab baru untuk membuat repositori baru, isi susuai inspirasi anda setelah selesai klik buat repositori. 

 ![Screenshot (13)](https://user-images.githubusercontent.com/115678077/196752454-cb717234-a336-4fb1-9645-80087f0f6209.png)

-  Lalu nanti di tab baru ada url, url ini akan digunakan untuk remote GitHub.

  ![Screenshot (14)](https://user-images.githubusercontent.com/115678077/196753172-80039262-69ab-483f-965f-44e404a3325d.png)

### _Membuat Reposiory Local_

- Lalu kita buka file explorer pilih dilocal disk c (atau dmana saja sesuai keinginan anda), lalu klik kanan pilih **Git Bash here** .
![Screenshot (11)](https://user-images.githubusercontent.com/115678077/196751276-79df7608-ea14-4f3b-9733-25b64f662327.png)


- Lalu kita akan menambahkan Config Global Repository  pakai user name dan user email yang tadi sudah dibuat, dengan perintah : 	
      **$ git config --global user.email “nama_user”**
      **$ git config --global user.name “nama_user”**

  ![Screenshot (5)](https://user-images.githubusercontent.com/115678077/196102383-4048bb41-2863-48f6-ac27-76afb62bfbf1.png)


- Buatlah direktori baru dengan menggunakan perintah *" mkdir lab_pemrograman1 "*  LALU *" cd lab_pemrograman1/![Screenshot (6)](https://user-images.githubusercontent.com/115678077/196103766-5fd84644-7ca6-49c0-84b5-a0bfa2ba5ad2.png)
 "*.

 ##### _Cara penggunaan git dengan perintah daasar git init fungsi  perintahnya  untuk membuat repository local_ 

- Lalu jalankan perintah *git init* untuk membuat membuat file kosong berformat GIT. File ini fungsinya untuk menyimpan semua perubahan pada working directory dan file ini terbentuknya hidden.
 
   ![Screenshot (7)](https://user-images.githubusercontent.com/115678077/196105249-32aa3e23-b93d-4787-8b4f-a167ae7c7171.png)


-  Lalu buat 1 file baru bernama README.md, dengan memasukan perintah _echo “#lab_pemrograman1” >> README.md. Lalu untuk melihat file ketik perintah “ls 

    ![Screenshot (8)](https://user-images.githubusercontent.com/115678077/196107442-533ef8f2-a381-42f7-9742-130cb1856673.png)

 ##### _Cara penggunaan git dengan perintah dasar git add  fungsi perintahnya untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit_
- Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah *git add*. Dengan perintah _$ git add README.md_. Kalau ingin melihat infonya ketik perintah _git status_.
  ![Screenshot (9)](https://user-images.githubusercontent.com/115678077/196108166-997b8fb3-aa81-4e10-aeda-61af6e3c15c8.png)


- Untuk menyimpan perubahan yang ada kedalam database gunakan perintah _git commit -m “komentar commit"_
  ![67557721-cadd1e80-f73f-11e9-8f44-dc52f8676eb3](https://user-images.githubusercontent.com/115677959/195979372-25d6dfbd-f125-4b89-9d0a-d4d48f5efc75.png)

##### **File berhasil tersimpan**

-  Langkah berikutnya kita kembali ke website GitHub untuk melihat repositori yang sudah dibuat.
Nah di Quick Setup nanti ada url github kita, url tersebut untuk perintah_ “git remote add origin [url] “ DAN PERINTAH GIT CLONE “ git clone [ url ] “_

 ##### _Cara penggunaan git dengan perintah dasar  git remote add origin [url], perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory)_

- Sudah mengetahui url githubnya lalu ketik perintah git remote add origin [url],urlnya diganti dengan url github anda https://github.com/SANEXP04/latihan3.git
   ![Screenshot (15)](https://user-images.githubusercontent.com/115678077/196754512-bfe1c73f-4e34-482f-bd7d-8ea647018ddb.png)


 ##### _Cara penggunaan git dengan perintah dasar git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository_

- Untuk  mengirim perubahan pada local repository ke server gunakan perintah “git push -u origin master”. Ingat pada langkah ini kita harus memasukan usernam dan pasword gethub.
   ![Screenshot (15)](https://user-images.githubusercontent.com/115678077/196754580-b2b4e7f3-cb86-4a49-bf35-77802f21c5fc.png)

 ##### _Cara penggunaan git dengan perintah dasar  git clone [url], perintah untuk membuat working directory yang diambil dari repositry sever._

- Kalau ingin melakukan cloning, gunakan perintah git clone [url], urlnya diganti dengan url github anda https://github.com/SANEXP04/latihan3.git . Jika ingin masuk kedirektorti gunakan perintah “cd [nama direktori anda]”, dan jika ingin melihat semua isi direktori gunakan perintah _“ls -1"_
  ![Screenshot (15)](https://user-images.githubusercontent.com/115678077/196754632-43c80da3-3cf1-4b45-8df7-2a6d35b9e3dd.png)


-  Selesai Jika ingin melihat hasilnya cek di laman gethub arahkan ke repositorinya
  
#### **FILE README.md tersebut masih kosong jikalau anda ingin mengisi kekosongan file tersebut silahkan klik saja icon pensil yang berada di kanan atas**. 
 
