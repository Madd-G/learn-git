Nama: Akhmad Nur Alamsyah

## Langkah praktikum

1. Buat repositori baru bernama 'learn git'
```
    echo "# learn-git" >> README.md
    git init
    git add README.md
    git commit -m "first commit"
    git branch -M main
    git remote add origin https://github.com/Madd-G/learn-git.git
    git push -u origin main
```
<img src="screenshot/new-repo.png" height=200 width=300>
<img src="screenshot/net-new-repo.png" height=200 width 300>

2. Modifikasi README.md pada main
```
    git add .
    git commit -m "modified branch 'main'"
    git push origin main
```

<img src="screenshot/main-modified.png">
<img src="screenshot/net-main-modified.png">

