# Bootcamp_TugasAkhir

## Langkah-langkah agar aplikasi berjalan dengan baik:
1. Di MySql Workbench klik tombol + untuk menambah connection
2. Lalu ganti
     Hostname = food-order.csif92yiwwkn.ap-southeast-2.rds.amazonaws.com
     Port = 3306
     Username = root
     Password = root1234
   * Untuk Connection Name bebas sesuai selera
3. Setelah tersambung, anda akan diarahkan ke Schemes dari database
4. Buka kode di VSCode
5. Ketik perintah 'php artisan migrate:fresh' untuk menjalankan sql query untuk membuat table yang dibutuhkan
6. Ketik perintah 'php artisan serve' untuk menjalankan server

