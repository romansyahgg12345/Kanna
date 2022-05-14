


## FOR DEPLOY HEROKU USER

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Kangsad01/Wabot-Tsb01)

### Instal Buildpack
* heroku/nodejs
* https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest.git
* https://github.com/DuckyTeam/heroku-buildpack-imagemagick.git

## FOR DEPLOY RAILWAY USER

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template?template=https%3A%2F%2Fgithub.com%2FKangsad01%2FWabot-Tsb01)

## FOR DEPLOY REPLIT USER

[![Run on Repl.it](https://repl.it/badge/github/FadliDarmawan/haruno)](https://repl.it/github/Kannachann/kanna-wabot/)
```cmd
Open Console
------------
> npm i
> npm i qrcode
> install-pkg webp
> install-pkg ffmpeg
-------------
Click Run
```
## Whatsapp

[![Grup WhatsApp](https://img.shields.io/badge/WhatsApp%20Group-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://chat.whatsapp.com/Hjr3H7l9iC8F2deP0cv6GT)
[![Whatsapp BOT](https://img.shields.io/badge/WhatsApp%20BOT-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/6283143393763/)

## UNTUK PENGGUNA WINDOWS/VPS/RDP

* Unduh & Instal Git [`Klik Disini`](https://git-scm.com/downloads)
* Unduh & Instal NodeJS [`Klik Disini`](https://nodejs.org/en/download)
* Unduh & Instal FFmpeg [`Klik Disini`](https://ffmpeg.org/download.html) (**Jangan Lupa Tambahkan FFmpeg ke variabel lingkungan PATH**)
* Unduh & Instal ImageMagick [`Klik Disini`](https://imagemagick.org/script/download.php)

```bash
git clone https://github.com/Kannachann/kanna-wabot/
cd kanna-wabot
npm i
npm update
node .
```

---------

## UNTUK PENGGUNA TERMUX
```bash
termux-setup-storage
pkg install git
pkg install nodejs
pkg install ffmpeg
pkg install imagemagick
pkg install libwebp
git clone https://github.com/Kannachann/kanna-wabot/
npm install -g npm@6.14.14
npm start
```

---------

## Arguments `node . [--options] [<session name>]`

#### Contoh: `node . --self --restrict --autoread`

### `--self`

Aktifkan mode self (Mengabaikan yang lain)

### `--prefix <prefixes>`

* `prefixes` dipisahkan oleh masing-masing karakter
Setel awalan

### `--server`

Digunakan untuk [heroku](https://heroku.com/) atau pindai melalui situs web

### `--db <json-server-url>`

Gunakan db eksternal alih-alih db lokal, 
Contoh Server `https://json-server.nurutomo.repl.co/`
Code: `https://repl.it/@Nurutomo/json-server`

`node . --db 'https://json-server.nurutomo.repl.co/'`

Server harus memiliki spesifikasi seperti ini

#### GET

```http
GET /
Accept: application/json
```

#### POST

```http
POST /
Content-Type: application/json

{
 data: {}
}
```

### `--big-qr`

Jika qr unicode kecil tidak mendukung

### `--restrict`

Mengaktifkan plugin terbatas (yang dapat menyebabkan nomor Anda **diblokir** jika digunakan terlalu sering)

* Administrasi Grup `add, kick, promote, demote`

### `--img`

Aktifkan pemeriksa gambar melalui terminal

### `--autoread`

Jika diaktifkan, semua pesan masuk akan ditandai sebagai telah dibaca

### `--nyimak`

Tidak ada bot, cukup cetak pesan yang diterima dan tambahkan pengguna ke database

### `--test`

**Development** Testing Mode

### `--trace`

```js
conn.logger.level = 'trace'
```

### `--debug`

```js
conn.logger.level = 'debug'
```

---------

 [![Nurutomo](https://github.com/Nurutomo.png?size=100)](https://github.com/Nurutomo) | [![Ariffb](https://github.com/ariffb25.png?size=100)](https://github.com/ariffb25) | [![Kannachann](https://github.com/Kannachann.png?size=100)](https://github.com/Kannachann)
----|----|----
[Nurutomo](https://github.com/Nurutomo) | [Ariffb](https://github.com/ariffb25) | [Kannachann](https://github.com/Kannachann)
 Penulis / Pencipta | Penulis ulang Ke-1 | Penulis ulang Ke-2
