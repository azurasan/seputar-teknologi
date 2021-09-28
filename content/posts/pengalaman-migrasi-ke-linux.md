---
title: "Pengalaman Migrasi Ke Linux"
date: 2021-09-24T19:12:54+07:00
draft: true
sidebar: "right"
categories:
  - "Sistem Operasi"
tags:
  - "Linux"
---

Halo temen-temen, di postingan ini saya akan berbagi pengalaman saat melakukan migrasi dari OS jendela ke Linux. Banyak kejadian seru yang terjadi disini. Omong-omong, cerita ini lumayan panjang. Jadi, siapkan kopi dan camilan ya

## Awal mula sebelum kenal Linux

Sebelum _ngincipi_ linux, saya mengenal sistem operasi yaitu ~~jendela~~ eh **Windows** dan Mac OS. Dulunya, saya merupakan pengguna Windows, namun semua berubah ketika negara api menyerang 😂. Beberapa versi windows yang pernah saya coba adalah Windows XP, 7, 8 , 8.1 dan 10. Karena sudah bertahun-tahun menggunakan Windows, mulailah muncul rasa bosan menggunakan Windows. Terlebih lagi, spek laptop yang digunakan sangatlah **kentang**. Hal ini membuat saya semakin ingin mencoba sistem operasi lain. Setelah melakukan penyelaman di **Google**, saya menemukan beberapa artikel tentang Linux. Dan beberapa hari kemudian, saya melihat laptop teman yang menggunakan Linux. Disitu rasa penasaran mulai muncul.

## Instalasi Linux (pertama kali)

Beberapa waktu berlalu, tepatnya pada semester 5 terdapat mata kuliah Manajemen Jaringan Komputer. Pada matkul tersebut, dosen memberi tugas kepada setiap mahasiswa untuk install Linux di Virtual Box supaya digunakan untuk konfigurasi samba, FTP, dan DHCP. Karena tugas bersifat wajib, maka mau tidak mau harus dilakukan. Kemudian, saya mencoba memberanikan diri mencoba Linux. Padahal hanya disuruh install melalui Virtual Box, tetapi saya merasa ketakutan. Rasa takut ini muncul karena ini merupakan hal baru. Install Linux aja takut apalagi nembak gebetan ? eaaaa 😀. Setelah mempersiapkan mental dan paketan TSEL 14GB seharga 100rb, saya menuju website Linux, dan saat itu debian menjadi pilihan. [Debian](https://www.debian.org/) menjadi pilihan saya, karena materi dari dosen menjelaskan tentang instalasi Debian. Setelah men-_download_ file ISO Debian, saya mencoba install. Setelah mengetahui bahwa [Virtual Box](https://www.virtualbox.org/) merupakan _software_ yang cukup berat, maka saya memutuskan untuk langsung menginstall Debian di laptop tanpa menggunakan (_virtual machine_). Proses instalasi dilakukan sambil membaca materi dari dosen, artikel dari website lain, dan do'a selamat dunia akhirat. Singkat cerita, proses instalasi berhasil. Tetapi, tiba-tiba muncul masalah baru, yaitu Debian tidak bisa menginstall _package_. Rasa panik, deg-degan muncul. Ditambah lagi, deadline semakin dekat.

### Laptop Rusak ?!

Setelah itu, mencoba hubungi teman tapi hasilnya masih _nihil_. Keesokan harinya, tiba-tiba laptop rusak. Tidak bisa dinyalakan, lampu indikator mati, mesin mati. Akhirnya saya memutuskan untuk meminjam laptop teman. Singkat cerita, saya mengalami hal yang sama. Debian masih tidak bisa digunakan untuk menginstall package. Kemudian, saya putuskan untuk mencoba distro lain. Buat kalian yang masih belum mengerti apa itu distro Linux, bisa coba _googling_. Kedepannya akan dibahas di postingan selanjutnya. Setelah melihat-lihat berbagai macam distro, pilihan jatuh kepada [Linux Mint](https://linuxmint.com/). Di distro ini, tidak terjadi masalah. Tugas pun selesai.

## Migrasi sepenuhnya ke Linux

Beberapa waktu kemudian, saya mendapat laptop dari orang tua. Masih dengan spek kentang, tapi setidaknya punya sendiri daripada pinjem orang lain. Laptop tersebut terinstall Windows 7. Setelah menggunakannya selama kurang lebih 3 bulan, tiba-tiba ingin migrasi sepenuhnya ke Linux. Tapi hal tersebut dibatalkan, karena sudah banyak tugas yang terlanjur dikerjakan menggunakan Windows.

Selang beberapa waktu, semua tugas telah selesai dan UAS pun selesai. Saya meminta bantuan teman untuk melakukan instalasi Linux. Awalnya, ingin mencoba untuk _dualboot_ Windows 7 dan Linux Mint, tetapi dibatalkan karena partisi masih MBR (hanya terbatas 4 partisi). Akhirnya, memutuskan untuk _single boot_ Linux Mint. Saat proses instalasi, terdapat masalah seperti boot Linux tidak terdeteksi, proses repair boot gagal. Tetapi pada akhirnya, setelah sekian kali percobaan hasilnya berhasil. Kesan pertama saat menggunakan Linux, yaitu sangat memuaskan. Performa lebih baik daripada saat menggunakan Windows, apalagi distro Linux Mint ini memiliki tampilan yang mirip dengan Windows sehingga tidak merasa terlalu kebingungan. Proses instalasi aplikasi pun cukup mudah, tinggal melakukan perintah seperti berikut :

`sudo apt install (nama aplikasi / nama package)`

FYI, perintah diatas tergantung dari **distro** yang digunakan.

Selain itu, jika kalian merupakan pengguna yang suka melakukan kustomisasi tampilan. Maka kalian akan merasa sangat senang menggunakan Linux karena kemudahan dalam kustomisasinya, kelengkapannya, dan terdapat berbagai _resource_ yang tersedia. Pindah ke linux juga merupakan salah satu langkah saya menghindari _software_ bajakan, karena pada saat masih menggunakan Windows masih menggunakan bajakan, license ilegal atau apapun itu. Buat kalian juga yang suka nge-game, kalian juga bisa memainkan game di Linux. Meskipun, tidak sebanyak di Windows. Dan terkadang perlu melakukan beberapa konfigurasi supaya pengalaman bermain game menjadi lebih baik.

Untuk yang menggunakan aplikasi perkantoran seperti Ms.Office, terdapat beberapa opsi software alternatif, diantaranya

1. [LibreOffice](https://www.libreoffice.org/)
1. [WPS Office](https://www.wps.com/phone/)
1. [OnlyOffice](https://www.onlyoffice.com/)

atau jika keseharian sebagai editor, berikut terdapat beberapa aplikasi yang bisa digunakan baik untuk edit foto,video dan audio

1. [Gimp](https://www.gimp.org/)
1. [Inkscape](https://inkscape.org/)
1. [Audacity](https://www.audacityteam.org/)
1. [Shotcut](https://shotcut.org/)
1. [Davinci Resolve](https://www.blackmagicdesign.com/products/davinciresolve/)

dan masih banyak lagi.

Di bawah ini terdapat tampilan desktop Linux milik saya,

![mydesktop](/img/mydesktop9.png)

**BTW i don't use [Arch](https://archlinux.org/)** 😂
