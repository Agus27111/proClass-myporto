Ini adalah project yang dibuat untuk kelas ProClass Harisenin.
aku membuat web portofolio, karena memang belum punya web porto sendiri.

aku buat ini dengan bantuan desain yang kutemukan di figma, dan terimakasih kepada Jacob telah membagi karyanya yang keren.
ini slicing dari desain Jacob dan beberapa modifikasi sendiri agar lebih sesuai keinginan.
ini file figmanya:
https://www.figma.com/file/7FERZlhF14HOOnjLcoJMUd/Personal-Portfolio-Web-Template-(Community)?node-id=1%3A40&mode=dev

Saya menggunakan bahasa pemrograman HTML dan CSS (Bootsrap5) + nanti akan ditambahkan JS dan di konversi ke React.

dalam pembuatannya saya sebenarnya menginginkan dalam page Home hanya ada satu halaman yang full 1 layar jadi tidak bisa di scroll down. olehkarena akhirnya saya membuat 4 BUAH FILE BERBEDA.
saya tidak tahu apakah ini cara yang benar atau tidak.

beberapa yang masih bug atau tidak sesuai yang diharapkan adalah:

0. Kesalahan saya adalah membuat dengan tampilan website terlebih dahulu sebelum mobile (lebih baik mobile kalau tidak salah) hal ini di karenakan saya ingin setidaknya file HTML dan CSS saya selesai secepatnya sedangkan file desain di FIgma yang dibagikan hanya menyediakan tampilan website, sehingga saya tidak mauu pusing dulu berpikir mobile saya ingin cepat melakukan kegiatan slicing

1. Saya belum tau betul cara membuat sideBar hidden ketika mobile, mungkin harus mencari resources lain (/28 Jan 2024)

2. pada bagian sideBar yatu icon sosial media, saat di hover saya ingin icon itu scale up.
   saya sudah coba menggunakan transform: scale(1.5) dan menambahkan efek transisi ke parent elementnya
   tapi hal tsb tidak bekerja. saya belum menemukan cara untuk membuat dia bisa responsive.

3. pada bagian icon sosial media di home bagian kanan juga sama ketika di hover tidak responsive dan sebenrnya saya ingin garisnya lebih panajng dan terlihat tapi ketikasaya menggunakan tag <hr> saya belum bisa memodifikasinya mungkin harus menggunakan svg.

4. bagian yang paling menantang adalah ketika membuat halaman works dimana untuk menampilkan hasil project saya menggabungkan antara scrollSpy dan Accordian dari bootsrap dan itu cukup menyita waktu. sebenarnya fitur ini pun masih perlu dikembangkan yaitu :
   => scrollSpy hanya berjalan jika kita meng klik bagian tag <a> jika kita meg klik dibagian luar dari <a> maka scrollSpy tidak akan berjalan walaupun accordiannya bekerja
   => jika kita menggunakan scroll dibagian scrollSpy sebenarnya ingin juga terhubung ke accordian agar misalnya jika kita scroll ke Item 2 maka accordian item2 juga akan terbuka, tapi ini sepertinya harus menggunakan tambahan JS dan masih belum terbayang.

apa yang dipelajari di sini :
banyak hal yang dipelajari dari pembuatan website portofolio ini diantaranya yaitu:

1. belajar menguanakn Bootsrap lagi karena sudah lama tidak menggunakannya, biasnya Tailwind CSS (walaupun belum bisa custom nya)

2. Bootsctrap nya ditambah dengan CSS eksternal, ini lebih menyenangkan sih untuk styling satu sisi cepat dari segi pembuatan bagian dengan Bootsrap satu sisi juga bisa styling seusai keinginan di CSS eksternal, walaupun sepertinya lebih powerfull dengan Saas. tapi belum pernah belajar Saas mungkin setelahnya bisa menmelajari ini kemudian digabung penggunaannya dengan Bootsrtsp.

3. manajeman waktu untuk pembuatan ini lumayan ekstra, karena website (HTML dan CSS dengan 4 halaman) setidaknya selesai sebelum hari senin 29 Jan 2024.
   aku mulai di pengerjaan di Kamis 25 Jan 2024
   dan Minggu 28 Jan 2024 baru selesai di desktop view.

4. sangat berhrap bisa menggunakan React segera walaupun belum belajr tentang ini.
