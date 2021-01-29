# WebSocket.
  **WebSocket** adalah standar baru untuk komunikasi realtime pada Web dan aplikasi mobile. 

  **WebSocket** dirancang untuk diterapkan di browser web dan server web, tetapi dapat digunakan oleh aplikasi client atau server. 
  
  **WebSocket** adalah protokol yang menyediakan saluran komunikasi full-duplex melalui koneksi TCP tunggal.

  **WebSocket** merupakan bagian dari HTML5. 
  
  **WebSocket** menghadirkan pengurangan besar dalam lalu-lintas jaringan yang tidak penting dan latency dibandingkan dengan solusi polling dan long-polling yang telah digunakan untuk mensimulasikan koneksi dua arah dengan cara menjaga dua koneksi tetap terhubung.

  Pendahulu **WebSocket** adalah Comet.

# Comet.
  *Comet* adalah model aplikasi Web yang memungkinkan server web untuk mengirim data ke browser klien tanpa harus mengirimkan rekues terlebih dahulu. 
  
  *Comet* menjadi istilah umum untuk teknik mencapai interaksi client-server seperti tersebut. *Comet* dikenal dengan nama lain seperti Ajax Push, Reverse Ajax, Two-way-web, HTTP Streaming dan HTTP server push. Teknik ini bergantung pada teknologi browser asli seperti JavaScript dan tidak menggunakan properti plug-in lain. 

  *Comet* adalah implementasi yang nontrivial, dan beban dari HTTP header dan TCP handshake yang tidak efisien untuk pesan-pesan yang kecil. Dari kekurangan itulah dikembangkan protokol websocket.

## Latar Belakang.
  dikarenakan permintaan client yang mengharuskan developer bisa membuat aplikasi berbasis web secara real time atau real-time apps.

## Alternatif WebSocket
  1. Polling
    Metode ini mengirimkan request data ke server secara terus menerus.
  2. Long Polling
    Metode ini adalah metode polling dengan interval waktu yang berkala.

## Manfaat.
  1. **WebSocket** memungkinkan server untuk mendorong data kepada klien yang terhubung.
  2. Mengurangi traffic atau lalu lintas jaringan yang tidak perlu dan latency menggunakan full duplex melalui koneksi tunggal.
  3. Streaming melalui proxy dan firewall, mendukung komunikasi simultan hulu dan hilir.
  4. Kompatibel dengan pre-**WebSocket** dunia dengan cara beralih dari koneksi HTTP ke **WebSocket**s.

## Sejarah Rilis.
  **WebSocket** pertama kali dirujuk sebagai TCP Connection dalam spesifikasi HTML5, sebagai tempat untuk berbasis TCP socket API. Pada bulan Juni 2008, Nama **WebSocket** diciptakan oleh Ian Hickson dan Michael Carter, serangkaian diskusi yang dipimpin oleh Michael Carter yang mengakibatkan versi pertama dari protokol dikenal sebagai **WebSocket**.
  **WebSocket** muncul pada tahun 2009 sebagai proposal, kemudian dikembangkan selama 3 tahun sehingga **WebSocket** sekarang jauh lebih stabil dan sudah banyak di-support oleh bermacam-macam browser.

### Pembelajaran
  1. Komponen Untuk Node JS.
  2. Metode Mengelola Service Server-Client.
  3. Metode Mengelola Folder.

### Example Case
  1. Service Chat.