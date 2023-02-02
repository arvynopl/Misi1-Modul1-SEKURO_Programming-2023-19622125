# Rangkuman Video 1 GIT & GITHUB oleh Web Programming UNPAS

<p>&nbsp;</p>

## Penulis:
### 19622125 - Arvyno Pranata Limahardja
 
<p>&nbsp;</p>

## Table of Contents

1. [VIDEO 1: APA ITU GIT & GITHUB?] (https://youtu.be/lTMZxWMjXQU)
2. [VIDEO 2: BEKERJA DENGAN GITHUB] (https://youtu.be/Q3Id0DgcrXY)
3. [VIDEO 3: GITHUB: BRANCH] (https://youtu.be/k1QXd-8VbPY)
4. [VIDEO 4: GITHUB: FORK] (https://youtu.be/8rry2ncZmfg)

<p>&nbsp;</p>

## VIDEO 1: APA ITU GIT & GITHUB?

1. GIT dan GITHUB merupakan 2 hal yang berbeda (dapat digunakan secara terpisah atau bersamaan)

2. Version Control System (VCS) = sistem yang mengelola perubahan dari sebuah dokumen

3. Alasan VCS perlu digunakan:

    a. Melacak versi atau histori perubahan

    b. Melakukan kolaborasi dengan pihak lain

    c. Memungkinkan untuk kembali ke keadaan awal (checkout)

4. GIT = VCS untuk mengelola perubahan file di dalam folder (repository)

5. Riwayat perubahan file disimpan menggunakan serangkaian commit

6. Informasi yang ditampilkan dalam commit

    a. Hash = penanda setiap commit

    b. Author

    c. Date

    d. Keterangan = penjelasan perubahan yang dilakukan

7. Fitur dalam Git Repo:

    a. Branch = percabangan dalam commit agar tidak mengganggu jalur utama (dilakukan jika ingin membuat fitur yang belum pasti digunakan)

    b. Merge = penggabungan dua branch (dilakukan ketika fitur yang sebelumnya dibuat di branch yang berbeda akan dirilis)

8. GitHub = layanan cloud untuk menyimpan dan mengelola repo git

9. Kita bisa mengirimkan repo ke GitHub (push) dan menyimpan repo dari GitHub (pull) dengan syarat:

    a. Membuat remote berupa repo di GitHub

    b. Repo tersebut dikloning di komputer

    c. Sebagai catatan, push dan pull merupakan commit

10. Percobaan dengan Terminal

<p>&nbsp;</p>

## VIDEO 2: BEKERJA DENGAN GITHUB

### Langkah-langkah bekerja dengan GitHub:

1. Membuat akun GitHub dan mengisi seluruh pertanyaan yang tersedia

2. Membuat repository baru dengan mengakses "Start a project", kemudian menyunting aturan-aturan seperti:

    a. Nama

    b. Deskripsi

    c. Pilihan "Public" atau "Private"

    d. dst.

3. Mengunggah file/folder dari komputer lokal ataupun membuat file baru dengan mengakses pilihan "Create new file"

4. Jika membuat file pada GitHub, dapat melakukan commit. Terdapat pilihan untuk melakukan commit di branch utama ataupun di branch lain

5. Menyunting file jika diperlukan perubahan

6. Mengakses histori pada file atau repository untuk mengetahui informasi seputar perubahan yang terjadi pada tiap versi commit yang dilakukan

<p>&nbsp;</p>

## VIDEO 3: GITHUB: BRANCH

1. Branch berfungsi untuk membuat snapshot tanpa menganggu jalur utama (master branch)

2. Branch umumnya digunakan untuk fitur eksperimental

3. Dalam konteks kerja kolaboratif, branch juga sering dilakukan untuk pengerjaan oleh 2 atau lebih orang

4. Langkah-langkah melakukan branch di GitHub:

    a. Membuat terlebih dahulu repository baru

    b. Mengakses pilihan branch untuk membuat branch baru. Jika membuat file baru di GitHub pada branch selain master branch, perubahan hanya akan berlaku pada branch tersebut branch yang lain tersebut

    c. Ketika akan menggunakan file dari branch selain master branch, dapat dilakukan pull request (istilah merge) untuk meminta izin kepada master melakukan penyatuan dengan master branch

    d. Bila branch tidak lagi dibutuhkan, maka dapat mengakses "Branches" untuk menghapus branch yang ingin dihilangkan

    e. Branch tidak bisa secara langsung dilakukan merge apabila terdapat perubahan pada line yang sudah ada di dalam file sebelumnya. Maka dari itu, sebagai master, perlu melakukan perubahan secara manual pada dokumen/program

    f. Sebagai informasi tambahan, terdapat dua tipe merging: fast-forward merging dan three-way merging
    
<p>&nbsp:</p>

## VIDEO 4: GITHUB: FORK

1. Fork = membuat duplikat repo milik orang lain (beserta histori commit-nya)

2. Jembatan antara repo original dan duplikatnya. Memungkinkan adanya modifikasi terhadap repo original yang bisa berkontribusi untuk repo orang lain

3. Fork berbeda dengan clone meskipun memiliki fungsi yang sama yaitu membuat duplikat repo. Fork digunakan untuk menduplikat repo milik orang lain di GitHub, sementara clone digunakan untuk menduplikat repo dari remote ke komputer lokal

4. Cara melakukan fork di Github:

    a. Melakukan pencarian profil akun milik orang lain untuk melakukan pemeriksaan pada repo orang lain. 
    
    b. Jika tertarik, terdapat dua cara yang bisa dilakukan. Cara pertama dengan melakukan edit secara langsung pada file yang ingin diubah (tombol yang biasanya berfungsi sebagai "Edit ..." berubah secara otomatis menjadi "Fork ...". Cara kedua dengan mengakses "Fork" pada repo yang diminati (halaman akan berubah dan menunjukkan bahwa repo tersebut sudah diduplikat di akun GitHub kita)

<p>&nbsp:</p>
