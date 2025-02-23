# Naoris Protocol Automation Bot
## **Fitur**
- Mengirim heartbeat secara otomatis.
- Mendukung penggunaan proxy (HTTP, SOCKS4, SOCKS5).
- Menampilkan status akun dan log aktivitas.
- Multi-wallet support dengan warna berbeda untuk setiap wallet.

---

## **Persyaratan**
- Python 3.7 atau yang lebih baru.
- Modul Python yang diperlukan (lihat di bawah).
- Proxy Kalo Ada

---

## **Instalasi**

1. **Clone Repository & Install Modul**:
   ```bash
   git clone https://github.com/0xMonnn/Naorisbot.git
   cd Naorisbot
   ```
   ## Jika menemukan error
  ```bash
   python3 -m venv venv_naorisbot
   ```
  ```bash
   source venv_naorisbot/bin/activate
   ```
  ```bash
   pip install requests requests[socks] colorama pyjwt
   ```
   ## Jika tidak menemukan error langsung
   ```bash
   pip install requests requests[socks] colorama pyjwt
   ```
---

2. **Cara Running**
- Ambil Token, Inspect Di Extension `Naoris Protocol Node` Contoh Token Dengan Awalan " ey "
- Setelah Di Ambil Masukkan Ke `data.txt` 
- Jika Ada Proxy Masukkan Proxy Kalian Ke `proxy.txt` Format Proxy Seperti Di Bawah Ini (OPTIONAL)
```bash
http://username:password@host:port
http://host:port
socks4://username:password@host:port
socks4://host:port
socks5://username:password@host:port
socks5://host:port
```
- Tinggal Running 
```bash
Python bot.py
```
