# labs06

### latihan 1
* Berikut penjelasanya 

```python
from os import system
```
<p> Diatas code untuk mengimport, untuk mendapatkan clear system pada system os<p>

```python
nama1 = []
nim1 = []
tugas1 = []
uts1 = []
uas1 = []
akhir1 = []
```
<p> Code diatas adalah program daftar nilai mahasiswa, maka kita buat terlebih dahulu list nya<p>

```python
def judul():
    print('==================================')
    print('|     Daftar Nilai Mahasiswa     |')
    print('==================================')
```
<p>Biatas code untuk menampilkan fungsi judul, karna ini function jadi kita bisa memanggil fungsi ini berkali kali, tanpa harus menulis ulang programnya, kita hanya perlu lmemanggilnya dengan cara mengetikan program *Contoh : fungsi()<p>

```python
def menu():
    system("cls")
    print("="*37)
    print("Input Data Nilai Mahasiswa".center(40))
    print("="*37)
    print("|    1. Tambah Data                 |")
    print("|    2. Tampilkan Data Mahasiswa    |")
    print("|    3. Ubah Data Mahasiswa         |")
    print("|    4. Hapus Data Mahasiswa        |")
    print("|    5. Selesai                     |")
    print("="*37)
    pilih = input("Pilih Menu  : ")
    if pilih == "1":
        tambah()
    elif pilih == "2":
        tampilkan()
    elif pilih == "3":
        ubah()
    elif pilih == "4":
        hapus()
    elif pilih == "5":
        selesai()
    else:
        tidak = input("Menu Tidak Ada")
        system("cls")
        menu()
```
<p>Diatas adalah code untuk membuat fungsi menu<p>

* Berikut ketika program dijalankan .

![gambar1](ss/hasil1.png)
