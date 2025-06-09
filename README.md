
# Analisis Spasial Bencana Banjir DKI Jakarta  
**Ujian Akhir Semester - Sistem Informasi Geografis**

## 📌 Deskripsi Project
Project ini bertujuan untuk menganalisis potensi dan dampak bencana banjir di wilayah DKI Jakarta menggunakan pendekatan Sistem Informasi Geografis (SIG). Analisis dilakukan dengan memanfaatkan data curah hujan, kejadian banjir, elevasi (DEM), serta data administrasi wilayah dan kelas lereng.

## 🗂️ Struktur Data
Beberapa file penting yang digunakan:

- **Data Curah Hujan & Kejadian Banjir**
  - `Data Curah Hujan Dan Hari Hujan Di DKI Jakarta Menurut.xlsx`
  - `Data Kejadian Bencana Banjir Tahun 2024.xlsx`

- **Data Elevasi (DEM)**
  - `DEM SRTM 30M DKI JAKARTA.tif` dan file pendukung (`.tfw`, `.aux`, `.ovr`, dll.)

- **Shapefile Administratif**
  - `Kecamatan DKI Jakarta.shp` dan file pendukung (`.dbf`, `.shx`, `.prj`, dll.)

- **Kelas Lereng**
  - `Kelas_Lereng_DKI_Jakarta.shp` dan file pendukung lainnya

## 📊 Tools & Teknologi
- **Python** (di Google Colab)
- **Library yang digunakan**:
  - `geopandas`
  - `matplotlib`
  - `rasterio`
  - `contextily`
  - `pandas`
  - `shapely`

## ⚙️ Fitur Analisis
1. **Visualisasi data curah hujan dan kejadian banjir**
2. **Overlay antara data DEM dan wilayah Kecamatan**
3. **Identifikasi daerah rawan banjir berdasarkan elevasi dan curah hujan**
4. **Klasifikasi kelas lereng untuk memahami kerentanan wilayah**
5. **Peta hasil analisis spasial** (visualisasi dalam notebook)

## 📍 Wilayah Studi
Provinsi **DKI Jakarta**, mencakup seluruh Kecamatan DKI Jakarta.

## 📁 Cara Menjalankan
1. Upload file `.ipynb` ke Google Colab
2. Upload seluruh file pendukung ke session Colab
3. Jalankan setiap sel notebook secara berurutan
4. Hasil analisis dan visualisasi akan tampil langsung di dalam notebook

## 👨‍💻 Penulis
- **Nama:** Fahim Ahmad Saputra
- **NPM:** G1A022037
- **Mata Kuliah:** Sistem Informasi Geografis

