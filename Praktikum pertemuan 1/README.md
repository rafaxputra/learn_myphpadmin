#Pengerjaan Jobsheet 1 Konsep Basis Data
**Pertemuan 1**
# Daftar Isi
[Praktikum 1](https://github.com/rafaxputra/learn_phpmyadmin/tree/main/Praktikum%20pertemuan%C2%A01#praktikum-1)

[Praktikum 2](https://github.com/rafaxputra/learn_phpmyadmin/tree/main/Praktikum%20pertemuan%C2%A01#praktikum-2)

[Praktikum 3](https://github.com/rafaxputra/learn_phpmyadmin/tree/main/Praktikum%20pertemuan%C2%A01#praktikum-3)

[Praktikum 4](https://github.com/rafaxputra/learn_phpmyadmin/tree/main/Praktikum%20pertemuan%C2%A01#praktikum-4)

# Praktikum 1

1.	Menjalankan Apache dan MySQL pada XAMPP
![image](https://github.com/rafaxputra/learn_myphpadmin/assets/75997309/e9874a86-30af-4856-bc6d-e90dc6f40262)

2.	Masuk ke http://localhost/phpmyadmin dan membuat database baru
![image](https://github.com/rafaxputra/learn_myphpadmin/assets/75997309/4bd3f201-8639-4ad1-90d6-588a2ea81019)

3.	Merestore basis data penjualan_produk melalui menu import
![image](https://github.com/rafaxputra/learn_myphpadmin/assets/75997309/80af27bc-88e5-47c7-aae9-c103ffc5da4f)

4. Tabel akan muncul setelah file selesai direstore

![image](https://github.com/rafaxputra/learn_myphpadmin/assets/75997309/393c46a8-cb32-4f38-b176-532169e5180d)

# Praktikum 2

1. Untuk menampilkan diagram dari database, klik nama databasenya, di bagian atas klik More, lalu klik **Designer**
   ![image](https://github.com/rafaxputra/learn_myphpadmin/assets/75997309/cc51ce31-bd5d-40b3-a39c-1f5c654cd993)
   ![image](https://github.com/rafaxputra/learn_myphpadmin/assets/75997309/c6e458d1-4a7b-4192-80d6-0e751abe7021)

2. Untuk menampilkan isi dari tabel caranya klik nama tabel. Maka data yang ada di dalam tabel akan muncul disisi kanan
   ![image](https://github.com/rafaxputra/learn_myphpadmin/assets/75997309/825be89a-e21d-43c4-b348-3026c68a809c)

# Praktikum 3

1. Untuk menambahkan data pada tabel penjualan, pilih tabel penjualan dan masuk menu insert
	![image](https://github.com/rafaxputra/learn_myphpadmin/assets/75997309/8613d3d6-d0e7-438d-bf25-883e2cf06063)

2. Menambahkan data penjualan sebagaimana berikut : <SOAL 1>
- kode_penjualan = 3 
- tgl = 8 Februari 2021 
- kasir = Dini 
- total_penjualan = 10.000

	![image](https://github.com/rafaxputra/learn_myphpadmin/assets/75997309/c24c94d9-de9b-417d-bb18-865bdf3045d9)

3. Menambahkan data penjualan sebagaimana berikut : <SOAL 2>
- kode_penjualan = 2 
- tgl = 10 Februari 2021 
- kasir = Dini 
- total_penjualan = 20.000

	![image](https://github.com/rafaxputra/learn_myphpadmin/assets/75997309/88574e46-b614-4d95-9b96-55fba8d50c52)

4. Q : Jelaskan bagaimana solusi agar data pada soal 2 dapat ditambahkan <SOAL 3 >
> A : Solusi agar data pada soal 2 dapat ditambahkan yaitu dengan merubah dahulu nilai dari kode_penjualan Doni yang awalnya 2 menjadi 4

![image](https://github.com/rafaxputra/learn_myphpadmin/assets/75997309/c794447e-36f8-4b19-8525-2d752da7d9a8)

5. Masuk pada tabel data_penjualan dan menambahkan datanya melalui menu insert
6. Tambahkan data detail_penjualan sebagaimana berikut 
- kode_penjualan = 2 
- kode_barang = 3 
- harga = 5.000 
- jumlah = 5

Q : Apakah data dapat ditambahkan? Jelaskan alasannya ! <SOAL 4>
> A : Data dapat ditambahkan karena sebelumnya belum ada data ini dalam tabel detail_penjuaalan

![image](https://github.com/rafaxputra/learn_myphpadmin/assets/75997309/5d2546ae-dc8b-43d8-95bc-0a2225d3ba7c)


7. Q : Jelaskan bagaimana solusi agar data pada soal 4 dapat ditambahkan <SOAL 5>
> A : tidak ada, karena data dapat ditambahkan tanpa error
8. Q : Terangkan apa yang bisa anda pahami dari soal 1-5 terkait dengan duplikasi dan inkonsisten data <Soal 6>
> A : Yang bisa saya pahami, Menambahkan nilai dari data yang sudah ada pada primary key (kode_penjualan) atau duplikasi data tidak bisa dilakukan karena jika bisa dapat menyebabkan inkonsistensi data

# Praktikum 4

1.	Menambahkan data detail_penjualan sebagaimana berikut 
- kode_penjualan = 2 
- kode_barang = 3 
- harga = 5.000 
- jumlah = 5 
 
Q: Apakah data dapat ditambahkan? Jelaskan alasannya ! <SOAL 7>
A: Tidak bisa, karena data sudah ada / sudah pernah ditambahkan sebelumnya  pada  praktikum 2 

2.	Menampilkan struktur dari basis data dengan masuk ke menu designer dan menghapus garis hubung antara tabel penjualan dan detail_penjualan dengan cara klik tanda lingkaran pada ujung garis antara tabel penjualan dan detail_penjualan lalu klik delete 
 
 ![image](https://github.com/rafaxputra/learn_myphpadmin/assets/75997309/483b715b-3c20-42dc-93bc-33a88a92e28c)

3.	Q: Ulangi kembali langkah ke-1 pada praktikum 4. Apakah data dapat ditambahkan? Jelaskan alasannya! <SOAL 8>
A: Tetap tidak bisa ditambahkan karena nilai nya sudah ada atau data tersebut pernah ditambahkan sebelumnya  
