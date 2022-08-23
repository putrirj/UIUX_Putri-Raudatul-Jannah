# Version control dan Branch Management (Git)

1. Versioning
  Versioning berfungsi untuk mengatur versi dari source code program. 
  Sejarah Version control :
  -	Single User (1972)
  -	Centralized (1986)
  -	Distributed (2005) yaitu Git
2.	Git dan Github
  GIT adalah salah satu version control system yang popular dikalangan Devloper yang berfungsi untuk mengembangan software secara bersama-sama (kolaborasi). Keunggulan dari GIT, dia dapat melacak perubahan yang terjadi.
  Sedangkan Github adalah layanan yang berguna untuk menyimpan sekaligus mengelola projek yang dinamakan repository.
3.	Beberapa fitur dan command pada Git
  -	Setting up git, dengan cara  melakukan config dengan command :
  git config –global user.name “nama”
  git config –global user.email “email.com”
  -	Menyimpan perubahan di Git
  Pada penyimpanan perbuhan terdapat kosep Stagging Area, diawali dengan working directory kemudian stagging area dan terakhir ke repository
  command yang digunakan adalah :
  git add . (menambahkan)
  git commit -m “add config file” (untuk commit)
  git diff (untuk melihat perubahan)
  git stash (untuk menyimpan perubahan)
  -	Branch
  Branch adalah cabang dari repository yang digunakan untuk melakukan perubahan. Beberapa command yang digunakan adalah :
  gitt branch –list (untuk melihat list branch)
  git branch <branch> (membuat branch)
  git branch -D <branch> (menghapus branch)
  git branch -a (remote branch)
  git merge new-feature (untuk melakukan merge antar branch)


