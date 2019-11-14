# Kontainer yang terdapat di docker ini
1. Nginx (web server)
1. PHP-FPM 5.5
1. PHP-FPM 5.6
1. PHP-FPM 7.1
1. PHP-FPM 7.2
1. Mariadb (database)

# Penjelasan isi file 
1. `public_html` : File program web diletakkan disini
1. `public_html\php55,56,71,71` : Letakan program web disalah satu folder tersebut dan php dengan versi tersebut akan tereksekusi
1. `php\www.conf` : File pengaturan php fpm.
1. `nginx` : Folder yang berisi pengaturan serta file log nginx.
1. `mysql` : Folder yang berisi file database.

# Konfigurasi Nginx (Cek Folder nginx/conf)
1. `nginx.conf` : Pengaturan untuk program PHP biasa.
1. `laravel.conf` : Pengaturan nginx untuk program PHP framework Laravel.
1. `codeigniter.conf` : Pengaturan untuk PHP framework codeigniter.

# Ekstensi PHP
Cek file Dockerfile untuk contoh instalasi ekstensi PHP
