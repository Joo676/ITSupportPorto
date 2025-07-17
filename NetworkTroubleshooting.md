# Jaringan LAN tidak dapat terhubung ke Komputer

Analisis:

Mengecek konfigurasi IP, Gateway dan DNS di PC Klien. Beberapa kasus yang terjadi
- IP Address konflik antar perangkat (Solusi : Mengganti IP Address perangkat ke IP address yang belum terisi oleh perangkat lain)
- Tidak bisa terhubung ke internet yang ternyata pengaturan Gateway-nya salah (Solusi : Mengganti gateway ke IP Router)

(Namun semua ini bisa langsung diatasi dengan mengatur ke DHCP jika router mendukung konfigurasi DHCP Server)
---
Mengecek konfigurasi Router
- Pengaturan DHCP yang salah seperti pengaturan Pool IP Address dan subnet (netmask) yang salah
- Pengaturan IP Address dari sumber internet yang salah menyebabkan internet tidak dapat diteruskan ke PC Client
---
Mengecek kabel LAN / Kabel UTP, dicek menggunakan LAN Tester
- Salah satu atau beberapa kabel UTP rusak / putus di dalamnya
- Kabel UTP yang tidak terpasang dengan benar ke konektor RJ-45 
