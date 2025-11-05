# Laporan Praktikum Jaringan Komputer
## Lab 10.4.4 - Build a Switch and Router Network

Repositori ini berisi file konfigurasi dan laporan untuk tugas praktikum jaringan komputer judul 2

---

### 👨‍🎓 Identitas Praktikan

* **Nama:** Muhammad Farhan
* **NPM:** 2315061083
* **Kelas:** JK-A

---

### 📝 Deskripsi Singkat Lab

Praktikum ini bertujuan untuk membangun topologi jaringan sederhana dari awal menggunakan satu router (R1), satu switch (S1), dan dua PC (PC-A & PC-B).



Tugas utama dalam lab ini meliputi:
1.  **Perakitan Fisik:** Menghubungkan perangkat sesuai diagram topologi.
2.  **Inisialisasi Perangkat:** Memastikan router dan switch dalam keadaan *default* (tanpa konfigurasi).
3.  **Konfigurasi PC:** Mengatur alamat IP statis (IPv4 dan IPv6), subnet mask, dan default gateway pada PC-A dan PC-B.
4.  **Konfigurasi Router (R1):**
    * Mengatur `hostname`, `enable secret`, kata sandi `console` dan `vty`, serta `banner motd`.
    * Mengkonfigurasi alamat IPv4, IPv6, dan link-local pada interface G0/0/0 dan G0/0/1.
    * Mengaktifkan *routing* untuk IPv6 dengan perintah `ipv6 unicast-routing`.
5.  **Konfigurasi Switch (S1):**
    * Mengatur `hostname`.
    * Mengkonfigurasi alamat IP dan subnet mask untuk manajemen pada `interface vlan 1`.
    * Mengatur `ip default-gateway` agar switch dapat dikelola dari jaringan lain.
6.  **Verifikasi:**
    * Menguji konektivitas *end-to-end* dari PC-A ke PC-B menggunakan `ping`.
    * Menggunakan perintah `show` (seperti `show ip route` dan `show ip interface brief`) untuk memvalidasi konfigurasi.

---

### 📚 Referensi Video

Berikut adalah video panduan yang digunakan sebagai referensi untuk menyelesaikan lab ini:

* **10.4.4 Lab - Build a Switch and Router Network:** https://youtu.be/2fWsuvAIVBo
