Repository GitHub:  
https://https://github.com/Ibnusabilx/PROJECT-APLIKASI-LIST-BARANG

## 🔗 Cara Menjalankan Proyek Ini

1. Buka XAMPP
2. Buka Terminal atau Shell di XAMPP
3. Arahkan ke direktori proyek menggunakan perintah:
   ```bash
   cd PROJECT-APLIKASI-LIST-BARANG
4. Jalankan perintah
   ```bash
    npm run dev
5. Kembali ke XAMPP Nyalakan Apache & MySQL
6. Buka Terminal atau Shell di XAMPP
7. Jalankan perintah
   ```bash
    php artisan serve
## 🔗 Cara Mengkloning Proyek

1. Clone repository dari GitHub:
   ```bash
    git clone https://github.com/Ibnusabilx/PROJECT-APLIKASI-LIST-BARANG
2. Masuk ke folder proyek
    ```bash
   cd PROJECT-APLIKASI-LIST-BARANG
3. Install dependency Laravel dan NPM
    ```bash
    composer install
4. Install dependency frontend (JS/Node):
    ```bash
    npm install
5. Pastikan kamu sudah install Composer dan Node.js + npm.
6. Salin dan ubah file environment
    ```bash
    npm install
6. Kemudian edit file .env untuk menyesuaikan koneksi database,
    ```bash
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=db_checklist_backup
    DB_USERNAME=root
    DB_PASSWORD=
4. Generate App Key
    ```bash
    php artisan key:generate
5. Jalankan migrasi dan seeder (jika ada)
    ```bash
    php artisan migrate
    php artisan db:seed
# Jika disediakan oleh projek
1. Jalankan server Laravel
    ```bash
    php artisan serve
2. Jalankan Vite (atau npm dev)
Jika di README disuruh npm run dev, jalankan:
    ```bash
    npm run dev
3. Buka di browser
Kalau pakai php artisan serve, buka:
    ```bash
    http://127.0.0.1:8000

⚠️ Catatan Tambahan
Kalau ada error npm run dev, mungkin butuh install vite atau laravel-vite-plugin.

Kalau pakai SQLite atau PostgreSQL, atur juga .env dengan benar.

Jalankan npm run build jika ingin membuat build production.
