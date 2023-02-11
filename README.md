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

## Penjelasan Fungsi

## Test Case
