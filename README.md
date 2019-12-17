# Hangman-2.0
Final Project (Pemrograman Lanjut)

No Kelompok   : 1                                                                                                                               
Judul Project : The Hangman Game 2.0                                                                                                     
Nama          : <br> Martin Hizkia Parasi (1806148750) <br>
                                Arvalinno (1806200160)                                                                                    


## Deskripsi Proyek : 
Game ini dimainkan dengan cara menebak huruf dari kata yang sudah di-random dari file listkata.txt. Nama dan skor pemain akan disimpan dalam file database.txt. Penyimpanan dan pemuatan data menggunakan linked list. Linked list digunakan untuk menyimpan nama beserta skor dari para pemain. Dikarenakan data pemain disimpan dalam file eksternal, maka ketika program ditutup , data pemain tidak akan hilang dan akan dimuat pada sesi permainan selanjutnya. Game ini terdiri dari 2 mode, yaitu ; mode single player dan multiplayer.
Program utama dijalankan menggunakan file testergrap.c

### Singleplayer :
Pemain akan memasukkan nama terlebih dahulu sebagai indentifikasi pemain dan untuk menyimpan skor permainan yang akan dimainkan.
Jika pemain menebak karakter dari kata yang ingin ditebak dengan benar, maka nyawa dan hangmannya akan tetap dan tidak berkurang. Kata yang ditebak berasal dari file listkata.txt yang diambil secara acak. Skor pemain akan disimpan dalam file eksternal bernama database.txt
<br>
### Multiplayer   :
Dimainkan oleh dua player, 

  - Player 1 diberikan sebuah kata untuk ditebak, kata tersebut adalah kata random dari listkata.txt, dan diberikan petunjuk berupa jumlah huruf yang harus ditebak. Point yang akan diperoleh oleh Player 1 akan bertambah sesuai dengan jumlah huruf yang ditebak benar, dan akan berkurang sesuai dengan jumlah huruf yang ditebak salah. 
  
 <br>
 
  - Player 2 juga diberikan sebuah kata untuk ditebak, panjang kata(jumlah huruf) yang diberikan akan sama dengan panjang kata(jumlah huruf) yang ditebak oleh Player 1, tetapi kata yang ditebak berbeda. Cara penilaian point pada player 2 akan sama dengan cara penilaian point pada player 1.
  
 <br>
 
 - Setelah Player 2 selesai menebak, maka Player dengan point lebih tinggi akan memenangkan permainan. Jika point kedua Player sama, maka permainan akan seri.
 
## DOKUMENTASI PROJECT
### Menu Awal
![menu awal](/image/menu.JPG)
Tampilan di atas merupakan menu awal dari permainan Hangman ini. Pada tampilan ini, terdapat 4 opsi menu yang dapat dipilih oleh player, antara lain: Singleplayer, Multiplayer, Help, dan Exit.

### Tampilan Awal Permainan
![tampilan awal](/image/awal.jpg)
Tampilan ini adalah tampilan yang pertama kali dilihat oleh player saat akan memulai permainan hangman.

### Tampilan Akhir Permainan
#### Tampilan ketika player kalah
![tampilan akhir1](/image/kalah1.JPG)
Tampilan ini adalah tampilan ketika player kalah dalam permainan.
#### Tampilan ketika player menang
![tampilan akhir2](/image/menang1.JPG)
Tampilan ini adalah tampilan ketika plyer menang dalam permainan.

### Score Board / Papan Skor
![skor](/image/scoreboard.JPG)
Pada opsi menu ini, terdapat nama-nama pemain beserta dengan skor yang didapat melalui permainan sebelumnya. Skor disimpan dalam file database.txt sehingga ketika program ditutup, data skor pemain tidak akan hilang dan akan dimuat di sesi program selanjutnya. Penyimpanan data menggunakan linked list yang berisi nama, skor, dan address dari node selanjutnya.<br>
![data](/image/database.JPG)<br>
Gambar diatas merupakan tampilan data pemain ketika disimpan dalam file database.txt


### Menu Bantuan
![help](/image/help.JPG)
Berisi tentang panduan dalam melakukan permainan hangman game ini.
