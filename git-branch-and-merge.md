## Git branch and merge

#### Langkah untuk melakukan branch pada repo di lokal

1. Lakukan initializati repo dengan menggunakan perintah `git init` yang ada [disini](#initialization-git-on-repository)
2. Ketik perintah `git branch` pada terminal untuk melihat kursor repo kita yang ditunjukan pada tulisan **`Head`**
   ![git branch <nama_branch>](https://cdn.statically.io/img/i.ibb.co/KD5Lk9N/2023-01-22-10-22.png)

3. Untuk menambahkan branch dengan menggunakan perintah `git branch <nama_branch>`
   ![menambah branch baru](https://cdn.statically.io/img/i.ibb.co/r7dd3nC/2023-01-22-11-05.png)

4. Lanjut dengan melihat log atau history dengan menggunakan perintah

   ```bash
   $ git log --all --decorate --oneline --graph
   ```

   atau kalian juga dapat membuat alias sehingga dapat mempersingkat perintah log history dengan cara

   ```bash
   $ alias graph="git log --all --decorate --oneline --graph"
   ```

   dan memanggil graph dengan perintah `graph`

   ```bash
   $ graph
   ```

   ![git graph](https://cdn.statically.io/img/i.ibb.co/0JNjvLM/2023-01-22-11-11.png)

5. Lakukan `git checkout <nama_branch>` untuk memindahkan kursor **`head`** pada branch yang mau kita tentukan
   ![memindahkan kursor head](https://cdn.statically.io/img/i.ibb.co/jDHgbBY/2023-01-22-11-17.png)
   maka kursor **`Head`** akan begerak pada branch yang kita tentukan
   ![memindahkan kursor head](https://cdn.statically.io/img/i.ibb.co/LJhCVJr/2023-01-22-11-19.png)

6. Lakukan `commit` pada branch tersebut dan akan nampak perubahan seperti gambar dibawah ini
   ![branch dosen maju](https://cdn.statically.io/img/i.ibb.co/WV4KJBz/2023-01-22-11-33.png)
7. Kemudian `checkout` dan pindahkan kursor **`Head`** ke branch `staff` dengan menggunakan perintah
   ```bash
   $ git checkout staff
   ```
   ![memindahkan kursor head ke staff](https://cdn.statically.io/img/i.ibb.co/3WTVk8f/2023-01-22-11-37.png)
8. Lakukan commit pada branch staff dengan menggunakan perintah
   ```bash
   $ git commit -m "isi pesan commit"
   ```
   ![commit branch staff](https://cdn.statically.io/img/i.ibb.co/253MywL/2023-01-22-11-39.png)
   dan ini tampilan `graph` pada terminal
   ![tampilan graph](https://cdn.statically.io/img/i.ibb.co/mvST6MW/2023-01-22-11-40.png)
