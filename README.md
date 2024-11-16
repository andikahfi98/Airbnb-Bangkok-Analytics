# Festival songkran
<div style="text-align: center;">
  <img src="https://github.com/user-attachments/assets/03ff792e-8350-4da4-b479-d524e28f0969" alt="Songkran">
</div>



# Background
Festival Songkran, yang dikenal sebagai Tahun Baru Thailand, adalah perayaan yang berlangsung selama tiga hari atau lebih dan menjadi salah satu tradisi paling penting di negara ini. Festival ini  jatuh pada tanggal 13 hingga 15 April 2023, bahkan ada yang merayakan sampai seminggu. Festival ini terkenal dengan kegiatan menyiram air sebagai simbol penyucian diri, membasuh nasib buruk, dan menyambut tahun baru dengan penuh sukacita. Songkran juga melibatkan ritual keagamaan, seperti memberi penghormatan kepada para leluhur dan pergi ke kuil untuk berdoa.

Selama perayaan, Bangkok menjadi pusat utama aktivitas, dengan beberapa distrik yang menjadi pusat festival antara lain Bang Rak, Parthum Wan dan Phra Nakhon. Di lokasi-lokasi ini, ribuan orang berkumpul untuk mengikuti pesta air, parade budaya, pertunjukan seni, dan acara hiburan lainnya yang berlangsung di jalan-jalan kota.

Airbnb berkomitmen untuk mendukung para wisatawan yang ingin merasakan keunikan Songkran dengan menyediakan akomodasi yang berkualitas dan nyaman. Untuk menarik lebih banyak pengunjung dan memastikan mereka mendapatkan pengalaman menginap terbaik, Airbnb akan memberikan rekomendasi listing selama festival berlangsung terutama pada wilayah pusat perayaan.

# Tujuan
1.  Melakukan segmentasi berdasarkan grade untuk listing pada Airbnb
1.  Menemukan strategi pemasaran yang tepat untuk mendapatkan profit pada Airbnb setelah segmentasi
1.  Menemukan strategi untuk menaikkan kualitas listing pada listing dengan grade rendah

# Kesimpulan

1. **Preferensi Akomodasi**: 
   - Mayoritas turis internasional, diperkirakan sekitar 300.000 orang, Asumsi turis lebih banyak memilih **Private Room** dan **Hotel Room**. Ini dikarenakan profil turis yang mengikuti festival biasanya terdiri dari pengunjung solo, berpasangan, atau kelompok kecil kurang dari lima orang. Oleh karena itu, akomodasi yang lebih besar seperti **Entire Home/Apt** kurang diminati.

2. **Segmentasi**: 
   -  Properti di kisaran harga atas berpotensi mendapatkan grade yang lebih tinggi (A atau B), sementara listing dengan harga terjangkau lebih banyak pada grade yang lebih rendah, keyword dalam segmentasi menjadi pembeda kualitas tiap listing.


4. **Kualitas Listing**: 
   - Banyak listing di distrik pusat perayaan festival memiliki grade rendah, menandakan bahwa lebih banyak akomodasi yang belum memadai untuk turis. Preferensi untuk akomodasi grade A sangat sedikit, menunjukkan bahwa pasar untuk akomodasi berkualitas tinggi di ketiga distrik ini masih terbatas.

Dengan demikian, pengelolaan akomodasi selama festival Songkran perlu mempertimbangkan preferensi turis serta kualitas akomodasi yang ditawarkan, untuk meningkatkan pengalaman wisatawan dan mendukung industri pariwisata di Bangkok.



# Rekomendasi untuk Meningkatkan Profit Perusahaan

### Tim Bisnis

1. **Pengembangan Program Peningkatan Kualitas:**
   - Kembangkan program pelatihan dan dukungan untuk host dalam meningkatkan kualitas properti mereka, baik dari segi fasilitas, estetika, maupun layanan pelanggan.

2. **Kampanye Pemasaran Terarah:**
   - Buat kampanye pemasaran yang tersegmentasi berdasarkan grade listing. Sesuaikan pesan dan saluran pemasaran untuk menargetkan pelanggan sesuai preferensi mereka, misalnya melalui media sosial, email marketing, atau iklan online.

3. **Penawaran Bundling:** 
   - Buat paket penawaran yang menggabungkan akomodasi dengan layanan tambahan seperti tur lokal, penjemputan di bandara, atau sewa kendaraan untuk meningkatkan pendapatan tambahan.

4. **Program untuk Host dengan Grade Rendah:** 
   - Tawarkan program berlangganan berbayar kepada host yang berhasil meningkatkan kualitas listing mereka dan mendapatkan grade yang lebih tinggi, misalnya dalam bentuk peringkat pencarian yang lebih tinggi, atau penempatan di posisi yang lebih terlihat di platform.

**Dataset**:

1. `id` : Identitas unik Airbnb untuk tempat tersebut.
2. `name` : Nama yang dari properti
3. `host_id` : Pengidentifikasi unik Airbnb untuk tuan rumah/pengguna.
4. `host_name` : Nama tuan rumah
5. `neighbourhood` : mengenai lingkungan (neighborhood) di mana properti tersebut terletak.
6. `latitude` : Menggunakan proyeksi Sistem Geodesi Dunia (WGS84) untuk lintang dan bujur.
7. `longitude` : Menggunakan proyeksi Sistem Geodesi Dunia (WGS84) untuk lintang dan bujur.
8. `room_type` : tipe kamar yang disediakan
9. `price` : Harga harian untuk menyewa properti, dinyatakan dalam mata uang lokal (bath).
10. `minimum_nights` :  Jumlah minimum malam yang harus diinap oleh penyewa untuk properti tersebut.
11. `number_of_reviews` : Jumlah ulasan yang diterima oleh properti tersebut
12. `last_review`	: tanggal terakhir review
13. `calculated_host_listings_count` : jumlah properti yang dimiliki oleh tuan rumah pada saat pengambilan data terbaru di suatu kota atau wilayah geografis.
14. `availability_365` : Ketersediaan properti selama 365 hari. Ini menunjukkan berapa banyak hari properti tersebut tersedia untuk disewa dalam satu tahun. 
15. `number_of_reviews_ltm` : Jumlah ulasan yang diterima oleh properti dalam 12 bulan terakhir (dalam 12 bulan terakhir).

