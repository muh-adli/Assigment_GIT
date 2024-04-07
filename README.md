# Assigment GIT - Day 3

Ini adalah dokumentasi untuk menunjukan command line GIT yang digunakan.

Adapun step yang akan dilakukan adalah:

- git clone
- git checkout -b {branch}
- create/modify files
- git add .
- git commit
- git push

## Screenshot

### git init

<img title="1" alt="1" src="./Screenshot/1. git_init.png">

Pada gambar diatas digunakan `git status` untuk mengecek repository yang berada di directory. Setelah memastikan tidak ada repository git, digunakan `git init` untuk menginisiasi repository.

### git status, branch, dan log

<img title="2" alt="2" src="./Screenshot/2. Pengecekan Status, Log, dan Branch git.png">

Dilakukan pengecekan status dengan command line `git status` untuk mengetahui branch yang sedang aktif, serta melihat file yang akan di lakukan commit dan yang akan di staged.

Lalu menggunakan `git branch` dan `git branch -a` untuk melihat branch yang aktif dan ada pada repository.

Terakhir menggunakan `git log` untuk melihat log commit yang ada pada branch aktif repository.

### git config

<img title="3" alt="3" src="./Screenshot/3. Pengecekan dan setting username dan email pada config git.png">

Melakukan pengecekan pada config git yang menggunakan `cat config` pada .git directory, setelah output terlihat ternyata belum ada name dan email. Lalu dilakukan pemasukan data dengan menggunakan command line `git config user.name` dan `git config user.email`

### 