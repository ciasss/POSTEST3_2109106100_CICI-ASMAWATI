# PROGRAM KASIR
# Variabel
nama_barang = [""] * (20)
harga_barang = [0] * (20)
jumlah_barang = [0] * (20)
total_harga = [0] * (20)
total_bayar = [0] * (20)
discount = [0] * (20)
no = 0
p = 0
r = 0

# Menu
def menu () :
    print("=======================================================")
    print("                   TREASURE THINGZ                     ")
    print("=======================================================")
    print("           Nama Barang                    Harga        ")
    print("=======================================================")
    print("               HOODIE POLOS                            ")
    print("                Ukuran S                   Rp. 67000   ")
    print("                Ukuran M                   Rp. 72000   ")
    print("                Ukuran L                   Rp. 72000   ")
    print("                Ukuran XL                  Rp. 77000   ") 
    print("                Ukuran XXL                 Rp. 77000   ")
    print("               HOODIE SABLON DAN BORDIR                ")
    print("                Ukuran S                   Rp. 72000   ")
    print("                Ukuran M                   Rp. 77000   ")
    print("                Ukuran L                   Rp. 77000   ")
    print("                Ukuran XL                  Rp. 83000   ")
    print("                Ukuran XXL                 Rp. 83000   ")
    print("               BASIC SWEATER                           ")
    print("                Ukuran S                   Rp. 63000   ")
    print("                Ukuran M                   Rp. 70000   ")
    print("                Ukuran L                   Rp. 70000   ")
    print("                Ukuran XL                  Rp. 76000   ")
    print("                Ukuran XXL                 Rp. 76000   ")
    print("               KAOS POLOS                              ")
    print("                Ukuran S                   Rp. 53000   ")
    print("                Ukuran M                   Rp. 58000   ")
    print("                Ukuran L                   Rp. 58000   ")
    print("                Ukuran XL                  Rp. 63000   ")
    print("                Ukuran XXL                 Rp. 63000   ")
    print("              KAOS SABLON DAN BORDIR                   ")
    print("                Ukuran S                   Rp. 56000   ")
    print("                Ukuran M                   Rp. 61000   ")
    print("                Ukuran L                   Rp. 61000   ")
    print("                Ukuran XL                  Rp. 66000   ")
    print("                Ukuran XXL                 Rp. 66000   ")
    print("=======================================================")
    print("                   !!!!!!!PROMO!!!!!!!                 ")
    print("             Min. Belanja 150RB DISCOUNT 10%           ")
    print("             Min. Belanja 250RB DISCOUNT 25%           ")
    print("=======================================================")
menu()
print("")

# Program
while True : 
    nama_barang[p] = input("Nama Barang ke - " + str(p+1) + ": ")
    harga_barang[p] = int(input("Harga Barang : "))
    jumlah_barang[p] = int(input("Jumlah Barang : "))

    total_harga[p] = harga_barang[p] * jumlah_barang[p]
    discount[p] = total_harga[p] - (total_harga[p] * 0)
    kontinu = input("Apakah Anda Ingin Lanjut? [Y/T] : ")

    p = p + 1

    if not(kontinu=="Y" or kontinu=="y") : break

total = 0
print("")
print("==============================================================")
print("                       TREASURE THINGZ                        ")
print("==============================================================")
print("No       Nama                   Harga       Jumlah      Harga ")
print("         Barang                 Satuan      Barang      Total ")
print("==============================================================")

for r in range(0,p) :
    no = no + 1
    total = total + discount[r]
    if total >=150000 :
        discount[r] = 0.10 * total
        total_bayar[r] = total - discount[r]
    elif total>=250000 :
        discount[r] = 0.25 * total
        total_bayar[r] = total - discount[r]
    else :
        discount[r] = 0 * total
        total_bayar[r] = total - discount[r]
    
    print("{}       {}              {}      {}      {}".format(no, nama_barang[r], harga_barang[r], jumlah_barang[r], total_harga[r]))

print("==============================================================")
print("Total Harga : {}".format(total))
print("Discount : {}".format(discount[r]))
print("Total Pembayaran : {}".format(total_bayar[r]))
print("==============================================================")
print("              TERIMAKASIH SUDAH BERBELANJA DISINI !           ")
print("                       TREASURE THINGZ                        ")
print("==============================================================")
