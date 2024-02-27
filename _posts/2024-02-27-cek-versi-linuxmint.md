---
layout: post
title: "Cara mengetahui versi Linux Mint dan Distro linux lainnya"
author: "Yosep Mohammad Firdaus"
categories: journal
tags: [Linux,Linux Mint,Ubuntu,Debian.]
image: 2024-02-27.png 
---

mengetahui versi lengkap dari Distro linux yang kita gunakan
itu sangat penting apalagi jika ingin mencoba beberapa konfigurasi
yang sering ada di blog maupun forum.  

mengetahui versi distro linux berguna juga ketika kalian ingin menginstall aplikasi
karena beberapa aplikasi di linux hanya kompatibel di beberapa
versi distro saja.  

untuk mengetahui versi linux mint yang kalian gunakan,
gunakan perintah berikut di terminal :  
> lsb_release -a  

perintah ini akan menunjukan informasi detail distro linux yang
kita gunakan dan juga versi distribusi distro linux yang digunakan.  

![lsb](/assets/img/2024-02-27/lsb_release1.png)  

# Cara lain untuk mengetahui versi linux mint yang kita gunakan  

Alternatif lain kalian bisa menggunakan perintah ini di terminal:  
> cat /etc/lsb-release  

output dari perintah di atas adalah sebagai berikut:  

![lsb](/assets/img/2024-02-27/lsb_release2.png)  

kalian bisa menggunakan perintah ini juga untuk mengetahui
versi linux mint yang kalian gunakan:  

> cat /etc/issue  

maka output dari perintah di atas adalah sebagai berikut :  

![lsb](/assets/img/2024-02-27/lsb_release3.png)  

# Cara mengetahui versi linux mint versi gambar  

cara ini yang paling mudah untuk kalian gunakan ketika ingin
mengetahui versi linux mint yang kalian pakai.  

kalian cukup pergi ke menu system settings 
setelah itu kalian pilih system info.

![lsb](/assets/img/2024-02-27/lsb_release4.png)  

maka akan muncul informasi detail distro linux yang kalian gunakan  

![lsb](/assets/img/2024-02-27/lsb_release5.png)  

# Cara mengetahui versi linux menggunakan Neofetch  

yang terakhir kalian bisa menggunakan aplikasi neofetch.
aplikasi ini menampilkan informasi distro linux kalian dengan cukup
detail dan lebih menarik.  

untuk menginstall neofetch silahkan langsung install sesuai dengan
distro linux yang kalian pakai, sebagai contoh karna disini
saya menggunakan linux mint. maka perintahnya sebagai berikut:  

> sudo apt install neofetch  

setelah terinstall kalian cukup jalankan neofetch di terminal:  

> neofetch  

tampilannya kurang lebih seperti ini :  

![lsb](/assets/img/2024-02-27/lsb_release6.png)  

oke kurang lebih seperti itu cara untuk mengetahui versi linux mint
dan distro linux yang kalian gunakan.  
semoga dengan cara ini bisa membantu kalian.
