# Churn-classification

#### main file 'Churn_FInal.ipynb'
#### visualitzation file 'visualisasi.pbix'
#### modeling file 'Churn_rf.pkl'
#### main dataset file 'commerce dataset.xlx'

- Customer ID = Id tiap customer
- Churn = Label customer churn atau tidak (1 Churn dan 0 tidak Churn)
- Tenure = lama pelanggan diukur dari pembelian pertama
- PreferredLoginDevice = perangkat yang digunakan pelanggan untuk login
- CityTier = Tingkat kota
- WarehouseToHome = jarak gudang ke rumah (estimasi dalam bentuk km)
- PreferredPaymentMode = metode pembayaran
- Gender = jenis kelamin
- HourSpendOnApp = jumlah jam yang dihabiskan pada aplikasi(kemungkinan diambil rata" tiap hari)
- PreferedOrderCat = kategori pesanan bulan lalu
- SatisfactionScore = tingak kepuasan pelanggan (mungkin diambil dalam bentuk review bintang)
- MaritalStatus = status pernikahan customer
- NumberOfAddress = total alamat yang ditambahkan pada tiap customer
- Complain = apakah ada keluhan pada customer tersebut bulan lalu
- OrderAmountHikeFromlastYear = peningkatan presentase pembelian dari tahun lalu
- CouponUsed = total kupon yang digunakan pada bulan lalu
- OrderCount = jumlah pesanan yang dilakukan pada bulan kemarin
- DaySinceLastOrder = terakhir customer melakukan order
- CashbackAmount = rata' cashabck yang didapat pada bulan lalu

Tools:
  - Pandas
  - numpy
  - seaborn
  - matlpotlib
  - scipy
  - pycaret
  - sklearn
  - ADASYN
  - grid search cv
  - standard scaler
  - metrics
  - pickle
  
Step
  1. importing library and load dataset
  2. get info from data
  3. handling missing value using skew
  4. handling outlier
  5. handling duplicated data
  6. feature engineering
  7. Encoding
  8. Feature Selection
  9. standardization
  10. modeling
  11. evaluation and validation testing
  12. hyperparameter tuning
  13. export to pickle file

Visualization
  - Power BI
