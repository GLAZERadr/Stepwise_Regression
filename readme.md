# stepwise linear regression

Nama        : Adrian Putra Pratama Badjideh
Universitas : Telkom University

**Regresi linear bertahap (stepwise linear regression)** adalah metode regresi yang digunakan untuk memilih subset variabel yang paling berpengaruh terhadap variabel target dalam model regresi linear. Dalam regresi linear bertahap, variabel-variabel independen dimasukkan atau dihapus dari model secara bertahap berdasarkan kriteria tertentu, seperti signifikansi statistik atau peningkatan nilai R-squared.

## Pendekatan
Terdapat dua pendekatan, yaitu:
1. **Regresi Linear Bertahap Maju (Forward Stepwise Regression)**: Pada pendekatan ini, model regresi dibangun dengan memasukkan satu variabel independen pada setiap langkahnya. Dimulai dengan variabel independen yang paling signifikan secara individu (berdasarkan uji statistik seperti uji t atau uji F), variabel tambahan dimasukkan satu per satu berdasarkan kriteria tertentu (misalnya, menambahkan variabel yang memberikan peningkatan R-squared terbesar). Proses ini berlanjut hingga tidak ada variabel lagi yang memenuhi kriteria untuk dimasukkan ke dalam model.
2. **Regresi Linear Bertahap Mundur (Backward Stepwise Regression)**: Pada pendekatan ini, model regresi dibangun dengan menghapus satu variabel independen pada setiap langkahnya. Dimulai dengan model regresi yang mencakup semua variabel independen, variabel yang paling tidak signifikan secara statistik (misalnya, variabel dengan koefisien regresi paling kecil) dihapus dari model. Proses ini berlanjut hingga tidak ada variabel lagi yang memenuhi kriteria untuk dihapus dari model.

## Data
Data yang digunakan dalam **stepwise linear regression** merupakan data **The World Factbook**, atribut yang dipilih untuk diteapkan pada stepwise linear regression yaitu:

* Export (X1)
* Import (X2)
* Industrial production growth rate (X3)
* Investment (X4)
* Unemployment rate (X5)
* GDP (Y)

sehingga susunan kolom dari data dapat berbentuk seperti tabel berikut.
| --- | --- | --- | --- | --- | --- |
| X1 | X2 | X3 | X4 | X5 | Y |
| --- | --- | --- | --- | --- | --- |
| x11 | x12 | x13 | x14 | x15 | y16 |
| x21 | x22 | x23 | x24 | x25 | y26 |
| . | . | . | . | . | . |
| xij | xij | xij | xij | xij | yij |

notes : **X** merupakan variabel independant, **Y** merupakn variabel dependant.