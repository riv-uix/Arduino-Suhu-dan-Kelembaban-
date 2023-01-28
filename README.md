# Arduino-Suhu-dan-Kelembaban-
program Arduino Untuk Monitorih Suhu dan Kelembaban
Program ini menggunakan library DHT untuk membaca data suhu dan kelembaban dari sensor DHT11, 
dan library WiFi untuk mengirim data ke server Thingspeak melalui koneksi WiFi. Setiap 30 detik, 
program akan membaca data dari sensor dan mengirimkannya ke server Thingspeak, sehingga Anda dapat melakukan monitoring suhu dan kelembaban secara real-time.

Catatan: pastikan untuk mengubah "YOUR_SSID", "YOUR_PASSWORD", dan "YOUR_API_KEY" sesuai dengan konfigurasi jaringan WiFi dan API key Thingspeak Anda.
