# Ekstraksi Fitur Citra Digital untuk Klasifikasi Bensin Asli dan Oplosan  

**Program ini mengimplementasikan metode analisis tekstur dan pola lokal untuk mendeteksi keaslian bensin berdasarkan citra digital.**  

---

## **Deskripsi**  
Program ini dirancang untuk mengekstraksi fitur citra digital menggunakan tiga metode utama: **Gray Level Co-occurrence Matrix (GLCM)**, **Local Binary Patterns (LBP)**, dan **Completed Local Binary Patterns (Co-LBP)**. Dengan memanfaatkan analisis tekstur dan pola lokal, program ini bertujuan untuk mengidentifikasi serta membedakan nilai RGB dari sampel bensin asli dan oplosan, membantu meningkatkan akurasi dalam proses klasifikasi.  

---

## **Fitur Utama**  

1. **Ekstraksi GLCM:**  
   - Menghitung matriks co-occurrence berdasarkan tingkat keabuan (grayscale).  
   - Mengidentifikasi pola tekstur dalam citra melalui fitur seperti **kontras**, **homogenitas**, **energi**, dan **korelasi**.  

2. **Ekstraksi LBP:**  
   - Mengonversi citra RGB menjadi pola biner untuk mendeteksi fitur lokal.  
   - Cocok untuk analisis tekstur mikro pada citra.  

3. **Ekstraksi Co-LBP:**  
   - Menghasilkan fitur yang lebih kaya dibandingkan dengan LBP tradisional.  
   - Menggunakan pola komplementer untuk meningkatkan akurasi dalam analisis tekstur.  

---

## **Tujuan Program**  
Program ini dirancang untuk:  
- Mendukung penelitian di bidang **pengolahan citra digital**, khususnya dalam mendeteksi keaslian bahan bakar bensin.  
- Mengidentifikasi karakteristik tekstur dan pola lokal antara bensin asli dan oplosan melalui analisis nilai RGB.  
- Meningkatkan akurasi klasifikasi dengan memanfaatkan kombinasi metode ekstraksi fitur yang komprehensif.  

---

## **Manfaat**  
- Mempermudah identifikasi bensin asli dan oplosan secara digital, yang sebelumnya hanya dapat dilakukan dengan uji laboratorium.  
- Menyediakan fitur analisis tekstur yang fleksibel dan akurat untuk berbagai aplikasi dalam pengolahan citra.  

---

## **Teknologi dan Metode yang Digunakan**  
- **GLCM (Gray Level Co-occurrence Matrix):** Analisis pola tekstur berbasis matriks co-occurrence.  
- **LBP (Local Binary Patterns):** Deteksi pola lokal melalui representasi biner.  
- **Co-LBP (Completed Local Binary Patterns):** Ekstraksi fitur dengan mempertimbangkan pola komplementer untuk hasil yang lebih detail.  

---

## **Cara Kerja Singkat**  
1. Masukkan citra digital dari sampel bensin asli dan oplosan.  
2. Ekstraksi fitur dilakukan menggunakan GLCM, LBP, dan Co-LBP.  
3. Data fitur yang diekstraksi dianalisis untuk membedakan karakteristik antara bensin asli dan oplosan.  
4. Hasil analisis digunakan untuk klasifikasi dan validasi akurasi.  

---  

Program ini memberikan solusi berbasis teknologi untuk mendukung analisis dan klasifikasi keaslian bensin dengan pendekatan inovatif dalam pengolahan citra digital.  
