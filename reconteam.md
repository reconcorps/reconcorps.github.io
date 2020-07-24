# Cara menambah artikel dan aturannya

* Clone [reponya](https://github.con/reconcorps/reconcorps.github.io)

```
git clone https://github.com/reconcorps/reconcorps.github.io.git
```

* Tulis artikel di folder src/posts dalam bentuk markdown sesuai aturan [berikut](https://raw.githubusercontent.com/panr/gatsby-starter-hello-friend/master/src/pages/showcase.md) atau [ini](https://raw.githubusercontent.com/panr/gatsby-starter-hello-friend/master/src/posts/hello.md)

* Tambahkan hasil tulisan kedalam repo

`git add .`

* Beri commit judul atau message yang jelas 

```
git commit -m "Add new article (judul)"
```

* Jika berisi writeup beri judul dancommit messagenya sesuai peraturanberikut:

`[Nama Lomba] - Nama Challenge`

* Lalu dipush ke repo dan branch source.

```
git push origin source
```

### PS: jika mau menambahkan gambar tambahkan nama folder di src/images/{nama artikel}

# Cara preview website secara lokal

* Clone [reponya](https://github.con/reconcorps/reconcorps.github.io)

```
git clone https://github.com/reconcorps/reconcorps.github.io.git
```

* Lalu install dependency yang dibutuhkan dengan npm

```
npm install
```

* Setelah sudah jalankan melalu gatsby atau yarn

```
yarn dev
```

atau 

```
gatsby clean && gatsby develop
```

* Jika ingin menghapus dipendencynya langsung hapus saja folder `node_modulesnya`