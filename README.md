# Laporan Proyek Machine Learning - Rizka Indah Puspita

## Project Overview
Buku merupakan sumber ilmu terbaik untuk memperluas wawasan, meningkatkan keterampilan berpikir kritis dan mendapatkan hiburan. Namun, dengan banyaknya pilihan buku yang tersedia, menemukan buku yang sesuai dengan preferensi dan kebutuhan pengguna bisa menjadi tantangan. Oleh karena itu, sistem rekomendasi buku hadir sebagai solusi untuk membantu pengguna menemukan buku yang sesuai dengan minat mereka.[[1]](https://kumparan.com/muhammad-yusuf-ardiansyah/buku-sebagai-sarana-penting-untuk-membangun-karakter-dan-pengetahuan-23Tqe8Z1AUN/full?utm_source=chatgpt.com)

Proyek "Rekomendasi Buku untuk Pengguna" bertujuan untuk mengembangkan sistem yang dapat memberikan rekomendasi buku berdasarkan berbagai faktor, seperti genre favorit, ulasan pengguna, popularitas, dan preferensi pribadi. Dengan menerapkan teknik berbasis data, seperti algoritma machine learning atau filtering berbasis konten dan kolaboratif, sistem ini diharapkan dapat memberikan rekomendasi yang lebih akurat dan relevan bagi setiap pengguna.[2](https://ejournal.undip.ac.id/index.php/jmasif/article/view/31482?utm_source=chatgpt.com)


## Business Understanding


### Problem Statements


### Goals


### Solution Statements


## Data Understanding

### Deskripsi Variabel
**Informasi Datasets**

| Jenis | Keterangan |
| ------ | ------ |
| Title | Book-Crossing: User review ratings |
| Source | [Kaggle](https://www.kaggle.com/datasets/ruchi798/bookcrossing-dataset/data) |
| Maintainer | [Ruchi Bhatia ](https://www.kaggle.com/ruchi798)|
| License | Other (specified in description) |
| Visibility | Publik |
| Tags | Arts and Entertainment, Online Communities, Literature  |
| Usability | 10.00 |

Setelah melakukan observasi pada dataset yang diunduh pada kaggle, didapatakan informasi sebagai berikut :

- Data berjumlah 1031175 sample (records)
- Terdiri dari 19 fitur/kolom ('Unnamed: 0', 'user_id', 'location', 'age', 'isbn', 'rating', 'book_title', 'book_author', 'year_of_publication', 'publisher', 'img_s', 'img_m', 'img_l', 'Summary', 'Language', 'Category', 'city', 'state', 'country')
- Terdiri dari 3 fitur/kolom numerik dengan tipe data int64 (Unnamed: 0, user_id, rating). Ini merupakan fitur numerik. Tetapi untuk fitur/kolom Unnamed: 0 merupakan fitur yang tidak diperlukan dan bisa dibuang.
- Terdiri dari 2 fitur/kolom numerik dengan tipe data float64 yaitu: age dan year_of_publication. Ini merupakan fitur numerik.
- Terdiri dari 14 fitur/kolom dengan tipe object (location, isbn, book_title,book_author, publisher, img_s, img_m, img_l, Summary, Language, Category, city, state, country). fitur/Kolom ini merupakan categorical features (fitur non-numerik) dimana fitur/kolom ini merupakan target fitur.


### Variable - variable pada 
1. `Unnamed: 0`: index pada data
2. `user_id`: Penomoran unik untuk tiap data dari pengguna
3. `location`: lokasi/alamat pengguna
4. `age`: umur pengguna
5. `isbn`: kode ISBN (International Standard Book Number) buku
6. `rating`: rating dari buku
7. `book_title`: judul buku
8. `book_author`: penulis buku
9. `year_of_publication`: tahun terbit buku
10. `publisher`: penerbit buku
11. `img_s`: gambar sampul buku (small)
12. `img_m`: gambar sampul buku (medium)
13. `img_l`: gambar sampul buku (large)
14. `Summary`: ringkasan/sinopsis buku
15. `Language`: bahasa yang digunakan buku
16. `Category`: kategori buku
17. `city`: Nama kota pengguna
18. `state`: Negara bagian pengguna
19. `country`: negara pengguna


### EDA - Univariate Analysis


### EDA - Multivariate Analysis


## Data Preparation


## Modeling
### _Decision Tree_ 

### _Random Forest_ 


## Evaluation


## _Referensi_
- [1] Muhammad Yusuf Ardiansyah (8 Sep 2024), https://kumparan.com/muhammad-yusuf-ardiansyah/buku-sebagai-sarana-penting-untuk-membangun-karakter-dan-pengetahuan-23Tqe8Z1AUN/full?utm_source=chatgpt.com
- [2] https://ejournal.undip.ac.id/index.php/jmasif/article/view/31482?utm_source=chatgpt.com