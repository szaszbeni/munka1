# Egy kódot kell csinálni ami bekér termékeket és öszeadja, addig kell be kérni amíg igaz nem irja be a 0 (packetracer ábra)

def feladat():

    a = input("Kérek egy terméket!")
    termek="router switch pc laptop telefon"
    eszkoz= 0
    for keres in a :
        if keres in termek:
            eszkoz += 1
    print(eszkoz)



def feladat2():
    termek=("router", "switch", "pc", "laptop", "telefon")
    hatar=0 
    ar=0
    szoveg=""
    while (termek>hatar):
        termek=int(input("Kerek egy termeket!:"))
        if (termek!=0):
            ar=ar+termek
            szoveg=szoveg + str(termek)
            utolsoelotti=termek
            szoveg=szoveg + ","
    kiiras="termekek("+utolsoelotti+") osszege:"
    print(kiiras,osszege)
    

#def feladat3():


#feladat()
#feladat2()
