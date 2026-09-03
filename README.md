# Website Profil XI RPL 2 Kelompok6
Website ini merupakan proyek pembelajaran kolaborasi Git dan GitHub.

## Anggota Tim
1. Nama PM : Miftah 
2. Nama Developer Profil : Melisa
3. Nama Developer Anggota : Reva
4. Nama Developer Kontak : Alriz 

## URL Repository
https://github.com/miftah323/kelompok6.git

## Apa arti hasil git status?
Menampilkan kondisi repository saat ini, seperti branch yang sedang digunakan dan apakah ada file yang berubah, belum di-staging, atau siap di-commit.

## Mengapa setiap developer tidak langsung bekerja pada main?
Agar perubahan dari setiap developer tidak langsung mengganggu atau merusak branch utama. Developer bekerja di branch masing-masing, kemudian perubahan diperiksa melalui Pull Request dan Code Review sebelum di-merge ke main. 

## Apa perbedaan pesan commit "update" dan "Menambahkan halaman profil kelas"? Mana yang lebih baik?
"update" terlalu umum sehingga tidak menjelaskan perubahan yang dilakukan. "Menambahkan halaman profil kelas" lebih jelas karena menunjukkan isi perubahan. Jadi, pesan commit kedua lebih baik.

## Apa fungsi git pull?
Untuk mengambil dan menggabungkan perubahan terbaru dari repository remote ke repository lokal.

## Apa yang terjadi jika programmer tidak melakukan git pull?
Repository lokal bisa tertinggal dari versi terbaru di GitHub sehingga programmer dapat bekerja dengan kode yang sudah tidak terbaru dan berpotensi menimbulkan konflik.

## Mengapa main harus dijaga agar tetap stabil?
Karena main merupakan branch utama yang berisi hasil proyek yang sudah diperiksa dan digabungkan. Menjaganya tetap stabil mencegah kode yang bermasalah mengganggu proyek.

## Mengapa conflict terjadi?
Karena dua developer mengubah bagian yang sama atau bagian yang saling bertentangan dalam sebuah file.

## Apakah conflict berarti Git rusak?
Tidak. Conflict merupakan hal normal dalam kolaborasi dan berarti Git membutuhkan developer untuk menentukan perubahan mana yang harus digunakan.

## Siapa yang harus menentukan versi kode yang benar?
Developer yang mengerjakan kode tersebut bersama tim/reviewer, berdasarkan kebutuhan dan kesepakatan proyek.

## Mengapa komunikasi antar programmer penting?
Agar setiap anggota memahami perubahan yang dilakukan, dapat menyelesaikan conflict dengan benar, dan menghindari kesalahan dalam pengembangan bersama. 

## Refleksi Akhir

Sebelum belajar GitHub, saya berpikir bahwa...
GitHub hanya digunakan untuk menyimpan kode atau project secara online.

Setelah melakukan kolaborasi dengan GitHub, saya memahami bahwa...GitHub dapat digunakan untuk bekerja sama dalam satu project, mengatur branch, melakukan Pull Request, Code Review, dan menggabungkan perubahan.

Kesalahan/error yang saya alami mengajarkan saya bahwa...Error bukan berarti gagal, tetapi menjadi informasi untuk mencari penyebab dan memperbaiki kesalahan.

Jika saya bekerja sebagai programmer dalam sebuah tim, saya akan...Menggunakan branch masing-masing, membuat commit yang jelas, melakukan Pull Request dan Code Review, serta berkomunikasi dengan anggota tim.


## Pertanyaan Refleksi Individu
1. Apa perbedaan bekerja sendiri dengan bekerja menggunakan Git dan GitHub? 
2. Apa manfaat branch? 
3. Mengapa Pull Request diperlukan? 
4. Apa manfaat Code Review? 
5. Error apa yang paling sulit kalian selesaikan? 
6. Bagaimana kalian menemukan solusinya? 
7. Apa kontribusi terbesar kalian dalam kelompok? 
8. Jika menjadi programmer profesional, kebiasaan apa dari kegiatan ini yang akan kalian pertahankan?

## Jawaban Developer 1
1. Bekerja sendiri biasanya dilakukan di satu perangkat tanpa koordinasi dengan orang lain, sehingga risiko bentrokan (konflik) kode sangat kecil atau tidak ada sama sekali. Sebaliknya, bekerja menggunakan Git dan GitHub melibatkan kolaborasi tim, pelacakan perubahan (version control), penyimpanan kode secara terpusat di awan (cloud), serta pengelolaan riwayat revisi yang transparan agar banyak orang bisa bekerja pada proyek yang sama secara bersamaan tanpa saling menimpa pekerjaan.

2. Branch memungkinkan pengembang untuk membuat jalur pengembangan terpisah dari kode utama (main atau master). Manfaat utamanya adalah kita bisa menguji fitur baru, melakukan eksperimen, atau memperbaiki bug secara aman tanpa merusak kestabilan kode utama yang sedang berjalan.

3. Pull Request (PR) diperlukan sebagai wadah diskusi, peninjauan, dan pengujian kode sebelum digabungkan (merge) ke cabang utama. PR menjembatani komunikasi antar anggota tim untuk memastikan bahwa kode yang masuk memenuhi standar kualitas dan tidak menimbulkan error baru.

4. Code Review membantu mendeteksi kesalahan lebih awal, meningkatkan kualitas serta keterbacaan kode, dan menjadi sarana berbagi pengetahuan antar anggota tim sehingga standar penulisan kode tetap terjaga secara konsisten.

5. Error yang paling sulit biasanya berkaitan dengan konflik merge yang kompleks saat dua orang mengubah baris kode yang sama secara bersamaan, atau masalah dependency/version mismatch yang menyebabkan aplikasi gagal dibangun (build) setelah digabungkan.

6. Solusi ditemukan dengan membaca pesan error secara teliti melalui terminal, memeriksa riwayat komit menggunakan perintah Git log untuk melihat perubahan terakhir, berdiskusi dengan rekan sekelompok, serta mencari referensi dokumentasi resmi atau forum diskusi seperti Stack Overflow.

7. Kontribusi terbesar biasanya mencakup perancangan struktur dasar proyek, pengelolaan alur kerja Git (mengatur branching strategy dan menyelesaikan konflik kode tim), serta memastikan integrasi kode dari setiap anggota berjalan lancar.

8. Kebiasaan profesional yang layak dipertahankan meliputi pembuatan komit dengan pesan yang jelas dan deskriptif, selalu menggunakan branch terpisah untuk setiap fitur baru, rutin melakukan Code Review sebelum menggabungkan kode, serta melakukan dokumentasi yang baik pada setiap perubahan yang dilakukan.

## Jawaban Developer 2
1. Apa perbedaan bekerja sendiri dengan bekerja menggunakan Git dan GitHub?
Kalau kerja sendiri, folder project biasanya berantakan banget karena suka bikin copy-paste kaya project_final_v1, project_final_fix. Kalau ada kode yang rusak juga susah buat balik ke versi sebelumnya. Nah, pas pake Git dan GitHub, semua riwayat perubahan tercatat rapi. Kita bisa ngerjain fitur beda-beda bareng temen tanpa takut kodenya saling ketimpa, plus kodenya otomatis ke-backup di cloud.

2. Apa manfaat branch?
Biar punya ruang kerja terpisah. Jadi kita bisa nyoba-nyoba fitur baru atau benerin bug di branch sendiri tanpa ngerusak kode utama yang udah jalan. Nanti kalau fiturnya udah dipastikan aman dan gak error, baru deh digabungin ke kode utama.

3. Mengapa Pull Request diperlukan?
Biar gak asal main gabungin kode aja. PR itu ibarat gerbang pengecekan—sebelum kode baru masuk ke repo utama, temen sekelompok bisa meriksa dulu kodenya. Ini penting banget biar gak ada kode yang rusak atau bentrok yang ketimpa ke branch utama.

4. Apa manfaat Code Review?

Bikin kodenya jadi lebih rapi dan minim bug karena dibantu cek sama temen.

Kita jadi bisa saling belajar cara nulis kode yang lebih efisien dari temen sekelompok.

5. Error apa yang paling sulit kalian selesaikan?
Pas dapet Git Merge Conflict. Itu pusing banget karena aku sama temen kelompok ketahuan ngedit baris kode yang sama di file yang sama, jadi Git-nya bingung mau pake kode yang mana.

6. Bagaimana kalian menemukan solusinya?
Langsung ngobrol bareng temen yang bersangkutan buat nentuin kode siapa yang mau dipake. Habis itu aku rapihin kodenya manual di VS Code, hapus penanda conflict-nya, terus tinggal simpen, commit, dan push ulang.

7. Apa kontribusi terbesar kalian dalam kelompok?
(Bisa disesuaikan) Kontribusi terbesarku itu ngerjain fitur [sebutin fiturnya, misal: halaman login], ngerapihin struktur folder project, sama bantu temen pas mereka kebingungan pas dapet merge conflict.

8. Jika menjadi programmer profesional, kebiasaan apa dari kegiatan ini yang akan kalian pertahankan?

Selalu bikin branch baru tiap mau ngerjain fitur baru dan rajin commit pake pesan yang jelas.

Biasain minta review dari temen lewat PR sebelum merge kode, biar kualitas kodenya tetep terjaga

## Jawaban Developer 3
1. Apa perbedaan bekerja sendiri dengan bekerja menggunakan Git dan GitHub? Perbedaan utama antara bekerja sendiri secara konvensional dan menggunakan Git serta GitHub mencakup beberapa aspek penting dalam manajemen proyek dan kolaborasi tim
2. Apa manfaat branch? Cabang atau branch dalam Git memberikan beberapa manfaat utama untuk pengembangan proyek, baik dikerjakan sendiri maupun bersama kelompok
3. Mengapa Pull Request diperlukan? Pull Request (PR) sangat diperlukan dalam kolaborasi proyek berbasis Git dan GitHub karena tempat diskusi dan Review Kode,Mencegah Konflik dan Bug
4. Apa manfaat Code Review? Meningkatkan Kualitas Kode,Berbagi Pengetahuan dan Memastikan Standar Koding
5. Error apa yang paling sulit kalian selesaikan? menurut saya yang sulit ketika error memasukan code tetpi kodenya aada yang salah
6. Bagaimana kalian menemukan solusinya? sayaa sukaa menanyakan dulu kepada temen tetapi kalo temen gatau sama, saya suka langsgsung menanykan kepada ai
7. Apa kontribusi terbesar kalian dalam kelompok? tidak tahu, karna saya mengerjakan apa yang saya kerjakan dan bertanggung jawab
8. Jika menjadi programmer profesional, kebiasaan apa dari kegiatan ini yang akan kalian pertahankan? yaa akan saya pertahankan


## Jawaban Refleksi Project Manager 
1. Bekerja sendiri membuat kode mudah bertabrakan dan membingungkan jika dikirim lewat pesan biasa. Dengan Git dan GitHub, pengerjaan proyek bisa dilakukan secara teratur bersama tim melalui fitur branching, pull request, dan riwayat commit yang jelas.
2. Branch memungkinkan setiap anggota tim mengerjakan fitur masing-masing tanpa mengganggu kode utama yang berada di branch main.
3.  Pull Request (PR) diperlukan agar perubahan kode yang dibuat anggota tim bisa diperiksa dan disetujui terlebih dahulu oleh Project Manager sebelum digabungkan ke kode utama (main).
4. Code Review berguna untuk memastikan tidak ada kesalahan sintaks (typo tag HTML, salah penulisan), memastikan kode rapi, serta menjaga kualitas proyek sebelum kode di-merge.
5.  Memahami error fatal: not a git repository saat salah direktori, memperbaiki kesalahan sintaks tag HTML (<htm1> alih-alih <html>), serta penanganan salah perintah saat melakukan git push (fatal: invalid refspec).
6. Dengan cara membaca pesan error yang muncul di terminal Git Bash, melakukan analisis pada kodingan yang merah/salah, serta berdiskusi dan berkonsultasi untuk menemukan sintaks atau perintah yang benar.
7. Membuat repository awal, membagi tugas ke anggota tim, membimbing anggota saat terjadi kesalahan pada kode/Git, melakukan Code Review, serta mengelola penggabungan (merge) seluruh fitur anggota ke branch main.
8. Kebiasaan selalu bekerja menggunakan branch terpisah, membuat pesan commit yang jelas, teliti melakukan Code Review, serta rajin melakukan sinkronisasi kode (git pull) agar kode selalu diperbarui bersama tim.

