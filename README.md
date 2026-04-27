# BMKG_Prakiraan-Cuaca
BACA DARI ATAS SAMPAI BAWAH!!!

Data prakiraan cuaca seluruh kelurahan dan desa di Indonesia dalam waktu 3 harian. 
Dalam 1 hari terdapat 8 data prakiraan cuaca (per 3 jam).

Format data: JSON
Jumlah data prakiraan: 3 hari
Jumlah data prakiraan dalam 1 hari: per 3 jam
Pemutakhiran data: 2 kali sehari
Lokasi kelurahan/desa: menggunakan kode wilayah administrasi tingkat IV dapat mengacu pada 
Keputusan Menteri Dalam Negeri Nomor 100.1.1-6117 Tahun 2022. 
Contoh: kode wilayah Kelurahan Kemayoran: 31.71.03.1001
Batas akses: 60 permintaan per menit per IP

PARAMETER KEY
utc_datetime: Waktu dalam UTC-YYYY-MM-DD HH:mm:ss
local_datetime: Waktu lokal-YYYY-MM-DD HH:mm:ss
t: Suhu Udara dalam °C
hu: Kelembapan Udara dalam %
weather_desc: Kondisi Cuaca dalam Indonesia
weather_desc_en: Kondisi Cuaca dalam English
ws: Kecepatan Angin dalam km/jam
wd: Arah Angin dari
tcc: Tutupan Awan dalam %
vs_text: Jarak Pandang dalam km
analysis_date: Waktu produksi data prakiraan cuaca dalam UTC-YYYY-MM-DDTHH:mm:ss

Untuk kode administrasi bisa diakses pada : https://sig.bps.go.id/bridging-kode/index
Lihat "Kode Desa/Kelurahan" yang berada di tabel kolom paling kanan.
Contoh: Kemayoran "31.71.03.1001"
Cikalong "32.04.17.2008"
