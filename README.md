# Proyek-Analisis-Data-Air-Quality-di-Shunyi 

## Dashboard
Link deploy https://4czrj8mwxgfpogb6wllcar.streamlit.app/

## Tetang Proyek
Proyek ini dibuat untuk modul "Belajar Analisis Data dengan Python" dari Dicoding. Saya berfokus pada analisis data perubahan titik embun, kecepatan udara dan hujan di Shunyi. Tujuannya adalah untuk mengungkap dari parameter tersebut.

## Sumber Data
Dataset yang digunakan dalam proyek ini mencakup pengukuran kualitas udara di Shunyi, sumber dataset diambil dari GitHub.(https://raw.githubusercontent.com/marceloreis/HTI/master/PRSA_Data_20130301-20170228/PRSA_Data_Shunyi_20130301-20170228.csv)

## Cara Membuat Dashboard
Untuk membuat Analisis Dashboard Air Quality, ikuti langkah berikut :

### Setup Environment
1. **Buat dan Aktifkan Python Environment**:
   - Jika mengunakkan conda (ensure [Conda](https://docs.conda.io/en/latest/) is installed):
     ```
     conda create --name airquality-ds python=3.9
     conda activate airquality-ds
     ```
   - Jika mengunakkan venv (standard Python environment tool):
     ```
     python -m venv airquality-ds
     source airquality-ds/bin/activate  # On Windows use `airquality-ds\Scripts\activate`
     ```

2. **Unduh Packages**:
   - Berikut Packages yang diperlukan untuk menjalankan analisis dashboard :
     ```
     pip install pandas matplotlib seaborn streamlit
     ```

     atau bisa dengan cara
     ```
     pip install -r requirements.txt
     ```
### Run Streamlit App

1. **Arahkan ke Direktori Projek** dimana `dashboard.py` di simpan.

2. **Run Streamlit App**:
    ```
    streamlit run dashboard.py
    ```

### File Lain

- Kumpulan data yang digunakan untuk analisis ini disertakan dalam repositori proyek.
- Notebook Python terperinci (`Proyek_Analisis_Data.ipynb`) yang berisi analisis dan visualisasi data juga disediakan.
---
### P.S.
Karena Dicoding merekomendasikan pembuatan struktur folder yang baik dan rapi, seperti `dashboard.py` di folder `dashboard`, maka penerapan Aplikasi Streamlit terpengaruh.

Itu sebabnya saya juga meletakkan `requirements.txt` di folder `dashboard`.

---
## Tentang Saya
- **Nama**: Teresia Yunita Putriani N
- **Email**: 6162001042@student.unpar.ac.id
- **ID Dicoding**: yunita30

