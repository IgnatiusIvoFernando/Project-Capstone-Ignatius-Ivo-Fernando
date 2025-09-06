# ANALISIS PERBADINGAN JARAK TEMPUH, KECEPATAN PENGECASAN, DAN HARGA ANTARA DUA MODEL MOBIL LISTRIK
# Project Overview
# 1.1  Latar Belakang
  Mobil listrik merupakan sebuah kendaraan berjenis mobil yang didorong menggunakan tenaga listrik dan menggunakan baterai sebagai sarana menyimpan listrik tersebut. Kendaraan mobil listrik tidak mengeluarkan emisi gas rumah kaca sehingga penggunaannya jauh lebih ramah lingkungan. Sebab mobil listrik diisi dengan daya listrik, maka setiap mobil listrik pasti memiliki waktu pengisian daya yang berbeda. Selain itu, setiap mobil listrik juga memiliki harga, jarak tempuh, model unit, perusahaan manufaktur, dan negara manufakturnya masing-masing.
  Spesifikasi mobil listrik yang menjadi fokus analisis ini yaitu harga, waktu pengecasan, jarak tempuh dan model mobil. Harga dipilih sebagai nilai pembayaran untuk menebus mobil tersebut, waktu pengecasan dipilih untuk mengetahui berapa lama sebuah model mobil listrik harus diisi daya sehingga jeda penggunaannya dapat diketahui, jarak tempuh menentukan lama unit mobil listrik berjalan, dan model mobil sebagai nama mobil listrik yang sedang dibandingkan.
  Sehingga diciptakanlah sebuah Capstone Project berjudul: “ANALISIS PERBANDINGAN JARAK TEMPUH, KECEPATAN PENGECASAN, DAN HARGA ANTARA DUA MODEL MOBIL LISTRIK”. Diharapkan proyek ini dapat menjadi panduan bagi pembaca untuk membeli mobil listrik.

# 1.2  Tujuan
Tujuan dari Capstone Project ini adalah:
1.  Melakukan analisa perbandingan dua model mobil listrik berdasarkan waktu pengecasan, jarak tempuh, dan harga.

# 1.3  Rumusan Masalah
1.  Model mobil listrik apakah yang memiliki waktu pengecasan dan jarak tempuh yang baik?
2.  Berapakah harga yang harus dikeluarkan untuk model mobil listrik tersebut?

# 1.4  Pendekatan
  Pendekatan yang saya akan lakukan merupakan pendekatan linier. Pendekatan ini merupakan tipe pendekatan terstruktur dengan setiap tahapan telah ditentukan secara runtun. Struktur-struktur tersebut meliputi: tujuan, pertanyaan, pengumpulan data, analisis data, interpretasi, temuan, penulisan, pelaporan & diseminasi, dan evaluasi.

# 1.5  Sumber Data
  Dataset didapatkan dari Kaggle Datasets dari link berikut: https://www.kaggle.com/datasets/pratyushpuri/ev-electrical-vehicles-dataset-3k-records-2025/data. 
  Dataset ini menyimpan katalog dari 3021 mobil listrik dari berbagai merek. Dataset ini memiliki kolom Vehicle_ID, Manufacturer, Model, Year, Battery_Type, Battery_Capacity_kWh, Charge_Time_hr, Price_USD, Color, Country_of_Manufacture, Autonomous_Level, CO2_Emissions_g_per_km, Safety_Rating, Units_Sold_2024, dan Warranty_Years.


# Insight & Findings
# 2.1  Kesimpulan
  Berdasarkan analisis yang telah dilakukan, penulis dapat menyimpulkan bahwa:
1.  Mobil listrik dengan performa rendah memiliki waktu pengecasan yang panjang ( > 10 jam) dan jarak tempuh yang pendek ( < 200 km), sementara mobil listrik dengan performa yang baik memiliki waktu pengecasan yang pendek ( < 3 jam dan jaran tempuh panjang ( > 400 km).
2.  Harga mobil listrik dengan performa terendah dengan harga mobil listrik dengan performma tertinggi tidak jauh beda. Yang berarti, ada faktor lain yang mempengaruhi harga dari sebuah mobil listrik.
   
# 2.2  Rekomendasi
  Sebab ada faktor selain waktu pengecasan dan jarak tempuh yang mempengaruhi harga dari mobil listrik, penulis merekomendasikan untuk melakukan riset tentang performa dari mobil listrik yang ingin dibeli. Hal tersebut dilakukan agar pembeli tidak menyesal setelah memiliki mobil listrik.

# AI Support Explaination
  Penulis memakai LLM IBM Granite dari perusahaan IBM. LLM IBM Granite digunakan untuk melakukan classification, summarization, comparison, dan menggambar grafik batang menggunakan invoke.
