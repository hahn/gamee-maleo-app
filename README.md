# Rainbow Blocks di Maleo

Memainkan game dari [Gamee](http://www.gameeapp.com) dengan menggunakan aplikasi Maleo. Aplikasi Maleo dapat diambil dari repo BlankOn di [sini](git remote add origin git@github.com:hahn/gamee-maleo-app.git). 

Di berkas repo ini, game yang dimainkan adalah permainan Rainbow Blocks. Untuk game yang lain, silakan kunjungi situs [resminya](http://www.gameeapp.com/#play-free). Berkas config.xml dan index.html dicontek dari reponya pak [Rania](https://github.com/raniaamina/kbbi4-daring). 

## Cara pakai

Setelah mengunduh repo ini (atau setelah Anda buat sendiri berkas index.html dan config.xml), lakukan langkah-langkah berikut:
1. Pasang aplikasi maleo di Linux Anda jika belum ada
2. Jalankan perintah `maleo /direktori/tempat/folder/gamee/disimpan`
3. Jika ingin agar aplikasi ini muncul di bar macam `docky` atau `plank`, edit berkas `gamee.desktop` lalu ganti bagian `exec` dan `Icon` dengan alamat tempat berkas game disimpan
4. Jika ingin memainkan game lain dari situs Gamee, kunjungi game yang disukai, lalu salin berkas code dari menu `embed game` (menunya ada di bagian kanan atas). Setelah itu ganti bagian `iframe` di berkas `index.html` dengan kode yang barusan disalin.

Selamat bermain!
