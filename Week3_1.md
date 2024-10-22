### Računalo kao dio IS

- Bistabili - elektronički sklopovi s dva stabilna stanja; osnovica za složenije digitalne sklopove

- Digitalno računalo razumije samo binarni zapis sadržaja -KODIRANJE

---

#### Bit, Bajt, Strojna riječ

- Bit - jedna znamenka u binarnom kodnom zapisu. Predstavlja najmanju jedinicu za zapis binarnih podataka

- Bajt - Bajt je duljine 8 bitova i predstavlja osnovnu jedinicu zapisa s kojom računalo manipulira

    - 16-bitna riječ = 2 bajta
    - 32-bitna riječ = 4 bajta

- Različite komponente zahtijevaju određeni format zapisa, pa se koriste odgovarajući kodovi za svaku vrstu podataka
    
    - npr: ASCII, BCD...
    - dotični kodni sustav mora imati dovoljno veliku abecedu tj. mora sadržavati dovoljno velik broj permutacija elementarnih kodnih simbola

- Redundanca - razlika između broja mogućih i broja iskorištenih binarnih riječi(permutacija) u nekom kodu

#### Provjera partiteta

- služi za otkrivanje grešaka nastalih tijekom prijenosa podataka između različitih jedinica za obradu u računalnom sustavu 

    - koristi se bit parnosti - jedan od bitova u bajtu ili strojnoj riječi rezerviran je za provjeru pariteta i neiskoristiv je za pohranu stvarnih podataka

- može biti:
    
    - parna = broj jedinica u bajtu mora biti paran
    - neparna = broj jedinica u bajtu mora biti neparan

- Neparna provjera :
    
    - 01110101 $\rightarrow$ 01110101 - ispravan prijenos

    - 01110101 $\rightarrow$ 01 $\fbox{0}$ 10101 - neispravan prijenos

---

#### Tipovi podataka 
    
- Diskretni 

    -  Cjelobrojni, nenumerički 
- Nediskretni: 
    - Brojevi s nepomičnim binarnim zarezom, Brojevi s pomičnim binarnim zarezom 

- Booleov ili logički tip 
- znakovni

- Nepakirani oblik zapisa - troši se cijeli bajt
- Pakirani oblik zapisa - koristi se za štednju prostora

---

#### Brojevni sustavi

- Binarni u oktalni $\rightarrow$ po tri bita
- Binarni u heksadekadski $\rightarrow$ po četiri bita 
- Dekadski s decimalnim brojem - cijeli dio normalno, decimalni npr. 0,75 x 2, 0.5 x 2 = 1 1(čita se istim redom)

  **Oduzimanje dvojnim komplementom** $\rightarrow$ znaš(puni s nulama do iste vrijednosti broj okreni 0 i 1, nakon toga dodaj 1 = dobijes dvojni komplement. Zbroji prvi broj koji je nepromijenjen s dvojnim komplementom) **Za Frana!!! - Jedinica ekstra se makne na početku**




