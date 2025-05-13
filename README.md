# USB-TETHERESTART

Script sederhana untuk **mengaktifkan, menonaktifkan, dan me-restart koneksi USB Tethering** di Android 11 melalui terminal Linux (bash).

![License](https://img.shields.io/github/license/MeowAce/USB-TETHERESTART)
![Platform](https://img.shields.io/badge/platform-Linux-blue)

---

## ✨ Fitur
- ✅ ON USB Tethering
- ✅ OFF USB Tethering
- ✅ Restart koneksi USB Tethering
- 🧩 Dirancang untuk Android 10 (bisa saja bekerja di versi lain)

---

## Tampilan
![Tampilan](/img/image.png)


## Cek PATH
```bash
echo $PATH
```

## 📦 Paket yang Dibutuhkan (untuk OpenWrt)

Agar script ini bisa berjalan di OpenWrt, pastikan paket-paket berikut sudah terinstall:

```bash
opkg update
opkg install bash coreutils sleep adb
```

## ⚙️ Instalasi

1. Clone repo:
```bash
git clone https://github.com/MeowAce/USB-TETHERESTART.git
cd USB-TETHERESTART
chmod +x usb-tere
mv usb-tere /local/bin/ #OR PATH
usb-tere
```
