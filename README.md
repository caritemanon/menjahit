# MyKasihBot

Tutorial MyKasih

# data yang diperlukan
1. Akun khusus (akun telegram)
2. 2 bot token, 1 untuk penampung, 2 untuk helper (Buat di @botfather)
3. Panel untuk web
4. VPS untuk bot
5. File untuk web, download disini https://www.mediafire.com/file/8z00axttdacbieq/mykasih.zip/file
# setting web
6. Masuk ke panel nya
7. Upload file untuk web yg didownload tadi
8. Extract file nya
9. Edit file index.html
- cari bagian var botToken lalu edit nilai nya menjadi bot token helper atau yg media
- cari bagian var chat lalu edit nilai nya menjadi id akun khusus (yg bisa diambil dari  @getmyid_bot)
10. Lakukan hal yang sama seperti nomer 4 di file verify.html dan authenticate.html
11. Jika Sudah disimpan saja, web sudas berjalan

# setting bot
1. Masuk ke vps 
( bisa pake cmd atau putty )
2. Ketik apt update
3. Ketik apt install -y tmux git python3-venv
4. Ketik git clone https://github.com/zacklie57/MyKasihBot
5. Ketik cd MyKasihBot
6. Ketik python3 -m venv v
8. Ketik . ./v/bin/activate (untuk masuk ke v)
9. Ketik pip install -r requirements.txt
10. Ketik cp sample.env .env
11. Ketik nano .env (isi data² yg diperlukan dan lihat bagian # isi data dibawah)
12. Jika sudah pencet Ctrl + s untuk menyimpan, lalu pencet Ctrl + x dan enter
13. Lalu ketik screen -S mykasih
14. Lalu ketik python3 main.py (bot akan aktif)
14. Ketik exit untuk keluar dari VPS

# Isi data
1. BOT_TOKEN (yang dibuat dari @botfather)
2. SESSION (session akun khusus, yang bisa dibuta dari @MakimaStringBot)
3. ADMINS (masukan id akun untuk akses bot penampung, bisa diambil dari @getmyid_bot)
4. OWNER (masukan id akun untuk akses bot penampung, bisa diambil dari @getmyid_bot)
5. USERBOT_ID (masukan id khusus untuk akses bot penampung, bisa diambil dari @getmyid_bot)
6. HELPER (username bot helper)
7. 
