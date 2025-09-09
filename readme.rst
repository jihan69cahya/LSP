<p align="center">
    <a href="https://codeigniter.com" target="_blank">
        <img src="https://codeigniter.com/assets/images/ci-logo-big.png" width="250" alt="CodeIgniter Logo">
    </a>
</p>

<h2 align="center">📂 Aplikasi Pengarsipan Surat</h2>

<p align="center">
    <a href="https://codeigniter.com/userguide3/"><img src="https://img.shields.io/badge/CodeIgniter-3-orange" alt="CodeIgniter"></a>
    <a href="https://www.mysql.com/"><img src="https://img.shields.io/badge/Database-MySQL-blue" alt="MySQL"></a>
    <a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/License-MIT-green" alt="License"></a>
</p>

---

## 📖 Tentang Aplikasi

Aplikasi **Pengarsipan Surat** adalah aplikasi berbasis web yang dibangun menggunakan **CodeIgniter 3** dengan **database MySQL**.  
Aplikasi ini dibuat untuk keperluan **LSP (Lembaga Sertifikasi Profesi)** dengan tujuan membantu pengelolaan arsip surat secara lebih terstruktur dan efisien.

### ✨ Fitur Utama
- 📌 Manajemen data surat masuk  
- 📂 Kategori dan klasifikasi arsip surat  
- 👥 Autentikasi pengguna  

---

## 🛠️ Teknologi yang Digunakan
- **Framework**: [CodeIgniter 3](https://codeigniter.com/)  
- **Database**: [MySQL](https://www.mysql.com/)  
- **Frontend**: Bootstrap (atau bisa dikombinasikan dengan template lain)  

---

## 🚀 Instalasi & Konfigurasi

```bash
# Clone repository
git clone https://github.com/username/nama-repo.git

cd nama-repo

# Install dependency PHP
composer install

# Copy file .env
cp .env.example .env

# Generate key
php artisan key:generate

# Sesuaikan database di .env lalu jalankan migration
php artisan migrate
