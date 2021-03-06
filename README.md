![pickdress](https://user-images.githubusercontent.com/55394643/120928939-fcd2a700-c710-11eb-9eb4-e8e123b3edac.png)

# Paralel 1

# Kelompok 8 
1. Fatimah Alfiatul Jannah (G64190014) Back End Developer
2. Nadira Nazla (G64190035) UI/UX Designer
3. Fathin Humaira (G64190070) Front End Developer

# Asisten Praktikum:
1. Indah Puspita
2. Qoriatul Khairunnisa

# About The App
PickDress adalah situs yang menyediakan ide kepada pengguna khususnya wanita, baik remaja maupun dewasa mengenai busana apa yang akan dipakai. Terdapat beribu-ribu mix & match busana yang tersedia mulai dari untuk keperluan acara formal maupun non-formal. Situs ini sangat mudah digunakan, pengguna hanya perlu mengunjungi kategori yang sesuai dengan kebutuhan lalu PickDress akan menampilkan berbagai macam ide berpakaian.

# User Analysis
### User story
1. Sebagai [pengunjung website], agar dapat melihat rekomendasi kombinasi baju sesuai kategori yang saya inginkan, saya dapat memilih kategori yang saya inginkan pada daftar kategori dan melihat kumpulan kombinasi baju pada kategori yang saya inginkan.
2. Sebagai [pengguna yang belum terdaftar], agar dapat menggunakan fitur aplikasi secara lebih lengkap, saya dapat membuat akun dengan cara mengetikkan nama email serta password dalam kotak sign up yang sudah disediakan.
3. Sebagai [pengguna terdaftar], agar dapat menggunakan fitur aplikasi secara lebih lengkap, saya dapat login dengan cara mengetikkan nama email serta password dalam kotak sign up yang sudah disediakan.
4. Sebagai [pengguna terdaftar], agar dapat sewaktu-waktu melihat kembali kombinasi baju yang saya sukai, saya dapat menambahkan kombinasi baju yang saya sukai ke dalam daftar favorit.
5. Sebagai [pengguna terdaftar], agar dapat mangatur kombinasi baju yang saya sukai, saya dapat menghapus kombinasi baju yang saya tidak lagi saya sukai dari dalam daftar favorit saya.
6. Sebagai [pengguna website], agar dapat mengirimkan saran untuk PickDress, saya dapat mengisi survey yang disediakan PickDress.

# Spesifikasi Teknis Lingkungan Pengembangan
1. Hardware 
  - Processor: Intel Core i5-8250U 1.6GHz 
  - Memory: 4 GB DDR4 
  - Graphics Card: NVIDIA GeForce MX150 with 2 GB VRAM 
  - Storage: 1000 GB HDD 

2. Software 
  - Text Editor: Sublime Text 3 dan vscode 
  - Operating System: Windows 10 
  - Database: MySQL 
  - Server: Apache 

3. More
  - Collaboration Platform: Github, Trello 
  - PHP, Javascript, CSS, HTML, Bootstrap
  - Visual Editing: Figma

# Hasil dan Pembahasan

### 1. Use Case Diagram
<br>![usecase4](https://user-images.githubusercontent.com/55395896/120944663-ea338e80-c75f-11eb-9140-3016c60171a3.png)</br>

### 2. Activity Diagram
#### Create account
![signup3](https://user-images.githubusercontent.com/55395896/120944015-88255a00-c75c-11eb-9d79-e37ad817a9f3.png)

#### Login
![login3](https://user-images.githubusercontent.com/55395896/120944021-8d82a480-c75c-11eb-9201-bc8322ca0cc8.png)

#### View Dress
![view](https://user-images.githubusercontent.com/55395896/120929510-82efed00-c713-11eb-9adf-c3a6791157d1.png)


#### Add to Favorite
![addfav png2](https://user-images.githubusercontent.com/55395896/120929522-8c795500-c713-11eb-9633-56f84e187c67.png)


#### Remove from Favorite
![delfav1](https://user-images.githubusercontent.com/55395896/120929488-6e135980-c713-11eb-8a42-93344d9f6d83.png)

#### Edit profile
![edit](https://user-images.githubusercontent.com/55395896/120929963-68b70e80-c715-11eb-8a46-8ae701328184.png)

#### Add dress [Admin]
![admn_adddress](https://user-images.githubusercontent.com/55395896/120943508-80b08180-c759-11eb-94d3-020b41db2c02.png)

#### Manage user [Admin]
![admn_manageuser](https://user-images.githubusercontent.com/55395896/120943521-8ad28000-c759-11eb-9f11-194a590ab591.png)

### 3. Class Diagram

![class3](https://user-images.githubusercontent.com/55395896/120944236-9d4eb880-c75d-11eb-895a-c37741bf1016.png)



### 4. Entity Relationship Diagram
![Untitled Diagram-Page-1](https://user-images.githubusercontent.com/55394643/120926977-6484f400-c709-11eb-960d-9d63e4ebcb0d.jpg)

### 5. Arsitektur Sistem
![Untitled Diagram-Page-2 (1)](https://user-images.githubusercontent.com/55394643/120927179-23d9aa80-c70a-11eb-8b31-a85319675911.jpg)


### 6. Fungsi Utama yang Dikembangkan
   - Pada fitur Home Page, terdapat beberapa outfit pilihan yang sedang menjadi tren sehingga user dapat mengetahui outfit apa saja yang sedang menjadi tren.
   - Pada fitur Categories, terdapat kategori outfit yang bervariasi. User dapat memilih kategori yang diinginkan pada daftar kategori dan melihat kumpulan kombinasi baju pada kategori yang diinginkan.
   - Pada fitur Favorite, user yang sudah log in dapat menyimpan outfit yang disukai sehingga user dapat melihat lagi outfit yang sudah tersimpan.
   - Pada fitur Delete, user dapat menghapus outfit yang pernah disukai.
   - Pada fitur Sign Up, user dapat membuat akun agar dapat menggunakan situs seara lebih lengkap dengan mendaftarkan e-mail dan password.
   - Pada fitur Log In, user yang telah memiliki akun dapat menggunakan situs seara lebih lengkap dengan mendaftarkan e-mail dan password.
### 7. Fungsi CRUD
  - Create
    - User: User membuat akun PickDress dengan menginput username, email, dan password
    - Admin: Admin membuat dress baru dengan menginput judul dress, gambar, deskripsi, kategori, dan keyword yang sesuai
  - Read
    - User: User dapat melihat berbagai macam dress sesuai kategori yang sudah di-fetch dari database
    - Admin: Admin dapat membaca seluruh data kecuali password user yang sudah dienkripsi
  - Update
    - User: User dapat mengupdate username dan email dengan cara mengeditnya di halaman profile
    - Admin: Admin dapat mengupdate list dress
  - Delete
    - User: User dapat menghapus dress yang tadinya sudah dimasukkan ke halaman favorit
    - Admin: Admin dapat menghapus list dress dan user

# Hasil Implementasi
### 1. Screenshot sistem
![Screenshot (173)](https://user-images.githubusercontent.com/78713826/120932551-8473e200-c720-11eb-98de-abd4c028deff.png)
![Screenshot (169)](https://user-images.githubusercontent.com/78713826/120932556-8b9af000-c720-11eb-8d69-4069e8c939c6.png)
![Screenshot (168)](https://user-images.githubusercontent.com/78713826/120932562-8fc70d80-c720-11eb-8f03-8ebade9fb9bd.png)
![Screenshot (171)](https://user-images.githubusercontent.com/78713826/120932588-a2414700-c720-11eb-96a4-52b1a6603589.png)
![Screenshot (170)](https://user-images.githubusercontent.com/78713826/120932592-a705fb00-c720-11eb-88e4-d7a81c531a47.png)
![Screenshot (172)](https://user-images.githubusercontent.com/78713826/120932598-abcaaf00-c720-11eb-9e16-73dddb5861a0.png)
![Screenshot (174)](https://user-images.githubusercontent.com/78713826/120932569-95245800-c720-11eb-8cea-593f30dc5077.png)

### 2. Link Aplikasi
   [PickDress](http://pickdress.herokuapp.com)

# Testing (test case)
  #### User Register
  ![Screenshot (144)](https://user-images.githubusercontent.com/78713826/120929624-ee39bf00-c713-11eb-87c6-88a8a9af39f8.png)

  #### User Login
  ![Screenshot (143)](https://user-images.githubusercontent.com/78713826/120929617-e843de00-c713-11eb-88d9-b062b7962066.png)

  #### User Favorit
  ![Screenshot (145)](https://user-images.githubusercontent.com/78713826/120929631-f3970980-c713-11eb-995e-0ad2f9c29313.png)

  #### User Profile
  ![Screenshot (146)](https://user-images.githubusercontent.com/78713826/120929639-f98cea80-c713-11eb-950c-05cb6396ffe5.png)
  
  #### Admin Add Dress
  ![Screenshot (158)](https://user-images.githubusercontent.com/78713826/120931790-5b058700-c71d-11eb-8e8d-67a4e8196d18.png)

  
  #### Admin Dress List
  ![Screenshot (159)](https://user-images.githubusercontent.com/78713826/120931796-6062d180-c71d-11eb-9390-c015988d2af9.png)
  ![Screenshot (160)](https://user-images.githubusercontent.com/78713826/120931799-65c01c00-c71d-11eb-9b88-be2fb4d1ca7b.png)
  
  #### Admin Add User
  ![Screenshot (166)](https://user-images.githubusercontent.com/78713826/120931979-23e3a580-c71e-11eb-8b2b-f4b312e4b0d8.png)


  #### Admin Manage User
  ![Screenshot (165)](https://user-images.githubusercontent.com/78713826/120931989-2c3be080-c71e-11eb-9507-02187232efd2.png)

  
# Saran untuk Pengembangan Selanjutnya
Situs yang kami buat masih jauh dari sempurna dikarenakan waktu dan keterbatasan di sana-sini. Oleh karena itu, selanjutnya ada beberapa fitur yang kami harap dapat kami terapkan ke dalam situs kami, yaitu :
1. User dapat melakukan mix and match sesuai keinginan. Dengan fitur ini, user dapat mengganti set outfit yang ada dengan selera user masing-masing mulai dari aksesoris rambut hingga alas kaki. Bahkan user dapat mengunggah outfit yang dimilikinya untuk kemudian dipadukan dalam fitur ini.
2. Fitur forum yang dapat digunakan oleh user untuk berdiskusi terkait fashion, baik berupa saran, kritik, ataupun rekomendasi.
3. Fitur most favorite outfits yang akan menampilkan beberapa set outfit yang paling banyak disukai oleh user sehingga user lain dapat menjadikan set tersebut sebagai bahan rekomendasi.
4. Fitur share yang memungkinkan user untuk membagikan outfit yang diinginkan kepada orang lain.
5. Fitur search & filter dapat digunakan user untuk mencari outfit sesuai dengan kata kunci yang dimasukkan. User bahkan dapat menggunakan filter untuk menyaring outfit dengan kriteria yang diinginkan.
6. Aplikasi dapat dikembangkan sebagai Mobile App di Android atau iOS, dan menggunakan framework untuk memudahkan pengembangan aplikasi.


Notes: [Repository final ada di branch deploy2]
