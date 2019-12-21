Flowchart Tugas 5

![image](https://user-images.githubusercontent.com/56398506/71300530-436efd00-23c8-11ea-8c0c-8d0b45b76007.png)

Penjelasan Tugas 5

Di dalam praktikum 5 ini membahas tentang program sederhana yang akan menampilkan daftar nilai mahasiswa menggunakan Dictionary atau dict{}. Di bawah ini merupakan kode-kode program yang digunakan beserta output dan penjelasannya.

![image](https://user-images.githubusercontent.com/56398506/71301285-c34c9580-23cf-11ea-8648-79d53b0a6d8c.png)

•	Mendeklarasikan dictionary kosong dengan nama dictionary data = {}

•	Menginput salah satu menu yang tersedia ((L)ihat, (T)ambah, (U)bah, (H)apus, (C )ari, (K)eluar) yang menggunakan perulangan While True
Menu "Tambah Data"

![image](https://user-images.githubusercontent.com/56398506/71301290-e1b29100-23cf-11ea-86f3-ad0029f8e02e.png)

Untuk menu "Tambah Data" :

•	Menggunakan inputan t dan menggunakan kondisi if

•	Melanjutkan perintah di bawahnya yaitu menginput data (Nama, NIM, Nilai Tugas, Nilai UTS, Nilai UAS).

•	Setelah itu, akan mengakses dictionary, nama sebagai key dan nama, NIM, tugas, uts, uas sebagai value.

•	Lalu akan mencetak dictionary, setelah data diinput.

Menu "Lihat Nilai"

![image](https://user-images.githubusercontent.com/56398506/71301302-06a70400-23d0-11ea-9dc0-c180f86e6669.png)

Untuk menu"Lihat Nilai" :

•	Menggunakan inputan l dan menggunakan kondisi elif

•	Menggunakan kondisi if dan else

•	Untuk kondisi if apabila sebelumnya sudah melakukan input pada menu "Tambah Data" lalu akan mencetak data dalam bentuk list yang menggunakan perulangan for x in data.values():

•	Tetapi, jika sebelumnya tidak melakukan input data, maka data tidak akan dicetak atau ditampilkan dan akan mencetak TIDAK ADA DATA yang menggunakan kondisi else.
Menu "Keluar"

![image](https://user-images.githubusercontent.com/56398506/71301308-23433c00-23d0-11ea-95ac-107f53051db3.png)

Pada menu "Keluar" menggunakan inputan k dan fungsi pernyataan break, maka program akan berhenti atau keluar.
Menu "Hapus Data"

![image](https://user-images.githubusercontent.com/56398506/71301313-36560c00-23d0-11ea-9987-764bb6f0f352.png)


•	Menggunakan inputan h dan menggunakan kondisi if dan else

•	Menginput nama

•	Untuk kondisi if, kode yang digunakan if nama in data.keys(): dan del data[nama] yang akan menghapus data apabila data tersebut sudah diakses.

•	Dan sebaliknya, untuk kondisi else, maka data tidak berhasil dihapus karena data tidak tersedia atau tidak diinput.
Menu "Ubah Data"

![image](https://user-images.githubusercontent.com/56398506/71301323-54237100-23d0-11ea-89ae-e163a34357fc.png)

•	Menggunakan inputan u dan menggunakan kondisi if else

•	Menginput nama

•	Kondisi if akan menginput (NIM, Nilai Tugas, Nilai UTS, Nilai UAS) yang akan diubah dan data berhasil diubah

•	Kondisi else apabila data belum diakses, maka data tersebut tidak dapat diubah atau data tidak ada.
Menu "Cari Data"

![image](https://user-images.githubusercontent.com/56398506/71301330-6ac9c800-23d0-11ea-92c5-a607c612561b.png)

•	Menggunakan inputan c dan menggunakan kondisi if else

•	Menginput nama

•	Apabila data tersebut sudah diakses, maka akan mencetak daftar nilai sesuai dengan nama yang dicari

•	Sedangkan, jika data tersebut tidak ada, maka tidak akan mencetak daftar nilai.
Kondisi Else

![image](https://user-images.githubusercontent.com/56398506/71301338-8208b580-23d0-11ea-895b-5052dd285b8f.png)

Perintah untuk memilih salah satu menu yang tersedia.
Contoh Output yang dihasilkan

![image](https://user-images.githubusercontent.com/56398506/71301346-9351c200-23d0-11ea-85d9-bf58e3abeb44.png)
