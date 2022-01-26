# assignment 03
Terdapat kode Python berikut ini yang akan digunakan.
```python
import html
char1 = html.unescape('&#x25FB;')
char2 = html.unescape('&#x25FC;')

NIM = '10219019'
for x in NIM:
  n = int(x, 10)
  s = ''
  for i in range(n):
    s += char
  print(n, ':', s, sep='')
```

## question 1
Ganti nilai variabel NIM dengan data Anda, jalankan kode yang diberikan, dan tampilkan hasilnya.

### anwser 1
![Screenshot 2022-01-26 120158](https://user-images.githubusercontent.com/97995541/151107462-d2d99e0e-31f4-4cd9-8f38-9cfeba102347.png)

## question 2
Ganti nilai variabel NIM dengan data Anda, modifikasi kode yang diberikan di atas dengan `s += char1`, jalankan dan tampilkan hasilnya.

### anwser 2
![Screenshot 2022-01-26 120235](https://user-images.githubusercontent.com/97995541/151107474-9935b228-ce36-41fc-a794-90bf994d8a6b.png)


## question 3
Ganti nilai variabel NIM dengan data Anda, modifikasi kode yang diberikan di atas dengan `s += char2`, jalankan dan tampilkan hasilnya.

### anwser 3
Hasil modifikasi kode di atas adalah
![Screenshot 2022-01-26 120113](https://user-images.githubusercontent.com/97995541/151107483-f245031f-9605-46b0-b73a-93966d7fe84d.png)


## question 4
Jelaskan dengan singkat hal yang dihasillkan oleh kode yang diberikan.

### answer 4
Kode di atas berfungsi untuk
+ Memberikan ilustrasi setiap angka dalam NIM dalam bentuk persegi
+ 

