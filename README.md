# labspy02-dan-03
**Nama   : Siti Latifah**<br>
**NIM    : 312010321**<br>
**kelas  : TI.2O.A2**<br>
**Matkul : Bahasa Pemrograman**<br>

## Praktikum 2
![Screenshot (18)](https://user-images.githubusercontent.com/73010098/98443269-e6457c80-213c-11eb-8505-0f52a8f824e9.png)

#### SYNTAX
Berikut merupakan syntax untuk menampilkan program diatas
``` python
A = int(input("50"))
B = int(input("30"))
C = int(input("45"))
if A > B and A > C:
    print(A, "A")
elif B > A and B > C:
    print(B, "A")
else:
    print(C, "A")
```
#### OUTPUT
Dibawah ini merupakan output dari syntax diatas
![Screenshot (19)](https://user-images.githubusercontent.com/73010098/98443476-15102280-213e-11eb-8b6c-0688ad4e5f54.png)
  
#### FLOWCHART
![Screenshot (20)](https://user-images.githubusercontent.com/73010098/98443731-de3b0c00-213f-11eb-8a5f-9c0420fce3e7.png)

## Praktikum 3
![Screenshot (23)](https://user-images.githubusercontent.com/73010098/98443826-9b2d6880-2140-11eb-84de-f336c2cbf481.png)
#### Latihan1.py
![Screenshot (22)](https://user-images.githubusercontent.com/73010098/98443899-ffe8c300-2140-11eb-8caf-b274285191c4.png)

#### SYNTAX
Berikut merupakan syntax untuk menampilkan program diatas
```python
print('Bilangan Acak Yang Lebih Kecil Dari 0.5')
import random
n = int ( input ("Masukkan Nilai;"))
a = 0
for c in range (n):
   a+= 1
   b = random.uniform(.0, .5)
   print('data ke:', a, '==>', b)
   print("selesai")
   ```
#### OUTPUT
![Screenshot (24)](https://user-images.githubusercontent.com/73010098/98456572-ec297500-21b1-11eb-8749-3c35f2c89e5c.png)

#### latihan2.py
![Screenshot (25)](https://user-images.githubusercontent.com/73010098/98456612-71ad2500-21b2-11eb-883f-4af28479ebfd.png)
#### SYNTAX 
Berikut merupakan syntax untuk menampilkan program di atas
```python
print('===== Menentukan Bilangan Terbesar =====')

max=0

while True:

    a=int(input('Masukkan Bilangan = '))

    if max < a:

        max = a

    if a==0:

        break

print('Bilangan Terbesar adalah = ',max)
```
#### OUTPUT
![Screenshot (26)](https://user-images.githubusercontent.com/73010098/98456691-40812480-21b3-11eb-8893-6c10f8004a45.png)

#### Program1.py

#### SYNTAX
Berikut merupakan syntax untuk menampilkan program diatas
```python
x=100000000

sum=0

y=0
lb = [int(0), int(0), int(x) * .1, int(x) * .1, int(x) * .5, int(x) * .5, int(x) * .5, int(x) * .2]

print('modal awal seorang pengusaha:', x)

for i in lb :

    sum=sum+i

    y+=1

    print('laba bulan ke-', y, 'sebesar :', i)
```
#### PENJELASAN PROGRAM
Penjelasan Program
```python
x=100000000
```
Menampilkan kalimat Modal Awal : dan data yang berisi di n yaitu 100000000.
```python
lb = [int(0), int(0), int(x) * .1, int(x) * .1, int(x) * .5, int(x) * .5, int(x) * .5, int(x) * .2]
```
Untuk Mendeklarasikan presentase laba tiap bulan dan di kali dengan x atau data inputan modal investasi yaitu 100000000.
```python
print('laba bulan ke-', y, 'sebesar :', i)
```
untuk perulangan data dengan isi data yaitu Y dengan menampilkan urutan laba perbulan sesuai range yang di tentukan dengan hasil ke untukan yang di inpput dari data Y.
```python
print('total laba yang didapat adalah:', sum)
```
berisi data penjumlahan data angka yang ada didalam kode A,B,C,D,E,F,G,H yang akan di tampilakan atau dicetak di jumlah laba selama 8 bulan.
#### OUTPUT
Dibawah ini merupakan hasil output dari syntax diaatas
![Screenshot (27)](https://user-images.githubusercontent.com/73010098/98456886-6a871680-21b4-11eb-945b-7c992cbbc6a2.png)
## AUTHOR SITI LATIFAH - 312010321





