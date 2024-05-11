
# Jobsheet-06 CDM PDM

# SOAL 1
# Perhatikan diagram ERD di bawah ini

![image](https://github.com/rafaxputra/learn_phpmyadmin/assets/75997309/64aaf2b6-12e8-4657-8754-8ad3df1b3fed)

Terdapat beberapa ketentuan dari diagram ERD tersebut:<br>
a. Setiap siswa dapat mengambil beberapa course<br>
b. Setiap course diambil oleh banyak mahasiswa<br>
c. Id_student memiliki tipe data integer dengan length 8<br>
d. Name memiliki tipe data char dengan length 30<br>
e. Address memiliki tipe data varchar dengan length 60<br>
f. Id_course memiliki tipe data varchar dengan length 5<br>
g. Course title memiliki tipe data varchar dengan length 25<br>
 Buatlah model relational, CDM, dan PDM dari ERD diatas


# CDM :

![image](https://github.com/rafaxputra/learn_phpmyadmin/assets/75997309/6a118aa2-463d-42f7-908c-b187045489e9)

# PDM :

![image](https://github.com/rafaxputra/learn_phpmyadmin/assets/75997309/26de1158-fddf-469c-963d-334bc7015d9b)



# SOAL 2
>> Buatlah CDM dan PDM untuk skenario berikut dengan terlebih dahulu membuat relational key yang terdiri dari nama relasi, superkey, candidate key, primary key, foreign key, dan alternate key.
Salah satu toko boneka di Malang ingin merubah sistem penjualan yang awalnya manual menjadi otomatis. Oleh karena itu dibutuhkan peracangan basis data dengan memperhatikan proses bisnis dan objek yang terlibat dalam kegiatan jual bali di toko boneka tersebut. Terdapat beberapa
ketentuan di toko tersebut sebagai berikut :<br>
1. Member memiliki salah satu jenis member<br>
2. Member dapat melakukan pembelian sebanyak mungkin selama membutuhkan. Dan setiap transaksi penjualan dilakukan oleh setiap member secara bergantian<br>
3. Pegawai dapat melayani banyak transaksi penjualan dalam sehari<br>
4. Setiap hari banyak boneka yang terjual, dan sekali transaksi penjualan dapat terdiri dari beberapa boneka secara sekaligus**


# CDM :

![image](https://github.com/rafaxputra/learn_phpmyadmin/assets/75997309/df91e3a2-983b-41f0-8f98-cb668f5d4e47)

# PDM :

![image](https://github.com/rafaxputra/learn_phpmyadmin/assets/75997309/e9c21e76-3a28-4c7a-a40e-4156a988f489)


# SOAL 3

# Buatlah tabel deskripsi, CDM dan PDM untuk skenario berikut :
Salah satu restaurant terbesar di Indonesia ingin memperbaiki sistem booking yang dulunya manual menjadi otomatis. Untuk itu diperlukan perncangan basis data sesuai dengan kebutuhan dan sistem yang ada di restaurant tersebut.
Konsumen : kode konsumen, nama awal, nama akhir, no telepon, email, dan keterangan.<br>
Booking : kode booking, dan tanggal<br>
Meja : no meja dan detil meja<br>
Pesanan : kode pesan, dan tanggal<br>
Staf : kode staf, nama awal, nama akhir<br>
Peranan : kode peranan, nama peranan<br>
Menu pesanan : kode menu pesanan, kuantitas, komen<br>
Menu : kode menu, tanggal<br>
Item menu : kode item menu, keterangan, harga<br>
Bahan : kode bahan, nama bahan<br>
Item bahan : kode item bahan dan kuantitas<br>
Tipe bahan : kode tipe bahan dan deskripsi<br>

>> Terdapat beberapa aturan dalam proses pemesanan di restaurant tersebut. Mulai dari setiap konsumen dapat melakukan banyak booking atau tidak sama sekali, setiap meja dapat dibooking oleh banyak konsumen atau tidak sama sekali. Setelah mendapatkan meja pemesanan dapat dilakukan atau tidak jadi dilakukan. Setiap pesanan dilakukan hanya pada satu meja, dan setiap staf dapat melayani banyak pesanan dalam suatu waktu atau tidak sama sekali. Staf yang melayani konsumen pasti memiliki peranan tertentu. Pemesanan dapat memesan banyak menu pesanan atau tidak sama sekali (dalam artian hanya meminjam meja saja tetapi menu dari luar). Setiap item menu terdapat dalam banyak menu pesanan atau tidak sama sekali. Item menu dapat
tertulis atau tidak tertulis di dalam menu yang disediakan. Item menu yang ada terdiri dari banyak Item bahan atau bahkan tidak tertulis di dalam item bahan. Semua bahan yang digunakan dalam item bahan tersimpan di dalam informasi bahan, tetapi belum tentu sebaliknya. Ternyata bahan tersebut memiliki tipe bahan yang bisa jadi sama antara satu bahan dengan bahan yang lain atau bahkan tidak ada di dalam bahan yang tersedia

# CDM :

![image](https://github.com/rafaxputra/learn_phpmyadmin/assets/75997309/21b9a716-4ce3-4557-af9c-1fb8cd4ee2cd)


# PDM :

![image](https://github.com/rafaxputra/learn_phpmyadmin/assets/75997309/ee4b9d44-4845-470a-bef6-67ab8f43f755)



