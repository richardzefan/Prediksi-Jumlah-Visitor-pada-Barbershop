# Prediksi-Jumlah-Visitor-pada-Barbershop

Kompetisi pada : https://inalyst.id/competition/86de3dd2-541a-419a-8225-c9add9414f7f/overview
![image](https://user-images.githubusercontent.com/66706999/169447160-7c8344a9-16aa-4a1d-ab0f-99f98ce95784.png)

# OVERVIEW
## Bisnis:
Barbershop ini terletak pada salah satu kota di Jawa Timur, yang dibangun sejak 2021. Selain menerima service haircut, barbershop juga menerima service lain seperti haircolor, hairperming, dll, serta penjualan produk seperti pomade, hairpowder, dsb.


## Tujuan:
Untuk mengoptimalkan stock & ekspansi bisnis, barbershop membutuhkan prediksi secara harian, berapa visitor yang akan datang pada beberapa hari yang akan datang.


## Tambahan informasi (Opini Owner):
Perbedaan bisnis barbershop dengan bisnis lain adalah adanya peluang bahwa pelanggan akan datang lagi atau tidak. Umumnya pelanggan yang pernah datang lebih dari 1 kali akan menjadi pelanggan tetap dan akan datang kembali. Terdapat juga informasi lain seperti berapa lama seseorang rutin akan datang lagi setelah potong rambut.
Hari weekday atau weekend juga bisa jadi berpengaruh terhadap banyaknya kedatangan customer.

# PENILAIAN
#### Dengan diberikan data transaksi, peserta diminta untuk memprediksi jumlah visitor harian pada beberapa hari yang akan datang (30 hari). Salah satunya menggunakan model Time Series (atau bisa menggunakan pendekatan lain sesuai eksplorasi data yang dilakukan.

### Penilaian:
#### Metrics yang akan digunakan untuk pengukuran akurasi adalah MAPE

# SUMMARY OF DATA
Data yang digunakan adalah:

### Data Transaksi: 
Data yang berisi transaksi tiap pelanggan yang datang, termasuk chanel payment dan product/service apa saja yang dibayarkan
Status (baru: pelanggan baru pertama kali datang, lama: pelanggan lama yang pernah datang)
Cukur ke (jumlah kedatangan customer ke store)
Capster (id pemotong rambut yang memberikan service)
Bayar (channel payment cash/qris)

### Data Traffic Google Business:
Data pada google business hasil dari marketing maupun proses lainnya (asumsi data di bulan april telah lengkap, sebagai proyeksi hasil marketing)

### Data Pricelist Product: 
Data Harga product & service barbershop
