# Pemantauan Risiko & Kinerja EPI 2026 — PLN BBN

Repository ini menayangkan **dashboard terkunci** pemantauan risiko & kinerja (EPI 2026) dan menautkan file kerja datanya.

## 🔐 Dashboard

👉 **[Buka Dashboard Risiko & Kinerja](https://risk-bbn.github.io/Risk-PLNBBN-v1/)**

- Isi dashboard **terenkripsi (AES-256)**; halaman akan meminta password saat dibuka.
- Password dipegang pengelola risiko dan dibagikan terpisah dari link ini — bukan lewat repo.

## 📊 File Kerja Aktif (Google Sheet)

👉 **[Google Sheet Pemantauan EPI 2026](https://docs.google.com/spreadsheets/d/1jTHW55eL54RDpUJO64cdnjBoDoglMMQ6PfZlnWX8cNY/edit?usp=sharing)**

- Satu-satunya tempat pengisian data. Akses dibatasi — klik **"Minta akses"** bila diperlukan.
- Setelan lokal spreadsheet: **Indonesia** (File → Setelan).

## 🔁 Alur Pembaruan Bulanan

1. Isi data bulan berjalan di Google Sheet.
2. Buka alat **Pembuat Dashboard Terkunci** (disimpan pengelola — **tidak** di repo ini) → unduh Excel terbaru → isi Executive Summary → buat `index.html` terkunci.
3. Ganti `index.html` di repo ini (**Add file → Upload files → Commit**). Website berubah 1–2 menit kemudian.

## 🗂️ Arsip per Triwulan

Snapshot `.xlsx` final tiap periode disimpan di folder `arsip/`.

| Periode | File | Tanggal Tutup |
|---|---|---|
| TW I 2026 | – | – |
| TW II 2026 | – | – |
| TW III 2026 | – | – |
| TW IV 2026 | – | – |

## 📌 Catatan

- `index.html` berisi data terenkripsi dan memang untuk publik; **jangan** meng-commit file Excel mentah atau alat pembuat ke repo ini.
- PIC: Divisi Manajemen Risiko PLN BBN *(sesuaikan)*.
