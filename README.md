# 📄 Surat Lamaran Generator

Generator surat lamaran kerja berbasis web — tinggal isi form, surat langsung terbentuk secara real-time. Tidak perlu install apapun, cukup buka satu file HTML.

![Demo](https://img.shields.io/badge/demo-live-brightgreen) ![License](https://img.shields.io/badge/license-MIT-blue) ![HTML](https://img.shields.io/badge/built%20with-HTML%2FCS%2FJS-orange)

---

## ✨ Fitur

- **Real-time preview** — surat otomatis terupdate setiap kamu mengetik
- **Form 3 tab** — Pengirim, Tujuan, dan Isi Surat
- **Cetak / Simpan PDF** — langsung dari browser, tanpa tools tambahan
- **Salin teks** — copy plain text surat ke clipboard
- **Lampiran opsional** — daftar berkas otomatis masuk ke isi surat
- **Dark mode** — mengikuti preferensi sistem
- **Responsive** — bisa dipakai di HP maupun desktop
- **Zero dependency** — satu file HTML, tidak butuh framework atau build step

---

## 🚀 Cara Pakai

### Opsi 1 — Buka langsung
Download file `index.html`, lalu buka di browser. Selesai.

### Opsi 2 — Deploy ke Netlify (drag & drop)
1. Download `index.html`
2. Buka [app.netlify.com/drop](https://app.netlify.com/drop)
3. Drag & drop file → langsung dapat URL publik

### Opsi 3 — GitHub Pages
1. Fork repo ini
2. Pergi ke **Settings → Pages**
3. Source: branch `main`, folder `/ (root)`
4. Simpan → situs live dalam ~1 menit

---

## 🗂️ Struktur Repo

```
surat-lamaran-generator/
├── index.html       # Landing Page
├── app.html         # Aplikasi utama
├── README.md        # Dokumentasi ini
└── LICENSE          # MIT License
```

---

## 🤝 Kontribusi

Kontribusi sangat disambut! Berikut cara ikut berkontribusi:

1. **Fork** repo ini
2. Buat branch baru: `git checkout -b fitur/nama-fitur`
3. Commit perubahan: `git commit -m "feat: tambah fitur X"`
4. Push ke branch: `git push origin fitur/nama-fitur`
5. Buat **Pull Request** ke branch `main`

### Ide fitur yang bisa dikerjakan
- [ ] Pilihan template surat (formal, semi-formal)
- [ ] Export ke format `.docx`
- [ ] Kop surat dengan logo / foto
- [ ] Simpan & load data form (localStorage)
- [ ] Tambah bahasa Inggris (cover letter)
- [ ] Pratinjau mobile dalam aplikasi

Kalau punya ide lain, silakan buka [Issue](../../issues) baru!

---

## 📝 Format Pesan Commit

Gunakan format [Conventional Commits](https://www.conventionalcommits.org/):

| Prefix | Kapan dipakai |
|--------|--------------|
| `feat:` | Fitur baru |
| `fix:` | Perbaikan bug |
| `style:` | Perubahan tampilan / CSS |
| `docs:` | Update dokumentasi |
| `refactor:` | Refactor kode |

---

## 📄 Lisensi

Proyek ini menggunakan lisensi [MIT](LICENSE) — bebas digunakan, dimodifikasi, dan didistribusikan.

---

Dibuat dengan ❤️ — cocok untuk mahasiswa, fresh graduate, dan siapa saja yang butuh surat lamaran cepat.
