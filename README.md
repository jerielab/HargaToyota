INSIGHT & INTERPRETASI ANALISIS HARGA TOYOTA COROLLA
(Manufacture Year, Fuel Type, Engine CC)

C14250147 - Jeriel Evander Ali Budiman & C14250066 Nicholas Reuben Kendengis

Dataset: ToyotaCorolla.csv
Output Workflow: 3 branch visualisasi Price Comparison
Metode: CSV Reader → Cleaning → GroupBy → Bar Chart / Line Plot

1. Analisis Harga Berdasarkan Manufacture Year

Insight:
Harga rata-rata Toyota Corolla meningkat pada tahun produksi yang lebih baru.

Perbedaan harga antar tahun cukup signifikan:
Semakin muda mobilnya → semakin mahal harganya (wajar karena depresiasi).

Ada tahun yang menunjukkan lonjakan harga (spike):
Biasanya terjadi ketika model facelift, upgrade fitur, atau generasi baru dirilis.

Tahun lama (misal 1998–2001) memiliki harga rata-rata rendah karena:
Umur kendaraan tinggi.
Fitur keselamatan dan kenyamanan kurang lengkap.
Kondisi fisik lebih banyak menurun.

<img width="1257" height="908" alt="image" src="https://github.com/user-attachments/assets/f4aa0d2c-fd55-487e-8629-27f53e4d4032" />

Interpretasi
“Harga mobil menunjukkan pola depresiasi yang kuat. Mobil produksi lebih baru cenderung jauh lebih mahal dibandingkan model lama. Lonjakan harga pada tahun tertentu mengindikasikan rilis generasi baru Toyota Corolla, sehingga meningkatkan nilai pasar mobil bekas pada tahun terkait. Pola ini konsisten dengan perilaku pasar mobil secara umum.”

2. Analisis Harga Berdasarkan Fuel Type

Insight:
(Bensin / Diesel)

Mobil bensin (Petrol) biasanya memiliki harga rata-rata lebih tinggi dibanding mobil diesel.

Alasan-alasan yang biasanya muncul di dataset mobil bekas:
Bensin lebih populer untuk Corolla → lebih banyak permintaan → harga stabil.
Mesin bensin cenderung lebih halus dan murah perawatan.
Diesel biasanya digunakan untuk jarak jauh (lebih banyak wear), menurunkan harga jual kembali.

<img width="1256" height="910" alt="image" src="https://github.com/user-attachments/assets/0540efc8-9bef-4189-b6c5-ec9318976381" />

Interpretasi
“Fuel type memiliki pengaruh nyata terhadap harga Toyota Corolla. Unit bermesin bensin memiliki harga lebih tinggi dibanding diesel karena permintaan pasar yang lebih besar dan biaya perawatan yang lebih rendah. Sementara itu, versi diesel cenderung dihargai lebih murah karena penggunaan yang lebih intens dan persepsi pasar terhadap biaya perbaikan yang lebih tinggi.”

3. Analisis Harga Berdasarkan Engine Capacity (CC)

Insight:
Mobil dengan CC lebih besar → harga rata-rata lebih tinggi.

Alasan:
Mesin besar identik dengan performa lebih baik.
Biasanya dilengkapi fitur tambahan yang meningkatkan harga.
Unit CC besar lebih jarang → membuat harga relatif lebih stabil.

Untuk CC kecil (1300–1400 cc):
Harga cenderung lebih rendah.
Segmen ini biasanya didesain hemat bahan bakar, bukan performa.
Supply banyak → harga turun.

<img width="1257" height="907" alt="image" src="https://github.com/user-attachments/assets/ee491ad2-5db3-4280-b1c7-be554e3b2b46" />

Interpretasi
“Engine capacity berhubungan langsung dengan harga jual mobil. Unit dengan kapasitas mesin lebih besar dihargai lebih tinggi karena menawarkan performa dan durabilitas yang lebih baik. Sebaliknya, mobil dengan CC kecil lebih murah karena supply yang lebih banyak dan orientasi pasar yang berbeda (ekonomis, irit bahan bakar). Temuan ini sejalan dengan tren umum di pasar mobil bekas.”

4. Kesimpulan Umum

Dari ketiga cabang analisis, ditemukan pola jelas mengenai faktor-faktor yang memengaruhi harga Toyota Corolla:

Manufacture Year → Faktor paling dominan
Semakin baru → semakin mahal (pola depresiasi jelas).

Fuel Type → Memengaruhi harga berdasarkan preferensi pasar
Bensin lebih mahal → lebih populer, perawatan lebih mudah.

Engine CC → Mempengaruhi harga berdasarkan performa
CC tinggi lebih mahal → performa lebih tinggi, supply lebih sedikit.

Interpretasi Keseluruhan
“Harga Toyota Corolla ditentukan oleh kombinasi umur kendaraan, jenis bahan bakar, dan kapasitas mesin. Ketiga faktor ini saling memperkuat tren umum harga di pasar mobil bekas. Analisis ini dapat membantu penjual, pembeli, dan dealer mobil dalam mengoptimalkan harga jual dan memahami variabel apa yang paling berpengaruh terhadap nilai pasar Toyota Corolla.”
