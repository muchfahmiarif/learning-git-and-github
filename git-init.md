# Materi Git

## Initialization git

#### Git Command (local)

```bash
$ git init
$ git add <files>
$ git status
$ git commit -m "text perubahan"
$ git config
$ git branch
$ git help
```

#### 3 area pada repo git

- Working tree [^working-tree]
- Staging area [^staging-area]
- History [^history]

[^working-tree]: Working tree adalah Folder tempat area bekerja
[^staging-area]: Kasih tau git kalau kalian telah melakukan perubahan
[^history]: Setelah melakukan commit akan masuk ke history

![3 area pada repo git](https://cdn.statically.io/img/i.ibb.co/HP32tGG/2023-01-22-00-45.png)

#### Initialization git on repository

Tahap initialization folder menjadi repo git ada 2 cara diantaranya :

| Dengan menggunakan `git add`       | ==Tanpa== menggunakan `git add`      |
| ---------------------------------- | ------------------------------------ |
| `$ git init`                       | `$ git init`                         |
| `$ git add .` or `git add <files>` | `$ git commit -am "isi pesan commit` |
| `$ commit -m "isi pesan commit"`   |                                      |

## Git branch and merge

#### Langkah untuk melakukan branch pada git

1. Lakukan perintah `git init` yang ada [disini](#Initialization-git-on-repository)
