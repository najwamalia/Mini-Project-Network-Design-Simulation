# Mini-Project-Network-Design-Simulation
## Deskripsi Project
Proyek ini merupakan simulasi perancangan dan implementasi jaringan komputer menggunakan Cisco Packet Tracer. Proyek ini terdiri dari beberapa skenario topologi jaringan yang dirancang untuk merepresentasikan jaringan kampus/perusahaan skala kecil hingga menengah. Setiap skenario topologi digunakan untuk mengimplementasikan konsep switching dan routing dalam membangun jaringan yang saling terhubung antar subnet dan antar VLAN.

## Ruang Lingkup Proyek
Proyek ini mencakup beberapa skenario desain jaringan, mulai dari jaringan internal gedung hingga interkoneksi antar gedung, yang meliputi:
- Segmentasi jaringan menggunakan VLAN
- Routing antar jaringan menggunakan static routing dan dynamic routing
- Pengujian konektivitas end-to-end

## Skenario Topologi Jaringan
1. Skenario Jaringan Internal Gedung (Inter-VLAN Routing)

Topologi ini mensimulasikan jaringan dalam satu gedung yang terdiri dari beberapa departemen yang dipisahkan menggunakan VLAN 10 dan VLAN 20. Router digunakan untuk menghubungkan komunikasi antar VLAN melalui mekanisme inter-VLAN routing. Skenario ini merepresentasikan jaringan internal fakultas atau kantor pusat.

2. Skenario Interkoneksi Antar Gedung Skala Menengah (Static Routing)

Topologi ini mensimulasikan koneksi tiga gedung yang saling terhubung menggunakan tiga router. Setiap gedung memiliki jaringan lokal dengan subnet berbeda, dan koneksi antar gedung dikonfigurasi secara manual menggunakan static routing. Skenario ini merepresentasikan jaringan antar kantor cabang skala menengah.

3. Skenario Jaringan Terpusat Skala Enterprise (Dynamic Routing)

Topologi ini mensimulasikan jaringan empat gedung yang terhubung ke satu core router. Setiap gedung memiliki jaringan lokal masing-masing dan terhubung melalui link point-to-point antar router. Routing antar gedung dikonfigurasi secara otomatis menggunakan protokol routing dinamis (RIP). Skenario ini merepresentasikan jaringan enterprise terpusat.

## Fitur yang Diimplementasikan
- Merancang topologi jaringan multi-segmen menggunakan Cisco Packet Tracer
- Mengonfigurasi VLAN, trunking, dan inter-VLAN routing
- Mengimplementasikan static routing antar subnet
- Mengimplementasikan dynamic routing antar router
- Melakukan pengujian konektivitas menggunakan ping dan traceroute

## Tools yang Digunakan
- Cisco Packet Tracer
- TCP/IP Protocol Suite
- VLAN dan Trunking
- Static Routing dan Dynamic Routing

## Pengujian Jaringan
Pengujian dilakukan dengan:
- Ping antar host beda subnet dan beda gedung
- Traceroute untuk memastikan jalur paket sesuai topologi
- Verifikasi tabel routing pada setiap router menggunakan show ip route

Seluruh skenario berhasil menunjukkan konektivitas jaringan berjalan dengan baik.
