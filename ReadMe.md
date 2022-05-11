# Venz Force Subscribe Bot
<p align="center">
  <img src="https://telegra.ph/file/78d150a3ce9488dcaa7cf.jpg"
</p>
Memaksa pengguna untuk bergabung dengan grup/saluran Anda agar dapat mengirim pesan dalam grup.

# Fitur
- Cek untuk semua anggota yang baru bergabung dengan pesan selamat datang yang dapat disesuaikan.
- Mengecek user yang sudah ada di grup tapi belum join channel.

# Variables
- `API_ID` - ID telegram api Anda dari my.telegram.org
- `API_HASH` - Hash telegram api Anda dari my.telegram.org
- `BOT_TOKEN` - Token bot telegram Anda.
- `CHANNEL` - Nama pengguna saluran/grup tempat pengguna harus bergabung.
- `WELCOME_MSG` - Pesan welcome yang kamu mau
`WELCOME_NOT_JOINED` - Pesan selamat datang untuk menunjukkan jika pengguna tidak ada di channel
- `ON_JOIN` - True/False - Tetapkan sebagai True jika pengguna harus dibisukan, jika tidak di Channel/group, langsung ketika dia bergabung.
- `ON_NEW_MSG` - True/False - Ditetapkan sebagai True jika pengguna harus dibisukan, jika tidak di Channel/grup, kirim pesan.

Note: `WELCOME_MSG` and `WELCOME_NOT_JOINED` keduanya dapat diformat menggunakan parameter seperti `{mention}`, `{title}`, `{fullname}`, `{username}`, `{name}`, `{last}`, `{channel}`

# Deploy to heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

# Deploy locally
- `git clone https://github.com/xditya/ForceSub`
- `cd ForceSub`
- `pip3 install -U -r requirements.txt`
- `touch .env`,  `nano .env` and fill in the [vars](.env.sample), Ctrl+S, Ctrl+X
- Run the bot, `python3 bot.py`

# Credits
- [Telethon](https://github.com/LonamiWebs/Telethon)
- [BotzHub](https://t.me/BotzHub)
- [Venz](https://t.me/moonscrsh)
- [Adit](https://xditya.me/tg)
