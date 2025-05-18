print("Hai, Selamat Datang Di Resto Kami")

banyak = int(input("untuk berapa orang? : "))

Nama = []

for i in range(0, banyak):
    print(f"orang ke {i}")
    input_nama = input("Nama : ")

    Nama.append(input_nama)

for i in range(0, len(Nama)):
    data_nama = Nama[i]
    

print("Silahkan Pilih Menu")
print("     Daftar Menu     ")
print("1 Ayam Geprek")
print("2 Soto Ayam")
print("3 Gulai Kambing")
print("4 Indomie Goreng")
print("5 Indomie Kuah")

Pilihan = []

for i in range(0, banyak):
    print(f"pilihan orang ke {i}")
    menu_pilihan = input("Menu : ")

    Pilihan.append(menu_pilihan)

    if menu_pilihan == "1":
        print("Menu Ayam Geprek Berhasil Ditambahkan")

    elif menu_pilihan == "2":
        print("Menu Soto Ayam Berhasil Ditambahkan")

    elif menu_pilihan == "3":
        print("Menu Gulai Kambing Berhasil Ditambahkan")

    elif menu_pilihan == "4":
        print("Menu Indomie Goreng Berhasil Ditambahkan")

    elif menu_pilihan == "5":
        print("Menu Indomie Kuah Berhasil Ditambahkan")

    else : 
        print("Menu Tidak Tersedia")

    if menu_pilihan == "x":
        print("Keluar Dari Program")

for i in range(0, len(Nama)):
    data_nama = Nama[i]
    data_pesanan = Pilihan[i]
    print(f"{data_nama} memesan menu no {data_pesanan}")

    
