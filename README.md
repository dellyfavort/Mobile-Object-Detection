# Edge AI Inventory Scanner

Aplikasi web berbasis **Edge AI** untuk mendeteksi objek secara real-time menggunakan kamera perangkat. Sistem memanfaatkan **TensorFlow.js** dan model **COCO-SSD** sehingga proses deteksi dapat dilakukan langsung di browser tanpa perlu mengirim video ke server.

Project ini dibuat sebagai prototype **Object Detection & Inventory Logging** dengan tampilan responsive yang dapat digunakan melalui laptop maupun perangkat mobile.

## Features

* Real-time object detection menggunakan kamera
* Bounding box dan confidence score pada objek yang terdeteksi
* Deteksi objek:

  * Person
  * Book
  * Cell Phone
  * Bottle
* Statistik deteksi secara real-time
* Average confidence
* Object detection log
* Penyimpanan data menggunakan Firebase Firestore
* Demo mode menggunakan Local Storage
* Export detection log ke CSV
* Snapshot kamera
* Sound alert
* Auto-save detection log
* Session timer
* Responsive design untuk desktop dan mobile

## Technologies

* HTML5
* CSS3
* JavaScript
* TensorFlow.js
* COCO-SSD
* Firebase Firestore
* Local Storage


## How It Works

```text
Camera
   ↓
TensorFlow.js
   ↓
COCO-SSD Object Detection
   ↓
Object + Confidence
   ↓
Statistics & Detection Log
   ↓
Firebase / Local Storage
```

## How to Run

1. Clone repository ini.
2. Buka folder project menggunakan Visual Studio Code.
3. Jalankan menggunakan **Live Server**.
4. Izinkan akses kamera pada browser.
5. Klik **Nyala Kamera**.
6. Klik **Start AI** untuk memulai object detection.

> Penggunaan kamera memerlukan izin dari browser dan umumnya berjalan lebih baik melalui `localhost` atau HTTPS.

## Notes

Project ini merupakan **prototype untuk pembelajaran dan demonstrasi Edge AI**, bukan sistem inventory management produksi. Hasil deteksi bergantung pada kemampuan model COCO-SSD, kondisi pencahayaan, posisi objek, dan kualitas kamera.

**Verine Shalom Utama**
Information Systems Student
