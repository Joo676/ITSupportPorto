# Mempercepat instalasi windows menggunakan SSD Eksternal

Waktu: Berulang kali sejak 2020

Tools: Rufus, WinPE (Windows Preinstallation Environment), SSD SATA Eksternal, USB SATA Converter

Deskripsi Pekerjaan:
- Umumnya instalasi Windows dilakukan menggunakan flashdisk bootable via Rufus. Namun, saya menemukan cara untuk mempercepat waktu instalasi dengan cara
  mengekstrak seluruh isi file ISO Windows langsung ke SSD eksternal

- Menggunakan flashdisk berisi bootable WinPE dari Rufus (ISO dummy) untuk memancing masuk ke mode instalasi.

- Dari WinPE, saya jalankan setup.exe melalui CMD bawaan WinPE

Waktu instalasi jauh lebih cepat karena kecepatan baca dan tulis SSD lebih tinggi dibanding flashdisk biasa.
Mempermudah proses instalasi di laptop tanpa DVD atau flashdisk besar karena bisa juga ditaruh berbagai isi iso dari berbagai versi windows.

! Ada beberapa kasus dimana saya tidak bisa menggunakan metode ini, kebanyakan adalah di instalasi Windows 11 !
