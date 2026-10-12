# Panduan Deployment GitHub Pages — Dokumen Legal Arshaka Cashier

Direktori ini berisi halaman web statis responsif resmi Arshaka Cashier untuk mematuhi kebijakan Google Play Store (Phase 12A POL-02):
- **`index.html`**: Portal beranda tautan legal.
- **`privacy-policy.html`**: Dokumen asli Kebijakan Privasi (36 pasal diselaraskan).
- **`terms.html`**: Dokumen asli Syarat & Ketentuan (18 pasal diselaraskan).
- **`delete-account.html`**: Sumber daya web eksternal penghapusan akun (*Google Play User Data Account Deletion Requirement*).
- **`style.css`**: Stylesheet responsif ringan tanpa dependensi eksternal.

---

## Informasi Resmi Kontak

- **Email Resmi:** `arshakacashier@gmail.com` (telah dikonfirmasi dan disinkronkan ke seluruh dokumen).

---

## Langkah Publikasi ke GitHub Pages

1. **Commit dan Push folder `docs/` ke repository GitHub Anda** (pada branch `main` atau branch default).
2. Buka repository GitHub di browser: **Settings &rarr; Pages**.
3. Pada bagian **Build and deployment**:
   - **Source**: Pilih `Deploy from a branch`.
   - **Branch**: Pilih `main` (atau branch utama Anda), lalu pada dropdown folder pilih **`/docs`**.
   - Klik **Save**.
4. GitHub Pages akan memproses deployment dalam 1–2 menit.

---

## Format URL Final untuk Google Play Console

Setelah GitHub Pages aktif, URL final akan mengikuti format username dan nama repository Anda:

| Dokumen | URL Format GitHub Pages | Digunakan Untuk |
|:---|:---|:---|
| **Privacy Policy** | `https://<username>.github.io/<repository>/privacy-policy.html` | Google Play Console &rarr; App content &rarr; Privacy Policy |
| **Account Deletion** | `https://<username>.github.io/<repository>/delete-account.html` | Google Play Console &rarr; App content &rarr; Data Safety &rarr; Account Deletion URL |
| **Terms & Conditions** | `https://<username>.github.io/<repository>/terms.html` | Referensi Syarat & Ketentuan Layanan |
| **Legal Hub** | `https://<username>.github.io/<repository>/` | Beranda Portal Legal |

*(Jika menggunakan custom domain, misalnya `legal.arshakacashier.com`, sesuaikan URL di atas).*

---

## Status Kesiapan Rilis

- [x] Email resmi dikonfirmasi: `arshakacashier@gmail.com`.
- [x] Seluruh placeholder email dukungan telah dibersihkan 100% dan digantikan dengan `arshakacashier@gmail.com`.
- [x] Pasal 29 Privacy Policy dan Pasal 15/32 Terms telah diselaraskan dengan implementasi POL-01 (penghapusan permanen langsung seketika).
- [x] Klaim SLA pemrosesan email dan retensi backup telah diaudit dan disesuaikan secara akurat tanpa janji waktu fiktif.
