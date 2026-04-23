1. Deskripsi Proyek
    Sistem Penjualan Sederhana terdiri atas:

    Backend REST API menggunakan FastAPI dengan autentikasi JWT.
    Frontend web menggunakan PHP native, Bootstrap 5, dan JavaScript untuk interaksi dinamis.
    Database MySQL/MariaDB dengan tabel: kategori, produk, pelanggan, transaksi_header, transaksi_detail.
    Fitur utama:

    Manajemen Kategori (CRUD)
    Manajemen Produk (CRUD)
    Manajemen Pelanggan (CRUD)
    Transaksi Penjualan multi-item dengan pengurangan stok otomatis

2. Persiapan Lingkungan
    Komponen	    Versi / Spesifikasi
    Web Server	    Apache (XAMPP/Laragon) dengan PHP 7.4+
    Database	    MySQL / MariaDB
    Backend	        Python 3.10+, FastAPI, Uvicorn
    Frontend	    PHP native, Bootstrap 5, JavaScript
    API Testing	    Postman, Newman
    UI Testing	    Selenium IDE (ekstensi browser), opsional Python Selenium
    
    Struktur Folder Proyek:

    C:/xampp/htdocs/penjualan/          (frontend)
    C:/Users/.../backend_penjualan/     (backend)

Menjalankan Backend:
cd backend
pip install -r requirements.txt
uvicorn main:app --reload --host 0.0.0.0 --port 8000

