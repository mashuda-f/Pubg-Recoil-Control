Aplikasi No-Recoil dengan Randomisasi Gerakan Manusia + Proteksi Behavioral

📌 1. Tentang Aplikasi
Recoil PRO v3.0 adalah aplikasi macro berbasis Windows API (low-level input) yang dirancang untuk membantu mengontrol recoil senjata secara otomatis. Berbeda dengan macro biasa, aplikasi ini dilengkapi dengan jitter acak (delay & posisi) serta gerakan bertahap untuk meniru pola pergerakan manusia, sehingga memperlambat deteksi oleh sistem anti-cheat berbasis statistik.

⚠️ Peringatan Teknis (Fakta, Bukan Moral):
Aplikasi ini beroperasi di user-mode (menggunakan SendInput dan mouse_event). Game dengan anti-cheat kernel-level seperti BattleEye (PUBG), EAC, Vanguard tetap memiliki kemampuan mendeteksi input sintetis. Penggunaan di game online kompetitif berisiko tinggi mengakibatkan permanent ban. Disarankan hanya digunakan di mode latihan, game PvE, atau offline.

⚙️ 2. Fitur Utama
Fitur	Deskripsi
  1. Klik Tahan (Hold)	Recoil aktif terus-menerus selama tombol kiri mouse ditekan (bukan sekali klik).
  2. Human-like Movement	Gerakan turun dipecah menjadi 2-4 langkah kecil dengan delay acak.
  3. Jitter Delay (30%)	Waktu antar langkah tidak pernah sama persis (contoh: set 10ms → real 7–13ms).
  4. Jitter Offset (±2px)	Jarak turun selalu berubah sedikit (contoh: set 15px → real 13–17px).
  5. Koreksi Simulasi	Setiap 10 siklus, mouse sedikit bergerak ke atas (simulasi koreksi bidikan).
  6. F1 Toggle (Global)	Matikan/nyalakan semua fungsi macro secara instan (tanpa harus close aplikasi).
  7. Startup Delay Acak	Aplikasi menunda aktivasi hook selama 3–7 detik secara acak untuk menghindari pola "buka game langsung buka macro".
  8. Slider Real-time	Ubah Jarak Turun (Offset) dan Kecepatan (Delay) tanpa restart aplikasi.
  9. Tanpa Enkripsi	Kode bersih, stabil, dan tidak ada obfuskasi yang berlebihan (memudahkan debugging).
      
💻 3. Persyaratan Sistem
OS: Windows 10 / 11 (64-bit)

Framework: .NET 8 Runtime (jika belum ada, installer akan otomatis terunduh atau Anda bisa build sendiri)

Hak Akses: Administrator (wajib karena menggunakan global hook)

Antivirus: Tambahkan folder aplikasi ke daftar pengecualian (jika terdeteksi false positive).

🚀 4. Cara Instalasi & Menjalankan (Jika Mendapatkan File .exe)
Ekstrak file RecoilFix.exe ke folder pilihan Anda (misal: C:\RecoilPRO).

Klik kanan pada file RecoilFix.exe, pilih Run as administrator.

Jendela aplikasi akan muncul setelah 3–7 detik (startup delay).

Pastikan status di bagian bawah berwarna hijau dan bertuliskan "Status: SIAP".

Tekan F1 untuk toggle ON/OFF (indikator di status akan berubah).

