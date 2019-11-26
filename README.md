# Program Sederhana Python Penambahan Data Ke Dalam List

Buat program sederhana untuk menambahkan data kedalam sebuah list dengan rincian sebagai berikut :

    1.Program meminta memasukkan data sebanyak-banyaknya (gunakan perulangan)
    2.Tampilkan pertanyaan untuk menambah data(y/t?), apabila jawaban t(Tidak), maka program akan menampilkan daftar datanya.
    3.Nilai Akhir diambil dari perhitungan 3 komponen nilai (tugas: 30%, uts: 35%, uas: 35%)
    4.Buat flowchart dan penjelasan programnya pada README.md
    5.Commit dan Push ke repository github

Tampilan Program

![Screenshot (68)](https://user-images.githubusercontent.com/53388439/69661909-d9f41b00-10b5-11ea-96f3-50aa5a087771.png)
 
 ![Screenshot (69)](https://user-images.githubusercontent.com/53388439/69662022-20e21080-10b6-11ea-9687-edf50c7ffd7a.png)
 
 Coding
 
    data=[]
    while(True):
    nim=input("masukan nim :  ")
    nama=input("masukan nama :  ")
    tugas=input("masukan nilai Tugas:  )
    uts=input("masukan nilai uts: ")
    uas=input("masukan nilai uas: ")
    data.append([nim, nama, tugas, uts, uas])
    ulangi=input("Tambah data (y/t)?")
    if ulangi.lower() == 't':
        break;

    print("\nDaftar Nama\n")
    print("==============================================================================")
    print("| No | Nama  |   Nim  |   Nilai Tugas  |  Nilai UTS  |  Nilai UAS  |  Akhir  |")
    print("| 1  | Ari   |    123 |     70         |    65       |      80     |   71.75 |")
    print("| 2  | Ali   |    124 |     65         |    80       |      90     |   79.00 |")
    print("==============================================================================")
