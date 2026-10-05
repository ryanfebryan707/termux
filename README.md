# 📱 Termux Scripts Collection

> A comprehensive collection of Termux scripts for Android devices designed to simplify terminal-based tasks and enable powerful automation workflows.

![GitHub](https://img.shields.io/badge/GitHub-ryanfebryan707%2Ftermux-blue?style=flat-square&logo=github)
![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)
![Status](https://img.shields.io/badge/status-Active-success?style=flat-square)
![Last Updated](https://img.shields.io/badge/last%20updated-2026-brightgreen?style=flat-square)

## 📖 Table of Contents

- [About](#about)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Scripts Available](#scripts-available)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## 🎯 About

Termux Scripts Collection adalah repository yang berisi kumpulan skrip otomasi dan utilitas untuk Termux di perangkat Android. Proyek ini dirancang untuk memudahkan pengguna dalam menjalankan tugas-tugas kompleks melalui command line dengan efisien.

**Repository ini menyediakan:**
- ✨ Skrip otomasi siap pakai
- 🔧 Tools utility untuk produktivitas
- 📚 Dokumentasi lengkap
- 🚀 Performa optimal untuk perangkat mobile

## ✨ Features

- **🤖 Automation Scripts** - Skrip otomatis untuk berbagai kebutuhan
- **⚡ Lightweight & Fast** - Dirancang khusus untuk performa mobile
- **📱 Android Compatible** - 100% kompatibel dengan Termux
- **🔧 Easy to Customize** - Mudah disesuaikan dengan kebutuhan Anda
- **📖 Well Documented** - Dokumentasi lengkap dan jelas
- **🛠️ Utility Tools** - Tools helper untuk meningkatkan produktivitas
- **🔐 Secure** - Fokus pada keamanan dan best practices

## 📋 Requirements

Sebelum menggunakan repository ini, pastikan Anda memiliki:

- **Termux** - Terminal emulator untuk Android
- **Bash/Shell** - Shell environment
- **Git** - Untuk clone repository
- **Basic Linux Knowledge** - Pemahaman dasar Linux

### Instalasi Termux

Jika belum memiliki Termux, download dari:
- [Google Play Store](https://play.google.com/store/apps/details?id=com.termux)
- [F-Droid](https://f-droid.org/packages/com.termux/)

## 🚀 Installation

### Step 1: Clone Repository

```bash
git clone https://github.com/ryanfebryan707/termux.git
cd termux
```

### Step 2: Set Permissions

```bash
chmod +x *.sh
chmod +x scripts/*.sh  # Jika ada subfolder scripts
```

### Step 3: Explore & Run

```bash
ls -la              # Lihat daftar semua script
./script-name.sh    # Jalankan script tertentu
```

## 💡 Usage

### Menjalankan Script Dasar

```bash
# Dengan parameter
./script-name.sh argument1 argument2

# Tanpa parameter
./script-name.sh

# Dengan options
./script-name.sh --help
```

### Tips Penggunaan

1. **Baca dokumentasi** setiap script sebelum menjalankan
2. **Test di environment aman** terlebih dahulu
3. **Backup data penting** sebelum menjalankan script otomasi
4. **Gunakan `--help`** untuk melihat opsi yang tersedia

## 📦 Scripts Available

| Script | Deskripsi | Status |
|--------|-----------|--------|
| `example.sh` | Script contoh template | ✅ Active |
| `utility.sh` | Utility tools helper | ✅ Active |

> 📝 **Catatan:** Daftar script akan diupdate seiring penambahan fitur baru.

## 🔧 Configuration

### Environment Setup

Tambahkan ke `~/.bashrc` atau `~/.zshrc`:

```bash
# Termux Scripts Configuration
export TERMUX_SCRIPTS_HOME="$HOME/termux"
export PATH="$PATH:$TERMUX_SCRIPTS_HOME"
```

Reload shell:
```bash
source ~/.bashrc
# atau
source ~/.zshrc
```

## 📚 Documentation

Untuk dokumentasi lengkap setiap script:

```bash
# Lihat help script
./script-name.sh --help

# Lihat versi script
./script-name.sh --version

# Lihat info script
./script-name.sh --info
```

## 🐛 Troubleshooting

### Permission Denied
```bash
chmod +x script-name.sh
```

### Script not found
```bash
./script-name.sh      # Gunakan ./ untuk menjalankan
source script-name.sh # Atau source untuk bash scripts
```

### Environment Issues
```bash
# Cek Termux environment
termux-setup-storage  # Setup storage access

# Cek Python/Node version
python --version
node --version
```

## 🤝 Contributing

Kami menerima kontribusi dari komunitas! Silakan:

1. **Fork** repository ini
2. **Create** branch untuk fitur baru (`git checkout -b feature/AmazingFeature`)
3. **Commit** perubahan Anda (`git commit -m 'Add some AmazingFeature'`)
4. **Push** ke branch (`git push origin feature/AmazingFeature`)
5. **Open** Pull Request

### Contribution Guidelines

- ✅ Pastikan code bersih dan well-commented
- ✅ Update README jika ada fitur baru
- ✅ Test script sebelum submit PR
- ✅ Follow existing code style
- ✅ Tambahkan deskripsi detail di PR

## 📄 License

Project ini belum memiliki lisensi resmi. Untuk informasi lebih lanjut, hubungi maintainer.

**Recommended License Options:**
- MIT License (Recommended)
- Apache 2.0
- GPL 3.0

## 📞 Contact & Support

- **Author:** [@ryanfebryan707](https://github.com/ryanfebryan707)
- **GitHub Issues:** [Report a bug](https://github.com/ryanfebryan707/termux/issues)
- **Discussions:** [Join discussions](https://github.com/ryanfebryan707/termux/discussions)

## 🙌 Acknowledgments

Terima kasih kepada:
- Termux community
- Kontributor open source
- Semua pengguna yang telah memberikan feedback

---

## 📊 Project Status

- ✅ Active Development
- 📈 Regular Updates
- 🐛 Bug Fixes
- ✨ New Features Coming Soon

---

<div align="center">

**[⬆ back to top](#-termux-scripts-collection)**

Made with ❤️ by [@ryanfebryan707](https://github.com/ryanfebryan707)

</div>
