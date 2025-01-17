<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Laporan Berbasis Web</title>
</head>
<body>
    <h2>Pengembangan Aplikasi Sistem Informasi<br>Manajemen Perpustakaan<br>Berbasis Web</h2>
    <br>
    <hr>
    <br>
    <h3>BAB I<br>PENDAHULUAN</h3>
    <br>
    <h4>1.1 Latar Belakang</h4>
    <p>Informasi merupakan sebuah elemen penting dalam kehidupan manusia yang semakin lama semakin maju. 
        Dengan adanya informasi, kita bisa mengetahui beberapa hal yang sedang terjadi di sekitar kita. 
        Tanpa informasi, kita menjadi buta akan keadaan sekitar, maka dibuatlah tempat untuk menyimpan 
        informasi yang disebut dengan perpustakaan.</p>
    <p>Perpustakaan adalah sebuah tempat dimana didalamnya terdapat banyak ilmu pengetahuan yang sangat bermanfaat bagi masyarakat. 
        Peranan perpustakaan pada kehidupan bermasyarakat adalah sebagai tempat menyimpan karya-karya masyarakat, 
        sebagai tempat mengalirnya informasi, sebagai tempat memperoleh ilmu.</p>
    <p>Seiring dengan perkembangan teknologi, sistem terkomputerisasi menjadi suatu kebutuhan dalam segala unit usaha. 
        Selain unit usaha terdapat juga unit perpustakaan yang memiliki peran sebagai salah satu tempat untuk mencari informasi. 
        Unit perpustakaan pada dasarnya membutuhkan pengelolaan terhadap aset-aset yang dimilikinya seperti pendataan aset, 
        proses transaksi pinjam-meninjam.</p>
    <p>Oleh karena itu, dibuatlah sebuah aplikasi Sistem Informasi Manajemen Perpustakaan berbasis web supaya memudahkan sekolah x 
        untuk mengelola pendataan dan transaksi yang terjadi di perpustakaan sekolah tersebut. Sistem ini dikembangkan dengan 
        menggunakan Bahasa pemrograman PHP dengan aturan sebuah web supaya lebih tersruktur menggunakan HTML, CSS.</p>
    <h4>1.2 Rumusan Masalah</h4>
        <p>Berikut permasalahan yang terjadi di perpustakaan sekolah x :</p>
    <ol>
        <li>Pendataan yang masih manual diperpustakaan tersebut.</li>
        <li>Belum adanya aplikasi manajemen perpustakaan yang mendukung pustakawan dalam mengelola data yang ada diperpustakaan.</li>
        <li>Pembuatan laporan yang lama membuat kinerja pustakawan kurang efektif dan efisien.</li>
    </ol>
    <h4>1.3 Batasan Masalah</h4>
        <p>Berikut batasan masalah adalah :</p>
    <ol>
        <li>Hak akses digunakan untuk admin, operator dan anggota</li>
        <li>Sistem dibangun menggunakan Bahasa Pemrograman PHP. dengan aturan web HTML, CSS. dan database MySQL</li>
        <li>Data yang diolah meliputi data admin, data operator dan data anggota/member</li>
    </ol>
    <h4>1.4 Tujuan</h4>
        <p>Adapun tujuan yang didapat :</p>
    <ol>
        <li>Merancang sistem manajemen yang lebih efisien dalam pendataan</li>
        <li>Merancang aplikasi perpustakaan berbasis web untuk sekolah x</li>
        <li>Merancang sistem aplikasi manajemen perpustakaan yang ramah pengguna, baik dari segi antarmuka ataupun fitur-fitur yang disediakan untuk memudahkan pustakawan dalam mengelola perpustakaan.</li>
    </ol>
    <br>
    <br>
    <h3>BAB II<br>PEMBAHASAN</h3>
    <br>
    <br>
    <h4>2.1 Landasan Teori</h4>
    <ol>
        <li><strong>PHP</strong></li>
        <p>PHP (PHP: Hypertext Preprocessor) adalah sebuah bahasa pemrograman server side scripting yang bersifat open source.<br>
            Sebagai sebuah scripting language, PHP menjalankan instruksi pemrograman saat proses runtime. Hasil dari instruksi tentu akan berbeda tergantung data yang diproses.<br>
            PHP merupakan bahasa pemrograman server-side, maka script dari PHP nantinya akan diproses di server. Jenis server yang sering digunakan bersama dengan PHP<br>antara lain Apache, Nginx, dan LiteSpeed.<br>
            Selain itu, PHP juga merupakan bahasa pemrograman yang bersifat open source. Pengguna bebas memodifikasi dan mengembangkan sesuai dengan kebutuhan mereka.</p>
        <li><strong>XAMPP</strong></li>
        <p>Definisi sederhana dari Xampp adalah perangkat lunak berbasis web server yang bersifat open source (bebas), 
            serta mendukung di berbagai sistem operasi, baik Windows, Linux, atau Mac OS. Xampp digunakan sebagai standalone 
            server (berdiri sendiri) atau biasa disebut dengan localhost. 
            Hal tersebut memudahkan dalam proses pengeditan, desain, dan pengembangan aplikasi.<br>
            Xampp tersusun atas kependekan dari beberapa kata berikut ini:</p>
        <ol>
            <li><strong>X (Cross Platform)</strong></li>
            <p>Maksudnya adalah, Xampp dalam dijalankan di berbagai perangkat sistem operasi yang ada, misalnya Windows, Linux, Mac OS, dan Solaris. 
                Dari ke semua sistem operasi tersebut, software ini bersifat open source atau dapat digunakan secara gratis.</p>
            <li><strong>A (Apache)</strong></li>
            <p>Apache merupakan aplikasi web server yang bertugas untuk menciptakan halaman website yang benar berdasarkan kode program PHP yang ditulis oleh pengembang web (developer). 
                Memungkinkan juga untuk mengakses sistem database terlebih dahulu untuk mendukung halaman situs yang dihasilkan.</p>
            <li><strong>M (MySQL / MariaDB)</strong></li>
            <p>MySQL merupakan salah satu aplikasi database server yang menerapkan bahasa pemrograman SQL (Structured Query Language). 
                Fungsi dari MySQL sendiri adalah untuk mengelola dan membuat sistem basis data secara terstruktur dan sistematis. </p>
            <li><strong>P (PHP)</strong></li>
            <p>PHP adalah bahasa pemrograman khusus berbasis web untuk kebutuhan pada sisi server (back end). Sehingga, PHP sangat memungkinkan untuk membuat suatu halaman website menjadi lebih dinamis dengan menerapkan server-side scripting. 
                PHP juga mendukung manajemen sistem pada Oracle, Postgresql, Microsoft Access, dan lain sebagainya.</p>
            <li><strong>P (Perl)</strong></li>
            <p>Perl merupakan bahasa pemrograman untuk segala kebutuhan (cross platform) yang berfungsi sebagai penunjuk eksistensi dari PHP. 
                Perl biasanya banyak digunakan untuk website development pada sistem berbasis CMS (Content Management System) seperti WordPress.</p>
        </ol>
        <li><strong>Data Flow Diagram (DFD)</strong></li>
        <p>Data Flow Diagram (DFD) adalah alat pembuatan model yang
            memungkinkan profesional sistem untuk menggambarkan sistem
            sebagai suatu jaringan proses fungsional yang dihubungkan satu
            sama lain dengan alur data, baik secara manual maupun
            komputerisasi. DFD ini sering disebut juga dengan nama Bubble
            chart, Bubble diagram, model proses, diagram alur kerja, atau model
            fungsi.
            </p>
        <p>DFD ini adalah salah satu alat pembuatan model yang sering
            digunakan, khususnya bila fungsi-fungsi sistem merupakan bagian
            yang lebih penting dan kompleks dari pada data yang dimanipulasi
            oleh sistem. Dengan kata lain, DFD adalah alat pembuatan model
            yang memberikan penekanan hanya pada fungsi sistem.</p>
        <p>DFD ini merupakan alat perancangan sistem yang berorientasi pada
            alur data dengan konsep dekomposisi dapat digunakan untuk
            penggambaran analisa maupun rancangan sistem yang mudah
            dikomunikasikan oleh profesional sistem kepada pemakai maupun
            pembuat program.</p>
        <li><strong>Komponen Data Flow Diagram</strong></li>
        <img src="komponen.PNG">
            <p>Gambar 1. Komponen Menurut Ahli</p>
        <li><strong>Bentuk Data Flow Diagram</strong></li>
        <p>Terdapat dua bentuk DFD, yaitu Diagram Alur Data Fisik, dan
            Diagram Alur data Logika. Diagram alur data fisik lebih
            menekankan pada bagaimana proses dari sistem diterapkan,
            sedangkan diagram alur data logika lebih menekankan proses-proses
            apa yang terdapat di sistem.</p>
            <p><strong>5.1 Bentuk Alur Data Fisik (DADF)</strong></p>
            <p>DADF lebih tepat digunakan untuk menggambarkan sistem yang ada
                (sistem yang lama). Penekanan dari DADF adalah bagaimana
                proses-proses dari sistem diterapkan (dengan cara apa, oleh siapa
                dan dimana), termasuk proses-proses manual.<br>
                Untuk memperoleh gambaran bagaimana sistem yang ada
                diterapkan, DADF harus memuat :
                </p>
            <ol>
                <li>Proses-proses manual juga digambarkan.</li>
                <li>Nama dari alur data harus memuat keterangan yang cukup terinci
                    untuk menunjukkan bagaimana pemakai sistem memahami kerja
                    sistem.</li>
                <li>Simpanan data dapat menunjukkan simpanan non komputer.</li>
                <li>Nama dari simpanan data harus menunjukkan tipe penerapannya
                    apakah secara manual atau komputerisasi. Secara manual
                    misalnya dapat menunjukkan buku catatat, meja pekerja. Sedang
                    cara komputerisasi misalnya menunjukkan file urut, file database.</li>
                <li>Proses harus menunjukkan nama dari pemroses, yaitu orang,
                    departemen, sistem komputer, atau nama program komputer yang
                    mengakses proses tersebut.</li>
            </ol>
            <img src="dadf-1.PNG">
                <p>Gambar 2. Diagram Alur Data Fisik</p>
            <p><strong>5.2 Bentuk Alur Data Logika (DADL)</strong></p>
            <p>DADL lebih tepat digunakan untuk menggambarkan sistem yang
                akan diusulkan (sistem yang baru). Untuk sistem komputerisasi,
                penggambaran DADL hanya menunjukkan kebutuhan proses dari
                sistem yang diusulkan secara logika, biasanya proses-proses yang
                digambarkan hanya merupakan proses-proses secara komputer saja.</p>
                <img src="dadl.PNG">
                    <p>Gambar 3. Diagram Alur Data Logika</p>

        <li><strong>Syarat-Syarat Pembuatan Data Flow Diagram</strong></li>
            <p>Syarat pembuatan DFD ini akan menolong profesional sistem untuk
                menghindari pembentukkan DFD yang salah atau DFD yang tidak
                lengkap atau tidak konsisten secara logika. Beberapa syarat<br>
                pembutan DFD dapat menolong profesional sistem untuk membentuk
                DFD yang benar, menyenangkan untuk dilihat dan mudah dibaca
                oleh pemakai.<br>
                Syarat-syarat pembuatan DFD ini adalah :</p>
            <ol>
                <li>Pemberian nama untuk tiap komponen DFD</li>
                <li>Pemberian nomor pada komponen proses</li>
                <li>Penggambaran DFD sesering mungkin agar enak dilihat</li>
                <li>Penghindaran penggambaran DFD yang rumit</li>
                <li>Pemastian DFD yang dibentuk itu konsiten secara logika</li>
            </ol>
        <br>
        <li><Strong>Diagram Konteks</Strong></li>
            <p>Diagram ini adalah diagram level tertinggi dari DFD yang<br>
            menggambarkan hubungan sistem dengan lingkungan luarnya.<br>Caranya :</p>
        <ul>
            <li>Tentukan nama sistemnya.</li>
            <li>Tentukan batasan sistemnya.</li>
            <li>Tentukan terminator apa saja yang ada dalam sistem.</li>
            <li>Tentukan apa yang diterima/diberikan terminator dari/ke sistem.</li>
            <li>Gambarkan diagram konteks.</li>
        </ul>
        <br>
        <li><strong>Diagram Level Zero</strong></li>
            <p>Diagram ini adalah dekomposisi dari diagram konteks.<br>Caranya :</p>
        <ul>
            <li>Tentukan proses utama yang ada pada sistem.</li>
            <li>Tentukan apa yang diberikan/diterima masing-masing proses
                ke/dari sistem sambil memperhatikan konsep keseimbangan
                (alur data yang keluar/masuk dari suatu level harus sama
                dengan alur data yang masuk/keluar pada level berikutnya).</li>
            <li>Apabila diperlukan, munculkan data store (master) sebagai
                sumber maupun tujuan alur data.</li>
            <li>Gambarkan diagram level zero.<br>
                - Hindari perpotongan arus data<br>
                - Beri nomor pada proses utama (nomor tidak menunjukkan
                urutan proses).</li>
        </ul>
        <br>
        <li><strong>Diagram Level Satu</strong></li>
            <p>Diagram ini merupakan dekomposisi dari diagram level zero.<br>Caranya :</p>
        <ul>
            <li> Tentukan proses yang lebih kecil (sub-proses) dari proses utama yang ada di level zero.</li>
            <li>Tentukan apa yang diberikan/diterima masing-masing subproses ke/dari sistem dan perhatikan konsep keseimbangan.</li>
            <li>Apabila diperlukan, munculkan data store (transaksi) sebagai
                sumber maupun tujuan alur data.</li>
            <li>Gambarkan DFD level Satu<br>
                - Hindari perpotongan arus data.<br>
                - Beri nomor pada masing-masing sub-proses yang<br>
                menunjukkan dekomposisi dari proses sebelumnya.<br>
                Contoh : 1.1, 1.2, 2.1</li>
        </ul>
        <br>
        <li><strong>Diagram Level Dua, Tiga, ...</strong></li>
    </ol>
    <br>
    <h4>2.2 Metode Perancangan</h4>
    <ol>
        <li>Metode Waterfall</li>
        <img src="waterfall.PNG">
            <p>Gambar 4. Metode Penelitian Waterfall</p>
        <p>Metode waterfall merupakan model pengembangan sistem informasi
            yang sistematik dan sekuensial. Metode Waterfall
            memiliki tahapan-tahapan sebagai berikut :</p>
        <ol>
            <li>Requirements analysis and definition</li>
            <p>Layanan sistem, kendala, dan tujuan ditetapkan oleh
                hasil konsultasi dengan pengguna yang kemudian
                didefinisikan secara rinci dan berfungsi sebagai
                spesifikasi sistem.</p>
            <li>System and software design</li>
            <p>Tahapan perancangan sistem mengalokasikan
                kebutuhan-kebutuhan sistem baik perangkat keras
                maupun perangkat lunak dengan membentuk arsitektur
                sistem secara keseluruhan. Perancangan perangkat lunak
                melibatkan identifikasi dan penggambaran abstraksi
                sistem dasar perangkat lunak dan hubungannya.</p>
            <li>Implementation and unit testing</li>
            <p>Pada tahap ini, perancangan perangkat lunak
                direalisasikan sebagai serangkaian program atau unit
                program. Pengujian melibatkan verifikasi bahwa setiap
                unit memenuhi spesifikasinya.</p>
            <li>Integration and system testing</li>
            <p>Unit-unit individu program atau program digabung dan
                diuji sebagai sebuah sistem lengkap untuk memastikan
                apakah sesuai dengan kebutuhan perangkat lunak atau
                tidak. Setelah pengujian, perangkat lunak dapat
                dikirimkan ke customer</p>
            <li>Operation and maintenance</li>
            <p>Biasanya (walaupun tidak selalu), tahapan ini
                merupakan tahapan yang paling panjang. Sistem
                dipasang dan digunakan secara nyata. Maintenance
                melibatkan pembetulan kesalahan yang tidak ditemukan
                pada tahapan-tahapan sebelumnya, meningkatkan
                implementasi dari unit sistem, dan meningkatkan
                layanan sistem sebagai kebutuhan baru.</p>
        </ol>
    </ol>
    <br>
    <h4>2.3 Hasil dan Pembahasan</h4>
    <br>
        <ol>
            <li><strong>Tahap Requirement Analisis</strong></li><br>
            <table border="1">
                <tr>
                    <td>1</td>
                    <td>Pemilik Perpustakaan</td>
                    <td>a.	Pemilik bisa melakukan login dan logout.<br>
                        b.	Bisa melihat laporan peminjaman buku.<br>
                        c.	Bisa menambah dan mengurangi daftar buku.</td>
                </tr>
                <tr>
                    <td>2</td>
                    <td>Penjaga Perpustakaan</td>
                    <td>a.	Penjaga bisa melakukan login dan logout.<br>
                        b.	Bisa mengelola laporan.<br>
                        c.	Bisa mengelola data anggota.<br>
                        d.	Bisa mengelola data peminjaman buku.<br>
                        e.	Bisa menambah dan mengurangi daftar buku.</td>
                </tr>
                <tr>
                    <td>3</td>
                    <td>Anggota</td>
                    <td> a.	Anggota bisa melakukan login dan logout.<br>
                        b.  Anggota bisa melakukan sign up atau pendaftaran di aplikasi.<br>
                        c.	Anggota bisa melakukan peminjaman buku.<br>
                        d.  Anggota bisa melakukan pengembalian buku.<br>
                        e.	Anggota bisa mengelola data pribadi.</td>
                </tr>
            </table>
            <br>
            <li><strong>Tahap Desain</strong></li>
            <ol>
                <li>Entity Relationship Diagram (ERD)</li>
                <p>Diagram Hubungan Entitas atau entity relationship diagram merupakan 
                    model data berupa notasi grafis dalam pemodelan data konseptual yang menggambarkan hubungan antara penyimpan.</p>

                <img src="erd-2.PNG" title="Entity Relationship Diagram">
                    <p>Gambar 5. Entity Relationship Diagram</p>

                <li>Diagram Konteks</li>
                <br>
                <img src="d-konteks.PNG" title="Diagram Konteks">
                    <p>Gambar 6. Diagram Konteks</p>
                
                <li>DFD Level 0</li>
                <br>
                <img src="Design/dfd0.png" title="Level 0">
                    <p>Gambar 7. DFD Level 0</p>
                
                <li>DFD Level 1</li>
                <br>
                <img src="Design/dfdlv1.png" title="Level 1">
                    <p>Gambar 8. DFD Level 1</p>
                
                <li>Desain Tabel User</li>
                <br>
                <img src="Design/tb_user.JPG" width="900" title="Desain Tabel User">
                    <p>Gambar 9. Desain Tabel User</p>

                <li>Desain Tabel Transaksi</li>
                    <br>
                    <img src="Design/tb_transaksi.JPG" width="900" title="Desain Tabel Transaksi">
                        <p>Gambar 10. Desain Tabel Transaksi</p>

                <li>Desain Tabel Buku</li>
                <br>
                <img src="Design/tb_buku.JPG" width="900" title="Desain Tabel Buku">
                    <p>Gambar 11. Desain Tabel Buku</p>
            </ol>
            <br>

            <li><strong>Tahap Implementasi dan Testing</strong></li>
            <p>Dalam pembuatan aplikasi perpustakaan kami menggunakan software Visual Studio Code
                dan untuk Desain UI kami menggunakan Adobe XD.</p>
                <p><strong>Desain Antarmuka</strong></p>
                <img src="login.PNG" title="Halaman Login">
                    <p>Gambar 12. Halaman Login</p>
                
                <img src="Design/Halaman Admin/dashboard_admin.png" width="600" title="Halaman Dashboard Admin">
                    <p>Gambar 13. Halaman Dashboard Admin</p>
                
                <img src="Design/Halaman Operator/dashboard_operator.png" width="600" title="Halaman Dashboard Operator">
                    <p>Gambar 14. Halaman Dashboard Operator</p>

                <img src="Design/Halaman Anggota/dashboard_anggota.png"  width="600" title="Halaman Dashboard Anggota">
                    <p>Gambar 15. Halaman Dashboard Anggota</p>
                
                <img src="Design/Halaman Admin/data_buku.png"  width="600" title="Halaman Data Buku">
                    <p>Gambar 16. Halaman Data Buku</p>

                <img src="Design/Halaman Anggota/transaksi_anggota.png"  width="600" title="Halaman Transaksi">
                    <p>Gambar 17. Halaman Transaksi</p>

                <img src="Design/Halaman Admin/tambah_akun.png"  width="600" title="Halaman Tambah Akun">
                    <p>Gambar 18. Halaman Tambah Akun</p>

                <img src="Design/Halaman Anggota/edit_akun.png"  width="600" title="Halaman Edit Akun">
                    <p>Gambar 19. Halaman Edit Akun</p>
            <br>
            <li><strong>Tahap Deployment</strong></li>
            <p> Dalam rancangan pengujian sistem dilakukan dengan 
                pengujian black-box terhadap semua fungsi dalam aplikasi.
                Pengujian black-box merupakan salah satu pengujian
                aplikasi atau perangkat lunak yang berfokus pada persyaratan
                fungsional perangkat lunak. Karena itu uji coba black-box
                memungkinkan pengembang software untuk membuat
                himpunan kondisi input yang akan melatih seluruh syarat- syarat fungsional suatu program</p>

            <li><strong>Tahap Maintenance</strong></li>
            <p>pemeliharaan sistem dirancang dengan dilakukannya pemeriksaan periodik
                terhadap data pada aplikasi.</p>

    <br>
    <br>
    <h3>BAB III<br>KESIMPULAN</h3>
    <br>
    <br>
    <p>Berdasarkan Perancangan Sistem Informasi Manajemen Perpustakaan untuk sekolah x yang dilakukan,
        maka dapat disimpulkan sebagai berikut :</p>
    <ul>
        <li>Rancangan dan Desain Sistem Informasi Manajemen Perpustakaan dapat mengelola data admin, opeator,
            anggota perpustakaan pada sekolah x lebih efisien dan terstruktur.</li>
        <li> Rancangan dan Desain Sistem informasi Manajemen Perpustakaan
            dikembangkan menggunakan metode Waterfall akan
            memberikan output/keluaran berupa data mengenai
            admin, operator, data anggota, data buku,  dan data transaksi pada perpustakaan sekolah x.</li>
    </ul>
