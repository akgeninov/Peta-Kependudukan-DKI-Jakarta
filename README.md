# Peta Kependudukan DKI Jakarta

## Deskripsi Proyek
**Peta Kependudukan DKI Jakarta** adalah aplikasi web interaktif yang dikembangkan dalam mata kuliah **Sistem Informasi Spasial**.  
Aplikasi ini memvisualisasikan data kependudukan DKI Jakarta secara demografis berdasarkan wilayah administrasi (kelurahan), memungkinkan pengguna untuk menjelajahi informasi seperti jumlah penduduk menurut kelompok usia & jenis kelamin, luas wilayah, dan kepadatan penduduk.  

Peta dasar dibuat menggunakan **QGIS**, lalu diintegrasikan ke dalam aplikasi berbasis web dengan **Leaflet.js** untuk interaktivitas.

## Tech Stack
- **QGIS** → untuk membuat peta dasar wilayah administrasi  
- **HTML5** → struktur halaman web  
- **CSS3** → styling dan tampilan aplikasi  
- **JavaScript** → interaktivitas (Leaflet.js untuk peta interaktif, dropdown, pop-up info, grafik)  

## Data Sumber
Proyek ini menggunakan gabungan dari dua dataset terbuka:  
1. **Dataset Kepadatan Penduduk Jakarta** – berisi informasi nama kota, kecamatan, kelurahan, luas wilayah, dan kepadatan penduduk.  
   Sumber: [Kaggle - Dataset Kepadatan Penduduk Jakarta](https://www.kaggle.com/datasets/elsaesitiya/dataset-kepadatan-penduduk-jakarta)  

2. **Data Jumlah Penduduk Berdasarkan Usia Per Kelurahan DKI Jakarta** – berisi jumlah penduduk berdasarkan kelompok usia dan jenis kelamin per kelurahan.  
   Sumber: [data.go.id - Data Jumlah Penduduk Berdasarkan Usia Per Kelurahan DKI Jakarta](https://data.go.id/dataset/dataset/data-jumlah-penduduk-berdasarkan-usia-per-kelurahan-dki-jakarta)  

## Fitur Utama
- Peta interaktif hasil olahan QGIS yang ditampilkan dengan **Leaflet.js**  
- Dropdown untuk memilih kelurahan yang ingin dilihat datanya  
- Pop-up informasi detail ketika area diklik, menampilkan:  
  - Nama kelurahan & kecamatan  
  - Luas wilayah  
  - Kepadatan penduduk  
  - Jumlah penduduk per kelompok usia & jenis kelamin  
- Grafik demografi (laki-laki, perempuan, total) berdasarkan usia  
- Header dan layout halaman yang rapi untuk navigasi pengguna  
- Layer toggle (lihat berdasarkan kota atau kepadatan penduduk)  

## Installation & Setup
1. Clone repository:
   ```bash
   git clone <URL-repo-anda>
   cd peta-kependudukan-jakarta
2. Unduh dataset:
   - Dataset Kepadatan Penduduk Jakarta (Kaggle)
   - Dataset Jumlah Penduduk Berdasarkan Usia per Kelurahan (data.go.id)
3. Simpan dataset ke dalam folder data/ (misal data/kepadatan.json dan data/penduduk_usia.json).
4. Pastikan file data terhubung ke script (index.html, main.js).
5. Buka index.html di browser, atau gunakan Live Server di VSCode.

## Kontribusi Saya
1. Membuat peta dasar menggunakan QGIS
2. Mengimplementasikan peta interaktif dengan Leaflet.js
3. Menambahkan fungsi interaktif: dropdown kelurahan, pop-up info, dan grafik demografi
4. Mendesain antarmuka menggunakan HTML dan CSS

## Preview
![Peta Kependudukan DKI Jakarta](./Peta%20Kependudukan%20DKI%20Jakarta.png)

