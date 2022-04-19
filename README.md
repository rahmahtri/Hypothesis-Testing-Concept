# Hypothesis-Testing-Concept
Repository ini berisi mengenai bagaimana cara pengujian hipotesis dengan python

Disini menggunakan dataset [Customer Personality Analysis](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis) untuk melakukan  pengujian hipotesis dalam membuktikan apakah education berpengaruh terhadap income atau tidak. Serta pada repository ini akan menampilkan bagaimana ukuran pemusatan dan ukuran penyebaran data.

## Requirements :
1. Download dataset pada [link ini](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)
2. Pastikan library berikut terinstall pada notebook anda `pandas, numpy, scipy, scipy.stats`

## Description
### Central Tendency Measurement
mean : sum of all data divided by number of data
median : middle of our data after sorted
mode : most frequent values of data

### Spread Measurement
variance : measures how far each number in the set is from the mean
standard deviation : variance squared
range : maximum minus by minimum
quartile/quantile : divided data into four (quarto) part

### Hypothesis Testing in Statistic
Null Hypothesis (H0) : hipotesis yang berkontradiksi dari pernyataan yang akan diuji
Alternative Hypothesis (H1) : Hipotesis yang ingin kita uji
P-Value : Metrics untuk mengukur resiko kesalahan menolak h0 

Cara mengambil keputusan :
Kondisi pengambilan keputusan dibagi menjadi 2:
1. Jika P-Value < α , maka kita akan mengambil H1
2. Jika P-Value > α , maka kita akan mengambil H0
