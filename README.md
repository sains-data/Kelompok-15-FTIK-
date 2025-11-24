Data Mart - FTIK
Tugas Besar Pergudangan Data - Kelompok 15

SD25-31007 - Pergudangan Data Tugas Besar Kelompok

## Team Members
- (123450011) EIGI ARTAMEVIA 
- (123450070) SALSABILA PUTRI MAHARANI 
- (122440119) MUHAMMAD ZAKY ZAIDDAN 
- (123450123) HANIFAH INAYA SANI 

## Project Description
Proyek ini bertujuan untuk membangun Data Mart FTIK berdasarkan data yang tersedia pada website resmi FTIK ITERA.
Data mart ini dirancang untuk mendukung kebutuhan analitik fakultas terkait:
- Aktivitas kegiatan fakultas dan prodi
- Publikasi berita
- Informasi unit organisasi
- Kategori aktivitas
- Analisis berbasis waktu

## Business Domain
Fakultas Teknologi Infrastruktur dan Kewilayahan (FTIK) adalah unit akademik yang menaungi beberapa program studi teknik seperti:
- Teknik Sipil
- Perencanaan Wilayah dan Kota
- Teknik Geologi
- Teknik Lingkungan
- Teknik Geomatika
- Teknik Infrastruktur Sipil
- Serta unit-unit organisasi pendukung lainnya

Website FTIK menjadi sumber utama informasi publik yang berisi berita, kegiatan, agenda, dan struktur organisasi.

## Architecture
- Approach: Kimball Dimensional Modeling
- Platform: SQL Server on Azure VM
- ETL: SSIS

## Key Features
- Fact tables: FACT_KEGIATAN, FACT_BERITA
- Dimension tables: DIM_WAKTU, DIM_PRODI, DIM_KATEGORI, DIM_UNIT_ORGANISASI
- KPIs: Jumlah kegiatan per prodi/unit, Frekuensi berita per kategori, Aktivitas per bulan/tahun, Kegiatan berdasarkan penyelenggara, Tren publikasi dari waktu ke waktu

## Documentation
- [Business Requirements](docs/Kelompok%2015_Tugas%20BesarDW_Business%20Requirements%20Analysis.pdf)
- [Design Documents](docs/Kelompok%2015_Tugas%20BesarDW_Dimensional%20model%20diagram.pdf)
- [Entity relationship](docs/Kelompok%2015_Tugas%20BesarDW_Entity%20relationship%20diagram%20(1).pdf)
- [Data Dictionary](docs/Kelompok%2015_Tugas%20BesarDW_Data%20Dictionary.pdf)
- [Data Source Identification](docs/Kelompok%2015_Tugas%20BesarDW_Data%20Source%20Identification.pdf)
- [Perancangan dan Implementasi Data Warehouse](docs/Dokumentasi%20Perancangan%20dan%20Implementasi%20Data%20Warehouse%20FTIK.pdf)  
## Timeline
- Misi 1: 17-11-2025
- Misi 2: 25-11-2025
- Misi 3: [Tanggal]
