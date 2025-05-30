# CARA MENJALANKAN BIKE SHARING DASHBOARD 

## Setup Environment 
```
mkdir proyek_analisis_data_bike
cd proyek_analisis_data_bike
pip install streamlit pandas matplotlib seaborn
```

## Run steamlit app
```
[streamlit run dashboard.py](https://public-bicycle-usage-analytics.streamlit.app/)
```

FITUR DASHBOARD
* Filter rentang waktu untuk analisis
* Filter hari dalam seminggu
* Analisis perbedaan pola penyewaan * pada hari kerja vs akhir pekan
* Analisis perbedaan penyewaan pada jam sibuk (prime time) vs jam biasa
* Visualisasi dengan heatmap, line chart, dan bar chart
* Statistik deskriptif data penyewaan

STRUKTUR DATA
Dashboard menggunakan dua dataset:
Dataset harian ("https://raw.githubusercontent.com/markavin/CustomerBehaviorUsagePatternAnalysisforaRentalBusiness/main/dataset/data_1.csv")
Dataset per jam ("https://raw.githubusercontent.com/markavin/CustomerBehaviorUsagePatternAnalysisforaRentalBusiness/main/dataset/data_2.csv")


REQUIREMENTS
Python 3.9 atau lebih baru
Streamlit
Pandas
Matplotlib
Seaborn
