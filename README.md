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
5. [VIDEO 5: BEKERJA DENGAN GIT] (https://youtu.be/e-6OkXRqWaE)
6. [VIDEO 6: GIT BRANCH & MERGE] (https://youtu.be/EGl7KxVOyNs)

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
    
<p>&nbsp;</p>

## VIDEO 4: GITHUB: FORK

1. Fork = membuat duplikat repo milik orang lain (beserta histori commit-nya)

2. Jembatan antara repo original dan duplikatnya. Memungkinkan adanya modifikasi terhadap repo original yang bisa berkontribusi untuk repo orang lain

3. Fork berbeda dengan clone meskipun memiliki fungsi yang sama yaitu membuat duplikat repo. Fork digunakan untuk menduplikat repo milik orang lain di GitHub, sementara clone digunakan untuk menduplikat repo dari remote ke komputer lokal

4. Cara melakukan fork di Github:

    a. Melakukan pencarian profil akun milik orang lain untuk melakukan pemeriksaan pada repo orang lain. 
    
    b. Jika tertarik, terdapat dua cara yang bisa dilakukan. Cara pertama dengan melakukan edit secara langsung pada file yang ingin diubah (tombol yang biasanya berfungsi sebagai "Edit ..." berubah secara otomatis menjadi "Fork ...". Cara kedua dengan mengakses "Fork" pada repo yang diminati (halaman akan berubah dan menunjukkan bahwa repo tersebut sudah diduplikat di akun GitHub kita)

<p>&nbsp;</p>

## VIDEO 5: BEKERJA DENGAN GIT

1. Terdapat pilihan dalam bekerja dengan git, yaitu dengan console (command prompt) atau GUI (Git Client). Lebih disarankan untuk belajar menggunakan console terlebih dahulu agar bisa memahami cara kerja GUI

2. Langkah-langkah menggunakan Git: 

    a. Mengunduh Git melalui https://git-scm.com

    b. Membuka Git Bash yang memiliki interface yang mirip dengan command prompt 

    c. Menuliskan command pada Git Bash

        i. $ git init = membuat folder menjadi repo Git

        ii. $ git add <file(s)> = memindahkan file ke staging area

        iii. $ git status = mengetahui bila ada perubahan pada folder (misal ada penambahan file baru)

        iv. $ git commit -m <""> = memindahkan file dari staging area ke history

        v. $ git config

        vi. $ git branch

        vii. $ git help

        viii. $ git rm = memindahkan kembali file yang sudah ada di staging area kembali ke working tree

        ix. $ git log = mendapatkan informasi berupa history commit

        x. $ git log -- <file> = mendapatkan informasi berupa history commit yang khusus terjadi pada file yang diminta 

        xi. $ git checkout <5 digit pertama commit hash> -- <file> = mendapatkan kembali file (yang diperlukan) yang sudah dihapus pada versi yang diinginkan   

        xii. $ pwd = mengetahui directory folder

        xiii. $ ls = mengetahui folder yang ada dalam directory folder

        xiv. $ clear = membersihkan tampilan console

        xv. $ cd = merubah directory folder

    d. Terdapat 3 area pada repo Git:

        i. Working tree

        ii. Staging area

        iii. History

        * Sebagai catatan, file(s) dalam staging area dan history akan tersimpan ke dalam folder .git

        ** Untuk memindahkan folder dari working tree menuju staging area, digunakan perintah git add. Sementara, untuk memindahkan folder dari staging area ke history dengan perintah git commit

    e. Membuka text editor untuk membuat file yang akan dipindahkan ke history pada directory folder yang sudah dirubah menjadi repo Git

    f. Ketika secara tidak sengaja membuka VIM melalui Git Bash, maka kita dapat keluar dari program dengan mengakses tombol "esc" pada keyboard dan menuliskan command berupa :q! 

    g. Bukti percobaan Git:
        
    <img width="500" alt="image" src="https://user-images.githubusercontent.com/53984537/216492828-4c970eee-0d31-4016-bca6-81b38f369f2f.png">
    
    <img width="500" alt="image" src="https://user-images.githubusercontent.com/53984537/216492938-675ce948-0d0c-4be0-9fc9-5fc46014bf72.png">

<p>&nbsp;</p>

## VIDEO 6: GIT BRANCH & MERGE

1. Branch

    a. Menggunakan command $ git branch <nama_branch> pada console untuk menambahkan branch baru selain master branch
    
    b. Menggunakan command $ git log --all --decorate --oneline --graph untuk menampilkan visualisasi branch 
    
    c. Command sebelumnya dapat disingkat dengan cara $ alias graph="git log --all --decorate --oneline --graph"
    
    d. Menggunakan command $ git checkout <nama_branch> untuk berpindah branch

2. Merge

    a. Terdapat dua jenis merge:

        i. Fast Forward
            Branch yang akan dilakukan merge berada dalam direct path

        ii. Three-way merge (merge commit)
            Branch yang akan dilakukan merge tidak berada dalam direct path 

    b. Sebelum melakukan merge terhadap branch, lakukan check out terlebih dahulu ke master branch
    
    c. Menggunakan command $ git merge <nama_branch> untuk menggabungkan dua branch

    d. Setelah merge berjalan dengan baik, gunakan command $ git branch -d <nama_branch> untuk menghapus branch yang sudah tidak diperlukan

    e. Sebagai informasi tambahan, untuk mengetahui branch yang telah dilakukan merge, dapat digunakan command $ git branch --merged

    f. Khusus untuk merge berjenis three-way merge, akan terbentuk commit baru sehingga perlu menambahkan message melalui text editor atau VIM (yang terbuka secara otomatis)        

