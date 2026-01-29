<div align="center">
  <a href="README.md">English</a> | <a href="README-ID.md">Bahasa Indonesia</a>
</div>
<br/>

# 🛠️ Berkas Konfigurasi OpenCode

Repositori ini berisi berkas konfigurasi OpenCode pribadi saya. Pengaturan ini dioptimalkan untuk alur kerja khusus saya tetapi dirancang agar fleksibel—jangan ragu untuk menggunakannya sebagai referensi atau langsung menggunakannya dalam pengaturan Anda.

## 🚀 Cara Penggunaan

Ikuti langkah-langkah berikut untuk menerapkan konfigurasi:

1. Klon repositori ini.
2. Salin berkas dari `.config/opencode/*` ke direktori konfigurasi OpenCode lokal Anda.
3. Jalankan OpenCode.

### Mulai Cepat (Linux/macOS)

```bash
# Salin berkas konfigurasi
cp -r .config/opencode/* ~/.config/opencode/
```

### Jalankan OpenCode
```bash
opencode
```

## Struktur Direktori Konfigurasi

![Contoh Struktur Direktori Linux](/Screenshoot/config-folder-linux.png)

## 🎭 Orkestrasi: oh-my-opencode

Saya telah menyediakan dua konfigurasi preset utama untuk Orkestrasi Agen/Skills `oh-my-opencode`. Anda dapat menukarnya tergantung pada penyedia LLM pilihan Anda:

*   [Full Gemini Preset](/.config/opencode/oh-my-opencode-full-gemini.json) – Dioptimalkan untuk model Google Gemini.
*   [Full Claude Preset](/.config/opencode/oh-my-opencode-full-claude.json) – Dioptimalkan untuk model Anthropic Claude.

**Penggunaan:**
Cukup salin konten berkas preset yang diinginkan dan ganti konten `oh-my-opencode.json` di direktori konfigurasi OpenCode Anda.

## 🔐 Konfigurasi Autentikasi Antigravity

Berkas [antigravity.json](/.config/opencode/antigravity.json) mewakili pengaturan autentikasi antigravity pribadi saya.

*   **Referensi:** Anda dapat menggunakannya sebagai referensi langsung atau memodifikasinya.
*   **Kustomisasi:** Untuk menyesuaikannya dengan benar, silakan merujuk ke skema resmi [di sini](https://raw.githubusercontent.com/NoeFabris/opencode-antigravity-auth/main/assets/antigravity.schema.json).
