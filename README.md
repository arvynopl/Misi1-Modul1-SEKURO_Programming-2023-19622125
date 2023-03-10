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
7. [VIDEO 7: GIT MERGE CONFLICT] (https://youtu.be/Vfwfeve72PA)
8. [VIDEO 12: GITIGNORE] (https://youtu.be/LK3kX4n-vLM)

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

        xvi. $ mkdir = membuat directory folder baru

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
    
3. Bukti percobaan dengan Git:
    
    <img width="500" alt="image" src="https://user-images.githubusercontent.com/53984537/216505710-b8e43739-9a26-4599-a67e-132b7c8a0653.png">
    
    <img width="500" alt="image" src="https://user-images.githubusercontent.com/53984537/216505899-a4600523-2b87-43be-9d49-34fce6c63927.png">
    
    <img width="500" alt="image" src="https://user-images.githubusercontent.com/53984537/216506099-c0fd817a-d4f8-440a-9114-97769f0c2b7a.png">
    
    <img width="500" alt="image" src="https://user-images.githubusercontent.com/53984537/216506153-d036cc84-8b5d-4dd7-b8d5-4d4c4b53bc6c.png">
    
    <img width="500" alt="image" src="https://user-images.githubusercontent.com/53984537/216506213-6bdde280-c12e-4f24-af50-a45eea0580b8.png">
    
    <img width="500" alt="image" src="https://user-images.githubusercontent.com/53984537/216506280-cc5d4083-3bc2-440d-ad9b-c0bd82528ac2.png">
    
    <img width="500" alt="image" src="https://user-images.githubusercontent.com/53984537/216506323-dff296d6-e671-4432-815a-531c0ad52e84.png">
    
    <img width="500" alt="image" src="https://user-images.githubusercontent.com/53984537/216506542-78578e5a-33c5-4a7f-bc79-87cd0dbcfad3.png">

<p>&nbsp;</p>

## VIDEO 7: GIT MERGE CONFLICT

1. Terjadi jika ada perubahan terhadap line yang sudah ada (bukan hasil penambahan) di antara kedua branch. Untuk menyelesaikannya, perlu dilakukan beberapa penyesuaian pada file

2. Jika diperlukan untuk melakukan checkout pada commit yang lama, maka terdapat langkah-langkah yang perlu dilakukan:

    a. Menggunakan command $ git log untuk mendapatkan 7 digit terakhir pada commit yang ingin diakses kembali 

    b. Akses tombol "q" pada keyboard untuk keluar dari log, kemudian gunakan command $ git checkout <7 digit terakhir commit>

    c. Pada layar, terdapat informasi bila HEAD sekarang sudah lepas dari branch dan berada di dalam commit yang telah diakses

    d. Jika ingin kembali ke branch terakhir, gunakan command $ git checkout <nama_branch>

    e. Jika ingin melanjutkan dan mengulang kembali di commit yang telah diakses, dapat membuat branch baru dengan menggunakan $ git branch <nama_branch>

    f. Untuk kondisi (e), bila kita memeriksa pada graph, HEAD belum mengarah pada branch. Maka, untuk mengarahkan HEAD kembali ke branch yang baru dibuat, dapat digunakan command $ git checkout <nama_branch>

3. Bukti percobaan dengan Git:
    
    <img width="500" alt="image" src="https://user-images.githubusercontent.com/53984537/216515222-47676d0b-388c-42c4-81c7-09ea3716077e.png">
    
    <img width="500" alt="image" src="https://user-images.githubusercontent.com/53984537/216515275-191fa050-6288-418e-b0f9-d29fe061597f.png">
    
    <img width="500" alt="image" src="https://user-images.githubusercontent.com/53984537/216515310-4523f4d0-ee0a-4cb1-8471-75b77c10e570.png">
    
    <img width="500" alt="image" src="https://user-images.githubusercontent.com/53984537/216515340-8c01ab0f-54f8-49c0-9123-13c8b70a8531.png">
    
    <img width="500" alt="image" src="https://user-images.githubusercontent.com/53984537/216515580-c34cd4fb-14e7-418b-bacf-9fee17403872.png">
    
    <img width="500" alt="image" src="https://user-images.githubusercontent.com/53984537/216515618-e774d4cc-eace-4a95-8abe-706f44eb547c.png">
    
    <img width="500" alt="image" src="https://user-images.githubusercontent.com/53984537/216515649-9b36281b-c267-44a6-b61b-36fa1efdc721.png">
    
    <img width="500" alt="image" src="https://user-images.githubusercontent.com/53984537/216515688-7960b48f-226b-4429-a92a-5d1d416fcb48.png">
    
    <img width="500" alt="image" src="https://user-images.githubusercontent.com/53984537/216516113-73612a61-95f7-448e-b201-207f96cda10b.png">
    
    <img width="500" alt="image" src="https://user-images.githubusercontent.com/53984537/216516148-ecf9f87c-f3bc-41da-bbe9-f2d3e8b8f434.png">
    
    <img width="500" alt="image" src="https://user-images.githubusercontent.com/53984537/216516170-4190c1aa-6047-4d45-8a6e-243495fdaf45.png">
    
    <img width="500" alt="image" src="https://user-images.githubusercontent.com/53984537/216516255-e9f9c805-9c0c-4741-b2d5-72e9417b5602.png">

<p>&nbsp;</p>

## VIDEO 12: GITIGNORE

1. .gitignore adalah file yang bisa disimpan dalam repo agar pada saat melakukan commit, ada file yang tidak ikut ke dalam proses commit

2. .gitignore dapat dibuat di text editor dan dapat diisi dengan beberapa hal seperti:

    a. nama_file.extension

    b. nama_folder/

    c. < * >.extension (* merupakan pola)

3. Dengan menuliskan seperti yang tertulis pada poin no(2) pada file .gitignore, maka file/folder yang didaftarkan tidak akan terbawa selama proses commit

4. Untuk mengetahui file/folder yang direkomendasikan masuk ke dalam file .gitignore, maka kita dapat mengunjungi website dengan alamat https://github.com/github/gitignore atau https://gitignore.io

5. Bukti percobaan dengan Git:

    <img width="500" alt="image" src="https://user-images.githubusercontent.com/53984537/216536521-d0a10afa-a43f-4b7c-8a14-e8e951855024.png">
    
    <img width="500" alt="image" src="https://user-images.githubusercontent.com/53984537/216536949-894ed428-df7d-41ef-93bd-bc5305c99eab.png">
    
    <img width="1000" alt="image" src="https://user-images.githubusercontent.com/53984537/216537000-ba70feae-f9f4-492a-b4e3-9e4998848ccf.png">


    
    

    
    










    
    

    
    
    
    





    
    



    
    
    
    

    
    
    
    


