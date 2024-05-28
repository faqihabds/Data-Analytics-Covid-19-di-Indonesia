# Data Analytics COVID-19 di Indonesia
Data Analytics COVID-19 di Indonesia dengan menggunakan menggunakan Excel dan Tableau.

# About The Project
Data Analytics COVID-19 di Indonesia adalah analisis data yang berfokus pada banyaknya jumlah terkena dan teratasi kasus COVID-19 di Indonesia, menggunakan Excel dan Tableu untuk memberikan wawasan dan pengambilan keputusan.

# Dataset 
Dataset yang digunakan adalah dataset COVID-19 Indonesia Dataset yang dapat diakses melalui [Kaggle](https://www.kaggle.com/datasets/hendratno/covid19-indonesia).

## Tentang Dataset

### Konteks
Dataset COVID-19 di Indonesia dibuat untuk mengetahui berbagai faktor yang dapat dipertimbangkan dalam pengambilan keputusan terkait tingkat ketatnya kebijakan di setiap provinsi di Indonesia.

### Konten
Data dikompilasi berdasarkan deret waktu, baik pada tingkat negara (Indonesia), maupun pada tingkat provinsi. Jika diperlukan di provinsi tertentu, data juga mungkin disediakan pada tingkat kota/kabupaten.

Data demografis juga tersedia, serta perhitungan antara data demografis dan data pandemi COVID-19.

### Pengakuan
Terima kasih kepada mereka yang telah menyediakan data secara terbuka sehingga kami dapat mengompilasinya menjadi dataset di sini, yaitu: covid19.go.id, kemendagri.go.id, bps.go.id, dan bnpb-inacovid19.hub.arcgis.com

# Data Cleaning
Langkah pertama dalam proses data cleaning adalah menghapus kolom yang tidak relevan untuk analisis lebih lanjut. Kolom-kolom yang dihapus termasuk `Location Level`, `City or Regency`, `Continent`, `Time Zone`, `Special Status`, `Total Regencies`, `Total Cities`, `Total Districts`, `Total Urban Villages`, `Total Rural Villages`, `Area (km2)`, `Population Density`, `Longitude`, `Latitude`, `New Cases per Million`, `Total Cases per Million`, `Growth Factor of New Cases`, dan `Growth Factor of New Deaths`. 

Setelah itu, kolom `Date` dipisahkan menjadi tiga kolom terpisah yaitu `Date`, `Month`, dan `Year` untuk memudahkan analisis berdasarkan waktu. Kolom `DMY` ditambahkan untuk menyimpan kombinasi hari dan bulan dalam format `dd-mmm`. 

Kolom yang dipertahankan dan dibersihkan termasuk `Date`, `Month`, `Year`, `DMY`, `Location ISO Code`, `Location`, `New Cases`, `New Deaths`, `New Recovered`, `New Active Cases`, `Total Cases`, `Total Deaths`, `Total Recovered`, `Total Active Cases`, `Province`, `Country`, `Island`, `Population`, `New Deaths per Million`, `Total Deaths per Million`, `Total Deaths per 100rb`, `Case Fatality Rate`, dan `Case Recovered Rate`. 

Langkah-langkah ini memastikan dataset yang lebih bersih dan terstruktur untuk analisis selanjutnya.

# Visualisasi Data

# Analisis Data
