# Repositori Praktikum Data Mining

Repositori ini memuat materi, implementasi kode, latihan mandiri (*hands-on*), serta tugas praktikum untuk mata kuliah **Data Mining** (Semester 3) pada Program Studi Rekayasa Kecerdasan Artifisial, Departemen Teknik Informatika, Institut Teknologi Sepuluh Nopember (ITS).

---

## Identitas Mahasiswa

| Informasi | Detail |
| :--- | :--- |
| **Nama** | Rasya Arya Ramadhan |
| **NRP** | 5054251019 |
| **Program Studi** | Rekayasa Kecerdasan Artifisial |
| **Departemen** | Teknik Informatika |
| **Fakultas** | Fakultas Teknologi Elektro dan Informatika Cerdas (FTEIC) |
| **Institusi** | Institut Teknologi Sepuluh Nopember (ITS) |
| **Mata Kuliah** | Data Mining (Semester 3) |

---

## Capaian Pembelajaran Mata Kuliah (CPMK)

Praktikum ini dirancang untuk mencapai beberapa kompetensi utama dalam bidang penambangan data:

1. **Eksplorasi dan Praproses Data**: Mampu menjelaskan tahapan penambangan data, karakteristik data, eksplorasi data, dan teknik praproses data beserta penerapannya pada kasus nyata.
2. **Klasifikasi dan Penanganan Ketidakseimbangan Kelas**: Mampu menerapkan teknik penanganan masalah ketidakseimbangan kelas (*class imbalance*) dan metode klasifikasi berbasis *ensemble*.
3. **Pola Asosiasi dan Sekuensial**: Mampu menganalisis dan mengimplementasikan algoritma *association rule mining* serta analisis pola berurutan (*sequential pattern analysis*).
4. **Pengelompokan (Clustering)**: Mampu menerapkan berbagai metode pengelompokan data tanpa label untuk menemukan pola tersembunyi.
5. **Deteksi Anomali**: Mampu menjelaskan konsep dan mengaplikasikan teknik pendeteksian data anomali (*outlier detection*).

---

## Prasyarat Lingkungan

- **Python**: Versi 3.10 atau yang lebih baru
- **Jupyter Notebook / JupyterLab / Visual Studio Code**

Seluruh dependensi pustaka Python dikelola secara dinamis melalui berkas `requirements.txt` dan akan diperbarui seiring penambahan topik praktikum.

---

## Panduan Instalasi dan Menjalankan Proyek

Ikuti langkah-langkah berikut untuk mengonfigurasi dan menjalankan lingkungan kerja secara lokal:

### 1. Kloning Repositori
```bash
git clone https://github.com/rasyaarya/Rasya-Arya_Data-Mining26.git
cd Rasya-Arya_Data-Mining26
```

### 2. Konfigurasi Lingkungan Virtual (Virtual Environment)
Gunakan lingkungan virtual terisolasi untuk mengelola dependensi proyek.

**Pada Windows (PowerShell / Command Prompt):**
```powershell
python -m venv .venv
.\.venv\Scripts\activate
```

**Pada Linux / macOS:**
```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Instalasi Dependensi
Pasang seluruh dependensi yang tercantum pada berkas `requirements.txt`:
```bash
pip install --upgrade pip
pip install -r requirements.txt
```

### 4. Registrasi Kernel ke Jupyter (Opsional)
Daftarkan kernel lingkungan virtual agar dapat dipilih langsung pada Jupyter Notebook:
```bash
python -m ipykernel install --user --name=dm-env --display-name="Python (Data Mining)"
```

### 5. Menjalankan Notebook
Jalankan antarmuka Jupyter:
```bash
jupyter notebook
```
atau buka direktori kerja di Visual Studio Code, lalu pilih kernel `.venv` yang telah dibuat.
