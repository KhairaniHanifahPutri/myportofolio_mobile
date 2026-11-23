# myportofolio_mobile

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Learn Flutter](https://docs.flutter.dev/get-started/learn-flutter)
- [Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Flutter learning resources](https://docs.flutter.dev/reference/learning-resources)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.


### Tugas 7
1. Sepemahaman saya, widget tree adalah struktur elemen atau komponen yang saling berhubungan di flutter berbentuk hirarki tree. Hubungan antara induk dan anak yaitu induk atau parent menentukan tugas child (misal: menampilkan kolom) lalu anak (child) menampilkan design atau isi sesuai yang sudah ditugaskan parent. 
2. Beberapa widget yang saya gunakan yaitu, text, icon, container, padding, center. Text berfungsi menampilkan tulisan, icon menampilkan ikon, container untuk group widget lain, padding untuk membuat ruang kosong, dan center bertugas untuk mengatur anak agar berada di tengah.
3. Material App adalah widget untuk mengatur tema atau desain aplikasi. Biasanya digunakan sebagai root widget karena bisa menentukan halaman awal, mengatur navigasi, juga menyediakan material untuk desain.
4. Stateless bersifat immutable, sedangkan stateful bersifat mutable. Jika ingin menampilkan informasi yang dinamis atau berubah-ubah, sebaiknya pakai stateful widget. Jika ingin mengganti sesuatu secara keseluruhan, bisa menggunakan stateless widget.
5. BuildContext adalah objek yang merepresentasikan lokasi widget di widget tree. Ini penting agar widget dapat dilihat dan diketahui di struktur widget tree. Digunakan sebagai refer di metode build agar metode build dapat mengambil dari struktur widget tree.
6. Hot reload yaitu melihat hasil perubahan kode tanpa kehilangan state aplikasi yang sedang berjalan. Hot restart mirip dengan hot reload, bedanya hot restart menjalankan ulang aplikasinya, sedangkan hot reload hanya memperbarui aplikasi. Jika perlu menjalankan ulang aplikasi maka hot restart pilihannya. Berlaku juga jika kita mengubah nilai state. 


### Tugas 8
1. Navigator.push() bertugas untuk menambahkan suatu route ke dalam stack route. Letaknya berada di paling atas stack. Navigator.pop() bertugas untuk menghapus suatu route yang berada di paling atas stack. Navigator.pushReplacement() berfungsi seperti gabungan antara push() dan pop(), yaitu menghapus suatu route dan menggantinya dengan suatu route baru. Metode yang digunakan untuk membuka formulir adalah push() karena kartu aksi mengarahkan ke form tersebut. Opsi Home di drawer bekerja dengan menghapus route yang sedang dibuka saat ini (apapun itu) lalu menggantinya dengan route yang mengarahkan ke home.  
2. Scaffold sebagai kerangka, AppBar sebagai header, dan Drawer sebagai navigator. Contoh penggunaan warna tema yaitu pertama mengatur warna nya terlebih dahulu di main.dart dengan colorScheme. Saat warna tersebut ingin digunakan, pada file tersebut, misal menu.dart, bisa ditambahkan variabel color dengan Theme.of(context).colorScheme.
3. Menurut saya, karena saat membuat formulir kita perlu menyediakan navigasi juga. Widget pengatur jarak untuk mengatur jarak antara icon, dan widget penggulir untuk memberikan peringatan ketika melebihi ruang layar yang ditentukan.
4. GlobalKey menyimpan id unik dari formulir yang sudah dibuat. Validator dan validate() digunakan untuk memvalidasi apakah formulir dikirim sesuai dengan apa yang kita harapkan. Misalnya dalam experience_form saya, saya mewajibkan untuk menulis nama pengalaman. Ketika user tidak menuliskan nama, formulir tidak akan disimpan karena saya mengharuskan user menulis nama.

Saya menggunakan generative AI dalam pengerjaan Tugas 8 untuk membantu saya dalam memahami kode yang saya ketik. Berikut merupakan prompt saya:
https://chatgpt.com/share/6b04089a-0fec-83ec-a3c4-5cc1068d678e