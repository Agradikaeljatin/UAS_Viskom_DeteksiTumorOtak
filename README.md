# 📄 UAS_Viskom_BrainTumorDetection

**OpenCV & CNN Python Jupyter Project**

Sistem analisis citra medis berbasis *Computer Vision* dan *Convolutional Neural Network* (CNN) untuk deteksi tumor otak dari citra MRI.

**Demo • Fitur • Instalasi • Penggunaan • Teknologi**

**Nama:** M. Agradika Ridhal Eljatin
**NPM:** *2208107010020*

---

## 📖 Deskripsi Proyek

Brain Tumor Detection System merupakan proyek Computer Vision yang dirancang untuk membantu analisis awal citra MRI otak. Sistem ini menggabungkan teknik pengolahan citra klasik dan metode deep learning berbasis CNN untuk mendeteksi serta mengklasifikasikan citra MRI otak menjadi **normal** atau **mengandung tumor**.

Proyek ini dikembangkan sebagai proyek akhir mata kuliah **Visi Komputer**, dengan tujuan mengintegrasikan seluruh materi pembelajaran dari pertemuan awal hingga lanjutan ke dalam satu sistem terpadu berbasis Jupyter Notebook.

---

## 🎯 Masalah yang Diselesaikan

| Masalah                             | Solusi                                  |
| ----------------------------------- | --------------------------------------- |
| 🧠 Kompleksitas citra MRI           | Pra-pemrosesan & normalisasi citra      |
| 🔍 Sulitnya identifikasi area tumor | Edge detection & segmentasi             |
| 📊 Variasi bentuk tumor             | Boundary detection & feature extraction |
| 🤖 Klasifikasi manual memakan waktu | CNN-based classification                |
| 👁️ Interpretasi visual terbatas    | Visualisasi hasil analisis              |

---

## ✨ Fitur Utama

### 🔍 Pengolahan Citra MRI

✅ Load dan normalisasi citra MRI
✅ Noise reduction dan image enhancement
✅ Deteksi tepi menggunakan Canny
✅ Boundary detection dengan contour
✅ Segmentasi area otak dan tumor

### 🧠 Analisis & Klasifikasi

✅ Ekstraksi fitur citra
✅ Klasifikasi citra MRI menggunakan CNN
✅ Prediksi citra **Normal / Tumor**
✅ Confidence score hasil klasifikasi

### 📊 Visualisasi

✅ Tampilan citra MRI asli
✅ Visualisasi hasil preprocessing
✅ Penandaan area tumor
✅ Grafik akurasi dan loss CNN

---

## 🎓 Integrasi Materi Kuliah

Proyek ini mengimplementasikan materi Visi Komputer (Pertemuan 1–15):

| Pertemuan | Materi             | Implementasi di Proyek |
| --------- | ------------------ | ---------------------- |
| P1        | Pengenalan CV      | Analisis citra MRI     |
| P2        | Math Review        | Normalisasi pixel      |
| P3        | Filtering          | Noise reduction        |
| P4        | Edge Detection     | Canny                  |
| P5        | Boundary Detection | Contour detection      |
| P6        | Feature Extraction | ORB / feature analysis |
| P7–8      | Segmentation       | Threshold & morphology |
| P10       | Object Tracking    | Perbandingan slice MRI |
| P11       | Object Recognition | CNN                    |
| P13       | Stereo Vision      | Simulasi depth         |
| P14       | Augmented Reality  | Overlay hasil          |
| P15       | CNN                | Klasifikasi tumor      |

---

## 🛠️ Teknologi

### Core Libraries

| Library            | Fungsi                    |
| ------------------ | ------------------------- |
| OpenCV             | Image processing          |
| NumPy              | Operasi numerik           |
| Matplotlib         | Visualisasi               |
| TensorFlow / Keras | CNN implementation        |
| scikit-image       | Image processing tambahan |

### Teknik Computer Vision

* Image preprocessing & normalization
* Edge & boundary detection
* Image segmentation
* Feature extraction
* CNN-based classification

---

## 📥 Instalasi

### Prasyarat

* Python 3.8+
* pip
* Jupyter Notebook / Google Colab

### Langkah Instalasi

```bash
pip install opencv-python numpy matplotlib tensorflow scikit-image
```

Jalankan notebook:

```bash
jupyter notebook brain_tumor_detection.ipynb
```

---

## 🚀 Cara Penggunaan

### 1. Persiapan Data

* Siapkan citra MRI otak format JPG/PNG
* Kelompokkan data ke dalam folder:

```
dataset/
├── mri1/
└── mri2/
```

### 2. Jalankan Notebook

* Buka file `.ipynb`
* Jalankan cell secara berurutan

### 3. Proses Sistem

Pipeline otomatis:

```
MRI Image
   ↓
Preprocessing
   ↓
Edge Detection
   ↓
Segmentation
   ↓
Feature Extraction
   ↓
CNN Classification
   ↓
Output & Visualization
```

### 4. Output

* Label klasifikasi (Normal / Tumor)
* Visualisasi area tumor
* Grafik performa model CNN

---

## 📈 Hasil & Evaluasi

### Metrics

| Metric          | Hasil                      |
| --------------- | -------------------------- |
| Accuracy        | Tinggi (dataset dependent) |
| Processing Time | Cepat                      |
| Visualization   | Informatif                 |

### Kelebihan

✅ Sistem otomatis
✅ Integrasi materi lengkap
✅ Visualisasi jelas
✅ Cocok untuk pembelajaran

### Limitasi

⚠️ Bergantung kualitas citra MRI
⚠️ Dataset terbatas
⚠️ Belum untuk diagnosis klinis

---

## 🗂️ Struktur Proyek

```
UAS/
├── brain_tumor_detection.ipynb
├── README.md
├── dataset/
│   ├── mr1/
│   └── mr2/
├── output/
└── requirements.txt
```

---

## 🔮 Pengembangan Selanjutnya

* Multi-class tumor classification
* Integrasi segmentation deep learning
* Web-based medical dashboard
* Dataset MRI yang lebih besar

---

## 📚 Referensi

* Gonzalez & Woods – *Digital Image Processing*
* Goodfellow et al. – *Deep Learning*
* OpenCV Documentation
* Kaggle Brain MRI Dataset

---

## 👨‍💻 Author

Proyek Akhir Mata Kuliah **Visi Komputer**
Semester 7 – 2024/2025

---

## 📝 License

Proyek ini dibuat untuk keperluan akademik sebagai bagian dari FINAL PROJECT mata kuliah Visi Komputer.

