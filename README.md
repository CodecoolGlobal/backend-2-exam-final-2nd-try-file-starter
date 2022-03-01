# Tükröző vírus
## Bevezetés
Sajnos a számítógépedet megfertőzte egy vírus. Azonban szerencsédre ezt egy kezdő vírusíró készítette, és csupán annyit 
kárt okozott, hogy a szöveges állományaidat megfordította sorról-sorra.


Írj egy programot, ami képes visszaállítani a megtükrözött fájljaidat!

## Feladatleírás

Írj egy osztályt, `FileMirror`, melynek van egy `mirror()` metódusa.
A `FileMirror`-t úgy lehet létrehozni, hogy konstruktorában megadjuk a tükrözendő fájl elérési útvonalát + nevét.
A `mirror` hívás beolvassa a fájl tartalmát, soronként megfordítja, és egy új fájlba menti,
melynek neve: `<eredeti fájl név>.mirror.<kiterjesztes>`. Pl.: `dog.txt` &rarr; `dog.mirror.txt`

Példák:

Bemenet:
```
54321
09876
FEDCBA
```
Kimenet:
```
12345
67890
ABCDEF
```