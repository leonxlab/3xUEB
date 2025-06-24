# 3xUEB - Universal Exam Browser

Aplikasi aman untuk ujian berbasis Electron yang mendukung konfigurasi universal dalam format `.3xlab`.

## 📌 Penggunaan:
- Buat konfigurasi baru dari toolbar utama.
- Simpan konfigurasi dalam format `.3xlab`.
- Buka konfigurasi dengan mengklik ganda atau drag-and-drop ke aplikasi.

## 🛡️ Keamanan:
- Konfigurasi terenkripsi menggunakan AES-256.
- Password admin diperlukan untuk membuka konfigurasi.
- Validasi checksum SHA-256 memastikan integritas konfigurasi.

## 📦 Dependencies:
- Electron
- Electron Builder

## 🚀 Menjalankan Aplikasi:

### Instalasi
```bash
npm install
```

### Mode Pengembangan
```bash
npm start
```

### Build Aplikasi
```bash
npm run build
```

## 📁 Struktur Direktori:
```
3xUEB/
├── build/
├── config/
│   └── active-config.3xlab
├── src/
│   ├── main/
│   ├── renderer/
│   │   ├── toolbar/
│   │   ├── exam/
│   │   └── config-creator/
│   └── preload/
├── security/
├── utils/
├── package.json
├── electron-builder.json
└── README.md
```

---

© 2025 LeonXlab Team. All rights reserved.