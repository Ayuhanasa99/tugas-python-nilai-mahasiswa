# tugas-python-nilai-mahasiswa
penjelasan program menghitung dan menampilkan data mahasiswa dan rata rata nilai yang di dapat, dengan perhitungan nilai (tugas : 30%, uts 35%, uas 35%). yang di input pada program ini yaitu Nama, Nim, Nilai tugas , Nilai uts, Nilai uas, (nilai akhir dihitung dari perhitungan nilai). hasil outputnya berupa table dengan menggunakan module texttable. disini saya menggunakan pyhton 3.6 di OS Windows kita harus mendownload dan instal Texttable dan PIP (Package) di https://pypi.python.org/pypi/texttable/0.8.4 . setelah itudi instal librarynya kita langsung bisa menggunakan texttable fungsinya yaitu untuk memanggil module texttable dengan menggunakan texttable kita bisa membuat output tabel dengan rapih sesuai dengan yang kita input. dan saya juga menggunakan list untuk program input pada koding, yaitu menggunakan python list methods : append ( ) menambah item dari belakang, selain itu saya menggunakan while untuk mengulang pertanyaan yang saya input while(jawab =="y"): nama.append(input("Masukan Nama :")) nim.append(input("Masukan Nim:")) nilai_tugas.append(input("nilai tugas:")) nilai_uts.append(input("nilai uts:")) nilai_uas.append(input("nilai uas:"))

jawab + input ("tambah data (y/t?") maka outputnya akan ada pertanyaan tambah data jika jawab "y" maka pertanyaan akan terulang kembali dan diinput kembalin seperti sebelumnya jika menjawab "t" maka perintah selesai dn keluat output hasil inputan. dengan cara kita bisa menginput lebih dari 1 inputan. atausesuai yg kita inginkan perintah for i in range yang telah ditentukan for i in range(no): tugas = int(nilai_tugas[i]) uts = int(nilai_uts[i]) uas = int(nilai_uas[i]) akhir = (tugas30/100) + (uts35/100) + (uas*35/100) table.add_rows([['No', 'Nama', 'Nim','Tugas','UTS','UAS','Akhir'],[i+1, nama[i],nim[i],nilai_tugas[i],nilai_uts[i],nilai_uas[i],akhir]]) print (table.draw())

sekian dari saya Ayu Hana Salsabila lebih dan kurangnya mohon diamaafkan dikarenakan masih tahap belajar, mohon kritik dan saran yang bersifat membangun dari kalian semua yang membaca.
