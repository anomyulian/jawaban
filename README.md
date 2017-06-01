#Jawaban Binar

1. Desain Aplikasi Ojek Online

Aplikasi Ojek Online (sebut saja Wojek demi kenyamanan)

Dalam Wojek, prosesnya adalah sebagai berikut:
1. Pelanggan mengirim pesan ke Wojek bahwa dia membutuhkan jasa Wojek melalui aplikasi.
2. Pada saat yang sama data lokasi pelanggan telah dicatat oleh Server Wojek.
3, Wojek mencari driver terdekat dari lokasi pelanggan. Disini server Wojek juga terus menerus memantau lokasi dari para driver.
4. Driver sampai di tempat pelanggan, diantar ke tujuan, dan sampai.
5. Wojek menanyakan ke pelanggan untuk melakukan rating dan pembayaran.

Aplikasi ini menggunakan teknologi berbasis lokasi. Untuk itu Wojek mengaplikasikan teknologi Google Maps Android API untuk Android. Sedangkan untuk iOS dapat menggunakan CoreLocation dan MapKit.

Untuk proses pengiriman notifikasi ke pelanggan Wojek menggunakan sistem push notification. Untuk itu Wojek menggunakan Google Cloud Messaging untuk Android dan Apple Push Notifications Services untuk iOS.

Wojek menggunakan pembayaran sistem non-tunai. Pelanggan membayar melalui kartu kredit atau sistem semacam pulsa. Ketika merancang sistem ini ada hal yang perlu diterapkan yaitu The Payment Card Industry Data Security Standards (PCI DSS). PCI DDS adalah sistem regulasi yang memastikan semua transaksi aman. Teknologi yang bisa digunakan adalah Card.io untuk Android atau iOS.

2. Keamanan

3. Koding
