---
layout: post
title: "Hal yang wajib dilakukan setelah install Linux Mint"
author: "Yosep Mohammad Firdaus"
categories: journal
tags: [Linux,Linux Mint]
image: wajibmint.png
---
Linux mint adalah salah satu distro Linux turunan Ubuntu yang cukup populer karna stable dan juga user friendly. jika kalian adalah salah satu pengguna yang baru menggunakan distro Linux mint ini, hal-hal ini perlu kalian lakukan ketika setelah pertama kali install di pc kalian :  

# Table Of Contents
1. [Buat Backup](#1-buat-backup)
2. [Update Sistem](#2-update-sistem)
3. [Install Driver](#3-install-driver)
4. [Install Aplikasi Tambahan](#4-install-aplikasi-tambahan)
5. [Aktifkan Firewall](#5-aktifkan-firewall)
6. [Install Multimedia Codecs](#6-install-multimedia-codecs)
7. [Install Font Microsoft](#7-install-font-microsoft)
8. [Improve System Performance](#8-improve-system-performance)  

# 1. Buat Backup
Hal penting yang perlu dilakukan adalah membuat Backup.  
antisipasi suatu saat kalian mengalami error atau apapun itu kalian bisa restore ke system yang sudah kalian backup sebelumnya.  
di linux mint sudah tersedia aplikasi bawaan yang bisa kalian gunakan untuk backup file yaitu **TimeShift** 

Cari **TimeShift** di system menu  
 <img src="{{site.baseurl | prepend: site.url}}assets/img/timeshift1.png" alt="timeshift" />
 
Pada menu wizard silahkan konfigurasi sesuaikan dengan perangkat anda :   
![a](/assets/img/timeshift2.png)  

* Pilih Snapshot Type nya **Rsync**  
* Pilih Disk tempat untuk menyimpan backup nya, saya sarankan simpan di Disk lain selain Disk yang utama.  
* Pilih level Snapshot nya (Harian, Mingguan atau Bulanan)  
* Pilih file yang tidak akan dimasukkan ke dalam daftar Backup.  
* Kalau sudah, Klik Finish.  

untuk membuat snapshot click pilihan menu **Create**  

![a](/assets/img/timeshift3.png)  

ada banyak alternatif cara untuk membackup data di Linux mint, cara ini adalah cara yang paling simple karna aplikasi ini akan membackup file yang sudah dikonfigurasi ke Drive yang lain seperti HDD External dsb.  

# 2. Update Sistem
Setelah berhasil install Linux Mint langkah selanjutnya yang paling wajib tentunya adalah update system. untuk memastikan aplikasi dan sistem keamanan sudah update ke versi yang paling baru.  

Cara Update Linux Mint   
Pertama update repositori terlebih dahulu dengan perintah :   
> sudo apt-get update  

setelah itu lalu upgrade dengan perintah :  
> sudo apt-get upgrade  

# 3. Install Driver  
hal terpenting berikutnya adalah Update driver, untuk driver sendiri di linux biasanya sudah otomatis terdeteksi dan langsung terinstall. ada beberapa device tertentu saja yang mengharuskan install driver tambahan.  

![a](/assets/img/driver1.png)  

untuk caranya kalian klik menu start, lalu di kolom pencarian ketik **driver manager**  

# 4. Install Aplikasi tambahan  
Secara default linux mint sudah menambahkan beberapa aplikasi default penting yang biasa kita gunakan di OS lain seperti office, music player, dll.  
berikut ada beberapa aplikasi tambahan yang saya rekomendasikan untuk kalian install di linux mint :  

* VLC
* Audacity
* Gimp (Alternatif Photoshop)
* Inkscape (ALternatif Corel draw & Adobe Illustrator)
* zoom
* Telegram
* Google Chrome atau Brave Browser
* Skype  

# 5. Aktifkan Firewall  
Setelah install linux mint, hal yang terpenting juga adalah mengaktifkan firewall untuk membantu melindungi sistem dari hal-hal yang tidak diinginkan. untuk cara mengaktifkannya silahkan ikuti langkah berikut :  
* klik menu lalu di kolom pencarian ketik **firewall**  
* pada bagian status rubah menjadi **enable**
* pada bagian outgoing pastikan pilih **Allow**
* pada bagian incoming pastikan pilih **Reject**  

![a](/assets/img/firewall.png)  

# 6. Install Multimedia Codecs  
beberapa format file audio dan video ada yang tidak bisa diputar karna tidak mendukung, oleh karena itu kita perlu menginstall multimedia codecs agar format file ini bisa diputar kembali seperti normal.  

untuk menginstall multimedia codecs ini kalian bisa install lewat software manager. pada menu software manager kalian masuk ke kolom pencarian lalu ketik **Multimedia Codecs**  
setelah itu kalian cukup install.  

![a](/assets/img/multimediacodecs.png)  

# 7. Install Font Microsoft  
untuk yang terbiasa menggunakan font seperti times new roman, arial, dll. kalian wajib install microsoft font ini karena di linux sendiri untuk font ini tidak tersedia secara default.   
untuk install font ini bisa lewat software manager lalu di kolom pencarian ketik **ttf-mscorefonts**  

# 8. Improve System Performance  
untuk kalian yang RAM nya lebih dari 16GB bisa ikuti cara ini untuk meningkatkan performa PC kalian. cara ini bekerja dengan cara mengurangi value swapp.  
untuk mengubah value snapp, jalankan perintah ini di terminal :  
> $ sudo sysctl -w vm.swappiness=10  

oke kurang lebih itulah hal-hal yang wajib kalian install dan konfigurasi setelah kalian menginstall linux mint.  
Terima kasih untuk yang sudah membaca Artikel ini.