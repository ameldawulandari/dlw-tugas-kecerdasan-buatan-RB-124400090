# Studi Ablasi RNN, LSTM, GRU vs ANN untuk Prediksi Trafik Seluler Milan

Tugas Workshop Deep Learning — Teknik Telekomunikasi ITERA.

<!-- Ganti seluruh isian bertanda [ ... ] di bawah. Hapus komentar ini. -->

## Kelompok

| Peran | Nama | NIM |
|---|---|---|
| Ketua | [Nama Lengkap] | [NIM] |
| Anggota | [Nama Lengkap] | [NIM] |
| Anggota | [Nama Lengkap] | [NIM] |

- **Kelas:** [RB]
- **Lokasi kelompok:** [0] — [nama lokasi] (Stazione Centrale)
- **Laporan:** [`laporan-latex/main.pdf`]

## Cara Menjalankan

```bash
uv sync
uv run jupyter lab
```

Buka `tugas_ablasi.ipynb`, isi `LOKASI_KELOMPOK`, lalu jalankan semua sel. Semua run tercatat di `hasil/ablasi.csv`.

Perangkat yang kami pakai: [contoh: laptop CPU Intel i5 / Google Colab T4], total waktu training: [x] menit.

## Ringkasan Hasil

[2–4 kalimat temuan utama, beserta angka test MAE terbaik per model.]

## Struktur

```
tugas_ablasi.ipynb      notebook eksperimen (di-commit beserta output)
data/                   Berisi dataset trafik seluler Milano
hasil/                  Berisi grafik hasil eksperimen ablasi dan grafik konvergensi
laporan-latex/ atau laporan-typst/   file sumber laTeX untuk penyusunan laporan format IEEE
starter/                Skrip utama pelatihan dan evaluasi model 
```

## Data

Telecom Italia Big Data Challenge (Barlacchi dkk., 2015, *Scientific Data*, lisensi ODbL), versi per jam dari Zhang dkk. (INFOCOM 2021). Disiapkan oleh pengajar di repo [mctosima/dl-workshop](https://github.com/mctosima/dl-workshop).
