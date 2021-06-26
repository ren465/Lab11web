# Renaldi
# TI.19C1
# Lab11web
# Langkah 1
Mengaktfikan Ektensi xampp , dengan menghilangkan tanda ; (titik koma) pada bagian ektensi yang akan digunakan kemudian restart apache webs server
# Langkah 2
Menginstall codeigniter 4.![1](https://user-images.githubusercontent.com/81818422/122623856-f7d60600-d0c7-11eb-9cec-b4d2caf1b85f.png)
# Langkah 3
Menjalankan command line interface dan perintah php spark
![2](https://user-images.githubusercontent.com/81818422/122623951-50a59e80-d0c8-11eb-9ae1-ac182c960cb3.png)
# Langkah 4
Mengaktifkan mode debugging untuk memudahkan mengetahui pesan eror apabila terjadi kesalahan dalam kode program
![3](https://user-images.githubusercontent.com/81818422/122624008-8cd8ff00-d0c8-11eb-984f-ae14b828821f.png)
# Contoh pesan eror dengan menghilangkan titik koma di akhir kode
![4](https://user-images.githubusercontent.com/81818422/122624084-dd505c80-d0c8-11eb-8276-a2542a43f03e.png)

![5](https://user-images.githubusercontent.com/81818422/122624088-df1a2000-d0c8-11eb-9314-bbe4d2a16ae3.png)
# Langkah 5
# Mengecek route, menambahkan controller baru dan menambahkan route baru
![6](https://user-images.githubusercontent.com/81818422/122624464-80ee3c80-d0ca-11eb-8f2a-5dffdd0317f6.png)
![7](https://user-images.githubusercontent.com/81818422/122624465-83509680-d0ca-11eb-911b-0fb2e488cc0a.png)
# Langkah 6
Mengakses route dengan url localhost/about karena server apache saya mengggunakan kode 80 maka tidak dituliskan localhost:8080/about
![8](https://user-images.githubusercontent.com/81818422/122624475-8c416800-d0ca-11eb-9167-0693fa193f73.png)
# Langkah 7
Mengaktifkan auto rooting dengan mengubah setAutoRoute(true)
![9](https://user-images.githubusercontent.com/81818422/122624486-99f6ed80-d0ca-11eb-9b8c-39eae5cd05f2.png)
# Langkah 8
Menambahkan method baru pada controller page dan mengaksesnya
![10](https://user-images.githubusercontent.com/81818422/122624503-a4b18280-d0ca-11eb-980c-b12c7f761508.png)
# Langkah 9
Menambahkan layout web dengan menggunakan css disini kita akan menggunakan css dari layout pratikum 4
![11](https://user-images.githubusercontent.com/81818422/122624535-cc084f80-d0ca-11eb-8e86-3e347b796bba.png)
# langkah 10 
Membuat database baru dan membuat tabel
![1](https://user-images.githubusercontent.com/81818422/123495113-91636180-d64c-11eb-9006-73e0459519a7.png)
# Langkah 11
Mengkonfigurasi koneksi database, disini kita akan mengkonfigurasi file .env
![2](https://user-images.githubusercontent.com/81818422/123495155-b1932080-d64c-11eb-9fdd-403db7ef44d5.png)
# langkah 12
Membuat model untuk memproses data artikel
![17](https://user-images.githubusercontent.com/81818422/123495806-6af2f580-d64f-11eb-87a5-c0e51a1be4d2.png)

# 13
Membuat controller baru dengan nama artikel.php
![3](https://user-images.githubusercontent.com/81818422/123495818-79411180-d64f-11eb-9064-16f201f79604.png)
# 14
Membuat view baru dengan nama artikel pada direktori app/view
![4](https://user-images.githubusercontent.com/81818422/123495875-ae4d6400-d64f-11eb-9608-11542ee5e05d.png)

# 15
Selanjutnya buka localhost/artikel maka akan tampil seperti ini
![5](https://user-images.githubusercontent.com/81818422/123495884-b60d0880-d64f-11eb-9e01-097b429da9ad.png)


# 16
Membuat tampilan detail artikel dengan menambahkan controller baru dengan view()
![6](https://user-images.githubusercontent.com/81818422/123495886-bb6a5300-d64f-11eb-811f-bcde43fd80df.png)



# 17
Membuat view detail dengan cara membuat file baru di direktori app/view/artikel/detail.php
![7](https://user-images.githubusercontent.com/81818422/123495893-c0c79d80-d64f-11eb-937d-058ba6bbcff4.png)


# 18
Membuat rooting untuk artikel detail

![8](https://user-images.githubusercontent.com/81818422/123495907-c7eeab80-d64f-11eb-9323-74ef69f76f68.png)


# 19
Membuat rooting untuk artikel detail

![9](https://user-images.githubusercontent.com/81818422/123495912-cf15b980-d64f-11eb-92fd-01aea950ed4f.png)

# 20
Membuat view untuk tampilan admin dengan nama admin_index.php
![10](https://user-images.githubusercontent.com/81818422/123495925-d937b800-d64f-11eb-90c4-7e38b6ccbcb4.png)

# 21
Menambahkan routing baru untuk menu admin
![11](https://user-images.githubusercontent.com/81818422/123495935-e18ff300-d64f-11eb-906d-09fc86e1b291.png)

# 22
Menambahkan method baru pada controller artikel dengan nama add()
![12](https://user-images.githubusercontent.com/81818422/123495941-e8b70100-d64f-11eb-8f84-fe8528ddc35f.png)


# 23
membuat view untuk form tambah dengan nama form_add.php
![13](https://user-images.githubusercontent.com/81818422/123495950-f2406900-d64f-11eb-9908-a2348f0dacf9.png)



# 24
Menambahkan method baru pada controller artikel dengan nama edit()
![14](https://user-images.githubusercontent.com/81818422/123495960-fb313a80-d64f-11eb-958c-754baae69f02.png)

# 25
Membuat view untuk membuat form tambah dengan nama form_edit.php
![15](https://user-images.githubusercontent.com/81818422/123495971-01bfb200-d650-11eb-93bf-e5cb029a5a8e.png)

# 26
Menghapus data dengan menambahkan method baru pada controller artikel dengan nama detele()
![17](https://user-images.githubusercontent.com/81818422/123495977-08e6c000-d650-11eb-9f97-d4825081128e.png)

# Sekian Dan Terimakasih




