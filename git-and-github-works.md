# How Does The Git and Github Works

## Question to Answer

Chapter I :

* What kind of program is Git?
    * Answer : Github
* What are the differences between Git and a text editor in terms of what they save and their record keeping?
    * Answer : Git mencatat perbedaan dalam file dan folder dan menyimpan catatan historis dari setiap penyimpanan. Sedangkan text editor mencatat seluruh kata kata dalam dokumen sebagai file tunggal.
* Does Git work at a local or remote level?
    * Answer : Ya, git bekerja pada mesin local. 
* Does GitHub work at a local or remote level?
    * Answer : Ya, github bekerja pada remote level di web untuk semua proyek pengkodean yang kita buat.
* Why is Git useful for an individual developer?
    * Answer : Karena git dapat melacak perubahan yang Anda buat pada file, sehingga Anda memiliki catatan tentang apa yang telah dilakukan, dan Anda dapat kembali ke versi tertentu jika perlu.
* Why are Git and GitHub useful for a team of developers?
    * Answer : Karena git dan github memberi Anda tempat terpusat di mana Anda dapat mengunggah perubahan dan mengunduh perubahan dari orang lain, memungkinkan Anda berkolaborasi lebih mudah dengan pengembang lain.

Chapter II :

* What is the Git command used to get a full copy of an existing Git repository from GitHub?
    * Answer : git clone
* What is the Git command used to check the status of your files?
    * Answer : git status
* What is the Git command used to track files with Git?
    * Answer : git add
* What is the Git command used to remove tracked files with Git?
    * Answer : git rm -cached
* What is the Git command used to commit files?
    * Answer : git commit -m "messege"
* What is the Git command used to view your commit history?
    * Answer : git log
* What is the Git command used to upload projects onto GitHub?
    * Answer : git push -u origin name
* Explain the two-stage system that Git uses to save files.
    * Answer : 
* Explain what origin is in git push origin main.
    * Answer : 
* Explain what main is in git push origin main.
    * Answer : 

Chapter III :

* How do you create a new repository on GitHub?
    * Answer : Pada github klik tombol NEW berwarna hijau, lalu buat nama untuk repository yang akan dibuat.
* How do you copy a repository onto your local machine?
    * Answer : Salin link yang terdapat pada SSH lalu pergi ke terminal dan ketik git clone {link}.
* What is the default name of your remote connection?
    * Answer : Nama default untuk remote connnection adalah origin master.
* How do you check the status of your current repository?
    * Answer : Dengan mengetik perintah git status pada repository.
* How do you add files to the staging area in git?
    * Answer : Untuk menambahkan file ke dalam staging area dengan mengetik git add . untuk semua file dalam repository atau hanya git add {nama file} saja.
* How do you commit the files to the staging area and add a descriptive message?
    * Answer : Dengan mengetik git commit -m "messege" sebagai pesan yang deskriptif meengenai fungsi dari file yang kita buat.
* How do you push your changes to your repository on GitHub?
    * Answer : Dengan mengetik git push origin name maka file yang telah dimodifikasi akan langsung terupdate ke repository di github.
* How do you look at the history of your previous commits?
    * Answer : Dengan mengetik git log maka kita dapat melihat detail dari log commit. Mulai dari nama author, waktu dan apa yang dimodifikasi.

## Git Command

* git clone
    * Perintah git untuk menyalin repository dari github.
* git status
    * Perintah git untuk melihat status dari file.
* git add
    * Perintah git untuk mentrack suatu file.
* git rm --cached
    * Perintah git untuk menghapus file yang telah di track.
* git commit -m "messege"
    * Perintah git untuk melakukan commit pada file yang telah di track.
* git log
    * Perintah git untuk melihat riwayat dari commit.
* git push -u origin name
    * Perintah git untuk mengupload projek atau file kedalam github.

## Glossary

* Version Control: sistem apa pun yang memungkinkan Anda memahami riwayat file dan perkembangannya.

* Git: program kontrol versi yang memungkinkan Anda memberi anotasi pada perubahan yang Anda buat untuk membuat riwayat sistem yang mudah dilalui.

* Commit: "snapshot" beranotasi tentang perbedaan yang dibuat pada sistem pada titik waktu tertentu.

* Local: mengacu pada komputer yang sedang Anda kerjakan saat ini.

* Remote: mengacu pada lokasi online.

* Repository (repo): folder khusus yang dikonfigurasi dengan kekuatan super Git yang berisi semua file yang berkaitan dengan proyek/sistem Anda.

* Github: mengambil riwayat komit lokal Anda dan menghostingnya dari jarak jauh sehingga Anda dapat mengaksesnya dari komputer mana pun.

* Pushing: tindakan mengambil komit Git lokal (dan pekerjaan apa pun yang tercakup ini) dan menempatkannya secara online di Github.

* Pulling: tindakan mengambil komitmen Github online dan membawanya ke mesin lokal Anda.

* Master (branch): "batang" dari "pohon" sejarah komit; berisi semua konten/kode yang disetujui.

* Feature branch: lokasi terisolasi, berdasarkan master, tempat Anda dapat menulis karya baru dengan aman sebelum memasukkan kembali perubahan tersebut ke master.

* Pull Request: alat Github yang memungkinkan pengguna untuk dengan mudah melihat perubahan (perbedaan atau "perbedaan") yang diusulkan oleh cabang fitur serta mendiskusikan tweak apa pun yang mungkin diperlukan cabang tersebut sebelum digabungkan menjadi master.

* Merging: tindakan mengambil komit dari cabang fitur dan menambahkannya ke puncak sejarah master.

* Checking out: tindakan berpindah dari satu cabang ke cabang lainnya.