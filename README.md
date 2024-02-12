# Tugas-Besar-Struktur-Data
Struktur Data Sistem Bioskop

# Final Proyek Struktur Data
<ul>
  <li>Mata Kuliah: Struktur Data</li>
  <li>Dosen Pengampu: <a href="https://github.com/Muhammad-Ikhwan-Fathulloh">Muhammad Ikhwan Fathulloh</a></li>
</ul>

## Kelompok
<ul>
  <li>Kelompok:  kelompok 11 </li>
  <li>Proyek:  Sistem Bioskop </li>
  <li>Anggota: </li>
  <ul>
    <li>Ketua: <a href="">RIFKI FEBRIAN</a></li>
    <li>Anggota 1: <a href="">MUHAMAD AL GHOZALI</a></li>
    <li>Anggota 2: <a href="">TUBAGUS BUDI SAMPURNO</a></li>
  </ul>
</ul>

## Judul Proyek
<p>SISTEM BIOSKOP</p>

## Penjelasan Proyek
<P>project yang kami buat adalah Sistem Bioskop dengan spesifikasi nya yaitu : peserta, film, kursi dengan pemilihannya, transaksi dan riwayat transaksi.
Masuk ke penjelasan kode, yang pertama kita membuat project pakage sistem bioskop lalu membuat import java util scaner, array, queue, linkedlist, comperator & iterator (opsional), dibawah class kita membuat public static untuk linear search untuk searching, lalu kita membuat scenner untuk membuat inputan dengan variabel input, selanjutnya membuat integer buat harga tiket film dengan variabel tiket film1: harganya 30000, tiket film 2: 35000, tiket film 3: 40000.
Lanjut membuat record dengan didalamnya untuk merecord data, kita membuat ada 5 record yaitu yang pertama record film yang di dalamnya String film, judul film, gendre film, jam tayang, studio film, harga tiket dang no kursi.
Record yang kedua yaitu kursi bioskop dengan data String kursi dan nomor kursi.
Record yang ketiga yaitu peserta dengan data String nama peserta dan integer id card.
Record yang keempat yaitu pemilihan film dengan data String nama pesserta, integer idcard, String pilih film, judul film, gendre film, jam tayang, studio film, harga tiket, no kursi, integer bayar, total harga dan kembalian.
Record yang kelima yaitu transaksi dengan data integer bayar dan total harga.

Sesudah membuat record kita melanjutkan membuat array untuk untuk mengumpulkan dan menyimpan datanya pada array, Array yang pertama untuk film dengan variabel list film array film index 0 film "1", judul film "HINDIANA JONES", gendre film "ADVENTURE", jam tayang "13.00 WIB", studio film "1", harga tiket "Rp.30000",no kursi "A1 - A5".
Array film index 1 film "2", judul film "FAST & FORIOUS", gendre film "ACTION", jam tayang "15.00 WIB", studuo film "2", harga tiket "Rp.35000", no kursi "B1 - B5".
Aray film index 2 film "3", judul film "THE NUN", gendre film "HOROR", jam tayang "17.00 WIB", studio film "3", harga tiket "Rp.40000", no kursi "C1 - C5".

Lanjut membuat array 2d untuk kursi dengan variabel kursi bioskop didalamnya ada string A1 – A5, B1 – B2 dan C1 – C5.
Membuat array untuk peserta dengan variabel pesertanya untuk data index 0 nama peserta "Lina" dan integer id card 123.
Array peserta index 1 nama peserta "Lolita" dan integer id card 234.
Array peserta index 2 nama peserta "Juki" dan integer id card 345.
Membuat array untuk searching dengan variabel film1 yang di dalamnya ada string "HINDIANA JONES", "FAST FORIOUS", "THE NUN".

Lanjut membuat tampilan utama Selamat Datang Di Bioskop TBXXI, Daftar Film Yang Tersedia & Sudah Rilis. Lalu bembuat for dengan variabel jadwal untuk membuat loop dan menggambil data dari array film index 0 sampai 2 dan menampilkan " Pilihan: film  " Judul Film: ", "  Gendre Film: ", " Jam Tayang: ", "  Studio Film: ", " Harga Tiket: ".

Lalu membuat pencarian film dengan menggunakan struktur data searching untuk menginputkan film apa yang ingin di cari jika ada akan mengarahkan pada pilihan 1, 2, dan 3 jika menginputkan film yang tidak ada akan menampilkan film ynag tidak ada / belum rilis.

Lanjut membuat antrian pesertanya menggunakan struktur data Queue, peserta yang antri adalah Lina, Lolita dan juki.
Membuat variabel list pemilihan film untuk riwayat transaksi menggunakan struktur data linked list, yaitu list Lina, Lolita dan Juki.
Lalu membuat looping dengan loop while untuk melooping antrian Lina, Lolita & Juki.
Membuat inputan untuk memesan tiket Y / T, if equals perbandingan (jika) Y antrian pertama memesan tiket.
Membuat inputan untuk pemilihan film ada 3 pilihan film yang akan dipilih, jika sudah memilih akan menampilkan judul film, gendre, jam tayang, studio film, harga film dan no kursi.
 Lalu membuat inputan lagi untuk transaksi nya, masukan jumlah uang yang akan dibayar – total harga nantinya akan menampilkan kembalian.
If jika uang bayar kurang dari total harga akan menampilkan maaf uang nya kurang, untuk no kursi sudah ditentukan sendiri.

Yang terakhir kita membuat riwayat transaksinya, mengambil list keseluruhan mulai dari peserta, idcard pilihan film yang di pilih dan transaksinya dari likedlist untuk dijadikan riwayat transaksinya
Program selesai dan menampilkan terima kasih.
</P>
## Komponen Proyek
<ul>
<li>	Record, Program mendefinisikan beberapa jenis record (film, kursibioskop, peserta, Pemilihanfilm, transaksi) untuk memodelkan berbagai aspek dari proses pemesanan bioskop. Record-record ini menggabungkan berbagai informasi seperti detail film, informasi kursi, detail peserta, dan riwayat transaksi.</li>
<li>	Metode Utama, Dalam metode utama, program dimulai dengan menginisialisasi harga tiket untuk tiga film. Kemudian, program membuat array untuk menyimpan daftar film yang tersedia, susunan kursi, dan detail peserta.</li>
<li>	Tampilan Film, Program menampilkan daftar film yang tersedia beserta detail seperti genre, waktu tayang, studio, dan harga tiket.</li>
<li>	Fungsi Pencarian, Ada fungsionalitas pencarian sederhana di mana pengguna dapat memasukkan nama film, dan program memeriksa apakah film tersebut ada dalam daftar. Jika ditemukan, pengguna diberi tahu nomor pilihan film.</li>
<li>	Antrian dan LinkedList, Program menggunakan Antrian (khususnya LinkedList) untuk mengelola peserta yang ingin memesan tiket. Setiap peserta diproses satu per satu sampai antrian kosong. Untuk setiap peserta, mereka dapat memilih apakah akan memesan tiket atau melewatkannya.</li>
<li>	Proses Pemesanan, Jika seorang peserta memilih untuk memesan tiket, mereka diminta untuk memilih film. Program mencari film yang sesuai dalam daftar film. Setelah film terpilih, peserta ditampilkan detail film, termasuk rentang kursi. Mereka kemudian diminta untuk membayar tiket, dan program menghitung kembalian yang diberikan kepada mereka.</li>
<li>	Riwayat Transaksi, Setelah pembayaran berhasil, program menyimpan detail transaksi dalam LinkedList yang spesifik untuk setiap peserta. Ini mencakup nama peserta, kartu identitas, detail film, harga tiket, total yang dibayarkan, dan kembalian yang diberikan.</li>
<li>	Opsi Lanjutan, Setelah memproses pemesanan peserta, mereka diberi opsi untuk melanjutkan dengan pemesanan lain atau keluar dari sistem.</li>
<li>	Pencarian Linear, Meskipun tidak digunakan dalam bagian utama program, ada metode linearSearch yang didefinisikan di bagian atas kelas. Metode ini melakukan pencarian linear pada array integer untuk elemen tertentu dan mengembalikan indeksnya jika ditemukan, atau -1 jika tidak ditemukan.</li>
</ul>

## Pembagian Tim
<p>Membuat Kode/Koding : Tubagus Budi Sampurno, Rifki Febrian<br>
Penjelasan Koding : Muhamad Al Ghozali</p>

## Demo Proyek
<ul>
  <li>Github: <a href="">https://github.com/tubagusbudis/Tugas-Besar-Struktur-Data</a></li>
  <li>Youtube: <a href="">https://youtu.be/R4l-TB8l8MI</a></li>
</ul>
