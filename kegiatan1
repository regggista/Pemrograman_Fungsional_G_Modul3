def konversi(minggu=0, hari=0, jam=0, menit=0):
    return ((minggu * 7 * 24 * 60) + (hari * 24 * 60) + (jam * 60) + menit)

data = [
    "3 minggu 3 hari 7 jam 21 menit",
    "5 minggu 5 hari 8 jam 11 menit",
    "7 minggu 1 hari 5 jam 33 menit"
]

outputData = []

for item in data:
    components = item.split()
    minggu = int(components[0])
    hari = int(components[2])
    jam = int(components[4])
    menit = int(components[6])
    konvert = konversi(minggu, hari, jam, menit)
    outputData.append(konvert)

print(outputData)
