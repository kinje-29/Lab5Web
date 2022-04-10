# Pratikum 5 Web

        Nama    : Fajar Firmansyah
        Nim     : 312010309
        Kelas   : TI.20.A2

### Membuat document.write dan console.log

![1.png](Gambar/1.png)

* Fungsi `document.write` untuk menampilkan  data langsung pada halaman web.
* Fungsi  `console.log` untuk menampilkan teks ke console javascrip, biasanya digunakan untuk debugging. Karna setiap pesan yang error akan di tampilkan pada console.

![1_1.png](Gambar/1_1.png)


### Membuat window.alert
![2.png](Gambar/2.png)

* Fungsi `window.alert` biasanya digunakan untuk menampilkan sebuah pesan peringatan atau informasi. 

![2_2.png](Gambar/2_2.png)


### Menampilkan Popap untuk menginput sebuah Teks
![3.png](Gambar/3.png)

* membuat variabel  dengan `var nama `
* fungsi dari `prompt()` untuk mengambil sebuah inputan dari pengguna, `prompt()` akan mengmbalikan sebuah nilai string dari apa yang dinputkan

![3_1.png](Gambar/3_1.png)
![3_2.png](Gambar/3_2.png)


### Menampilkan Informasi atau pesan
![4.png](Gambar/4.png)

* fungsi `alert` biasanya digunakan untuk menampilkan sebuah pesan peringatan atau informasi.

![4_4.png](Gambar/4_4.png)


### Membuat Perhitungan Arithmetic
![5.png](Gambar/5.png)

* membuat tombol button pada bagian body dan memasukan `onclick=test(9,4).
* `function test(val1,val2)`, test diambil pada bagian onclik lalu `val1 dan val2` menggantikan angka 9 dan 4
* mencetak val1 dan val2 dengan cara `document.write` lalu masukan karakter tambah,kurang,bagi,perkalian, modulus. 

![5_1.png](Gambar/5_1.png)

* Ketika Tombol ditekan akan menampilkan hasil dari kode diatas

![5_5.png](Gambar/5_5.png)


### Membuat Pernilaian
![6.png](Gambar/6.png)

* membuat variabel nilai dengan tipe `var`
* membuat variable hasil dengan tipe `var`
* membuat kondisi if dan else.
* `if` jika `nilai lebih besar samadengan 60` maka akan menampilkan `hasil = Lulus`
* `else` jika `Nilai lebih kecil dari 60` maka akan menampilkan `hasil = Tidak lulus`
* Menampilkan hasil `document.write("Hasil: " + hasil)`, panggil variabel hasil kedalam write.  

![6_1.png](Gambar/6_1.png)

* Ketika menginputkan nilai kurang dari 60 maka akan menampilkan Tidak Lulus.
* Ketika menginputkan nilai lebih besar dari 60 maka akan menampilkan LULUS

![6_6.png](Gambar/6_6.png)


### Membuat Looping Switch
![7.png](Gambar/7.png)

* Membuat tombol dengan `onclike=test()`
* memanggil `test` dan membuat variabel baru `(val1)`
* Mesaukan `switch(val1)` memanggil variabel `val1` kedalam switch.
* Jika memilih angka 1 maka akan masukan kedalam  `case "1"` lalu menampilkan isi didalam `case "1"` lalu `break` agar tidak mengeksekusi pada `case` yang ada dibawahnya dan menghentikan program ketika value pada `case` sama dengan yang di harapkan

![7_7.png](Gambar/7_7.png)

* Memasukan nilai maka hasilnya seperti dibawah

![7_7.png](Gambar/7_77.png)


### Menetukan bilangan ganjil dan genap
![8.png](Gambar/8.png)

* hasilnya seperti dibawah

![8_8.png](Gambar/8_8.png)


### Merubah Tampilan Warna dan Teks Warna
![9.png](Gambar/9.png)

* Membuat Tombol button dengan onclik="ubahWarnaLB" 
* Membuat Tombol button dengan onclik="ubahEarnaaLD"
* memanggil onclik="ubahWarnaLB" kedalam javascrip
* melakukan eksekusi jika user mengklik `ubahWarnaLB` maka tampilan akan berubah sesuai dengan warna yang telah ditentukan

![9_9.png](Gambar/9_9.png)


### Membuat Daftar Menu Makanan
![10.png](Gambar/10.png)

* Membuat CheckBox dengan id `menu1,menu2,menu3` lalu `onclik="hitung(this)"`
* Membuat tampilan Total bayar dengan `strong` dengan `id="total"`
* Memanggil onclik ke dalam javascrip.
* Membuat variabel `total` dengan tipe var lalu menggambil id `total` yang berada di dalam `stronge`
![10_10.png](Gambar/10_10.png)




# Pertanyaan dan Tugas
1. Buat script untuk melakukan validasi pada isian form.


![11.png](Gambar/11.png)
![12.png](Gambar/12.png)

* Membuat class Login
* Membuat Form dengan method POST lalu onsumbit="validasi()"
* Membuat Tampilan Nama, Email, Password dan Alamat.
* Membuat Tombol dengan type `sumbit` dan class `tombol`

#### JavaScrip
* Memanggil onsumbit `validasi()`.
* Membuat Variabel disetiap isi di dalam Form seperti nama,email,password,alamat dan memanggil `id(nama) id(email) id(password) id(alamat)`
* Melakukan Kondisi If dan Else. Jika nama, email, alamat, password tidak kosong maka program akan mengeksekusi yang berada di bawah if dan menampilkan pesan/informasi, namun jikan salah satu dari form tidak di isi maka program akan mengeksekusi bagian else dan menampilkan pesan/informasi

#### CSS Validasi_form
![13.png](Gambar/13.png)
![14.png](Gambar/14.png)

#### Menampilkan hasil dari HTML/CSS dan JavaScrip
![15.png](Gambar/15.png)
![16.png](Gambar/16.png)
![17.png](Gambar/17.png)