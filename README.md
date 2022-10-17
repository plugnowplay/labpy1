# Latihan VCS

# Cara Penggunaan Git
## 1.	Download Git, buka website resminya Git (git-scm.com). 

![1](https://user-images.githubusercontent.com/115965039/196099592-086a0136-3808-438c-8d5b-7d9fdb173888.png)

## 2.	Kemudian unduh Git sesuai dengan arsitektur komputer kita. Kalau menggunakan 64bit, unduh yang 64bit. Begitu juga kalau menggunakan 32bit.

![2](https://user-images.githubusercontent.com/115965039/196099641-6e36f3bf-00f7-439d-b7b0-2fa2ad6a3c39.png)

## 3.	Install Git

![3](https://user-images.githubusercontent.com/115965039/196099661-577474d6-7fc8-4b6c-bfe7-903f8921f524.png)

## 4.	Selamat, Git sudah terinstal di Windows. Untuk mencobanya, silahkan buka CMD atau PowerShell, kemudian ketik perintah 
>git --version

![4](https://user-images.githubusercontent.com/115965039/196099673-dda0d1c4-f20d-42e2-abaf-4f6484a087bb.png)

## 5.	Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi user.name dan user.email
Config Global Repository
>$ git config --global user.name “nama_user”

>$ git config --global user.email “nama_user” 

 
![5](https://user-images.githubusercontent.com/115965039/196100013-4b285dd3-f75c-42de-8c23-323bd59b84e9.png)


## 6.	Buka direktory aktif, misal: d:\LatihanVCS (buka menggunakan Windows Explorer) lalu klik kanan pada direktory aktif tersebut, dan pilih menu Git Bash, sehingga muncul git bash commad
 
![6](https://user-images.githubusercontent.com/115965039/196100038-8995ea3b-80ff-4abe-9690-392369c1e813.png)

## 7.	Buat direktory project praktikum pertama dengan nama “latihanvcs”
>$ mkdir latihanvcs

>$ cd latihanvcs 

![7](https://user-images.githubusercontent.com/115965039/196100062-d245957d-3406-4bf4-ac0d-951305fbbc53.png)


## 8.	Jalankan perintah git init, untuk membuat repository local.
>$ git init 

![8](https://user-images.githubusercontent.com/115965039/196100075-d862e3c2-01e9-4bfe-88db-504c4b3cd754.png)



## 9.	Menambahkan File baru pada repository
>$ echo “# Latihan VCS” >> README.md 

![9](https://user-images.githubusercontent.com/115965039/196100091-ae326271-d59b-4ddd-827f-02b8d620eee5.png)


## 10.	Menambahkan File baru pada repository
>$ git add README.md 

![10](https://user-images.githubusercontent.com/115965039/196100104-f95111ce-b295-492d-a184-279b2a7f27ec.png)


## 11.	Commit (Menyimpan perubahan ke database)
>$ git commit -m “File Latihan VCS” 

![11](https://user-images.githubusercontent.com/115965039/196100154-ec4be467-24a8-4627-84cb-7ee0bcbb4d19.png)


## 12.	Membuat repository server pada github klik menu (icon +), klik New Repository

![12](https://user-images.githubusercontent.com/115965039/196100183-2fe36f85-47ed-4fce-b6fa-24e9c10bc4d2.png)

 
## 13.	Isi nama repositorynya, labpy1.
Lalu klik tombol Create repository  
![13](https://user-images.githubusercontent.com/115965039/196100203-e9be3a8e-a268-4bb1-b872-316aace10e5d.png)



## 14.	Menambahkan Remote Repository Untuk menambahkan remote repository server, gunakan perintah
>$ git remote add origin https://github.com/plugnowplay/labpy1.git  

![14](https://user-images.githubusercontent.com/115965039/196100238-052b9d3e-eba9-40d6-9281-8bcdf33f0195.png)


## 15.	Push (Mengirim perubahan ke server), Untuk mengirim perubahan pada local repository ke server gunakan perintah git push.
>$ git push -u origin master

![15](https://user-images.githubusercontent.com/115965039/196100260-b9f8f089-ff25-4a68-b258-f62ea0ce99ea.png)

 
## 16.	Hasilnya pada server repository 

![16](https://user-images.githubusercontent.com/115965039/196100269-75be7d21-be8b-48a3-b4d5-021faf20422d.png)


