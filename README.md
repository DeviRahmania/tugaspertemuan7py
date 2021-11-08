# lab 2 latihan 1
## soal
disini saya akan mengerjakan soal sebagai berikut

![img](gambar/soallthn1.png)

cara mengerjakan nya masukan syntak dibawah ini

    N=int(input("banyaknya data = "))
    if N>0:
        i=1
        x=int(input("data ke -"+str(i)+"="))
        max=x;total=x
        for i in range(2,N+1):
            x=int (input("data ke -"+str(i)+"="))
            total+=x
            if max<x:
                max=x

        print("bilangan terbesar =",max)

yang akan menghasilkan output berikut ini 

![img](gambar/output1.png)

# lab 2 latihan 2
## soal
disini saya akan mengerjakan soal sebagai berikut

![img](gambar/soallthn2.png)

cara mengerjakan nya masukan syntak dibawah ini

    data = []
    for i in range (5):
        x =int(input("masukan bilangan : "))
        data.append(x)
    print('data sebelum diurutkan: ',data)
    list.sort(data)
    print('data setelah diurutkan: ',data)

yang akan menghasilkan output berikut

![img](gambar/output2.png)

# lab 3 latihan 1
## soal
disini saya akan mengerjakan soal sebagai berikut

![img](gambar/soallthn3.png)

cara mengerjakan nya masukan syntak dibawah ini

    baris = 10
    kolom = baris

    for bar in range(baris):
        for col in range(kolom):
            tab = bar+col
            print("{0:>5}".format(tab), end='')
        print()


yang akan menghasilkan output berikut

![img](gambar/hasil1.png)

# lab 3 latihan 2
## soal
disini saya akan mengerjakan soal sebagai berikut

![img](gambar/soallthn4.png)

cara mengerjakan nya masukan syntak dibawah ini

    import random
    print(40*"=")
    print("Bilangan acak yang lebih kecil dari 0,5")
    print(40*"=")
    jum = int( input("Masukan nilai n : "))
    i = 0
    for i in range(jum):
        i += 1
        angkaDec = random.uniform(0, 0.5)
        print("Data ke", i, " = ", angkaDec)

yang akan menghasilkan output berikut

![img](gambar/hasil2.png)