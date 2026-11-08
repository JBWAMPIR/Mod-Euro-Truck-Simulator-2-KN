# Kuehne+Nagel ETS2 – dokumentacja projektu

**Autor projektu: JBWAMPIR**

Projekt obejmuje własne malowania ciężarówki Volvo FH 2024 oraz naczep Kuehne+Nagel do Euro Truck Simulator 2.

## 1. Środowisko

- Gra: Euro Truck Simulator 2
- Wersja gry: 1.62.1.0
- Ciężarówka: oryginalne Volvo FH 2024
- Firma: Kuehne+Nagel
- Format modów: `.scs`

## 2. Mody ciężarówki Volvo FH 2024

### Navy 0.12
- Ciemnogranatowa kabina.
- Białe logo KUEHNE+NAGEL z kotwicą.
- Logo powiększone 1,5 raza.
- Logo podniesione względem pierwotnej pozycji.
- Zatwierdzona pozycja i wielkość logo.
- Miniatura z białym logo na granatowym tle.

### White 0.14
- Biała kabina.
- Granatowe logo KUEHNE+NAGEL z kotwicą.
- Logo w tym samym zatwierdzonym rozmiarze i położeniu co Navy.
- Miniatura z granatowym logo na białym tle.

## 3. Mod naczepy Kuehne+Nagel

### Trailer Colors 1.5

Jeden mod zawierający dwa warianty malowania dostępne jednocześnie w katalogu naczep.

**Kuehne+Nagel Navy**
- Granatowa naczepa.
- Białe logo KUEHNE+NAGEL z kotwicą.
- Miniatura z białym logo na granatowym tle.

**Kuehne+Nagel White**
- Biała naczepa.
- Granatowe logo KUEHNE+NAGEL z kotwicą.
- Miniatura z granatowym logo na białym tle.

Oba warianty są widoczne i dostępne do wyboru w grze.

## 4. Zasady rozwoju projektu

1. Zachowywać zgodność z ETS2 1.62.1.0.
2. Nie zmieniać zatwierdzonego wyglądu logo bez uzgodnienia.
3. Każde malowanie powinno mieć własną, prawidłową miniaturę.
4. Przy kilku wariantach kolorystycznych zapewnić możliwość wyboru każdego z nich.
5. Każda wersja powinna mieć prawidłowy `manifest.sii`.
6. Identyfikatory jednostek SII muszą być zgodne z wymaganym formatem gry.
7. Nazwy plików, definicje SII i odwołania do tekstur muszą być zgodne.
8. Nie usuwać działających wariantów przy dodawaniu nowych.
9. Przed przekazaniem sprawdzić strukturę archiwum `.scs`, kompletność plików i poprawność ZIP.

## 5. Testowanie

Kontrola archiwum ZIP nie jest równoznaczna z testem w grze.

Po każdej istotnej zmianie należy:
- uruchomić ETS2,
- sprawdzić obecność malowania w katalogu,
- sprawdzić miniaturę,
- sprawdzić wygląd naczepy lub ciężarówki w garażu,
- zweryfikować `game.log`,
- usunąć błędy dotyczące nieprawidłowych identyfikatorów, brakujących plików i tekstur.

## 6. Zatwierdzone wersje referencyjne

| Mod | Wersja | Status |
|---|---:|---|
| Volvo FH 2024 Navy | 0.12 | Zatwierdzony wygląd |
| Volvo FH 2024 White | 0.14 | Zatwierdzony wygląd |
| Trailer Colors | 1.5 | Oba kolory działają |

## 7. Założenia projektu

Zatwierdzone elementy projektu traktować jako wersje referencyjne. Nowe funkcje rozwijać bez pogarszania dotychczasowego wyglądu i działania modów.
