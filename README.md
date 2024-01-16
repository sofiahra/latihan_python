# Ini adalah repo python pertama saya

silahkan baca dan komen

# ini hanya dilakukan pertama x saja saat sinkron folder baru
PS C:\Users\ASUS\Downloads\latihan_python> git init
Initialized empty Git repository in C:/Users/ASUS/Downloads/latihan_python/.git/
PS C:\Users\ASUS\Downloads\latihan_python> git add .
### warning: in the working copy of 'second.ipynb', LF will be replaced by CRLF the next time Git touches it ####
PS C:\Users\ASUS\Downloads\latihan_python> git commit -m "first commit"
[master (root-commit) b64ced1] first commit
 2 files changed, 108 insertions(+)
 create mode 100644 first.py
 create mode 100644 second.ipynb
PS C:\Users\ASUS\Downloads\latihan_python> git branch -M main

PS C:\Users\ASUS\Downloads\latihan_python> git remote add origin git@github.com:sofiahra/latihan_python.git
PS C:\Users\ASUS\Downloads\latihan_python> git push -u origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 838 bytes | 279.00 KiB/s, done. 
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:sofiahra/latihan_python.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

# ini jika ada file baru atau ada perubahan di file 
PS C:\Users\ASUS\Downloads\latihan_python> git add .
PS C:\Users\ASUS\Downloads\latihan_python> git commit -m "add Readme"
[main 806bdf2] add Readme
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md
PS C:\Users\ASUS\Downloads\latihan_python> git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 306 bytes | 153.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:sofiahra/latihan_python.git
   b64ced1..806bdf2  main -> main
PS C:\Users\ASUS\Downloads\latihan_python> 

# jika update dr web ke pc
git fetch
git pull