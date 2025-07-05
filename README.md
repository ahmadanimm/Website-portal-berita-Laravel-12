### **💡 Tentang Aplikasi**

---

> Website portal berita adalah platform digital yang dirancang untuk memberikan informasi terkini dari berbagai bidang seperti hiburan, otomotif, kesehatan, politik, bisnis, olahraga, makanan. Aplikasi ini dibuat menggunakan Laravel v12.16.0 dan minimal PHP v8.4.6Ll jadi apabila pada saat proses instalasi atau penggunaan terdapat error atau bug kemungkinan karena versi dari PHP yang tidak support.

### **📝 To-Do List**

---
### User
-   [x] Halaman Utama.
-   [x] Berita Terkini.
-   [x] Terpopuler.
-   [x] Halaman Berita per Kategori.
-   [x] Halaman Berita per Penulis.
-   [x] Like, Dislike, Save, Komentar  Berita.
-   [x] Halaman Profil.
-   [x] Login.
-   [x] Register.

### Admin
-   [x] Dashboard.
-   [x] Manajemen Berita.
-   [x] Manajemen Kategori.
-   [x] Manajemen Penulis.

### **🕙 Instalasi & Kolaborasi**

---

1. Clone repository
    
    ```bash
    git clone https://github.com/ahmadanimm/Website-Portal-Berita-Laravel-12.git
    ```

2. Masuk ke folder repository kalian
    
    ```bash
    cd Portal-Berita
    ```

3. Install dependency
    
    ```bash
    composer install
    ```

4. Copy file `.env.example` menjadi `.env`
    
    ```bash
    cp .env.example .env
    ```

5. Generate key
    
    ```bash
    php artisan key:generate
    ```

6. Buat database baru (sesuaikan dengan nama database yang ada di file `.env`) melalui phpmyadmin atau terminal
    
    ```bash
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=portal-berita
    DB_USERNAME=root
    DB_PASSWORD=
    ```

7. Migrasi database
    
    ```bash
    php artisan migrate
    ```
    
8. Lakukan seeding data
    
    ```bash
    php artisan db:seed
    ```
9. Lakukan Storage:Link untuk menyimpan gambar

    ```bash
    php artisan storage:link
    ```


10. Jalankan server
    
    ```bash
    php artisan serve
    ```

11. Buka browser dan akses `http://localhost:8000`

11. Login Admin dengan akun

    ```bash
    Email : admin@gmail.com
    password :adminadmin
    ```
