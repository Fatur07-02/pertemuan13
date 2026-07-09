ProfileCard
Deskripsi Aplikasi

ProfileCard adalah aplikasi mobile sederhana berbasis React Native (Expo) yang memungkinkan pengguna membuat kartu profil pribadi. Pengguna dapat mengubah foto profil menggunakan kamera atau galeri, memasukkan nama, melihat lokasi GPS saat ini, serta menyimpan data profil agar tetap tersedia ketika aplikasi dibuka kembali.

Aplikasi ini dibuat sebagai implementasi penggunaan native device features pada React Native dengan Expo.

📱 Fitur Aplikasi
Level 1
✅ Menampilkan kartu profil.
✅ Input nama pengguna.
✅ Menampilkan foto profil.
✅ Menggunakan Permission Flow sebelum mengakses fitur perangkat.
Level 2
✅ Mengambil foto menggunakan Kamera.
✅ Memilih foto dari Galeri.
✅ Mengambil lokasi GPS pengguna.
✅ Menyimpan data profil menggunakan AsyncStorage.
🔐 Native Features yang Digunakan
📷 Kamera (expo-image-picker)
🖼️ Galeri (expo-image-picker)
📍 GPS / Lokasi (expo-location)
💾 Penyimpanan Lokal (@react-native-async-storage/async-storage)
📷 Screenshot
1. Halaman Utama / Profile Card

(Masukkan Screenshot 1 di sini)

2. Dialog Permission Kamera atau Lokasi

(Masukkan Screenshot 2 di sini)

3. Hasil Foto Profil / Koordinat Lokasi

(Masukkan Screenshot 3 di sini)

🚀 Cara Menjalankan Aplikasi
Clone repository
git clone https://github.com/USERNAME/profile-card.git
Masuk ke folder project
cd profile-card
Install dependency
npm install

atau

npx expo install
Jalankan aplikasi
npx expo start
Scan QR Code menggunakan aplikasi Expo Go pada Android atau iPhone.
🛠 Tech Stack
React Native
Expo SDK
JavaScript
expo-image-picker
expo-location
AsyncStorage
📂 Struktur Project
ProfileCard
│
├── App.js
├── app.json
├── package.json
├── assets
└── README.md
📦 Expo Snack

Tambahkan link Expo Snack di bawah ini.

Expo Snack:

[https://snack.expo.dev/](https://snack.expo.dev/@fatur07-02/profile-card)
