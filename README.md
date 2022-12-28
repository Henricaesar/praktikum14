# praktikum12
## String 

~~~bash
Nama    :Henri Caesar Bimantara

Nim     :312210017

Kelas   :TI.22.C1
~~~




## String

### Penjelasan

#### Code


- Latihan 1


~~~bash
txt = 'Hello World'
print(f"Teks = {txt}")
# Menghitung jumlah karakter
print("Jumlah Karakter = ",len(txt))
# Mengambil karakter terakhir
a = txt[-1]
print('Karakter Terakhir = ',a)
# Mengambil karakter ke-2 sampai ke-4
b = txt[2:5]
print(f"Karakter ke-2 sampai ke-4 = {b}")
# Hilangkan spasi pada text 
c = txt.replace(" ","")
print("Spasi di hilangkan = ",c)
# Ubah teks menjadi huruf besar
d = txt.upper()
print(f"Teks menjadi huruf besar = {d}")
# Ubah teks menjadi huruf kecil
e = txt.lower()
print(f"Teks menjadi huruf kecil = {e}")
# Ganti karakter H dengan karakter J
f = txt.replace("H","J")
print(f"Menganti karakter H dengan J = {f}")
~~~

![image](Screenshot/Screenshot%20(16).png)










- Latihan 2


~~~bash
umur = int(input("Silahkan masukan umur anda : ))
txt = 'Hello, nama saya John Still In The House, dan umur saya adalah {0} tahun'
print(txt.format(umur))
~~~



### Output



![image](Screenshot/Screenshot%20(17).png)









Terimakasih
