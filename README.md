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
