### Von Neumannov model računala

### Mooreov Zakon:

 Broj tranzistora se udvostručuje svakih 18-24 mjeseca

+ Od 1946 do danas računalo u svojoj osnovi isto radi

+ Zahtjevi koji su poslužili kao ishodište za određivanje arhitekture računala:

    + Računalo opće namjene s potpuno automatskim izvođenjem programa
    + Pohranjivanje podataka(ulaznih, međurezultata i rezultata)
    + Pohranjivanje slijeda instrukcija(programa)

#### Značajke

+ Instrukcije svedene na numerički kod - podaci i instrukcije pohranjuju se u istoj jedinici(memoriji)

+ Računalo - stroj za računanje mora imati jedinicu za izvršavanje osnovnih aritmetičkih i logičkih operacija (ALU)

+ Jedinica koja "razmije" i tumači instrukcije te upravlja slijedom izvođenja operacija(Upravljačka jedinica)

+ Računalo mora imati mogućnost komunikacije s vanjskim svijetom(koristnikom, procesom, drugim računalo) jedinica koja mu to omogućava - Ulazno izlazna jedinica

---

**Strojna instrukcija je naredba kojom računalom govorimo što napraviti s sadržajem neke memorijske lokacije**

**Operand je sadržaj s kojim računalo nešto radi**

Četiri osnovne funkcijske jedinice koje čine računalo:

+ ALU
+ Upravljačka 
+ Ulazno-izlazna 
+ Memorija

Jezgra procesora je jedinica koja može samostalno izvršiti instrukcije

ALU mora sadržavati registre

+ Registar - najmanji dio memorije koji sadrži operand

    + Operandi Von Neumannovog računala je duljine 40 bita 

**Stroja instrukcija Von Neumanna**

| op kod (8 bita)| adresa(12 bita) | op kod | adresa |
|------------ | -------------- | ----------- |  --------------- |
|lijeva instrukcija| | desna instrukcija|  |

|$\leftarrow$ ----------------20 bita----------------- $\rightarrow$|$\leftarrow$ ------------ 20 bita -----------$\rightarrow$|

|$\leftarrow$ ------------------------------------- 40 bita ------------------------------------- $\rightarrow$|

*Na svaku adresu ide 40 bitova*

U programskom brojilu se nalazi adresa podatka koji se treba dohvatiti

Dekoder dio upravljačke jedinice koji će jednoznačno dekodirati instrukciju



##### Instrukcijski ciklusi

+ Faza pribavi
+ Faza izvrši





