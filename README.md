# Tugas-Akhir-PBO
Kode di atas adalah implementasi permainan Hangman (tebak kata) dalam bahasa Python. Berikut adalah penjelasan singkat dari setiap bagian kode:

Impor Modul: Kode dimulai dengan impor modul random, yang digunakan untuk memilih kata kunci secara acak dari daftar kata-kata yang tersedia.

Daftar Kata Kunci: Variabel kata_kunci adalah daftar kata-kata yang dapat dipilih untuk permainan Hangman.

Fungsi ambil_kata_kunci(): Fungsi ini digunakan untuk memilih kata kunci secara acak dari daftar kata_kunci. Ia mengembalikan kata kunci yang dipilih.

Fungsi tampilkan_gantungan_hangman(kesalahan): Fungsi ini menerima argumen kesalahan yang menunjukkan jumlah kesalahan yang telah dilakukan oleh pemain. Fungsi ini mengembalikan representasi visual gantungan Hangman sesuai dengan jumlah kesalahan yang diberikan.

Fungsi tampilkan_kata_tersembunyi(kata, tebakan): Fungsi ini menerima kata kunci dan daftar huruf yang telah ditebak. Fungsi ini mengembalikan string yang menampilkan kata kunci dengan huruf-huruf yang belum ditebak digantikan dengan garis bawah.

Fungsi tampilkan_status(tebakan, kesalahan): Fungsi ini mencetak status permainan saat ini, termasuk huruf-huruf yang telah ditebak, jumlah kesalahan, dan kata tersembunyi.

Fungsi main(): Fungsi utama yang mengatur alur permainan. Ia memilih kata kunci, menginisialisasi variabel untuk kesalahan dan tebakan, dan memulai loop permainan. Di dalam loop, ia menampilkan gantungan Hangman, kata tersembunyi, dan status permainan. Ia juga memeriksa apakah pemain menang atau kalah, dan mengizinkan pemain untuk menebak huruf. Loop permainan berlanjut sampai pemain menang atau mencapai batas kesalahan. Setelah loop berakhir, pesan akhir dicetak.

if __name__ == '__main__':: Ini adalah blok yang mengeksekusi fungsi main() hanya jika file ini dijalankan secara langsung sebagai skrip, bukan diimpor sebagai modul.

Kode ini dapat digunakan untuk membuat permainan Hangman sederhana di lingkungan Python. Pemain akan diminta untuk menebak huruf-huruf dalam kata kunci yang tersembunyi dan akan melihat representasi visual dari gantungan Hangman saat mereka membuat kesalahan.
