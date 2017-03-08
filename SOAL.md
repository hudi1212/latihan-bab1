# Soal Latihan Bab 1

Buatlah sebuah game pacman sederhana yang memiliki maze 10x10 seperti dibawah

```
##########
#      ︎☺ #
##   #####
#        #
##   #   #
#    #####
#      # #
#  ##    #
#   ##   #
##########
```

Ketentuan :

1. Pacman merupakan obyek. Dia punya posisi (x,y), poin dan sisa langkah. Ketika ia melangkah maka sisa langkahnya berkurang 1, dan jika memakan makanan, maka poin bertambah 1;
2. Posisi makanan pada maze silakan dibuat statis saja;
3. Pacman tidak bisa menabrak maze, ia hanya bisa bergerak jika ada jalan kosong. Jika berhadapan dengan maze, silakan cari jalan lain;
4. Jika sisa langkah dari pacman habis, dan makanan masih tersisa, maka kalah. Jika makanan sudah habis, maka menang;
5. Kontrol pacman menggunakan tombol `W`, `A`, `S`, `D`. Tombol `W` untuk berjalan kedepan, tombol `A` untuk berjalan ke kiri, tombol `S` untuk berjalan ke belakang, dan tombol `D` untuk berjalan ke kanan.