# Data_structures
STRUKTURE PODATAKA
Zadaci za laboratorijske vježbe
1. Napisati program koji prvo pročita koliko redaka ima datoteka, tj. koliko ima studenata zapisanih u datoteci. Nakon toga potrebno je dinamički alocirati prostor za niz struktura studenata (ime, prezime, bodovi) i učitati iz datoteke sve zapise. Na ekran ispisati ime, prezime,apsolutni i relativni broj bodova. Napomena: Svaki redak datoteke sadrži ime i prezime studenta, te broj bodova na kolokviju. relatvan_br_bodova = br_bodova/max_br_bodova*100
2. Definirati strukturu osoba (ime, prezime, godina rođenja) i napisati program koji:
a) dinamički dodaje novi element na početak liste,
b) ispisuje listu,
c) dinamički dodaje novi element na kraj liste,
d) pronalazi element u listi (po prezimenu),
e) briše određeni element iz liste,
U zadatku se ne smiju koristiti globalne varijable.
3. Prethodnom zadatku dodati funkcije:
a) dinamički dodaje novi element iza određenog elementa,
b) dinamički dodaje novi element ispred određenog elementa,
c) sortira listu po prezimenima osoba,
d) upisuje listu u datoteku,
e) čita listu iz datoteke.
4. Napisati program za zbrajanje i množenje polinoma. Koeficijenti i eksponenti se čitaju iz datoteke. Napomena: Eksponenti u datoteci nisu nužno sortirani.
5. Za dvije sortirane liste L1 i L2 (mogu se pročitati iz datoteke ili unijeti ručno, bitno je samo da su sortirane), napisati program koji stvara novu vezanu listu tako da računa:
a) L1L2,
b) L1L2.
Liste osim pokazivača na slijedeću strukturu imaju i jedan cjelobrojni element, po kojem su sortirane.
6. Napisati program koji pomoću vezanih listi simulira rad:
a) stoga,
b) reda.
Napomena: Funkcija "push" sprema cijeli broj, slučajno generirani u opsegu od 10 -100.
7. Napisati program koji iz datoteke čita postfiks izraz i zatim korištenjem stoga računa rezultat. Stog je potrebno realizirati preko vezane liste.
8. Napisati program koji pomoću vezanih listi (stabala) predstavlja strukturu direktorija. Omogućiti unos novih direktorija i pod-direktorija, ispis sadržaja direktorija i povratak u prethodni direktorij. Točnije program treba preko menija simulirati korištenje DOS naredbi: 1- "md", 2 - "cd dir", 3 - "cd..", 4 - "dir" i 5 – izlaz.
9. Napisati program koji omogućava rad s binarnim stablom pretraživanja. Treba omogućiti unošenje novog elementa u stablo, ispis elemenata, brisanje i pronalaženje nekog elementa.
10. Napisati program koji iz datoteke čita postfiks izraz i zatim stvara stablo proračuna. Iz gotovog stabla proračuna upisati u datoteku infiks izraz.
11. Napisati kod koji za zadane podatke studenata (matični broj, ime i prezime) pravi hash tablicu sa zasebnim redovima. Tablica ima 11 mjesta, a funkcija za preslikavanje ključ računa da se zbraja ASCII vrijednost prvih pet slova prezimena i zatim računa ostatak cjelobrojnog dijeljenja te vrijednosti s veličinom tablice. Studenti s istim ključem se pohranjuju u vezanu listu sortiranu po prezimenima i imenima. Kada se tablica izgradi treba ispisati cijelu tablicu (naglasiti na kojem ključu se nalaze koji podaci) te ponuditi mogućnost da se za određenog studenta (prezime i ime) ispiše njegov matični broj.
