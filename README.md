# 🌿 MPI Rantai Makanan — IPAS Kelas 4 SD

> **Media Pembelajaran Interaktif** yang dikembangkan sebagai **Project LK 3** dalam kegiatan **BIMTEK Digitalisasi Pembelajaran**.
> Mata Pelajaran **IPAS** · Materi **Rantai Makanan** · Kelas **4 SD**

![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-7-646CFF?logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-4-06B6D4?logo=tailwindcss&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer%20Motion-11-0055FF?logo=framer&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

---


## 📖 Tentang Media

Media Pembelajaran Interaktif (MPI) ini dirancang untuk membantu siswa **Kelas 4 SD** memahami konsep **Rantai Makanan** dalam mata pelajaran **IPAS** (Ilmu Pengetahuan Alam dan Sosial). Disusun mengikuti prinsip Kurikulum Merdeka dengan pendekatan **belajar aktif, menyenangkan, dan bermakna**.

### 🎯 Capaian Pembelajaran

Peserta didik mampu:
1. Mengidentifikasi komponen-komponen dalam rantai makanan.
2. Menjelaskan peran **produsen, konsumen, dan pengurai** dalam ekosistem.
3. Menganalisis aliran energi pada rantai makanan.
4. Memprediksi dampak perubahan populasi terhadap keseimbangan ekosistem.

---

## 🧭 Struktur Menu

Media terdiri dari **5 menu utama**:

| Menu | Konten |
|---|---|
| **🏠 Beranda** | Judul materi, identitas penyusun, capaian pembelajaran, navigasi ke seluruh menu |
| **📖 Teori Dasar** | Konsep rantai makanan, komponen ekosistem, aliran energi (Hukum 10%), jaring-jaring makanan, piramida ekologi, keseimbangan ekosistem — dengan **simulasi aliran energi interaktif** |
| **📝 LKPD** | Lembar Kerja Peserta Didik interaktif: tujuan pembelajaran, alat & bahan, langkah kerja, tabel pengamatan, 5 pertanyaan esai + kesimpulan, dilengkapi tombol **Simpan sebagai PDF** |
| **🎮 Quiz** | **Game 1**: Drag & Drop susun rantai makanan · **Game 2**: Cross the Words (word search) — keduanya memiliki tombol **Reset** |
| **🎯 Evaluasi** | Petunjuk pengerjaan → **10 soal pilihan ganda (6 poin)** + **5 soal esai (8 poin)** → skor otomatis (maks 100) → **tidak dapat diulang** |

### 🎵 Backsound

Media dilengkapi **musik latar (backsound)** dengan perilaku:
- **Autoplay** (dengan fallback interaksi pertama jika diblokir browser)
- **Loop otomatis**
- **Pause / Play / Volume / Mute** dapat dikontrol
- Preferensi tersimpan di `localStorage`

---

## 🛠️ Teknologi

| Lapisan | Teknologi |
|---|---|
| **Framework** | React 19 + Vite 7 |
| **Bahasa** | TypeScript (strict mode) |
| **Styling** | Tailwind CSS v4 (`@tailwindcss/vite`) |
| **Animasi** | Framer Motion 11 |
| **Ikon** | React Icons (Font Awesome 5 + Game Icons) |
| **Build** | Vite |
| **Deploy** | Vercel (static) |

---

## 🚀 Cara Menjalankan

### Prasyarat
- **Node.js ≥ 20**
- **npm ≥ 10**

### Instalasi

```bash
# 1. Clone repository
git clone <URL_REPO_KAMU> mpi-rantai-makanan
cd mpi-rantai-makanan

# 2. Install dependensi
npm install

# 3. Jalankan development server
npm run dev