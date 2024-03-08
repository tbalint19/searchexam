## Készítsetek egy könyvtár admin felületet.

Legyen egy input mező címre kereséshez, illetve egy select kategóriára szűréshez (sci-fi, romantikus...), valamint egy gomb, mely a keresést indítja. Minden könyvhöz legyen egy checkbox, ennek segítségével lehet átállítani, hogy a könyv jelenleg elérhető e.

### Elvárt működés:
- Az adatbázisban legalább 5 könyv van.
- Minden szűrés a backenden történik.
- Az elérhetőség átállítása is a szerveren mentődik el.
- Az elérhetőség sikeres átállítása után ezt a változást a kliens is megjeleníti.
- Sikertelen módosítás esetén egy kis üzenet jelenik meg, mely erről tájékoztat, majd 3 másodperc után eltűnik.
- Legyen lekezelve mind szerver, mind kliens oldalon a szerver oldali hiba, a kliens oldali hiba, illetve kliens oldalon a nem várt válasz és az internetkapcsolat hiánya is.

### Elvárt tech stack:
- Typescript
- Vite
- CSS framework / convention
- git, github

### Bónusz:
- A keresés induljon meg keresés gomb nélkül, ha 2 másodperce egyik keresési paraméter se változott meg (de ne sűrűbben.)
- Sikeres módosítás esetén a frissített adatmegjelenítéshez se teljes oldalújratöltés, se új adatbetöltés ne legyen megindítva.
