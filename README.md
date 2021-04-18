# LAB-9
LIST
print("====Program Hitung Tengah ====")
banyak = int(input("Mau hitung berapa angka: "))
m = []
for i in range (banyak):
    num= (input("Masukkan angka: "))
    m = m + [num]
k = max(m)
b = min(m)
print("Nilai terbesar dari list:",k)
print("Nilai terkecil dari list:",b)
m = sorted(m)

z = 0

for i in m:
    if i==k or i==b:
        continue
    else:
        z += int(i)

print("Hasil Perhitungan tengah dari",m, "yaitu",z)
