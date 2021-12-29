# Serverlees

# Hello World Function

# Membuat Application dan Function
1. 	Masuk ke akun https://cloud.oracle.com dan navigasi ke menu Developer Services -> Applications
![langkah](src/1.png)
2. 	Tekan tombol Create Application dan lengkapi informasi form Name dengan hello-app. Lengkapi juga VCN dan subnet yang dibutuhkan. Jika anda belum mempunyai VCN, silahkan membuat terlebih dahulu VCN.
![langkah](src/2.png)
3.	Tekan tombol create dan tunggu sampai muncul halaman Getting Started.
![langkah](src/3.png)
4. 	Pada halaman Getting Started terdapat contoh langkah-langkah deploy menggunakan perintah fn. Terdapat dua pilihan deploy, melalui Cloud Shell Setup atau Local Setup.
![langkah](src/4.png)
5. 	Aktifkan Cloud Shell dengan menekan tombol Launch Cloud Shell. Tunggu proses provisioning cloud shell selesai. Anda akan mendapatkan sebuah terminal built-in yang dapat digunakan untuk melakukan proses deployment.
![langkah](src/5.png)
![langkah](src/6.png)
6. 	Ikuti langkah-langkah dengan melakukan copy perintah kemudian tempelkan ke dalam terminal Cloud Shell.
![langkah](src/7.png)
![langkah](src/8.png)
![langkah](src/9.png)
7. 	Perhatikan pada langkah ke 4, ubah nilai [repo-name-prefix] menggunakan username / repository name. Sebagai contoh: polinema
![langkah](src/10.png)
8. 	Pada langkah ke 5, dilakukan proses pembuatan token untuk autentikasi. Tekan tombol Generate Token dan lengkapi form Description dengan nama yang relevan (contoh: faas). Simpan token tersebut.
![langkah](src/11.png)
![langkah](src/12.png)
9. 	Token yang didapatkan, akan digunakan untuk autentikasi pada langkah ke 6. Tempel token yang didapatkan dan pastikan proses login telah berhasil.
![langkah](src/13.png)
10. Ikuti langkah-langkah sampai anda dapat menampilkan tampilan “Hello, world!”
![langkah](src/14.png)
![langkah](src/15.png)
![langkah](src/15.1.png)
![langkah](src/15.2.png)
![langkah](src/15.3.png)
![langkah](src/16.png)
11. Navigasi menu ke Functions di sebelah kiri bawah. Anda akan mendapatkan detil fungsi yang tersedia. Pada halaman ini terdapat informasi mengenai Functions, serta invoke endpoint yang dapat digunakan untuk pemanggilan function.
![langkah](src/17.png)

# Memanggil Function
1. Selain menggunakan fn, Function pada FaaS dapat juga dipanggil menggunakan oci-cli.
2. Salin invoke endpoint kemudian panggil
![langkah](src/18.png)