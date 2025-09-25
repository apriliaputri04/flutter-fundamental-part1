**JOBSHEET 4 APLIKASI PERTAMA DAN WIDGET DASAR FLUTTER**

## 👩‍🎓 Identitas
- Nama: Aprilia Putri Anggraeni  
- NIM: 2341760043  
- Kelas: 3F – SIB/05  

--------------------------------------------------------------------------------------------------------------------------------------------------
**Praktikum 1: Membuat Project Flutter Baru**
<br>Langkah 1:
<br>Buka VS Code, lalu tekan tombol Ctrl + Shift + P maka akan tampil Command Palette, lalu ketik Flutter. Pilih New Application Project.

![Screenshot hello_world](images/Pratikum1/01.png)

<br>Langkah 2:
<br>Kemudian buat folder sesuai style laporan praktikum yang Anda pilih. Disarankan pada folder dokumen atau desktop atau alamat folder lain yang <br>tidak terlalu dalam atau panjang. Lalu pilih Select a folder to create the project in.

![Screenshot hello_world](images/Pratikum1/02.png)

<br>Langkah 3:
<br>Buat nama project flutter hello_world seperti berikut, lalu tekan Enter. Tunggu hingga proses pembuatan project baru selesai.

![Screenshot hello_world](images/Pratikum1/03.png)

<br>Langkah 4:
<br>Jika sudah selesai proses pembuatan project baru, pastikan tampilan seperti berikut. Pesan akan tampil berupa "Your Flutter Project is ready!" <br>artinya Anda telah berhasil membuat project Flutter baru.

![Screenshot hello_world](images/Pratikum1/04.png)

![Screenshot hello_world](images/Pratikum1/05.png)

--------------------------------------------------------------------------------------------------------------------------------------------------
**Praktikum 2: Menghubungkan Perangkat Android atau Emulator**
<br>Melanjutkan dari praktikum 1, Anda diminta untuk menjalankan aplikasi ke perangkat fisik (device Android atau iOS). Silakan ikuti langkah-langkah pada codelab tautan berikut ini.
<br>https://developer.android.com/codelabs/basic-android-kotlin-compose-connect-device?hl=id#0
---------------------------------------------------------------------------------------------------------------------------------------------------
**Praktikum 3: Membuat Repository GitHub dan Laporan Praktikum**
<br>Langkah 1:
<br>Login ke akun GitHub Anda, lalu buat repository baru dengan nama "flutter-fundamental-part1"

![Screenshot hello_world](images/pratikum3/01.png)

<br>Langkah 2:
<br>Lalu klik tombol "Create repository" lalu akan tampil seperti gambar berikut

![Screenshot hello_world](images/Pratikum3/02.png)

<br>Langkah 3:
<br>Kembali ke VS code, project flutter hello_world, buka terminal pada menu Terminal > New Terminal. Lalu ketik perintah berikut untuk inisialisasi git pada project Anda.

![Screenshot hello_world](images/Pratikum3/03.png)

<br>Langkah 4:
<br>Pilih menu Source Control di bagian kiri, lalu lakukan stages (+) pada file .gitignore untuk mengunggah file pertama ke repository GitHub.

![Screenshot hello_world](images/Pratikum3/04.png)

<br>Langkah 5:
<br>Beri pesan commit "tambah gitignore" lalu klik Commit (✔)

![Screenshot hello_world](images/Pratikum3/05.png)

<br>Langkah 6:
<br>Lakukan push dengan klik bagian menu titik tiga > Push

![Screenshot hello_world](images/Pratikum3/06.png)

<br>Langkah 7:
<br>Di pojok kanan bawah akan tampil seperti gambar berikut. Klik "Add Remote"

![Screenshot hello_world](images/Pratikum3/07.png)

<br>Langkah 8:
<br>Salin tautan repository Anda dari browser ke bagian ini, lalu klik Add remote

![Screenshot hello_world](images/Pratikum3/08a.png)

Setelah berhasil, tulis remote name dengan "origin"

![Screenshot hello_world](images/Pratikum3/08b.png)


<br>Langkah 9:
<br>Lakukan hal yang sama pada file README.md mulai dari Langkah 4. Setelah berhasil melakukan push, masukkan username GitHub Anda dan password berupa token yang telah dibuat (pengganti password konvensional ketika Anda login di browser GitHub). Reload halaman repository GitHub Anda, maka akan tampil hasil push kedua file tersebut seperti gambar berikut.

![Screenshot hello_world](images/Pratikum3/09.png)

<br>Langkah 10:
<br>Lakukan push juga untuk semua file lainnya dengan pilih Stage All Changes. Beri pesan commit "project hello_world". Maka akan tampil di repository GitHub Anda seperti berikut.

![Screenshot hello_world](images/Pratikum3/10.png)

<br>Langkah 11:
<br>Kembali ke VS Code, ubah platform di pojok kanan bawah ke emulator atau device atau bisa juga menggunakan browser Chrome. Lalu coba running project hello_world dengan tekan F5 atau Run > Start Debugging. Tunggu proses kompilasi hingga selesai, maka aplikasi flutter pertama Anda akan tampil seperti berikut.

![Screenshot hello_world](images/Pratikum3/11.png)

<br>Langkah 12:
<br>Silakan screenshot seperti pada Langkah 11, namun teks yang ditampilkan dalam aplikasi berupa nama lengkap Anda. Simpan file screenshot dengan nama 01.png pada folder images (buat folder baru jika belum ada) di project hello_world Anda. Lalu ubah isi README.md seperti berikut, sehingga tampil hasil screenshot pada file README.md. Kemudian push ke repository Anda.

![Screenshot hello_world](images/Pratikum3/12.png)

---------------------------------------------------------------------------------------------------------------------------------------------------
**Praktikum 4: Menerapkan Widget Dasar**
<br>Langkah 1: Text Widget
<br>Buat folder baru basic_widgets di dalam folder lib. Kemudian buat file baru di dalam basic_widgets dengan nama text_widget.dart. Ketik atau salin kode program berikut ke project hello_world Anda pada file text_widget.dart.

![Screenshot hello_world](images/Pratikum4/01a.png)

Lakukan import file text_widget.dart ke main.dart, lalu ganti bagian text widget dengan kode di atas. Maka hasilnya seperti gambar berikut. Screenshot hasil milik Anda, lalu dibuat laporan pada file README.md.

![Screenshot hello_world](images/Pratikum4/01b.png)

Langkah 2: Image Widget
<br>Buat sebuah file image_widget.dart di dalam folder basic_widgets dengan isi kode berikut.

![Screenshot hello_world](images/Pratikum4/02a.png)

Lakukan penyesuaian asset pada file pubspec.yaml dan tambahkan file logo Anda di folder assets project hello_world.

![Screenshot hello_world](images/Pratikum4/02b.png)

Jangan lupa sesuaikan kode dan import di file main.dart kemudian akan tampil gambar seperti berikut.

![Screenshot hello_world](images/Pratikum4/02c.png)

---------------------------------------------------------------------------------------------------------------------------------------------------
**Praktikum 5: Menerapkan Widget Material Design dan iOS Cupertino**
<br>Langkah 1: Cupertino Button dan Loading Bar
<br>Buat file di basic_widgets > loading_cupertino.dart. Import stateless widget dari material dan cupertino. Lalu isi kode di dalam method Widget build adalah sebagai berikut.

![Screenshot hello_world](images/Pratikum5/01a.png)

![Screenshot hello_world](images/Pratikum5/01b.jpg)

Langkah 2: Floating Action Button (FAB)
Button widget terdapat beberapa macam pada flutter yaitu ButtonBar, DropdownButton, TextButton, FloatingActionButton, IconButton, OutlineButton, PopupMenuButton, dan ElevatedButton.
<br>Buat file di basic_widgets > fab_widget.dart. Import stateless widget dari material. Lalu isi kode di dalam method Widget build adalah sebagai berikut.

![Screenshot hello_world](images/Pratikum5/02a.png)

![Screenshot hello_world](images/Pratikum5/02b.jpg)

Langkah 3: Scaffold Widget
<br>Scaffold widget digunakan untuk mengatur tata letak sesuai dengan material design.
Ubah isi kode main.dart seperti berikut.

![Screenshot hello_world](images/Pratikum5/03a.png)

![Screenshot hello_world](images/Pratikum5/03b.png)

Langkah 4: Dialog Widget
<br>Dialog widget pada flutter memiliki dua jenis dialog yaitu AlertDialog dan SimpleDialog.
Ubah isi kode main.dart seperti berikut.

![Screenshot hello_world](images/Pratikum5/04a.png)

![Screenshot hello_world](images/Pratikum5/04b.png)

Langkah 5: Input dan Selection Widget
<br>Flutter menyediakan widget yang dapat menerima input dari pengguna aplikasi yaitu antara lain Checkbox, Date and Time Pickers, Radio Button, Slider, Switch, TextField.

![Screenshot hello_world](images/Pratikum5/05.png)

Langkah 6: Date and Time Pickers
<br>Date and Time Pickers termasuk pada kategori input dan selection widget, berikut adalah contoh penggunaan Date and Time Pickers.

![Screenshot hello_world](images/Pratikum5/06a.png)

![Screenshot hello_world](images/Pratikum5/06b.png)















