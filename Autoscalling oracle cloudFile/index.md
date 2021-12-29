# AutoScalling Oracle Cloud

# Konfigurasi Instance
1. Pada halaman detail instance, klik menu More Actions dan pilih Create Instance Configuration.
![langkah1](src/1.png)
2. Pilih kompartemen Anda.
![langkah1](src/2.png)
3. Untuk nama, masukkan instance-config.
![langkah1](src/3.png)
4. Click Create Instance Configuration.
![langkah1](src/4.png)

# Instance Pool
1.	klik Create Instance pool
![langkah1](src/5.png)
2.	Dari daftar Kompartemen, pilih kompartemen tempat Anda membuat konfigurasi instans.
![langkah1](src/6.png)
3.	Untuk nama, masukkan my-instance-pool.
![langkah1](src/7.png)
4.	Dari daftar Konfigurasi Instance, pilih instance-config.
![langkah1](src/8.png)
5.	Untuk number of instans, masukkan 3. Jumlah instans menunjukkan jumlah maksimum instans yang dapat disediakan di kolam instans. Jumlah instans yang dapat disediakan bergantung pada batas layanan penyewa Anda dan ketersediaan bentuk komputasi di wilayah Anda.
![langkah1](src/9.png)
6.	Klik next
![langkah1](src/10.png)

# konfigurasi Autoscalling
1.	Klik menu More Actions dan pilih Create Autoscaling Configuration.
![langkah1](src/11.png)
2.	Untuk nama, masukkan my-autoscaling-config.
![langkah1](src/12.png)
3.	Dari daftar Buat di kompartemen, pilih kompartemen tempat Anda membuat kumpulan instans.
![langkah1](src/13.png)
4.	Klik Next.
5.	Setelah Anda mengonfigurasi Autoscalling policy, klik Create. Anda dapat menentukan beberapa konfigurasi penskalaan otomatis untuk kumpulan instance yang sama, dan Anda dapat mengaktifkan atau menonaktifkannya salah satunya.
![langkah1](src/14.png)
