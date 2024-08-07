
# Sistem Pelaporan Kerusakan

## Description
Sistem Laporan Kerusakan dibuat menggunakan Framework Laravel.Aplikasi ini mengizinkan user melaporkan kerusakan dengan mengungggah gambar dan melihat status laporan yang dikirm user tersebut. Dengan aplikasi ini, memudahkan perbaikan yang terjadi di sekitar kampus. 



## Structure Directory

``` bash

api
      config
      filters
backend

common

console

modules

public

tests

themes

vendor/

widgets


```

# Installation
Step 1 : [install composer](https://getcomposer.org/download/)

Step 2 : [install git](https://git-scm.com/download/win) untuk remote project

Step 3 : install php dan MySQLterbaru. disini bisa menggunakaan [XAMPP](https://www.apachefriends.org/download.html)

Step 4 : download repo pada link dibawah 
```bash
https://github.com/raissidiq16/ppl-laporan-kerusakan.git 

```
Step 5 : buat database dengan nama laratas

Step 6 : instalasi semua dependensi 
```
composer install
```
Step 7 : ubah .env.evample menjadi .env

step 8 : 
Step 6 : lakukan migrate database
``` bash
php artisan migrate
```
Step 6 : hubungkan storage
``` bash
php artisan storage:link
``` 

step 7 : jalankan program
``` bash
php artisan serve
``` 


## Project Member

1. Muhammad Cahyo Nugroho (M0521049)
2. Muhammad Rais Sidiq (M0521055)
3. Sitti Ayuningrum Setiyawan (M0521074)
4. Mohamad Bin Idrus Abdullah (M0518033)
