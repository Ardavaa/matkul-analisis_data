# Workspace Mata Kuliah Analisis Data

Repositori ini merupakan workspace resmi untuk mata kuliah **Analisis Data** (Semester 4). Seluruh file di dalamnya digunakan sebagai bahan praktikum, tugas, dan pembelajaran konsep statistik inferensial serta analisis data menggunakan Python. Workspace ini dirancang untuk mendukung pemahaman teori melalui implementasi langsung pada data nyata dan simulasi.

## 📚 Tentang Mata Kuliah

Mata kuliah **Analisis Data** membahas berbagai teknik statistik untuk menganalisis, menginterpretasi, dan menarik kesimpulan dari data. Melalui workspace ini, mahasiswa dapat:
- Mempelajari konsep dasar dan lanjutan statistik inferensial
- Mengaplikasikan teori statistik pada data riil
- Mengembangkan kemampuan analisis data dengan Python dan Jupyter Notebook
- Melatih keterampilan interpretasi hasil analisis statistik

## 📁 Struktur File Workspace

### 🔧 Notebook Utama

| File | Deskripsi |
|------|-----------|
| `0_latsol.ipynb` | **Latihan Soal Penaksiran Parameter** - Contoh soal dan solusi untuk selang kepercayaan |
| `1_penaksiran_parameter1.ipynb` | **Penaksiran Parameter 1 Populasi** - Selang kepercayaan untuk mean populasi |
| `2_penaksiran_parameter2.ipynb` | **Penaksiran Parameter 2 Populasi** - Perbandingan mean dua populasi |
| `3_penaksiran_parameter_proporsi.ipynb` | **Penaksiran Parameter Proporsi** - Selang kepercayaan untuk proporsi |
| `4_uji_hipotesis_1.ipynb` | **Uji Hipotesis** - Pengujian hipotesis statistik |
| `5_anova.ipynb` | **ANOVA One-Way** - Analisis varians satu arah |
| `6_anova_two_way.ipynb` | **ANOVA Two-Way** - Analisis varians dua arah |
| `7_two_way_anova.ipynb` | **Two-Way ANOVA** - Implementasi lanjutan ANOVA dua arah |
| `8_regresi-linear-berganda.ipynb` | **Regresi Linear Berganda** - Analisis regresi dengan multiple variabel |

### 📊 Data

| File | Deskripsi |
|------|-----------|
| `Kel 4 Data PPKS 1(2018).csv` | Dataset PPKS (Penyandang Masalah Kesejahteraan Sosial) 2018 dengan 35 observasi dan 6 variabel |

## 🎯 Topik yang Dipelajari

1. **Penaksiran Parameter (Confidence Intervals)**
2. **Uji Hipotesis (Hypothesis Testing)**
3. **Analisis Varians (ANOVA)**
4. **Regresi Linear Berganda**

Setiap topik dilengkapi dengan contoh soal, pembahasan, dan implementasi kode Python.

## 🚀 Cara Menggunakan Workspace

### Prasyarat
```bash
pip install numpy scipy pandas matplotlib seaborn jupyter
```

### Menjalankan Notebook
1. Clone repositori ini
2. Buka terminal di direktori project
3. Jalankan Jupyter Notebook:
```bash
jupyter notebook
```
4. Pilih notebook sesuai topik yang ingin dipelajari

### Urutan Pembelajaran yang Disarankan
1. `1_penaksiran_parameter1.ipynb` - Konsep dasar selang kepercayaan
2. `2_penaksiran_parameter2.ipynb` - Perbandingan dua populasi
3. `3_penaksiran_parameter_proporsi.ipynb` - Selang kepercayaan proporsi
4. `4_uji_hipotesis_1.ipynb` - Uji hipotesis
5. `5_anova.ipynb` - ANOVA one-way
6. `6_anova_two_way.ipynb` - ANOVA two-way
7. `8_regresi-linear-berganda.ipynb` - Regresi berganda

## 📈 Contoh Hasil Analisis

- **Regresi Linear Berganda**: Persamaan regresi, analisis korelasi, dan evaluasi model
- **ANOVA**: Uji F untuk membandingkan rata-rata beberapa kelompok
- **Uji Hipotesis**: Interpretasi nilai p dan keputusan statistik

## 📚 Library yang Digunakan
- **NumPy**: Operasi array dan perhitungan numerik
- **SciPy**: Distribusi statistik dan uji hipotesis
- **Pandas**: Manipulasi dan analisis data
- **Matplotlib**: Visualisasi dasar
- **Seaborn**: Visualisasi statistik lanjutan

## 📝 Catatan
- Semua kode dan analisis ditulis untuk tujuan pembelajaran
- Penjelasan dan komentar dalam bahasa Indonesia
- Dataset PPKS 2018 digunakan sebagai studi kasus nyata

---

**Mata Kuliah**: Analisis Data  
**Semester**: 4  
**Fokus**: Statistik Inferensial dan Analisis Data dengan Python
