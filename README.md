![HKI](https://img.shields.io/badge/Project-HKI-blue?logo=github&color=%23F7DF1E)
![CI4](https://img.shields.io/badge/-Codeigniter4-darkblue?style=flat&logo=Codeigniter)
![JS](https://img.shields.io/badge/Javascript-brown.svg?&style=flat&logo=javascript&logoColor=%23F7DF1E)
![JQUERY](https://img.shields.io/badge/JQuery-%23323330.svg?&style=flat&logo=jquery&logoColor=%23F7DF1E&color=FF3366)
![JSON](https://img.shields.io/badge/JSON-%23323330.svg?&style=flat&logo=json&logoColor=%23F7DF1E&color=9900FF)
![Bootstrap](https://img.shields.io/badge/-Bootstrap-purple.svg?&logo=bootstrap&logoColor=white)
![PHP](https://img.shields.io/badge/-PHP-darkgreen.svg?&logo=PHP&logoColor=white)
![MySQL](https://img.shields.io/badge/-MySQL-darkcyan.svg?style=flat&logo=mysql&logoColor=white)

# IBMAETER
<strong>IPR Project</strong><br>
IBMAETER is a website that facilitates users in managing warehouse inventory activities and warehouse worker management. The features provided can maintain business performance while maintaining full control of stock inventory, item prices, item weight, and others that are presented quickly and in real time, so that users do not need to do all activities manually. Users also benefit in saving their time.

<br>

## Features / Framework / Tools
| Part | Description |
| --- | --- |
| Features | Login, Create, Read, Update, Delete, Validation, Print, Export excel, Pagination, Search, ETC |
| Framework | Bootstrap 4, CodeIgniter 4 |
| Tools | Visual Studio Code, XAMPP (PHP Version 7.4), Composer, Git |

<br>

## Environment
1. Download XAMPP dengan PHP versi 7
```bash
https://sourceforge.net/projects/xampp/files/XAMPP%20Windows/7.4.30/xampp-windows-x64-7.4.30-1-VC15-installer.exe/download
```
2. Download Visual Studio Code 
```bash
https://code.visualstudio.com/docs/?dv=win
```
3. Download Composer
```bash
https://getcomposer.org/Composer-Setup.exe
```
4. Download Git
```bash
https://git-scm.com/download/win
```
5. Buat database dengan nama warehouse_db di local, ketikkan pada browser :
```bash
localhost/phpmyadmin/
```
6. Import database dengan nama warehouse_db_default.sql
7. Import semua trigger dan arahkan ke database warehouse_db yang sudah dibuat tadi di local (opsional).

<br>

## Install Codeigniter Melalui Composer
Install Codeigniter 4 dengan nama ibmaeter-ci4 melalui gitbash arahkan pada htdocs
```bash
composer create-project codeigniter4/appstarter ibmaeter-ci4
```

<br>

## Run Server
1. Pastikan masih berada di dalam folder ibmaeter-ci4 -> Klik kanan pilih gitbash lalu ketikkan :
```bash
php spark serve
```
2. Buka XAMPP lalu start apache dan mysql
3. Buka browser anda (Tab baru) lalu ketikkan -> localhost:8080 atau sesuaikan yang ada pada gitbash

<br>

## Solusi Error Sewaktu Run Server
1. Ketiklah di gitbash seperti ini :
```bash
composer update --no-dev
```
2. Kemudian cek ada permasalahan lagi atau tidak, kalau semisal masih ada error tinggal menyesuaikan dengan keadaan saja.

<br>

## Akun untuk login
| Role | Email | Password |
| --- | --- | --- |
| Admin | af@gmail.com | Superadmin123 |
| Pekerja | adeline@gmail.com | User123456 |

<br>

## Cara Menjalankan Web Secara Local
1. Download repository ini
2. Environment pastikan semua telah dilakukan -> Install Codeigniter 4 melalui gitbash
3. Lalu buka file XAMP (php.ini) -> hapus semicolon (;) didepan extension=intl ->save
4. Extract file yang di download tadi -> Copy & Paste isi folder yang di download tadi ke -> XAMP (htdocs) -> masuk kedalam folder ibmaeter-ci4 / jika belum ada buat dulu foldernya
5. Run Server
6. Login akun
7. Selesai, selamat menikmati

<br>

## Anggota Tim Project IBMAETER
| NO | NAMA ANGGOTA TIM |
| --- | --- |
| 1 | Rizky Parlika, S.Kom., M.Kom. |
| 2 | Rifky Akhmad Fernanda, S.Kom. |
| 3 | Devan Cakra Mudra Wijaya, S.Kom. |
| 4 | Merdin Risalul Abrori, S.Kom. |
| 5 | Arista Pratama, S.Kom., M.Kom. |
| 6 | Lugito Michael Imanuel Prasetya, S.Kom. |
