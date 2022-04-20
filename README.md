# sistem-ecommerce
jalankan composer update (didalam project perpus)
lalu jalankan copy .env.example .env
setelah itu php artisan key:generate
jangan lupa buat database (perpusku_gc) di phpmyadmin
langkah selanjutnya setting database nya di .env
jalankan php artisan migrate
jalankan juga php artisan db:seed
terakhir php artisan serve
Buat database baru dengan nama laravel-ecommerce.
Import database aplikasi ke dalam database laravel-ecommerce.
Login dengan email : rifki@admin.com, Password : admin.


#Fitur Aplikasi :
    Login Admin
    Login Member
    Pendaftaran Member
    Katalog Produk
    Kategori Produk
    Keranjangan Belanja
    Data Pesanan
    Data Pengiriman
    LogOut
    dan lainnya.
