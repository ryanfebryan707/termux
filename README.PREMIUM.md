# 🔥 Termux Scripts Collection

<div align="center">

```
╔═══════════════════════════════════╗
║  TERMUX SCRIPTS COLLECTION        ║
║  Otomasi & Produktivitas Android  ║
╚═══════════════════════════════════╝
```

![Android](https://img.shields.io/badge/Android-Termux-brightgreen?style=flat-square&logo=android)
![Bash](https://img.shields.io/badge/Shell-Bash-4EAA25?style=flat-square&logo=gnu-bash)
![Status](https://img.shields.io/badge/Status-Active-success?style=flat-square)
![GitHub Stars](https://img.shields.io/github/stars/ryanfebryan707/termux?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)

**Kumpulan skrip profesional untuk meningkatkan produktivitas di Termux**

[🚀 Mulai](#instalasi) | [📚 Dokumentasi](#dokumentasi) | [🤝 Berkontribusi](#berkontribusi) | [💬 Diskusi](https://github.com/ryanfebryan707/termux/discussions)

</div>

---

## 📖 Tentang Proyek

Termux Scripts Collection adalah repository yang menyediakan koleksi skrip otomasi berkualitas tinggi untuk pengguna Termux di perangkat Android. Proyek ini dirancang untuk memudahkan workflow terminal dan meningkatkan produktivitas pengguna mobile.

## ✨ Keunggulan

| Fitur | Deskripsi |
|-------|-----------|
| 🚀 **Performa Tinggi** | Optimasi khusus untuk perangkat mobile |
| 📱 **Mobile First** | Kompatibel 100% dengan Termux Android |
| 🛠️ **Mudah Dikonfigurasi** | Setup minimal, langsung bisa dipakai |
| 📚 **Dokumentasi Lengkap** | Setiap script punya dokumentasi detail |
| 🔐 **Aman & Terpercaya** | Best practices security diterapkan |
| 🎯 **Production Ready** | Siap untuk penggunaan production |

## 🎯 Use Cases

✅ Otomasi tugas-tugas repetitif  
✅ System monitoring & maintenance  
✅ File management & backup  
✅ Network & connectivity tools  
✅ Development utilities  
✅ Custom automation workflows

## ⚡ Quick Start

### 1️⃣ Clone Repository

```bash
git clone https://github.com/ryanfebryan707/termux.git
cd termux
```

### 2️⃣ Setup Permissions

```bash
chmod +x *.sh
chmod +x scripts/*.sh 2>/dev/null
```

### 3️⃣ Jalankan Script

```bash
./script-name.sh
# atau dengan parameter
./script-name.sh --help
```

## 📚 Dokumentasi

### Struktur Project

```
termux/
├── README.md           # Dokumentasi utama
├── LICENSE             # Lisensi MIT
├── script-1.sh        # Script otomasi
├── script-2.sh        # Script utility
└── scripts/           # Folder skrip tambahan
    ├── utility.sh
    └── tools.sh
```

### Menjalankan Script

```bash
# Help command
./script-name.sh --help

# Verbose mode
./script-name.sh -v

# Dry run (preview)
./script-name.sh --dry-run

# Dengan parameter
./script-name.sh param1 param2
```

## 🔧 Konfigurasi

### Setup Environment

Tambahkan ke `~/.bashrc`:

```bash
export TERMUX_SCRIPTS_HOME="$HOME/termux"
export PATH="$PATH:$TERMUX_SCRIPTS_HOME"
```

Reload:
```bash
source ~/.bashrc
```

### Logging

Script mendukung logging otomatis:

```bash
# Default log location
~/.termux-scripts/logs/

# View logs
tail -f ~/.termux-scripts/logs/script.log
```

## 📦 Fitur Script yang Tersedia

| Script | Kategori | Status | Deskripsi |
|--------|----------|--------|-----------|
| `example.sh` | Utility | ✅ Active | Template contoh |
| `monitor.sh` | System | ✅ Active | System monitoring |
| `backup.sh` | Backup | ✅ Active | Backup automation |
| `network.sh` | Network | 🔄 Coming | Network tools |

## 🐛 Troubleshooting

### Problem: Permission Denied
```bash
chmod +x script-name.sh
```

### Problem: Script Not Found
```bash
# Cek apakah script ada
ls -la script-name.sh

# Jalankan dengan path lengkap
/path/to/termux/script-name.sh
```

### Problem: Environment Issues
```bash
# Setup storage access
termux-setup-storage

# Verify Termux installation
termux-info
```

## 🚀 Performance Tips

- ✅ Jalankan script pada waktu idle untuk hasil optimal
- ✅ Monitor resource usage dengan `top` atau `htop`
- ✅ Set proper permissions untuk script yang sensitive
- ✅ Backup penting data sebelum jalankan script baru
- ✅ Test script di environment safe terlebih dahulu

## 🤝 Berkontribusi

Kami sangat menerima kontribusi! Bagaimana cara berkontribusi:

### Workflow Kontribusi

1. **Fork** repository ini
2. **Create** branch untuk fitur: `git checkout -b feature/amazing-feature`
3. **Commit** changes: `git commit -m 'Add amazing feature'`
4. **Push** ke branch: `git push origin feature/amazing-feature`
5. **Open** Pull Request

### Panduan Kode

- ✅ Gunakan Bash script standards
- ✅ Tambahkan comments yang jelas
- ✅ Test script sebelum submit
- ✅ Update dokumentasi jika diperlukan
- ✅ Follow existing code style

## 📊 Statistik Project

![GitHub Watchers](https://img.shields.io/github/watchers/ryanfebryan707/termux?style=social)
![GitHub Forks](https://img.shields.io/github/forks/ryanfebryan707/termux?style=social)
![GitHub Stars](https://img.shields.io/github/stars/ryanfebryan707/termux?style=social)

## 📞 Support & Kontak

- 🐛 **Report Bug**: [Issues](https://github.com/ryanfebryan707/termux/issues)
- 💬 **Diskusi**: [Discussions](https://github.com/ryanfebryan707/termux/discussions)
- 👤 **Author**: [@ryanfebryan707](https://github.com/ryanfebryan707)
- 📧 **Email**: Available di GitHub profile

## 📄 Lisensi

Project ini dilisensikan di bawah **MIT License** - Lihat file [LICENSE](LICENSE) untuk detail lengkap.

```
MIT License

Copyright (c) 2023-2026 ryanfebryan707

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction...
```

## 🙏 Penghargaan

- Terima kasih kepada komunitas Termux
- Semua kontributor yang telah membantu
- Pengguna yang memberikan feedback berharga

## 🗺️ Roadmap

- [x] Initial release
- [x] Documentation
- [ ] Enhanced features
- [ ] Performance optimization
- [ ] Additional utilities

---

<div align="center">

### ⭐ Jika project ini membantu, silakan berikan star! ⭐

**[⬆ Kembali ke atas](#-termux-scripts-collection)**

Made with ❤️ by [@ryanfebryan707](https://github.com/ryanfebryan707)

Last updated: 2026

</div>
