# Analysis efisiensi pendidikan di wilayah Kalimantan (2021–2024)

## Ringkasan

Proyek ini mengeksplorasi kondisi pendidikan dari tingkat SD hingga SMA/SMK di Kalimantan, Indonesia, dari tahun 2021 - 2024. Dengan menggunakan data publik dari Kemendikbud, kami menganalisis tren putus sekolah, rasio siswa-guru, dan distribusi siswa terhadap fasilitas pendidikan di lima provinsi Kalimantan.

## Permasalahan

Meskipun secara nasional pendidikan Indonesia terus berkembang, daerah terpencil seperti Kalimantan masih menghadapi ketimpangan dalam akses dan kualitas pendidikan. Angka putus sekolah yang tinggi, kekurangan ruang kelas, dan beban kerja guru yang tinggi mencerminkan permasalahan sistemik. Proyek ini bertujuan untuk mengidentifikasi pola dan hambatan utama untuk mendukung pengambilan keputusan kebijakan dan distribusi sumber daya.

## Dataset

* **Sumber**: [Kemendikbud](https://data.go.id/)
* **Tahun cakupan**: 2021–2024
* **Jenjang**: SD, SMP, SMA/SMK
* **Wilayah**: Kalimantan Barat, Kalimantan Timur, Kalimantan Tengah, Kalimantan Selatan, Kalimantan Utara

## Rumusan masalah

* 1. Berapa jumlah siswa dan guru per jenjang dan tahun?
* 2. Berapa rasio siswa terhadap guru?
* 3. Bagaimana tren putus sekolah dari tahun ke tahun ?
* 4. Bagaimana rasio fasilitas (siswa per rombel/ ruang kelas) ?

## Insights

* **Tren Putus Sekolah**: Kalimantan Barat menunjukkan lonjakan tertinggi pada angka putus sekolah di tahun 2022, terutama di tingkat SD
* **Kekurangan Guru**: Beberapa provinsi memiliki rasio lebih dari 25 siswa per guru, melampaui standar nasional ideal yaitu 20:1([UNESCO, 2023](https://uis.unesco.org/)).
* **Rasio Fasilitas**: Kekurangan ruang kelas dan rombel paling parah terjadi di Kalimantan Utara dan Kalimantan Tengah, yang berkontribusi pada kondisi ruang belajar yang terlalu padat.

## Visualisasi

* Tren putus sekolah dari tahun ke tahun
* Diagram batang rasio siswa-guru per provinsi
* Scatter plot perbandingan rasio fasilitas dan angka putus sekolah

## Struktur folder

```
education-analysis-kalimantan/
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
│   └── kalimantan-education-notebook.ipynb
├── images/
│   └── *.png
├── README.md
├── requirements.txt
```

## Saran untuk kedepan

* Membangun model prediktif untuk risiko putus sekolah
* Menggabungkan indikator sosial ekonomi (contoh: tingkat kemiskinan)
* Melakukan prediksi tren menggunakan time series

## File pendukung
* Presentasi : [PPT analysis](https://docs.google.com/presentation/d/11Mpj3KCsQFXLyUWrQPRuGPorq-0WmNeL/edit?usp=sharing&ouid=112814808339704803161&rtpof=true&sd=true)

## Credits

* Data: Kemendikbud (data.go.id)
* Tools: Python (Pandas, Matplotlib, Seaborn)

