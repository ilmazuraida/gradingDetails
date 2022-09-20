**Bantulah seorang dosen muda untuk menghitung dan memasukkan nilai mahasiswa** <br />
----------------------------------------
1. Buatlah sebuah fungsi Login dimana jika salah id / password munculkan pesan status error,<br/>
jika berhasil buatlah variabel untuk menyimpan ```status_login = active```
2. jika ```status_login = active``` maka dosen tersebut dapat memasukkan nilai dengan rincian <br/>
```
Halo user_name,
Masukkan Nama Mahasiswa yang akan di grading : _
Nama Mata Kuliah : _
Silahkan Masukkan nilai Presensi : _ 
Silahkan Masukkan nilai Tugas : _
Silahkan Masukkan Nilai UTS : _
Silahkan Masukkan Nilai UAS : _
```
Tampunglah data mahasiswa dan nilai tersebut dengan menggunakan struktur data array of object
3. Buatlah fungsi untuk menghitung nilai tersebut dengan rumus
```
total_nilai = (0.05 * nilai presensi) + (0.1 * nilai tugas ) + (0.30 * Nilai tugas) + (0.25 * Nilai UTS) + (0.30 * Nilai UAS)
```
4. Buatlah kondisi jika nilai total
```
A : 100 - 85
B : 84 - 70
C : 69 - 50
D : 49 - 30
E : 30 - 0
```

5. Print hasilnya dengan tampilan berikut
```
Mahasiswa X mendapatkan nilai A untuk Mata Kuliah X dengan skor total 100
```
----
**lakukan git clone menggunakan https pada repository ini, untuk mengarahkan origin folder anda pada repo ini<br/> lalu buatlah branch anda sendiri dan lakukan pull request**
----