<h1 align="center">Selamat datang di Ticket! 👋</h1>

## Apa itu Ticket?

Web Ticket yang dibuat oleh <a href="https://github.com/Naufaldhia"> Naufal Dhia </a>. **Ticket adalah Website untuk pemesanan ticket dengan mudah melalui website.**

## Fitur apa saja yang tersedia di Ticket?

-   Autentikasi Admin
-   User & CRUD
-   Rute & CRUD
-   Transportasi & CRUD
-   Category & CRUD
-   Pemesanan Ticket
-   Dan lain-lain

## Screenshot

Halaman Utama <br>
<img src="/public/img/TampilanLogin.jpg"><br>
Halaman Dashboard Admin <br>
<img src="/public/img/TampilanAwalHome.jpg">

## Release Date

**Release date : 28 Apr 2025**

> Ticket merupakan project open source yang dibuat oleh Naufal Dhia. Kalian dapat download/fork/clone. Cukup beri stars di project ini agar memberiku semangat. Terima kasih!

---

## Default Account for testing

**Admin Default Account**

-   username: admin
-   Password: admin123

---

## Install

1. **Clone Repository**

```bash
cd Ticket-Laravel
composer install
cp .env.example .env
```

2. **Buka `.env` lalu ubah baris berikut sesuai dengan databasemu yang ingin dipakai**

```bash
DB_PORT=3306
DB_DATABASE=laravel
DB_USERNAME=root
DB_PASSWORD=
```

3. **Instalasi website**

```bash
php artisan key:generate
php artisan migrate
```

4. **Jalankan website**

```bash
php artisan serve
```

## Author

-   Facebook : <a href="https://www.facebook.com/naufal.dhia.79/"> Naufal Dhia</a>
-   LinkedIn : <a href="https://id.linkedin.com/in/naufal-dhia-885b98243"> Naufal Dhia</a>

## Contributing

Contributions, issues and feature requests di persilahkan.
Jangan ragu untuk memeriksa halaman masalah jika Anda ingin berkontribusi. **Berhubung Project ini saya sudah selesaikan sendiri, namun banyak fitur yang kalian dapat tambahkan silahkan berkontribusi yaa!**

## License

-   Copyright © 2025 Naufal Dhia.
-   **Ticket is open-sourced software licensed under the MIT license.**
