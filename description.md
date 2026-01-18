# Judul Project

## Repository Outline
```
1. README.md - Penjelasan gambaran umum project
2. P0M1_julius-william.ipynb - Notebook ini berisiki dokumentasi Milestone 1. Mulai dari Perkenalan, Buisness Understanding, Data Understanding, Data Preperation, Analysis dan Conclution
3. VechicleInsuranceData.csv -
4. data_tab.csv -
```

## Problem Background
`Sebuah perusahaan asuransi mobil ingin melakukan evaluasi terhadap ajuan-ajuan dan klaim asuransi yang terjadi belakangan ini. Perusahaan sudah mengumpulkan datanya yang dapat dilihat di 'VehicleINsuranceData.csv'. Denagn tujuan untuk meningkatkan customer lifetime value (CLV), yaitu sebuah metrik yang mengukur seberapa berharga pelanggan tersebut ke perusahaan, perusahaan ingin mencari tau faktor-faktor apa saja yang mempengaruhi kenaikan CLV ini.`

## Project Output
`https://public.tableau.com/app/profile/julius.william1751/viz/DashboardMilestone1_17599185286110/DashboardFaktor-FaktorCLVAsuransiMobil?publish=yes`

## Data
`Di data ini terdapat 22 kolom dan 8360 baris. Nama, tipe data dan deskripsi sebagi berikut.
- ID (int)      : ID dari pemegang polis
- CLV (FLoat)     : Customer Lifetime Value adalah nilai pelanggan untuk perusahaan. Semakin besar maka akan lebih menguntungkan untuk perusahaan.
- Response      : Respon ajuan klaim. Yes berarti di terima, NO berarti ditolak.
- Coverage (Str): Tipe protekssi asuransi
- Education (str)  : Edukasi terakhir pemegang polis.
- Gender (str)    : Jenis kelamin pemegang polis.
- Location.Code (str) : kode lokasi pemegang polis.
- Marital.Satatus (str) : status pernikahan pemegang polis.
- Monthly.Premium.Auto (Float)      : Harga Premi bulanan pemegang polis.
- Months.Since.Last.Claim (Int) : Berapa bulan setelah klaim terakhir
- Months.Since.Policy.Inception (Int): Sudah berapa bulan memegang polis ini.
- Number.of.Open.Complaints (Int)   : Sudah berapa kali mengajukan klaim.
- NUmber.of.Policies (Int)     : Banyaknya polis yang di miliki pemegang polis.
- Policy.Type (Str)     : Tipe polis
- Policy    (Str)       : Kategori Polis
- Renew.Offer.Type  (Str): Tipe tawaran pembaruan kontrak
- Sales.Channel (Str)   : Membeli dari siapa
- Total.Claim.Anount    (Int): Sudah berapa kali melakukan klaim
- Vechicle.Class (Str)  : Kelas mobil
- Vehicle.Size (Str)   : ukuran mobil`

## Method
`Pada project ini, ada beberapa metode yang digunakan, untuk membersihkan data digunakan Turkey's Rule untuk menghilangkan outlier. Unutk analisa menggunakan beberapa metode statistik, mulai dari metode statistik deskriptif seperti mencari mean dan metode statistik inferensial seperti t test.`

## Stacks
`import pandas as pd : pandas digunakan untuk membuat dan memanipulasi dataframe.
import matplotlib.pyplot as plt : matplotlib digunakan untuk membuat plot di python. Plot yang digunakan seperti bar chart, pie char, scatter plot dan lain-lain.
from scipy import stats : scipy, kususnya stats digunakan untuk malakukan berbagai uji statistik seperti t test. `

## Reference
`https://www.kaggle.com/datasets/junglisher/vehicle-insurance-data/data`

---

**Referensi tambahan:**
- [Basic Writing and Syntax on Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [Contoh readme](https://github.com/fahmimnalfrzki/Swift-XRT-Automation)
- [Another example](https://github.com/sanggusti/final_bangkit) (**Must read**)
- [Additional reference](https://www.freecodecamp.org/news/how-to-write-a-good-readme-file/)