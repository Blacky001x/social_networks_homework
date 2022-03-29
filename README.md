# Mini projekat na kursu Socijalne mreže (Network science)

## Opis podataka
- Data je mreža istraživača koji se bave network science-om, čvorovi predstavljaju pojedinačne istraživače, a dva čvora su povezana linkom ukoliko su objavili barem jedan zajednički rad.
- Mreža je neusmerena i težinska (težina je određena prema Njumanovoj formuli).

## Zadatak
Koristeći alat po izboru (korišćen je Python i networkx biblioteka), analizirati datu mrežu.
Neke od analiza koje je trebalo pokriti:
- Analize povezanih komponenti (koliko ima komponenti, broj čvorova i veza u najvećoj komponenti,  i sl.)
Za najveću komponentu je trebalo uraditi dodatne analize, između ostalog:
- Osnovne metrike (pod)mreže nastalom posmatranjem najveće povezane komponente (gustina, prosečan stepen,   dijametar, koeficijent klasterisanja..)
- Ekstrahovati top 10 istraživača koje imaju najviše metrike centralnosti (betweeness, closeness, degree, eigenvector).
- Za svaku od četiri osnovne metrike centralnosti (pomenute iznad), napraviti vizuelizaciju najveće povezane komponente, pri tome jasno istaći čvorove sa najvišim stepenom metrike.
- Odrediti istraživače koji pripadaju maksimalnom koru najveće povezane komponente. Dodatno, vizuelizovati maksimalni kor.
