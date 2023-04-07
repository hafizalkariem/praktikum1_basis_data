# Praktikum1_basis_data
```
Nama : Ahmad Hapizhudin
NIM  : 312210370
Prodi: Teknik Informatika
```
# Tugas Praktikum 1  "SQL DDL (Data Definition Language)"

untuk script beserta langkah langkahnya dapat anda lihat di file `LAPORAN PRAKTIKUM BASIS DATA`

# Evaluasi dan Pertanyaan

## 1. Apa Maksud dari int (11) ?

Yang dimaksud dari int(11) disini adalah INT(11) dalam DDL (Data Definition Language) pada MySQL merupakan tipe data bilangan bulat (integer) dengan panjang digit maksimum 11.

## 2. Ketika kita melihat struktur tabel dengan perintah desc, ada kolom Null yang berisi Yes dan No. Apa maksudnya ?

kolom "Null" yang terlihat pada output perintah DESC di MySQL menunjukkan apakah sebuah kolom pada tabel dapat memiliki nilai NULL atau tidak.

Jika kolom "Null" memiliki nilai "YES", artinya kolom tersebut diperbolehkan memiliki nilai NULL. Sebaliknya, jika kolom "Null" memiliki nilai "NO", artinya kolom tersebut tidak diperbolehkan memiliki nilai NULL.

Ketika sebuah kolom tidak diperbolehkan memiliki nilai NULL, maka kolom tersebut harus selalu diisi dengan nilai yang valid pada setiap saat. Jika nilai kolom tidak diisi, akan terjadi kesalahan saat operasi tertentu seperti saat melakukan operasi INSERT atau UPDATE.

Namun, ketika sebuah kolom diperbolehkan memiliki nilai NULL, maka nilai kolom tersebut dapat diisi dengan nilai NULL jika tidak ada nilai yang valid atau relevan untuk diisi pada saat itu. Kolom dengan nilai NULL ini kemudian dapat diisi nilai valid di kemudian hari ketika informasi sudah tersedia atau ketika nilai tersebut memang tidak diperlukan.


