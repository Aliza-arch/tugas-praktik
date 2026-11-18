Pengumpulan C. Soal praktik 
print ("===SISTEM PENGELOLAAN BARANG===")
print ("Toko Serba Ada")

nama_barang =input("Masukkan Nama Barang:")
stok=int(input("Masukkan jumlah stok awal"))

print("===PILIH TRANSAKSI")
print("1.barang masuk")
print("2.barang keluar")
print("3.stok akhir")
pilihan= input("Masukkan pilihan(1/2/3)")

if pilihan == "1":
   masuk = int(input("Masukan jumkah barang masuk :"))
   stok = stok + masuk
   print(f"barang masuk berhasil!stok {nama_barang}sekarang:{stok}")

elif pilihan == "2":
   keluar = int(input("Masukkan jumlah barang keluar:"))
if keluar > stok:
   print (f"stok saat ini hanya:")
else: 
   stok = stok + keluar 
   print(f"Barang keluar berhasil! stok sekarang:")
if pilihan == "3":
   Break 
else:
   print("pilihan tidak valid!")

   print ("\n---HASIL AKHIR")
   print(f"Nama barang :(Nama_Barang)")
   print(f"Jumlah stok terakhir:{stok}")
   print("Terima Kasih")
