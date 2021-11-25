# Live Code 1

```{attention}
This page is still on development.
```


## Instruction

Live Code ini dikerjakan dalam format ***notebook*** isi *notebook* harus mengikuti *outline* di bawah ini:
1. Perkenalan\
   Bab pengenalan harus diisi dengan identitas
2. **Judul/Penanda Soal**\
    Sediakan *Cell* Markdown sebelum cell import pustaka yang berisi nomor soal dan judul problem yang dikerjakan di tiap soalnya. Tiap soal mengikuti format nomor 2-5.
3. *Import* pustaka yang dibutuhkan\
   *Cell* pertama pada *notebook* **harus berisi dan hanya berisi** semua *library* yang digunakan dalam *project*.
4. *Data Loading*\
   Bagian ini berisi proses *data loading* yang kemudian dilanjutkan dengan *explorasi data* secara sederhana. Jika tidak ada data, bagian ini tidak perlu.
5. *Answer*\
   Bagian ini berisi proses dalam menjawab soal.
6. Simpan file jupyter notebook dengan nama file h8_p0lc1_NAMA.ipynb dan push ke repository yang telah disediakan (P0LC1) di github organization batch.

---

## Problems

Kamu adalah salah satu tim relawan back office penanganan COVID-19 di Indonesia. Kamu diminta untuk memperoleh data baru dari dataset yang sudah disediakan. Kerjakan dan jawab pertanyaan-pertanyaan berikut.
1. Ambil data kasus kumulatif Covid-19 tanggal 27 Agustus 2021 untuk negara-negara dengan latitude di bawah 0. Negara mana yang paling tinggi jumlah kumulatif kasus Covidnya per tanggal tersebut? Jika bukan Indonesia, bandingkan jumlah kumulatif kasus negara tersebut dengan Indonesia per tanggal yang sama!
2. Buatlah fungsi untuk menghitung jumlah kasus harian Covid-19 (dataset yang disediakan merupakan jumlah kasus kumulatif)!
3. Pada tanggal berapa puncak tertinggi kasus Covid-19 di Indonesia? bandingkan dengan tanggal 27 Agustus 2021, apakah mengalami penurunan jumlah kasus?
4. Buatlah sebuah list dimana berisikan jumlah kasus harian Covid-19 dengan ketentuan hanya mengambil data Indonesia saja dan jumlah kasus di bawah 10000. Berapa jumlah hari dengan kasus di bawah 10000?


## Dataset:

Dataset dapat diakses melalui link ini: https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_global.csv



---

## Assignment Rubrics

### Code Review

|Criteria|Meet Expectations|Points|
|--- |--- |--- |
|Data Loading|Mampu memuat data dengan Pandas| 2 pts |
|Looping Implementation|Mampu menerapkan looping while dalam suatu kasus| 10 pts |
|Conditional If Implementation|Mampu menerapkan konsep conditional if dalam suatu kasus| 10 pts |
|Function Implementation|Mampu menerapkan function pada sebuah kasus| 10 pts |
|Pandas Query Implementation|Mampu mengimplementasikan pandas query dalam pengolahan data| 10 pts |

### Readability

|Criteria|Meet Expectations|Points|
|--- |--- |--- |
|Tertata Dengan Baik|Semua Cell Di Notebook Terdokumentasi Dengan Baik Dengan Markdown Pada Tiap Cell Untuk Penjelasan Kode.| 8 pts |


---

```{admonition} Total Points
**50**
```
