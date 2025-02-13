# Rezervare-sali

## Descriere
Acest program permite utilizatorilor să gestioneze rezervările pentru săli de evenimente. Utilizatorii pot vizualiza sălile disponibile, pot face o rezervare sau să anuleze una și pot căuta săli în funcție de numărul de locuri sau după anumite funcționalități.

## Funcționalități
- Adăugarea unei rezervări pentru o sală
- Vizualizarea sălilor disponibile
- Anularea unei rezervări pe baza informațiilor introduse
- Căutarea unei/mai multor săli în funcție de numărul de locuri și anumitor funcționalități

## Structura Fișierelor
- `main.c` - Conține funcțiile principale ale programului
- `rezervari.txt` - Stochează informațiile despre rezervări
- `sali.txt` - Stochează informațiile despre săli
- `headers.h` - Conține definiții și structuri utilizate în program


## Utilizare
Cum se anulează o rezervare
1. Introdu numele folosit pentru rezervare
2. Introdu ora și data rezervării
3. Selectează sala rezervată
4. Programul va verifica fișierul `rezervari.txt` și va elimina rezervarea dacă este găsită
   
Cum se face o rezervare
1. Vei primi o listă cu sălile disponibile și detaliile despre acestea
2. Vei introduce numărul sălii care dorești să o rezervi
3. Introduci numele pe care dorești să faci rezervarea, apoi data și ora pentru rezervare
4. Programul va adăuga în fișierul `rezervari.txt` rezervarea  

## Observații
- Fișierul `rezervari.txt` trebuie să existe și să fie accesibil
- Programul folosește funcții pentru manipularea fișierelor și validarea datelor


