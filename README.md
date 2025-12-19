# Dashboard RUP 2025 - Production Ready

📊 Dashboard interaktif untuk analisis dan monitoring Rencana Umum Pengadaan 2025

## Features

- **Interactive Filtering**: Filter data berdasarkan metode, jenis, satuan kerja, dan range pagu
- **Multi-tab Analysis**: Overview, Top Satker, Trend Analysis, dan Data Export
- **Real-time Charts**: Visualisasi interaktif menggunakan Plotly
- **Data Export**: Export data ke CSV dengan berbagai format
- **Performance Optimized**: Caching untuk loading data yang lebih cepat
- **Responsive Design**: Tampilan yang optimal di berbagai ukuran layar

## Tech Stack

- **Streamlit**: Web framework untuk dashboard
- **Pandas**: Data manipulation dan analysis
- **Plotly**: Interactive visualization
- **Python 3.x**

## Installation

1. Clone repository:
```bash
git clone <repository-url>
cd bootcampbsi
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Prepare data:
   - Pastikan file `data/rup2025.parquet` tersedia

4. Run aplikasi:
```bash
streamlit run streamlit_app.py
```

## Usage

Dashboard akan terbuka di browser dengan URL `http://localhost:8501`

### Sidebar Filters:
- **Metode Pengadaan**: Filter berdasarkan metode (Tender, E-Purchasing, dll)
- **Jenis Pengadaan**: Filter berdasarkan jenis pengadaan
- **Satuan Kerja**: Pilih satuan kerja tertentu
- **Range Pagu**: Slider untuk filter range nilai pagu
- **Status Khusus**: Filter PDN, UKM, dan PRADIPA

### Dashboard Tabs:
1. **Overview & Distribution**: Distribusi metode, jenis, dan status pengadaan
2. **Top Satker**: Analisis satuan kerja berdasarkan jumlah paket dan total pagu
3. **Trend Analysis**: Tren pengumuman paket per bulan
4. **Data Table & Export**: Tabel data lengkap dengan fitur export

## Deploy to Streamlit Cloud

1. Push code ke GitHub
2. Buka [share.streamlit.io](https://share.streamlit.io)
3. Connect repository Anda
4. Deploy!

## Data Source

Data bersumber dari Sistem Informasi Rencana Umum Pengadaan (SIRUP)

## License

Project ini dibuat untuk keperluan pembelajaran dalam Bootcamp Data Science.
