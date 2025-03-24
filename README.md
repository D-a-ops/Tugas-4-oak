# Tugas-4-oak
1. Jelaskan Struktur Antar Hubungan dan Beri Contohnya?

         Struktur Antar Hubungan
      Struktur antar hubungan adalah suatu pola atau sistem yang menggambarkan bagaimana elemen-elemen dalam suatu sistem saling berinteraksi dan berhubungan satu sama lain.       Dalam berbagai aspek kehidupan, baik dalam organisasi, lingkungan, sosial, maupun teknologi, hubungan antar elemen ini sangat penting untuk memastikan bahwa sistem           tersebut berjalan dengan baik dan mencapai tujuannya.

      Struktur ini menunjukkan bahwa tidak ada elemen yang berdiri sendiri tanpa keterkaitan dengan elemen lain. Setiap bagian memiliki peran dan fungsi yang saling                mendukung, membentuk sebuah jaringan kerja sama yang harmonis. Jika salah satu elemen terganggu, maka dapat berdampak pada elemen lainnya, sehingga pemahaman tentang          struktur antar hubungan sangat penting untuk menjaga keseimbangan dan efektivitas suatu sistem.

      Contoh Struktur Antar Hubungan dalam Berbagai Aspek
      1. Struktur Antar Hubungan dalam Organisasi Perusahaan
      Dalam sebuah perusahaan, terdapat berbagai posisi yang memiliki tugas dan tanggung jawab masing-masing. Namun, mereka tidak bekerja sendiri, melainkan saling terhubung       untuk mencapai tujuan bersama.

      Misalnya, dalam struktur organisasi perusahaan:

      CEO (Chief Executive Officer) bertanggung jawab atas arah dan strategi perusahaan secara keseluruhan. CEO memberikan arahan kepada manajer untuk memastikan perusahaan          berjalan sesuai visi dan misi.

      Manajer bertugas mengelola berbagai divisi dan memastikan pekerjaan yang ada dalam tim berjalan dengan baik. Manajer mengomunikasikan kebijakan dan strategi dari CEO          kepada timnya.

      Supervisor adalah penghubung antara manajer dan karyawan. Mereka bertanggung jawab dalam mengawasi pekerjaan sehari-hari, memastikan tugas diselesaikan dengan baik,          serta memberikan arahan teknis kepada karyawan.

      Karyawan menjalankan tugas operasional sesuai dengan instruksi dari supervisor dan manajer.
   
      Jika salah satu elemen ini tidak menjalankan tugasnya dengan baik, maka sistem dalam perusahaan bisa terganggu. Misalnya, jika manajer tidak dapat mengomunikasikan           strategi dengan baik kepada supervisor, maka karyawan mungkin akan mengalami kebingungan dalam menjalankan tugasnya.

2. Bila terlalu banyak modul atau perangkat dihubungkan pada bus maka akan terjadi penurunan kinerja, sebutkan penyebabnya?:

           Kalau terlalu banyak perangkat atau modul dihubungkan ke satu jalur bus, kinerjanya bisa menurun. Ini karena beberapa alasan utama:

            Banyak yang Berebut Jalur

            Bayangkan bus ini seperti jalan raya. Kalau terlalu banyak kendaraan (perangkat) yang ingin lewat dalam waktu bersamaan, pasti bakal macet. Perangkat harus                   bergantian mengirim data, jadi semuanya jadi lebih lambat.

            Waktu Tunggu Makin Lama

            Karena semua perangkat harus menunggu giliran untuk menggunakan bus, semakin banyak yang terhubung, semakin lama waktu tunggunya. Seperti antrean di kasir yang                makin panjang, makin lama juga sampai giliran kita.

            Sinyal Jadi Lambat

            Setiap perangkat yang terhubung ke bus itu menambah beban listrik (kapasitansi) di sistem. Ini bikin sinyal data berjalan lebih lambat, kayak kalau kabel listrik             terlalu panjang, arusnya jadi melemah.

            Kecepatan Internet Dibagi-Bagi

            Misalnya kita punya WiFi di rumah. Kalau cuma satu orang pakai, internetnya ngebut. Tapi kalau semua anggota keluarga streaming video sekaligus, kecepatan buat               masing-masing orang bakal turun. Begitu juga dengan bus: semakin banyak perangkat yang menggunakannya, semakin kecil bagian bandwidth yang bisa dipakai tiap                  perangkat.

            Kemacetan Data

            Kalau terlalu banyak perangkat mengirim data dalam waktu bersamaan, bus bisa jadi kewalahan. Akibatnya, ada delay atau malah data harus dikirim ulang karena                  terjadi gangguan.

            Gangguan Sinyal

            Dengan banyak perangkat terhubung, sinyal bisa saling mengganggu. Ini seperti kalau banyak orang bicara di ruangan kecil, suara jadi campur aduk dan sulit                    dimengerti.

3. Umumnya perangkat berprioritas paling rendah memiliki waktu tunggu rata-rata yang paling singkat. Dengan dasar ini biasanya CPU diberi perioritas tertinggi pada SBI. Sebutkan alasan perangkat berprioritas 16 memiliki waktu tunggu rata-rata paling rendah? Dibawah kondisi seperti apa keadaan diatas tidak berlaku?:

              Mengapa Perangkat Berprioritas 16 Memiliki Waktu Tunggu Rata-Rata Paling Rendah?
               Dalam sistem bus SBI (Synchronous Bus Interface) atau sistem bus yang menggunakan prioritas interupsi, perangkat dengan prioritas lebih tinggi akan                           mendapatkan akses lebih dulu dibandingkan perangkat dengan prioritas lebih rendah.

               Namun, jika perangkat berprioritas paling rendah (misalnya prioritas 16, dengan asumsi skala prioritas 1 adalah tertinggi dan 16 adalah terendah) memiliki                    waktu tunggu rata-rata paling rendah, ini bisa disebabkan oleh:

               Perangkat Prioritas Tinggi Jarang Digunakan

               Jika perangkat dengan prioritas tinggi jarang meminta akses ke bus, maka perangkat berprioritas rendah justru bisa sering mendapat giliran lebih cepat karena                 antreannya tidak terlalu penuh.

               Interupsi Tidak Terlalu Padat

               Dalam kondisi normal, sistem mungkin tidak menerima banyak permintaan interupsi, sehingga perangkat prioritas rendah dapat memperoleh akses tanpa harus                       menunggu lama.

               Sistem Tidak Overload

               Jika beban kerja sistem tidak terlalu tinggi, semua perangkat, termasuk yang berprioritas rendah, bisa mendapatkan akses dengan cepat karena tidak banyak                     persaingan dalam menggunakan bus.

               Kondisi di Mana Keadaan Ini Tidak Berlaku
               Namun, ada beberapa kondisi di mana perangkat prioritas rendah tidak lagi memiliki waktu tunggu rata-rata yang lebih rendah, yaitu:

               Terlalu Banyak Perangkat Prioritas Tinggi yang Aktif

               Jika banyak perangkat dengan prioritas lebih tinggi sering meminta akses ke bus, maka perangkat prioritas rendah akan semakin lama menunggu, karena harus                     mengalah pada perangkat prioritas tinggi.

               Sistem Menggunakan Algoritma Round Robin atau Time-Slicing

               Jika sistem menerapkan skema time-slicing (misalnya sistem fair scheduling) yang membagi waktu secara merata ke semua perangkat, maka prioritas tidak terlalu                 berpengaruh dan perangkat berprioritas rendah tidak akan mendapatkan akses lebih cepat dari rata-rata.

               Interupsi Berprioritas Tinggi Selalu Aktif (Starvation)

               Jika ada perangkat yang terus-menerus mengirimkan permintaan dengan prioritas lebih tinggi, maka perangkat prioritas rendah bisa kelaparan (starvation) dan                   waktu tunggunya justru meningkat drastis.

               Sistem Menggunakan Mekanisme Aging

               Dalam beberapa sistem, ada mekanisme aging, di mana jika perangkat prioritas rendah terlalu lama menunggu, sistem akan menaikkan prioritasnya. Dalam kasus                    ini, prioritas asli perangkat tidak lagi menentukan waktu tunggu rata-ratanya.

               Kesimpulan
               Perangkat dengan prioritas rendah bisa saja memiliki waktu tunggu rata-rata paling rendah jika sistem tidak terlalu sibuk dan perangkat prioritas tinggi                      jarang digunakan. Namun, dalam kondisi di mana perangkat berprioritas tinggi aktif secara intensif, perangkat berprioritas rendah akan mengalami waktu tunggu                 yang lebih lama.
