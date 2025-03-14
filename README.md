# Analisis Bike Sharing Dataset

## Ringkasan Analisis
Dataset ini berisi data penyewaan sepeda selama 2011-2012. Analisis menunjukkan bahwa:
- **Peminjaman tertinggi** terjadi pada musim gugur dan saat cuaca cerah.
- **Pola harian** menunjukkan lonjakan penyewaan pada jam 08.00 dan 17.00.
- **Hari kerja** lebih tinggi jumlah penyewa dibanding akhir pekan.
- **Pelanggan terdaftar** lebih mendominasi dibanding penyewa kasual.

## Kesimpulan
- Fokus promosi pada jam sibuk dan musim dengan peminjaman rendah.
- Menarik lebih banyak pelanggan dengan promo khusus akhir pekan.

---

# Dashboard Bike Sharing

## Cara Menjalankan Dashboard

### 1. Aktifkan Virtual Environment (Opsional)
```
python -m venv env
source env/bin/activate  # Untuk macOS/Linux
env\Scripts\activate    # Untuk Windows
```

### 2. Instalasi Dependensi 
```
pip install -r requirements.txt
```

### 3. Menjalankan Dashboard
```
streamlit run dashboard.py
```

### 4. Deploy ke Streamlit Community Cloud
1. Buat repository di GitHub dengan nama **Belajar Analisis Data dengan Python**.
2. Push kode proyek ke repository tersebut.
3. Buka [Streamlit Community Cloud](https://share.streamlit.io/), login, dan hubungkan dengan repository.
4. Deploy dan jalankan dashboard secara online.

---

*Dashboard ini dibuat untuk menganalisis tren peminjaman sepeda dan membantu pengambilan keputusan bisnis berdasarkan data.*
