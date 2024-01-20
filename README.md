# Jobsheet-2-Buku-Catatan-Riva-Febtriani-21343070

Pengenalan Modul Node.js
Node.js menggunakan sistem modul untuk mengorganisir kode ke dalam unit-unit yang dapat digunakan kembali. Paradigma sistem modul ini membantu dalam memecah aplikasi menjadi bagian-bagian kecil yang mudah dikelola dan dipahami.
•	CommonJS: Node.js mengadopsi paradigma CommonJS untuk sistem modulnya. Ini memungkinkan definisi dan penggunaan modul dengan menggunakan fungsi require() dan module.exports.

Pemanfaatan Modul
•	require(): Digunakan untuk mengimpor modul di dalam file JavaScript Anda.
const myModule = require('./myModule');

•	module.exports: Digunakan untuk mengekspor fungsionalitas dari modul agar dapat digunakan di modul lain.
// myModule.js
module.exports = {
    myFunction: function() {
        // implementasi
    }
};

Manajemen Paket dengan NPM
•	Node Package Manager (NPM): NPM adalah manajer paket untuk Node.js. Ini memungkinkan Anda mengelola dependensi proyek dan menginstal paket dari repositori NPM.
•	package.json: File konfigurasi proyek yang mendefinisikan metadata proyek dan dependensi.
•	npm install: Perintah untuk menginstal semua dependensi yang terdaftar dalam file package.json
•	npm publish: Proses untuk mempublikasikan paket Anda ke repositori NPM agar dapat diakses oleh orang lain.

Argument Command Line pada Node.js
•	process.argv: Digunakan untuk menangkap argumen baris perintah yang diberikan saat menjalankan program Node.js.
•	Parsing Argument: Keterampilan untuk menguraikan dan mengelola argumen baris perintah dengan cermat.

Penerapan Modul dan NPM pada Proyek
•	Aplikasi Modul: Membuat modul kustom yang sesuai dengan kebutuhan proyek dan mengintegrasikannya ke dalam aplikasi Node.js.
•	Pengelolaan Paket dengan Mahir: Keterampilan mengintegrasikan paket eksternal dengan lancar ke dalam proyek Anda.

Memanfaatkan Alat Eksternal: Nodemon dan Yargs
•	Nodemon: Alat pengawas perubahan kode yang memungkinkan pengembangan dengan memantau dan menghidupkan kembali server secara otomatis setiap kali ada perubahan.
•	Yargs: Library untuk parsing argumen baris perintah dengan lebih terstruktur dan terorganisir.

Manajemen Data dengan JSON
•	Penyimpanan dan Manipulasi Data: Mengelola dan memanipulasi data secara efisien menggunakan format JSON.

Implementasi Fungsionalitas dalam Proyek
•	Implementasi Fitur: Menerjemahkan konsep ke dalam fitur fungsional dalam aplikasi, seperti penambahan, penghapusan, tampilan list, dan membaca catatan.
•	Pengujian Fungsionalitas: Melakukan pengujian komprehensif untuk memastikan kehandalan dan efektivitas fitur yang diimplementasikan.

