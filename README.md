# Ddos_flood_attack
# Http Flood DDoS Simulator

Script simulasi serangan HTTP Flood dengan 6 level kekuatan. Dilengkapi installer otomatis dan bypass Cloudflare.

## Cara Instalasi (di Termux)
```bash
git clone https://github.com/MrAYAMGORENG/Http_flood_ddos
cd Http_flood_ddos
bash install_flood.sh
python flood_web_full.py

Level Serangan
Level 1: Newbie (10 thread)

Level 2: Skid (100 thread)

Level 3: Script Kiddie (500 thread)

Level 4: Black Hat (1000 thread)

Level 5: Elite (2000 thread)

Level 6: Legend (5000 thread)

Fitur
Bypass Cloudflare (cloudscraper)

Statistik real-time (request sukses, gagal, RPS)

Warna terminal interaktif

Aman: tidak bisa digunakan untuk menyerang localhost
