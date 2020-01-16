# Juskselapp om Java på Norsk (Oversatt av meg)

## Vokabular og ordliste

Liste over forskjellige begreper og hva de kan oversettes til. Jeg er ikke en offisiell oversetter, eller en programmerer enda, men dette er erfaringer jeg har gjort meg opp så langt i opplæringsløpet.

---

## Datatyper

| Engelsk | Oversettelse | Definisjon |
|---------|--------------|------------|
| Char | Tegn | Ett enkelt tegn, vanligvis skrevet som 'a'. |
| Integers | Heltall | Alle tall som kan skrives uten komma. Ofte referert til som 'int'. Disse kan være alle hele tall mellom -2147483648 til 2147483647. |
| Floating Point Numbers | Desimaltall | Alle tall som ikke er heltall. |
| [Strings](#Strings) | Streng | En liste med tegn med en bestemt lengde. |
| Byte | Byte | Representert ved ett nummer mellom -128 og 127. |
| Object | Objekt |  |
| Class | Klasse | Der vi definerer hva objektene skal ha av egenskaper |
| Void | Tomrom | Hverken tallet eller verdien 0. Det store absolutt ingenting. |

---

### Utdypende

#### Strings

Streng konstanter kan defineres med både "hermetegn" og gravistegn ( ` ) [engelsk: *backticks*].

Forskjellen mellom disse er at tekst mellom hermetegn ikke kan gå over flere linjer, og tillater spesielle rømningssekvenser. Eksempler på dette er:

* "\n" som blir byttet ut med en ny linje
* "\t" som blir byttet ut med en tab

## Oppsett av kode

Siden Java er Objekt-Orientert, så er vi helt avhengig av å definere objekter for å få gjort noe som helst. Derav navnet Objekt-Orientert. Måten vi lager og sorterer objekter, er gjennom et klassesystem. I en klasse definerer vi alt objektene i klassen inneholder.