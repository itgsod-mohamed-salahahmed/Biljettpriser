
# Biljettautomat#

Den här uppgiften går ut på att skriva en del av mjukvaran i en biljettautomat för pendeltåg.

## Bedömningsmatris ##

### Planering ###

| Förmågor                         | E 																																   | C | A |
|----------------------------------|-----------------------------------------------------------------------------------------------------------------------------------|---|---|
| Aktivitetsdiagram och pseudokod  | Du använder pseudokod och/eller aktivitetsdiagram för att planera dina uppgifter utifrån exempel, eller i samråd med utbildaren.  | Som för E, men utan exempel eller handledning |   |

### Syntax och Teori ###
| Förmågor                                       | E 																			| C | A |
|------------------------------------------------|------------------------------------------------------------------------------|---|---|
| Grundläggande syntax		                     | Du kan redogöra för och använda programmeringsspråkets grundläggande syntax  |   |   |
| Villkor och IF-satser		                     | Du kan redogöra för och använda villkor och IF-satser                        |   |   |

### Kodning och kodningsstil ###

| Förmågor                                      | E                                                                         | C                                               | A                                              |
|-----------------------------------------------|---------------------------------------------------------------------------|-------------------------------------------------|------------------------------------------------|
| Komplexitet									| **Du kan skriva enkla program**                                               | Du kan skriva lite mer avancerade program       | Du kan skriva komplexa program
| Sekventiell- & funktionsbaserad programmering | Du använder dig av sekventiell programmering och fördefinerade funktioner | **Du skapar och använder enkla funktioner**         | Du skapar mer komplexa funktioner              |
| Struktur		 				                | Du skriver kod som är delvis strukturerad, har en konsekvent kodningsstil och tydlig namngivning | Som för E, men du skriver kod som är helt strukturerad |   			   |
| Felsökning                                    | Du felsöker på egen hand enkla syntaxfel | Som för E, men systematiskt, och dessutom även körtidsfel och programmeringslogiska fel | Som för C, men med effektivitet   	   |
| Undantagshantering                            |     																		| Du validerar användardata						  | Som för C, men du skriver även kod som använder undantagshantering |
| Dokumentering 								| Du skriver kod som är delvis dokumenterad									|  												  | Du skriver kod som är utförligt dokumenterad   |

## Uppgiftsbeskrivning ##

Du har blivit inhyrd för att skriva den del av mjukvaran i en biljettautomat som räknar ut vad biljetten kostar.

Priserna ser ut som följer

* Från och med 0 till och med 17 år: 10 kr
* Från och med 18 till och med 64 år: 20 kr
* Från och med 65 år: 15kr.

Ditt program ska ta ålder som inparameter och returnera pris i SEK som svar.

## Genomförande ##

### Versionshantering ###

Gör en `fork` av repot. Klona sen ner till din dator. Kom ihåg att checka in dina ändringar och synka med GitHub.

### Flödesschema ###

Innan du börjar koda ska du skapa ett flödesschema för programmet.
När du känner att du har ett fungerande flödesschema, be läraren att kolla på det.

### Kodning ###

Skriv programmet med hjälp av en eller flera funktioner, som skall placeras i modulen tickets.

Testa att funktionerna fungerar genom att skriva **tester** i tickettest.py

Fundera över vad som kan gå fel? I version 2 ska vi lösa detta.


## Tips och länkar ##

* Om du inte kan beskriva lösningen i ord kommer det vara så gott som omöjligt att skapa ett flödesschema
* Fundera på vilka variabler som behövs
* Testa flödesschemat med hjälp av penna och papper

### Python ###

Läs mer om villkor och if-satser i övning 27-30 i [*Learn Python the Hard Way*](http://learnpythonthehardway.org)

* [Learn Python the Hard Way - Exercise 27: Memorizing Logic](http://learnpythonthehardway.org/book/ex27.html)
* [Learn Python the Hard Way - Exercise 28: Boolean Practice](http://learnpythonthehardway.org/book/ex28.html)
* [Learn Python the Hard Way - Exercise 29: What If](http://learnpythonthehardway.org/book/ex29.html)
* [Learn Python the Hard Way - Exercise 30: Else and If](http://learnpythonthehardway.org/book/ex30.html)

Läs om python moduler

* [Modules and Packages](http://www.learnpython.org/en/Modules_and_Packages)

Läs om undantagshantering 

* [Python Programming/Exceptions](https://en.wikibooks.org/wiki/Python_Programming/Exceptions)

Exempel på dokumentering

* [Google Style Python](http://sphinxcontrib-napoleon.readthedocs.org/en/latest/example_google.html)