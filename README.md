# praktikum-6
# Fungsi

• Membuat Fungsi

• Memanggil Fungsi
def tampilkan(nama): #definisi fungsi
"""fungsi ini untuk menampilkan nama yang dikirim melalui
parameter"""
print("Hello"

, nama, ". Selamat datang")

tampilkan("Ari") #call function with string input 'Ari'
nama = "Ari Santoso"
tampilkan(nama) #call function with variable nama

# Fungsi dengan return value

• Membuat Fungsi

• Memanggil Fungsi
def hitung(a, b): #definisi fungsi
return a + b

hitung(4, 5) #call function with int input 4 and 5
a = 10
b = 15
hitung(a, b) #call function with variable a and b

# Fungsi dengan Argumen Default

• Membuat Fungsi

• Memanggil Fungsi
def tampilkan(nama, msg=

". Apa kabar?"): #definisi fungsi
"""fungsi ini untuk menampilkan nama yang dikirim melalui
parameter"""
print("Hello"

, nama, msg)

tampilkan("Ari") #call function with string input 'Ari'
nama = "Ari Santoso"
tampilkan(nama) #call function with variable nama
tampilkan(nama, ". Selamat datang") #call function with

# Fungsi dengan Keyword Arguments

• Membuat Fungsi

• Memanggil Fungsi
def hitung(a, b): #definisi fungsi
return a + b

hitung(4, 5) #call function with int input 4 and 5
hitung(a=10, b=15) #call function with keyword a and b
hitung(b=15, a=25) #call function with keyword b and a
hitung(10, b=25) #call function with input 10 and keyword b

# Fungsi dengan Arbitrary Arguments

• Membuat Fungsi

• Memanggil Fungsi
def tampilkan(*names): # definisi fungsi
for nama in names:
print("Hello"

, nama, ". Apa kabar?")

tampilkan("Ari") #call function with string input 'Ari'
tampilkan("Ari"
,
"Dina"
,
"Ratna") #call function with list of name

# Lambda Function

my_list = [1, 5, 4, 6, 8, 11, 3, 12]

#filter out only the even items from a list
new_list = list(filter(lambda x: (x%2 == 0) , my_list))

#Output: [4, 6, 8, 12]
print(new_list)

#double each item in a list using map()
new_list = list(map(lambda x: x * 2 , my_list))

#Output: [2, 10, 8, 12, 16, 22, 6, 24]
print(new_list)

# Latihan 1

Ubahlah kode dibawah ini menjadi fungsi menggunakan lambda.

import math

def a(x):
return x**2

def b(x, y):
return math.sqrt(x**2 + y**2)

def c(*args):
return sum(args)/len(args)

def d(s):
return "".join(set(s))

![code math](https://github.com/Reardhyan/praktikum-6/assets/148032571/420847cf-7706-4e95-a6bf-b674920a515f)

# Tugas Praktikum

Buat program sederhana dengan mengaplikasikan penggunaan fungsi
yang akan menampilkan daftar nilai mahasiswa, dengan ketentuan:

• Fungsi tambah() untuk menambah data

• Fungsi tapilkan() untuk menampilkan data

• Fungsi hapus(nama) untuk menghapus data berdasarkan nama

• Fungsi ubah(nama) untuk mengubah data berdasarkan nama

• Buat flowchart dan penjelasan programnya pada README.md. 

• Commit dan push repository ke github.

![code praktikum 6](https://github.com/Reardhyan/praktikum-6/assets/148032571/1fd2ffbf-62f5-491b-b538-e03c1a5ab19b)
![Screenshot (141)](https://github.com/Reardhyan/praktikum-6/assets/148032571/61ed7580-c7b9-4ad4-86e6-102f70d89045)


