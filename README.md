# Menghitung luas dan keliling lingkarn menggunakan Python
1. Buat File bernama luasKelilingLingkaran.py
2. Berikut Flowchart untuk menghitung luas dan keliling lingkaran
    <img width="625" alt="flow" src="https://user-images.githubusercontent.com/115972485/198948996-7d65a138-87f8-43f7-a642-71bbf1fe08d6.png">
3. Lalu Masukan CODE berikut :

            #import module math
          import math

          #Variable jariJari menampung nilai input yang dimasukan yaitu berupa string
          jariJari = input('Masukan jari-jari lingkaran :')

          """

          rumus luas & keliling lingkaran
          _____________________________________

          luas     = phi * r^2

          keliling = 2 * phi * r

          _____________________________________

          """

          #convert string to integer
          jariJari = int(jariJari)

          #hitung luas lingkaran
          luas = math.pi * (jariJari * jariJari)

          #hitung luas keliling
          keliling = 2 * math.pi * jariJari

          #output luas & keliling lingkaran
          #.2f => mengambil 2 angka setelah (,)
          print("Berikut Luas lingkaran =  ", format(luas, '.2f'))
          print("Berikut Keliling lingkaran = ", format(keliling, '.2f'))
 
 4. Ketika dijalankan Inputkan Jari jari dan Berikut Hasil nya
 
    ![ASEP1](https://user-images.githubusercontent.com/115972485/198949906-58005fc5-37cf-41dd-bbff-aa74e3fb6b9f.PNG)
    
 5. Selesai Begitulah cara menghitung luas dan keliling Lingkaran
