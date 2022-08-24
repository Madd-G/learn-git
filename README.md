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

3. Buat branch baru bernama development dan ubah README.md
```
    git checkout -b development
    git add .
    git commit -m "added branch 'development'"
    git push origin development
```
<img src="screenshot/new-development.png">
<img src="screenshot/net-new-development.png">

4. Buat branch baru bernama branchA dan ubah README.md
```
    git checkout -b featureA
    git add .
    git commit -m "added branch 'featureA'"
    git push origin featureA
```

<img src="screenshot/new-featureA.png">
<img src="screenshot/net-new-featureA.png">