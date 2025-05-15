# ProWeb  
## Praktikum Pemrograman Web untuk Aplikasi Medis, Pekan 11, 15 Mei 2025  

Langkah-langkah:  
1. Membuat repositori  
2. Daftar GitHub Education (opsional)
3. Buka GitHub Cheat Sheet    
4. Instal Git Graph  
5. Buat struktur berikut:  
    ```
    main
    |-dev
        |-frontend (misal, Fe - CRUD (ganti nama juga gapapa, tapi tidak disarankan))
        |-backend 
    ```
6. Ketikkan di terminal `git branch`  
7. Ketikkan di termunal `git branch dev`
8. `git branch`
9. `checkout dev` --> switch ke branch `dev`
10. `git add <file>`
11. `git commit -m "pesan isi di sini"`
12. `git push origin <branch>`
13. Gini caranya mengupdate branch lain
    ```
    # 1. Pindah ke dev dulu biar pastiin datanya paling baru
    git checkout dev

    # 2. Ambil update terbaru dari remote dev (GitHub/GitLab)
    git pull origin dev

    # 3. Pindah ke main (branch tujuan merge)
    git checkout main

    # 4. Merge isi dev ke main
    git merge dev

    # 5. Dorong perubahan main ke remote
    git push origin main
    ```

