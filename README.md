# Python Project Pacmann - Super Cashier
Tugas Akhir Introduction Python dari Sekolah Data PACMANN pada Program Analytics dan Data Science 

## Latar Belakang
Andi seorang pemilik supermarket besar yang memiliki rencana untuk melakukan ekspansi bisnis dengan membuat sistem kasir self-service. Tujuannya adalah agar customer bisa membeli barang secara langsung melalui sistem kasir self-service tersebut, bahkan ketika mereka tidak berada di kota tersebut. Setelah melakukan riset, Andi menemukan bahwa untuk mewujudkan rencana ini, dia membutuhkan seorang programmer untuk membuat fitur-fitur yang dibutuhkan agar sistem kasir self-service tersebut dapat berjalan dengan lancar.

## Fitur-Fitur Program
Program sistem kasir self service yang diminta sebagai berikut:
1. Customer membuat ID Transaksi customer dengan membuat nama objek dari class transaksi_1 = c.Transaction() akan menggunakan skrip dari Cashier.py
2. Customer menambahkan barang yang ini dibeli dan detail jumlah dan harganya transaksi_1.add_item('Nama Barang', Jumlah Barang, Harga Satuan Barang)
3. Customer mengecek barang yang telah diinputkan dengan transaksi_1.check_data item()
4. Customer ingin menghapus salah satu barang yang telah diinputkan dengan transaksi_1.delete_item('Nama Barang')
5. Customer ada mengalami kesalahan dalam memasukkan nama item atau jumlah item atau harga item tetapi tidak ingin menghapus itemnya dan menampilkan Kesalahan Inputnya, Customer bisa melakukan dengan sebagai berikut:
* a. Update nama barang dengan method: transaksi_1.update_name_item('Nama Barang', 'Nama Barang Terbaru')
* b. Update jumlah barang dengan method: transaksi_1.update_amount_item('Nama Barang', Jumlah         Barang Terbaru)
* c. Update harga barang menggunakan method: transaksi_1.update_price_item('Nama Barang', Harga   Barang Terbaru)
6. Customer yang ingin menghapus seluruh data yang diinput secara langsung dapat menggunakan method: transaksi_1.reset_transaction()
7. Customer akan mendapatkan diskon secara langsung dengan ketentuan:
* a. Jika total belania Andi diatas Rp 200.000 maka akan mendapatkan diskon 5%
* b. Jika total belania Andi diatas Rp 300.000 maka akan mendapatkan diskon 8%
* c. Jika total belania Andi diatas Rp 500.000 maka akan mendapatkan diskon 10%

## Flowchart Program

![Python Project Pacmann_Super Cashier](https://user-images.githubusercontent.com/109641986/218257477-7593a56d-0fa6-4c76-87eb-f1e89b5967a3.jpg)


## Penjelasan Fungsi
a. Fungsi __init__(self): fungsi yang menginisialisasi dictionary data transaksi

b. Fungsi add_item(self, name_item, amount_item, price_item): fungsi menambahkan item ke data transaksi 

c. Fungsi update_amount_item(self, name_item, new_amount): fungsi untuk memperbarui data jumlah barang di record yang sudah ada

d. Fungsi update_price_item(self, name_item, new_price): fungsi untuk memperbarui data harga satuan barang di record yang sudah ada

e. Fungsi  update_name_item(self, name_item, new_name): fungsi untuk memperbarui data nama barang di record yang sudah ada

f. Fungsi check_data_item(self): Menampilkan daftar transaksi belanja barang beserta diskon dan total akhir pembayaran.

g. Fungsi delete_item(self, name_item): fungsi ini digunakan untuk menghapus item transaksi.

h. Fungsi reset_transaction(self): Fungsi yang digunakan untuk mereset atau menghapus semua data transaksi

i. Fungsi total_discount(self, total_price): Fungsi yang menghitung diskon transaksi

## Test Case
![image](https://user-images.githubusercontent.com/109641986/218247787-320a4422-dd82-41f9-81d6-11cd2425c682.png)
![image](https://user-images.githubusercontent.com/109641986/218247813-9bc69181-fecb-4f3f-a6c2-7afd8228e7ce.png)
![image](https://user-images.githubusercontent.com/109641986/218247878-5abe2f11-098b-4dd9-907e-3f110a4b5389.png)
![image](https://user-images.githubusercontent.com/109641986/218247897-8d0e80ff-e1d1-4757-b1c3-3b87d0d45d55.png)
![image](https://user-images.githubusercontent.com/109641986/218247917-e9ba2899-73ae-448f-b74d-f9dd13d16d60.png)
![image](https://user-images.githubusercontent.com/109641986/218247933-0880f27a-db5c-4d3d-8660-ac893aaaeb6f.png)
![image](https://user-images.githubusercontent.com/109641986/218247942-63eca841-0184-4d84-bb6b-be3b73f98634.png)

