
# MALANGSARI-RAMDISK-SEMI-PERMANENT

Bypass tool untuk iPhone 5s hingga X (iOS 12–17) dengan fitur lengkap dan dukungan bypass semi-permanen yang aman dari reboot dan kehabisan baterai.

## 🔧 Fitur Utama:

- ✅ **Bypass Semi-Permanent**
  - iPhone tetap aktif meskipun kehabisan baterai atau reboot.
  - Tidak perlu menjalankan ulang script setelah reboot.

- ✅ **Restore Activation + Bypass**
  - Aktivasi dipulihkan otomatis tanpa perlu login Apple ID.
  - iPhone siap digunakan langsung setelah proses.

- ✅ **Patch NAND (opsional)**
  - Memperbaiki masalah lock ulang dengan menyentuh partisi NAND secara aman.
  - Tidak menghapus data penting, bisa dipulihkan jika perlu.

- ✅ **Fix Reboot & Battery Drain**
  - Menghindari kondisi bootloop atau baterai cepat habis setelah bypass.
  - Teruji pada iPhone 5s–X iOS 12–16.x.

- ✅ **Deteksi Device Otomatis**
  - Menampilkan model iPhone dan ECID saat terkoneksi.
  - ECID disimpan ke file `.txt` otomatis.

- ✅ **Check DFU / pwnDFU Mode**
  - Memastikan device sudah masuk mode eksploitasi sebelum proses.

- ✅ **Erase Device (opsional)**
  - Untuk menghapus isi perangkat sepenuhnya via DFU Mode.

- ✅ **Fix Setup.app / Hello Screen**
  - Menghilangkan halaman "Hello" atau "Activate iPhone".

---

## 📁 Struktur Folder:

- `patch_nand.sh` → Patch partisi sistem NAND
- `restore_activation.sh` → Kembalikan file aktivasi dan jalankan bypass
- `fix_bypass.sh` → Digunakan jika iPhone restart (semi-tethered)
- `detect_model.sh` → Tampilkan model dan ECID
- `erase_device.sh` → Wipe semua isi iPhone (opsional)
- `check_pwndfu.sh` → Cek apakah iPhone sudah dalam mode pwnDFU

---

## ⚠️ Catatan Penting:
- Bypass ini **tidak bersifat permanen jika dilakukan full flash / restore iOS**.
- Patch NAND hanya menyentuh bagian aktivasi, **tidak akan merusak data pengguna** jika dilakukan dengan benar.
- Pastikan baterai mencukupi saat proses patch berlangsung.

---

**Developer: MALANGSARI TEAM**  
🔐 `#iPhoneBypass #SemiPermanent #RamdiskTools`

