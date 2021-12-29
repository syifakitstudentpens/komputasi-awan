# Software as a Service

## Pembuatan Aplikasi 
1. Membuat Aplikasi (Create Web Application)
* Login OCI
![langkah](src/pembuatan_aplikasi/1.png)
* Pilih OCI Classic Service -> Create Instace
![langkah](src/pembuatan_aplikasi/2.png)
* Isi nama instace, nama, deskripsi dari instance, Region dan tak
![langkah](src/pembuatan_aplikasi/3.png)
* Hasil instance yang telah dibuat:
![langkah](src/pembuatan_aplikasi/4.png)
![langkah](src/pembuatan_aplikasi/5.png)
![langkah](src/pembuatan_aplikasi/5.1.png)
* Lihat pada pojok kiri, terdapat simbol menu (klik simbol tersebut dan akan muncul menu beriku),
Kemudian pilih Open Visual Builder Home Page
![langkah](src/pembuatan_aplikasi/6.png)
* Tunggu beberapa saat, kemudian jika berhasil akan muncul halaman berikut. Klik New Application
![langkah](src/pembuatan_aplikasi/7.png)
![langkah](src/pembuatan_aplikasi/8.png)
* Isi informasi tentang aplikasi yang akan dibuat :
![langkah](src/pembuatan_aplikasi/9.png)
* Jika kita berhasil membuat akan muncul nama aplikasi yang akan kita buat seperti gabari dibawah ini
![langkah](src/pembuatan_aplikasi/10.png)
* Klik nama aplikasi yang telah kita buat (seperti pada gambar sebelumnya), maka akan muncul
halaman beriku:
![langkah](src/pembuatan_aplikasi/11.png)
* Pada sisi kiri adalah menu dari (kotak berwarna merah) visual builder dari aplikasi yang akan kita
buat, pilih ikon web kemudian akan muncul menu berikut :
![langkah](src/pembuatan_aplikasi/12.png)

2. Pada dialog box Create Application, isi nama web dengan nama “hrwebapp” dan untuk
novigation style biarkan none.
![langkah](src/pembuatan_aplikasi/13.png)
3. Expand hrwebapp, kita akan melihat struktur struktur dari aplikasi web, kurang lebih seperti
gambar dibawah ini:
![langkah](src/pembuatan_aplikasi/14.png)


## Import Location Busines dari file
1. Klik Busines Object , pada tab navigator:
![langkah](src/Import_Location_Busines_dari_file/1.png)
2. Klik tombol + Busines Object.
![langkah](src/Import_Location_Busines_dari_file/2.png)
3. Pada dialog box Busines Object, isi field label dengan “Location” kemudian tekan tombol create
(pada field name akan otomatis terisi).
![langkah](src/Import_Location_Busines_dari_file/3.png)
4. Klik Field tab
![langkah](src/Import_Location_Busines_dari_file/4.png)
5. . Klik + Field untuk menambahkan Busines Object
![langkah](src/Import_Location_Busines_dari_file/5.png)
6. Ketika pup-up box, masukan
* Label: Name
* Field Name: name (automatically populated)
* Type: String String (selected by default)
![langkah](src/Import_Location_Busines_dari_file/6.png)
7. Pada property instpector, centang Required di bawah label constrain
![langkah](src/Import_Location_Busines_dari_file/7.png)
8. Klik Menu icon dan pilih Data Manager (Data Manager bisa kita gunakan untuk mengimpor
data dari berbagai sumber)
![langkah](src/Import_Location_Busines_dari_file/8.png)
9. Pilih Impor From File.
![langkah](src/Import_Location_Busines_dari_file/9.png)
![langkah](src/Import_Location_Busines_dari_file/10.png)
![langkah](src/Import_Location_Busines_dari_file/11.png)
10. Di kotak dialog Impor Data, klik kotak impor, pilih Location.csv, dan klik Impor. Ketika impor
berhasil, klik Tutup.
![langkah](src/Import_Location_Busines_dari_file/12.png)
![langkah](src/Import_Location_Busines_dari_file/13.png)
11.  di panel Bisnis Object, klik Location, lalu klik tab Data untuk melihat Location
![langkah](src/Import_Location_Busines_dari_file/14.png)

## Department Business Object
1. Pada panel Business Objects, klik tanda +, lalu pilih Business Object
2. Pada new Business Object dialog Box, Pada field label isi dengan “Department”.
![langkah](src/departement_bussines_object/1.png)
![langkah](src/departement_bussines_object/2.png)
3. Klik Fields tab kemudian klik + Field.
![langkah](src/departement_bussines_object/3.png)
4. Pada pop-up box, masukan:
* Label: Name
* Field Name: name (automatically populated)
* Type: String String icon (selected by default)
* Click Create Field.
![langkah](src/departement_bussines_object/4.png)
5. Pada property instpector, centang Required di bawah label constrain.
6.  Klik Fields tab kemudian klik + Field

* Label: Location
* Field Name: location (automatically populated)
* Type: Reference Reference icon
* Referenced Business Object: Location

## Employee Business Object
1. Pada panel Bisnis oject, klik tanda +, lalu pilih Bisnis Objek.
![langkah](src/employe_bussines_object/1.png)
2. Pada new Business Object dialog Box, Pada field label isi dengan “Employee”.
![langkah](src/employe_bussines_object/2.png)
3. . Klik Fields tab kemudian klik + Field.
![langkah](src/employe_bussines_object/3.png)
4. Pada pop-up box, masukan:
* Label: Name
* Field Name: name (automatically populated)
* Type: String String icon (selected by default)
* Click Create Field.
![langkah](src/employe_bussines_object/4.png)
5. Pada property instpector, centang Required di bawah label constrain.
![langkah](src/employe_bussines_object/5.png)

6. . Pilih + Fields, kemudian mauskan atau is
* Label: Department
* Field Name: department (automatically populated)
* Type: Reference Reference
* Referenced Business Object: Department

* Display Field: Name (automatically populated)
* Klik Create Field
![langkah](src/employe_bussines_object/6.png)
7. Pilih + Fields, kemudian mauskan atau isi
* Label: Hire Date
* Field Name: hireDate (automatically populated)
* Type: Date Date
* Klik Create Field.
![langkah](src/employe_bussines_object/7.png)
8. Pilih + Fields, kemudian mauskan atau isi:
* Label: Email
* Field Name: email (automatically populated)

* Type: Email Email
* Klik Create Field, Di editor properti, Format diatur ke Email.
![langkah](src/employe_bussines_object/8.png)
9. Klik tab Endpoints dan lihat API resource dan REST end point yang dibuat untuk Business Object
Empoyee. Karena Object Employee merujuk ke Department, kita dapat melihat end point untuk
kedua objek terseut jika Anda memperluas node departmentObject. Perluas node Resource API
untuk melihat URL untuk mengakses metadata dan data untuk objek bisnis, lalu perkecil lagi.
![langkah](src/employe_bussines_object/9.png)
10. Di panel Objek Bisnis Navigator, klik tab Diagram, lalu klik tombol + busines object diagram
![langkah](src/employe_bussines_object/10.png)
11. Pada Create Business Object Diagram dialog box, isi field Diagram name dengan “HRDiagram”
![langkah](src/employe_bussines_object/11.png)
12. Pada properti inspector, pilih semua
![langkah](src/employe_bussines_object/12.png)

# main-start Page untuk Display Departments

1. Pilih Web Applications pada tab navigator.
![langkah](src/main_start_Page_untuk_Display_Departments/1.png)
2.  Expand main nodes
![langkah](src/main_start_Page_untuk_Display_Departments/2.png)
3. . Perhatikan pada componen palette, tempatkan Heading komponen pada bagian common
kemudian drag (heading) ke halaman.
![langkah](src/main_start_Page_untuk_Display_Departments/3.png)
4.  Pada heading property inspector, isi text field dengan “ Departments” .
![langkah](src/main_start_Page_untuk_Display_Departments/4.png)
5. . Pada components palette, scroll down sampai menemukan collection, pilih table, kemudian drop
di bawah heading (departement)
![langkah](src/main_start_Page_untuk_Display_Departments/5.png)
6. Klik Add Data di Property Inspector untuk membuka Add Data Quick Stats
![langkah](src/main_start_Page_untuk_Display_Departments/6.png)
7. . Pada halaman Quick Start, pilih busines object Departemen, lalu klik next.
![langkah](src/main_start_Page_untuk_Display_Departments/7.png)
8. Pada halaman Bind Data, di bawah item[i], centang id dan nama
![langkah](src/main_start_Page_untuk_Display_Departments/8.png)
9. Perluas node locationObject dan item dan pilih name untuk mengaktifkan location name agar
muncul di tabel. Klik next.
![langkah](src/main_start_Page_untuk_Display_Departments/9.png)
10. .Pada halaman Query Page, klik Finish.
![langkah](src/main_start_Page_untuk_Display_Departments/10.png)
11. .Untuk membuat kolom nama lokasi deskriptif, klik Data tab. dibawah Table (side menu bar
sebelah kanan), klik ikon Detail arrow disebelah Name (locationObject)
![langkah](src/main_start_Page_untuk_Display_Departments/11.png)
12. .Pada kolom, Header text field, ubah “Name” menjadi “Location”. Kemudian klik untuk kembali
ke sub menu Data tab. 
![langkah](src/main_start_Page_untuk_Display_Departments/12.png)

 # Page untuk Department Business Object
 1. . Klik ta Quick Start (side menu sebelah kanan), kemudian klik Add Create Page.
 ![langkah](src/Page_untuk_Department_Business_Object/1.png)
 2. Kemudian pada halaman End point, pilih busines object Department, kemudian pilih next.
 ![langkah](src/Page_untuk_Department_Business_Object/2.png)
 3. Pada halaman detail page, dibawah endpoint structure, pilih dan centang location.
 ![langkah](src/Page_untuk_Department_Business_Object/3.png)
 4. Isi field Button label dengan “Create”. Kemudian klik tombol Finish,
 * Setelah kita tekan tombol finish, akan muncul komponen tombol Create di atas tabel di halaman
awal utama. Klik tab Web Application (side menu sebelah kiri) untuk melihat halaman maincreate-department yang berada dalam satu list main-start.
![langkah](src/Page_untuk_Department_Business_Object/4.png)
 5. . Klik main-create-department dan buka Page Designer. Pada halaman tersebut kita bisa melihat
ada 2 filed sama seperti langkah ke-4. Selain itu terdapat 2 tomol Cancel dan Save.
![langkah](src/Page_untuk_Department_Business_Object/5.png)
 6. Pada halaman Quic Preview klik Live, pada mode ini kita bisa mencoba apakah form yang kita
buat sudah berjalan atau tidak.
![langkah](src/Page_untuk_Department_Business_Object/6.png)
 7.  Pada field Name ise dengan “Administration” dan untuk lokasi pilih Floor 1
 * Kemudian klik Save, maka akan muncul pesan dan Oracle Visual Builder akan mengarahkan kita
ke halaman flow diagrarm dari halaman yang kita buat. 
![langkah](src/Page_untuk_Department_Business_Object/7.png)
 8. Buka, halaman main-start, bisa kita lihat data pada tabel telah ditambahkan.
![langkah](src/Page_untuk_Department_Business_Object/8.png)

# Menambah Halaman Display Employees
1. Pada main klik simbol + pada main node.
2. Pada dialog box Creating Page, masukkan " employees” setelah prefix main-, kemudian klik
create.
![langkah](src/Menambah_Halaman_Display_Employees/1.png)
3. Kemudian tambahkan Heading pada halaman main-employess, dengan cara melakukan drop
komponen heading ke halaman main-employess.
![langkah](src/Menambah_Halaman_Display_Employees/2.png)
4. Ganti filed text pada side menu (sebelah kanan) properties Heading dengan “ Employees”
![langkah](src/Menambah_Halaman_Display_Employees/3.png)
5. Kemudian tambahkan komponen Table pada halaman main-employess.
![langkah](src/Menambah_Halaman_Display_Employees/4.png)
6. Klik Add Data.
![langkah](src/Menambah_Halaman_Display_Employees/5.png)
7. Pada menu pop-up add data, pilih busines object Employee, kemudian pilih next
![langkah](src/Menambah_Halaman_Display_Employees/6.png)
8. Untuk filed data pilih id, name, hireDate, dan Emai
![langkah](src/Menambah_Halaman_Display_Employees/7.png)
9. Expand departmentObject -> item nodes, pilih name, kemudian pilih next.
![langkah](src/Menambah_Halaman_Display_Employees/8.png)
10. .Kita bisa melewat halaman Define Quire, pilih Finish
![langkah](src/Menambah_Halaman_Display_Employees/9.png)
11. .Kembali ke menu properties pilih tab Data, dibawah table column name (paling bawah) klik
pada field columnt header text isi dengan ” Department”.
![langkah](src/Menambah_Halaman_Display_Employees/10.png)
12. Klik untuk kembali ke Data tab.
![langkah](src/Menambah_Halaman_Display_Employees/11.png)

# Halaman Create untuk Employee Busines Object
1. Quick Stari, klik Add Create Page
![langkah](src/Halaman_Create_untuk_Employee_Busines_Object/1.png)
2. . Pilih end point Employee.
![langkah](src/Halaman_Create_untuk_Employee_Busines_Object/2.png)
3. . Untuk filed pilih hireDate, email, dan departement (name otomatis dipilih karena required field).
![langkah](src/Halaman_Create_untuk_Employee_Busines_Object/3.png)
4. Pada field Button Lable isi dengan Create, klik finish
![langkah](src/Halaman_Create_untuk_Employee_Busines_Object/4.png)
5. Klik live, kemudian masukan data name: Lasile Smith, Hire Date: (today), email:
lsmith@example.com Departmet: Administration. Kemudian pilih Save. Setelah itu kita akan
diarah ke halaman Page Flow. Ketika kita kembali ke halaman main-employess akan tampil data
yang telah kita isikan (jika tidak tampil klik tombol reload page ).
![langkah](src/Halaman_Create_untuk_Employee_Busines_Object/5.png)
6. Klik Code untuk melihat kode HTML dari halaman main-employess. 
![langkah](src/Halaman_Create_untuk_Employee_Busines_Object/6.png)
7.  Klik Design untuk kembali ke halaman main-employees, kemudian klik Structure
![langkah](src/Halaman_Create_untuk_Employee_Busines_Object/7.png)
8. Klik Structure lagi untuk menutup structure view.

# Mengganti Nama Halaman main-start

1. Pada Side menu (Web Apps) klik kanan pada main-start, kemudian pilih rename.
![langkah](src/Mengganti_Nama_Halaman_main_start/1.png)
2. Pada pop-up menut, pada filed ide Ganti nama start dengan departments, sehingga akan menjadi
seperti:
![langkah](src/Mengganti_Nama_Halaman_main_start/2.png)
3. Double klik pada main-departments
![langkah](src/Mengganti_Nama_Halaman_main_start/3.png)
4. Klik Source View expand webApps, hrwebapp, flows, dan main nodes. Kemudian klik mainflow.json
![langkah](src/Mengganti_Nama_Halaman_main_start/4.png)

# Action Chain halaman Departments ke halaman Employess

1. . Tambahkan Button pada halaman main-departments, beri nama botton “Dispalay Employee”.
![langkah](src/Action_Chain_halaman_Departments_ke_halaman_Employess/1.png)
2. klik + New Event (side bar properties), pilih Quick Start: ‘ojAction’, setelah di klik sebuh action chain akan dibuat dengan nama ButtonActionChain, berisi Start action.
![langkah](src/Action_Chain_halaman_Departments_ke_halaman_Employess/2.png)

3. Drag Navigate action dari Navigation section yang ada di Action Palatte ke tanda + dibawah
action start.
![langkah](src/Action_Chain_halaman_Departments_ke_halaman_Employess/3.png)
![langkah](src/Action_Chain_halaman_Departments_ke_halaman_Employess/4.png)

4. Pada Navigate Property insptector, Pada filed Target pilih main-employees.
![langkah](src/Action_Chain_halaman_Departments_ke_halaman_Employess/5.png)

5. . Klik Preview . di header untuk menguji halaman dan navigasi. Applikasi akan membuka
browser tab yang lain, click Crate dan tambahkan data departemetn (contoh: IT -> Floor 2).
Kemudian klik Save
![langkah](src/Action_Chain_halaman_Departments_ke_halaman_Employess/6.png)

6. Klik Display Employees Page, kemudian klik Create. Tambahkan data employee sesuatikan
dengan nama departemet yang baru dibuat
![langkah](src/Action_Chain_halaman_Departments_ke_halaman_Employess/7.png)


# Action Chain halaman Employess ke halaman Departments

1. . Untuk proses action chain halaman employees ke halaman departments sama dengan pada langkah
sebelumnya, berinama tombol “Display Departments”. Untuk Navigate Page “Navigate maindepartments
![langkah](src/Action_Chain_halaman_Departments_ke_halaman_Employess/1.png)
2. Klik Preview
![langkah](src/Action_Chain_halaman_Departments_ke_halaman_Employess/2.png)
3. Klik main -> Page Flow, akan muncul diagram kurang lebih seperti berikut:
![langkah](src/Action_Chain_halaman_Departments_ke_halaman_Employess/3.png)
![langkah](src/Action_Chain_halaman_Departments_ke_halaman_Employess/4.png)
![langkah](src/Action_Chain_halaman_Departments_ke_halaman_Employess/5.png)
![langkah](src/Action_Chain_halaman_Departments_ke_halaman_Employess/6.png)
![langkah](src/Action_Chain_halaman_Departments_ke_halaman_Employess/7.png)
![langkah](src/Action_Chain_halaman_Departments_ke_halaman_Employess/8.png)
![langkah](src/Action_Chain_halaman_Departments_ke_halaman_Employess/9.png)
![langkah](src/Action_Chain_halaman_Departments_ke_halaman_Employess/10.png)

# Import Data ke Busines Object

1. . Pada Navigator, Pilih tab Busines Object , kemudian klik Object tab
![langkah](src/Import_Data_ke_Busines_Object/1.png)
2. Klik Departement kemudian klik Data tab, kemudian akan tampil jenis object yang telah kita
buat tadi
![langkah](src/Import_Data_ke_Busines_Object/2.png)
3. Klik Import from File .
![langkah](src/Import_Data_ke_Busines_Object/3.png)
4. Pada dialog-box import data, pilih Replace untuk Row Handling jika belum dipilih. Kemudian
klik upload box, browse, pilih file Departement.csv dan klik Import.
![langkah](src/Import_Data_ke_Busines_Object/4.png)
![langkah](src/Import_Data_ke_Busines_Object/5.png)
5. Ulangi langkah yang sama (langkah 1-4) untuk import data Employee menggunakan file
Employee.csv.

![langkah](src/Import_Data_ke_Busines_Object/6.png)
![langkah](src/Import_Data_ke_Busines_Object/7.png)
![langkah](src/Import_Data_ke_Busines_Object/8.png)
![langkah](src/Import_Data_ke_Busines_Object/9.png)
![langkah](src/Import_Data_ke_Busines_Object/10.png)

# Halaman Edit Department Busines Object (data manipulation
1. Pada aplikasi HR Application, tab Web Application pilih halaman main-departments ->
Page Designer. Klik Reload Page jika diperlukan, untuk menampilkan update halaman
terbaru (setelah import data).
![langkah](src/Halaman_Edit_Department_Busines_Object_(datamanipulation)/1.png)
2. Klik komponen table yang ada di halman main-departments, kemudian pada properties (side
menu sebelah kanan) pilih Quick Start, klik Add Edit Page.
![langkah](src/Halaman_Edit_Department_Busines_Object_(datamanipulation)/2.png)
3. Untuk halaman end point, pilih business object Department, kilik Next.
![langkah](src/Halaman_Edit_Department_Busines_Object_(datamanipulation)/3.png)
4. Untuk update end point, pilih businees object Departmetn, kemudian klik Next
![langkah](src/Halaman_Edit_Department_Busines_Object_(datamanipulation)/4.png)
5. . Pada halaman Page Details, pilih location dibawah struktur Endpoint (name otomatis akan
dipilih), klik Finish. Tombol Edit Department akan tampil pada halaman main-department, tetapi
halaman tersebut masih belum aktif. 
![langkah](src/Halaman_Edit_Department_Busines_Object_(datamanipulation)/5.png)

# Halaman Detail untuk Department Busines Object

1. Pilih Quick Start menu, klik Add Detail Page.
![langkah](src/Halaman_Detail_untuk_Department_Busines_Object/1.png) 
2. Pilih halaman end point business object Department, 
![langkah](src/Halaman_Detail_untuk_Department_Busines_Object/2.png)
3. Pada Page Detail, pilih name dibawah EndPoint Structure, expand locationObject dan items
(item[i]) pilih name, klik Finish. Tombol Department Detail akan ditampilkan pada toolbar
yang ada pada halaman main-department, untuk saat ini tombol tersebut masih belum aktif
![langkah](src/Halaman_Detail_untuk_Department_Busines_Object/3.png)
4. Klik Live, pilih data (terserah), klik tombol Departement Detail untuk membuka halaman maindepartment.
![langkah](src/Halaman_Detail_untuk_Department_Busines_Object/4.png)
5. Klik Design untuk kembali ke mode Desain.
![langkah](src/Halaman_Detail_untuk_Department_Busines_Object/5.png)
6. Klik main-department-detial, pilih Name (paling bawah), ganti label menjadi Location
(Properties -> General -> Label Hit)
![langkah](src/Halaman_Detail_untuk_Department_Busines_Object/6.png)

# Halaman Delete untuk Department Busines Object
1. . Kembali ke halaman main-department, klik Quick Start kemudian klik Add Delete Action.
![langkah](src/Halaman_Delete_untuk_Department_Busines_Object/1.png)
2. Pilih Endpoint busines object Department, 
![langkah](src/Halaman_Delete_untuk_Department_Busines_Object/2.png)
3. Tombol Delete Department akan ditampilkan pada toolbar, kondisi tombol akan berada pada
inactive.

# Test Fungsi Halaman Department Busines Object
1. . Lakukan test pada setiap tombol yang telah Anda buat dengan menggunakan mode review.
2. Cobalah menambahkan Data, Update, dan menghapus data.

* Test Fungsi Create
![langkah](src/Test_Fungsi_Halaman_Department_Busines_Object/create/1.png)
![langkah](src/Test_Fungsi_Halaman_Department_Busines_Object/create/2.png)
* Test Fungsi Read
![langkah](src/Test_Fungsi_Halaman_Department_Busines_Object/read/1.png)
![langkah](src/Test_Fungsi_Halaman_Department_Busines_Object/read/2.png)
* Test Fungsi Update
![langkah](src/Test_Fungsi_Halaman_Department_Busines_Object/update/1.png)
![langkah](src/Test_Fungsi_Halaman_Department_Busines_Object/update/2.png)
* Test Fungsi Delete
![langkah](src/Test_Fungsi_Halaman_Department_Busines_Object/delete/1.png)
![langkah](src/Test_Fungsi_Halaman_Department_Busines_Object/delete/2.png)

# Employee Business Object
1. Tambahkan halaman edit, detail dan delete pada halaman busines object Employee.
![langkah](src/employe_bussines_object/1.png)
2. . Preses pembuat halaman sama dengan langkah sebelumnya, Pilih Quick Start (Add Edit Page dan
Delete Action Page.
![langkah](src/employe_bussines_object/2.png)
3. Untuk page details pada busines object employee pilih name (otomatis dipilih) hireDate, email dan department
![langkah](src/employe_bussines_object/3.png)
4. . Set agar tampilan pada halaman Edit employe menjadi seperti ini (2 row):
* Pilihan halaman main-edit-employee -> klik formlayout yang ada pada halaman -> Properties ->
General -> set Max Columns 2
![langkah](src/employe_bussines_object/4.png)
5. Untuk field detal page pilih name, hireDate, email. Expand departmentObject -> items ->
name. Klik Finish.
![langkah](src/employe_bussines_object/5.png)
6. . Ganti label name (yang ke dua/paling bawah) pada halaman Employee Detail menjadi
Department (Properties-> General -> Label Hint).
![langkah](src/employe_bussines_object/6.png)
7. Tambahkan halaman Delete Employee dengan menggunakan objct busines Employee, sehingga
tampilan akhir dari main-employee menjadi seperti dibawah ini
![langkah](src/employe_bussines_object/7.png)

# Test Fungsi Halaman Employee Busines Object
1. Lakukan test pada setiap tombol yang telah Anda buat dengan menggunakan mode review.
![langkah](src/employe_bussines_object/.png)
2. Cobalah menambahkan Data, Update, dan menghapus data.
![langkah](src/employe_bussines_object/.png)


# Stage and Publish
* stage
1. Kembali ke halaman utama Visual Builder
![langkah](src/Stage_and_Publish_Stage/1.png)
2. Pada aplikasi yang telah dibuat klik Options , kemudian select Stage.
![langkah](src/Stage_and_Publish_Stage/2.png)
3. Pada popup-box pilih Populate Stage with Development data kemudian klik Stage.
![langkah](src/Stage_and_Publish_Stage/3.png)
* Application stage berubah dari development ke stage.
![langkah](src/Stage_and_Publish_Stage/4.png)
4. Klik Stage, pilih hrwebapp (nama apliaksi web yang kita buat). Setelah kita klik akan membuka
tab baru pada web browser yang kita gunakan. Pada halaman yang baru dibukan akan ada data
yang kita tambahkan pada saat development.
![langkah](src/Stage_and_Publish_Stage/5.png)

* Publish
1. Klik ikon menu dan select Publish
![langkah](src/Publish_Application/1.png)
2. Pada pop-up box select Include data from Stage dan klik Publish.
![langkah](src/Publish_Application/2.png)
3. Klik OROCLE Visual Builder untuk kembali Visual Applications page
![langkah](src/Publish_Application/3.png)
![langkah](src/Publish_Application/4.png)
4. Klik Live dan pilih hrwebapp. Aplikasi akan membuka tab browser baru.
![langkah](src/Publish_Application/5.png)
* Data akan secara otomatis terisi dengan data saat kita melakukan stage, tetapi jika ingin memulai aplikasi dengan database yang kosong kita bisa memilih Publish application with a clean
database.
5. Catat link dari aplikasi yang telah kita buat, dari link tersebut kita membagikannya ke Public User

# Import data (Opsional) – Stage

1. Proses ini dilakukan ketika stage bukan saat apliakasi duah live, buka Visual Applications page, klik HR Application, klik Busines Object , klik Menu , dan pilih Data Manager.
![langkah](src/Import_data_(Opsional)/2.png)
2. Dari dropdown list pojok kanan, pilih staging import data ke staging database
![langkah](src/employe_bussines_object/3.png)
3. Klik Import from File, pada dialog box pilih file HR_Application_Stage.zip, klik import, setelah import sukses klik Close.
![langkah](src/employe_bussines_object/4.png)
4. Pada busines object, klik Department, klik Data, pilih Staging pada drop-down list untuk melihat Department baru saja ditambahkanl.
![langkah](src/employe_bussines_object/5.png)
5. Klik Employee -> tab Data ->kemudian pilih Staging untuk melihat employee baru yang barun
ditambahkan
![langkah](src/employe_bussines_object/6.png)






