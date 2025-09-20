# Uppgift 2 – Programmering Nivå 1

## Beskrivning
Detta program innehåller flera små övningar för att träna på **villkor (if/else)** och logiska operatorer i Python.  
Programmet är menybaserat – du kan välja vilken övning du vill köra.

### Innehåll:
1. Even or odd – kontrollera om ett tal är jämnt eller udda.  
2. Age categories – avgör om en person är *Child*, *Teenager* eller *Adult*.  
3. Compare two numbers – jämför två tal.  
4. Grade checker – översätt poäng (0–100) till betyg A–F.  
5. Password checker – kolla om lösenordet är `secret123`.  
6. Logical operator test – kolla om man får rösta i Sverige.  
7. Bonus – skriv veckodag och få ett meddelande.  

---

## Så här kör du
1. Öppna **Kommandotolken** (eller PowerShell).  
2. Navigera till mappen där filen ligger:  
   ```bash
   cd Uppgift-2
   ```
3. Kör programmet:  
   ```bash
   py Uppgift2.py
   ```
   (eller `python Uppgift2.py` beroende på din installation).  

---

## Exempelutskrift
```
=== Menu ===
1) Exercise 1: Even or odd
2) Exercise 2: Age categories
3) Exercise 3: Compare two numbers
4) Exercise 4: Grade checker
5) Exercise 5: Password checker
6) Exercise 6: Logical operator test
7) Bonus: Day of the week
0) Exit
Choose an option: 1
Enter a number: 7
Odd
```

---

## Funktioner
- Säkrare heltalsinmatning (programmet ber om nytt värde om man skriver fel).  
- Meny så man enkelt kan testa alla uppgifter utan att starta om programmet.  
- Bonusdel som tränar på `lower()` och listor.  

---

## Filstruktur
```
Uppgift-2/
│
├── Uppgift2.py   # Själva programmet
└── README.md     # Denna fil
```

---

## ✍️ Författare
- Lucas Bergman
