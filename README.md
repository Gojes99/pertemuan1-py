### kode dari pertemuan 1
## Mata kuliah pemrograman GUI
# S1SE01A

Microsoft Windows [Version 10.0.17763.379]

(c) 2018 Microsoft Corporation. All rights reserved.


C:\Users\User>python

Python 3.7.1 (default, Dec 10 2018, 22:54:23) [MSC v.1915 64 bit (AMD6

4)] on win32

Type "help", "copyright", "credits" or "license" for more information.

>>> pins = {"Firman": 6969, "Galuh": 8989, "Yahya": 0909}

>>> pins["Firman"]

6969

>>> type(pins["Firman"])

<class 'int'>

>>> pins.keys()

dict_keys(['Firman', 'Galuh', 'Sembodo'])

>>> pins.values()

dict_values([6969, 8989, 0909])

>>> pins["Princesben"] = 0707

>>> pins

{'Firman': 6969, 'Galuh': 8989, 'Sembodo': 0909, 'Princesben': 0707}

>>> pins.pop("Princesben")

0707

>>> pins

{'Firman': 6969, 'Galuh': 8989, 'Sembodo': 0909}

>>> pins["Affandi"] = 'AB123'

>>> pins

{'Firman': 6969, 'Galuh': 8989, 'Sembodo': 0909, 'Affandi': 'AB123'}

>>> masukan =input("Masukan Nama Anda :")

Masukan Nama Anda :Firman

>>> bilangan = input("Masukan angka :")

Masukan angka :1000

>>> print(masukan)

Firman

>>> type(masukan)

<class 'str'>

>>> bilangan = int(input("masukan angka :"))

masukan angka :99

>>> type(bilangan)

<class 'int'>

>>> print(bilangan**2)

9801

>>> bilangan= float(input("masukan angka :"))

masukan angka :10

>>> print(bilangan/2)

5.0

>>> bilangan = float(input("masukan angka :"))

masukan angka :9.5

>>> type(bilangan)

<class 'float'>

>>> print(bilangan/2)

4.75

>>> pins

{'Firman': 6969, 'Galuh': 8989, 'Sembodo': 0909, 'Affandi': 'AB123'}

>>> pins.values()

dict_values([1234, 3333, 9999, 'AB123'])

>>> kode = 9999

>>> kode in pins.values()

True

>>> kode = 1111

>>> kode in pins.values()

False

>>> if 1<5:

... print("Yes")

... else:

... print("No")

...

Yes

>>>

>>> if 1==5:

... print("Benar")

... else:

... print("Salah")

...

Salah

>>> user_input = float(input("Masukan angka :"))

Masukan angka :77

>>> if user_input >100:

... print("Greater")

... else:

... print("Smaller")

...

Smaller

>>> if user_input >100:

... print("Lebih Besar")

... else user_input == 100:

  File "<stdin>", line 3

    else user_input == 100:

                  ^

SyntaxError: invalid syntax

>>> if user_input >100:

... print("Lebih Besar")

... elif user_input == 100:

... print("Sama Dengan")

... else:

... print("Lebih Kecil")

...

Lebih Kecil

>>> user_input = float(input("Masukan aAngka :"))

Masukan aAngka :100

>>> if user_input >100:

... print("Lebih Besar")

... elif user_input == 100:

... print("Sama Dengan")

... else:

... print("Lebih Kecil")

...

Sama Dengan

>>> def printing():

... print("Wahai")

... print("Kroco Krocoku")

...

>>> printing()

Wahai

Kroco Krocoku

>>> def luas_persegi(sisi):

... luas = sisi * sisi

... return luas

...

>>> luas_persegi(9)

81

>>> def luas_segitiga(alas,tinggi):

... luas = (alas*tinggi)/2

... print("Luas Segitiga : %d" %luas)

...

>>> luas_segitiga(100,50)

Luas Segitiga : 2500

>>> def hitung_umur(tahun):

... umur = 2019-tahun

... print("Umur Saya : %d" %umur)

...

>>> hitung_umur(1998)

Umur Saya : 21

>>>

>>>

