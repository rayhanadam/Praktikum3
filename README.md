# Tugas Pertemuan 6 Praktikum 3 <hr> <br>

## Daftar isi 
1. [Latihan 1](#Latihan-1)
2. [Latihan 2](#Latihan-2)
3. [Latihan 3](#Latihan-3)
4. [Menghitung Luas dan Keliling Lingkaran](#Menghitung Luas dan Keliling Lingkaran)

# Latihan 1
<br>
* buat Source Code <br>

![Screenshot_20221031_132357](https://user-images.githubusercontent.com/115473812/198944716-7a8a0454-5052-4ab5-911c-6c494838b205.png)

```python 
#penggunaan end
print('A', end=' ')
print('B', end=' ')
print('C', end=' ')
print()
print('X')
print('Y')
print('Z')

# penggunaan separator
w,x,y,z = 10,15,20,25
print(w,x,y,z)
print(w,x,y,z, sep = ',')
print(w,x,y,z, sep = '')
print(w,x,y,z, sep = ':')
print(w,x,y,z, sep = '-----')

#string format
print(0, 10**0)
print(1, 10**1)
print(2, 10**2)
print(3, 10**3)
print(4, 10**4)
print(5, 10**5)
print(6, 10**6)
print(7, 10**7)
print(8, 10**8)
print(9, 10**9)
print(10, 10**10)

#string format
print('{0:3} {1:>16}'.format(0, 10**0))
print('{0:3} {1:>16}'.format(1, 10**1))
print('{0:3} {1:>16}'.format(2, 10**2))
print('{0:3} {1:>16}'.format(3, 10**3))
print('{0:3} {1:>16}'.format(4, 10**4))
print('{0:3} {1:>16}'.format(5, 10**5))
print('{0:3} {1:>16}'.format(6, 10**6))
print('{0:3} {1:>16}'.format(7, 10**7))
print('{0:3} {1:>16}'.format(8, 10**8))
print('{0:3} {1:>16}'.format(9, 10**9))
print('{0:3} {1:>16}'.format(10, 10**10))
```

* Lakukan Run File
* Hasil Output : <br>
![Screenshot_20221031_132629](https://user-images.githubusercontent.com/115473812/198945048-7f42a500-f462-4073-9c84-6b0bfd39562c.png)

<br>

```

A B C 
X
Y
Z
10 15 20 25
10,15,20,25
10152025
10:15:20:25
10-----15-----20-----25
0 1
1 10
2 100
3 1000
4 10000
5 100000
6 1000000
7 10000000
8 100000000
9 1000000000
10 10000000000
  0                1
  1               10
  2              100
  3             1000
  4            10000
  5           100000
  6          1000000
  7         10000000
  8        100000000
  9       1000000000
 10      10000000000

```
<br><br>

# Latihan 2 
![Screenshot_20221031_133009](https://user-images.githubusercontent.com/115473812/198945679-ec8e36e0-e627-460c-ad29-6e0e6a05d6ec.png)

* buat kode <br>

<br>

```python
#input nilai variabel
a = input("masukan nilai pertama: ")
b = input("masukan nilai kedua: ")

#cetak nilai variabel
print("variabel a = ", a)
print("variabel b = ", b)
print("Hasil Penggabungan {1} & {0} = %s".format(a,b) %(a+b))

#konversi nilai variabel 
a = int(a)
b = int(b)


print("Hasil penjumlahan {1} + {0} = %d".format(a,b) %(a+b))
print("Hasil pembagian {1} / {0} = %d".format(a,b) %(a/b))
```

* lakukan run file
* hasil output :
![Screenshot_20221031_133020](https://user-images.githubusercontent.com/115473812/198945724-d45c66ab-855c-46dd-8efb-bf8dd7e0caa2.png)

<br>

```
masukan nilai pertama: 3
masukan nilai kedua: 5
variabel a =  3
variabel b =  5
Hasil Penggabungan 5 & 3 = 35
Hasil penjumlahan 5 + 3 = 8
Hasil pembagian 5 / 3 = 0
```
# Latihan 3
* buat kode <br>
![Screenshot_20221031_133702](https://user-images.githubusercontent.com/115473812/198946537-bffb9beb-73eb-4ee2-9181-eac6981f9878.png)

<br>

```python
# menampilkan output * berbentuk diamond
inputData = eval(input("Enter diamond's height: "))

for i in range(inputData):
    print(" " * (inputData - i), "*" * (2*i + 1))
for i in range(inputData - 2, -1, -1):
    print(" " * (inputData - i), "*" * (2*i + 1))
```

* lakukan run file
* Hasil Output : <br>
![Screenshot_20221031_133721](https://user-images.githubusercontent.com/115473812/198946897-ddbcbc9a-6aea-4ed6-817c-a56affd9f81b.png)

<br>

# Menghitung Luas dan Keliling Lingkaran
* buat flowchart <br>
<img width="625" alt="flow" src="https://user-images.githubusercontent.com/115473812/198947513-f6f7161a-d30a-4586-a307-95095df8275f.png">

* Buat code <br>
![Screenshot_20221031_134518](https://user-images.githubusercontent.com/115473812/198947776-16477636-8baf-49db-8d1a-bf9561a78fb3.png)

```
# import module math
import math

# Variable jariJari menampung nilai input yang dimasukan yaitu berupa string
jariJari = input('Masukan jari-jari lingkaran :')

"""
rumus luas & keliling lingkaran
_____________________________________
luas     = phi * r^2
keliling = 2 * phi * r
_____________________________________
"""

# convert string to integer
jariJari = int(jariJari)

# hitung luas lingkaran
luas = math.pi * (jariJari * jariJari)
```

* Lakukan run file
* Hasil Output
![Screenshot_20221031_134542](https://user-images.githubusercontent.com/115473812/198948028-410526eb-9d99-4637-8971-3fa89b95a386.png)































