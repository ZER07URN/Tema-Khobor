# Tema-Khobor
Themes for OpenSID

1. beberapa widget tidak ditampilkan saat memasuki halaman first(beranda)
2. meta tag property="og:image" silahkan ganti dengan foto desa masing2 file ada di khobor/assets/up.jpg (nama harus sama)
3. galeri foto di halaman firs menggunakan foto dari sub-galeri
   jika mau dirubah seperti diatas skripnya ada di
   donjo-app>models>First_gallery_m.php
   
   	// daftar album di widget
   line 93 > $sql = "SELECT * FROM gambar_gallery WHERE enabled = '1' and parrent = 0 order by rand() limit 4";
   
   ganti menjadi 
   
   $sql = "SELECT * FROM gambar_gallery WHERE enabled = '1' and  parrent != ''  order by id DESC limit 8";
   
4. (jika punya appid FB)untuk memasukan appid facebook file ada di > khobor/commons/source_js.php  

5. jangan ngerubah copyright ya...

//////////////////////////////////////////

widget keuangan dan apdes kayaknya masih bug,, belum dicobain.
struktur folder tema masih nyontek tema cosmos by Diki Siswanto, hehe

terimakasih.....

   

  
  
         
