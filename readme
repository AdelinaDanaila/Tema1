# Tema1
fisier = open('numbers.txt')
for linie in fisier:
    suma_pe_linie = 0
    numere = linie.split(",")
    for numar in numere:
        suma_pe_linie = suma_pe_linie + int(numar)
print(suma_pe_linie)
    
fisier = open('numbers.txt')
suma = 0
for linie in fisier:
    numere = linie.split(",")
    suma_pe_linie = 0
    for numar in numere:
        suma_pe_linie = suma_pe_linie + int(numar)
    suma = suma + suma_pe_linie
print(suma)

fisier = open('numbers.txt')
continut = ""
for linie in fisier:
    linie = linie.strip("\\n")
    numere = linie.split(",")
    linie_fara_virgule = ''.join(numere)
    continut = continut + linie_fara_virgule
print(continut)

fisier = open('numbers.txt')
mai_mari_de_30 = 0
for linie in fisier:
    numere = linie.split(",")
    for numar in numere:
        if int(numar) > 30:
            mai_mari_de_30 = mai_mari_de_30 + 1
print(mai_mari_de_30)

fisier = open('numbers.txt')
mai_mici_decat_i = 0
for i in range (1, 100):
    j=int(i)
    for linie in fisier:
        numere = linie.split(",")
        for numar in numere:
            numar_intreg = int(numar)
            print (numar_intreg + " " + j)
            if numar_intreg < j:
                mai_mici_decat_i = mai_mici_decat_i + 1
print(mai_mici_decat_i)
