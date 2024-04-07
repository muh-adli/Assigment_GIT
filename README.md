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

### Create/modify files

<img title="4" alt="4" src="./Screenshot/4. Melakukan perubahan file readme.png">

Melakukan update dokumentasi pada README.md sesuai penggunaan.

### git commit

<img title="5" alt="5" src="./Screenshot/5. Pengecekan file yang berubah.png">

Menggunakan `git status` untuk melakukan pengecekan file yang berubah pada repository.

Lalu melakukan staging data dengan command `git add .` untuk menambahkan semua data yang berubah. Dapat dilihat perubahan pada command line warna hijau dengan data yang berubah.

<img title="6" alt="6" src="./Screenshot/6. melakukan commit dan mengecek commit.png">

Melakukan commit pada git dengan command `git commit -m "docs: initiate README file and add screenshot"`, command yang dipakai adalah `git commit -m` dengan tambahan massage `"docs: initiate README file and add screenshot"` yang menyesuaikan aturan penulisan commit.

Lalu menggunakan `git log` dan `git log --online` untuk melakukan pengecekan commit

### git checkout, git branch, and add/modify branch

<img title="7" alt="7" src="./Screenshot/7. Melakukan pembuatan branch python.png">

Melakukan pembuatan branch `python` dengan command `git checkout -b python` dan mengecek branch yang aktif dengan `git branch -a`.

<img title="8" alt="8" src="./Screenshot/8. adding python file.png">

Membuat `assigment.py` dengan isi

```python
print("hello world!")
```

<img title="9" alt="9" src="./Screenshot/9. checking git status and add.png">

melakukan pengecekan git status dan menambahkan file ke staging

<img title="10" alt="10" src="./Screenshot/10. commit on diff branch.png">

melakukan commit

### Setting-up remote repository

<img title="11" alt="11" src="./Screenshot/11. connect to remote repo.png">

menggunakan command `git branch ` untuk melihat branch dan `git branch -M master` untuk membuat branch master sebagai main branch, lalu
`git remote add origin https://github.com/muh-adli/Assigment_GIT.git` untuk menambahkan remote repository dan `git push -u origin master` yang digunakan untuk melakukan push ke remote repository. Melakukan pengecekan dengan `git branch -a` untuk melihat remote repository.

### Membuat commit pada branch, melakukan pembuatan file, dan melakukan push serta merge

<img title="10" alt="10" src="./Screenshot/10. commit on diff branch.png">

<img title="12" alt="12" src="./Screenshot/12. melakukan pembuatan file python, commit, dan push ke origin.png">

<img title="13" alt="13" src="./Screenshot/13. membuat push.png">

