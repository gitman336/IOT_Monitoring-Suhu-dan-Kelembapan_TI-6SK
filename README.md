# IOT_Monitoring-Suhu-dan-Kelembapan_TI-6SK
Proyek ini merupakan implementasi sistem monitoring suhu dan kelembapan secara real-time menggunakan mikrokontroler ESP8266, sensor DHT11/DHT22, dan platform cloud ThingSpeak sebagai antarmuka visualisasi data. ESP8266 digunakan untuk membaca data dari sensor DHT11 dan menampilkannya ke layar LCD maupun mengirimkannya ke platform ThingSpeak. Sensor DHT11 dapat mendeteksi suhu dan kelembapan dengan cukup baik, dan datanya bisa diakses secara langsung dan jarak jauh. Layar LCD 16x2 menampilkan informasi suhu dan kelembapan secara real-time, sehingga memudahkan pemantauan secara langsung. Sistem ini juga mampu terhubung dengan WiFi dan mengirim data secara berkala ke internet, memungkinkan kita memantau kondisi lingkungan dari mana saja.

Hardware :

Esp8266
LCD 16x2 l2C
Sensor DHT11
Software dan Tools :

Arduino IDE
Library:
ESP8266WiFi.h
DHT.h
ThingSpeak.h
ThingSpeak (akun dan channel)
Wiring Diagram : Diagram

Desain Circuit: Desin

Buat Channel di ThingSpeak https://thingspeak.mathworks.com/

Daftar/login ke ThingSpeak
Buat channel baru
Aktifkan field 1 dan field 2 untuk suhu dan kelembapan
Salin Write API Key
Instal Library di Arduino IDE

Melalui Library Manager:
DHT sensor library by Adafruit
ThingSpeak library
ESP8266 board melalui Board Manager
Upload Kode ke ESP8266

Foto Hasil: hasil 
