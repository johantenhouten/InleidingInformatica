![Webpagina](https://github.com/johantenhouten/InleidingInformatica/blob/main/media/programeren.png)

In deze module (ongeveer 70 minuten), gaan we de basis van programmeren leren.

In de eerste module is gesproken over informatie. In een computer wordt informatie binair opgeslagen (dus alleen een 0 of een en 1). 
De ***context*** bepaalt wat die bits betekenen. Soms zijn de bits een deel van een video, soms zijn ze een deel van een 
tekstbericht en soms betekenen die bits een stipje op een foto. Soms zijn ze een programma.

Een programma is een aantal opdrachten voor de computer die tezamen een bepaalde taak uitvoeren. Die taak kan een spelletje zijn, het berekenen 
van je cijfergemiddelde of het zenden en ontvangen van berichten met vrienden. 

Een programma wordt gemaakt met een programmeertaal. Het maken van een programma met een programmeertaal heet programmeren. Programmeren is niet voor iedereen weggelgd. Wie daar geen zin in heeft of het niet kan kan kant en klare programmas van het internet downloaden of kopen. Hier gaan wij zelf een programma maken.

Er zijn ongelofelijk veel programmeertalen. Iedere taal kent zijn eigen trucjes, en de schrijfwijze kan compleet anders zijn. 

```C
System.out.println("Hello World!!");
cout <<"\nHello World"<< endl;
print "Hall0"
Console.WriteLine("Hello World!");
printf("Hallo");
console.log("Hallo");
puts 'Hello World'
```
Het is niet de bedeling dat je elke taal kan schijven of zelfs begrijpen. Ze lijken ook veel op elkaar, maar er zijn belangrijke verschillen. Bij deze ene taal MOET je een regel aflsuiten met een puntcomma bij een andere taal moeten opdracht gevat zijn in haakjes.

In deze les gaan we met Python en met Scratch aan de gang. Python is een programmeertaal waar je tekst invoert (print "hallo") om de computer te laten werken. Bij scratch werk je met grafische blokjes die een bepaalde taak uitvoeren.

----

### Programmeren 1 - eerste regels in python

Een computerprogramma voert een bepaalde taak uit. Om die taak uit te voeren heeft het programma informatie nodig. Die informatie wordt opgeslagen  
in een ***variabele***. Een variabbele is een plekje in het computergeheugen. De naam zegt het al : die kan veranderen. Een variabele heeft een naam. Met die naam rekent het programma. 

Laten we met een eenvoudg voorbeeld beginnen. Je kan je opgeven om te werken bij Albert-Heijn. Er is een website die vraagt wat je naam is en wat je leeftijd is. 

Dat zijn twee variabelen. Laten we die voor het gemaak "naam" en "leeftijd" noemen. Een logische  en verstadige keuze, maar je mocht ze ook n en l noemen of x en y. Het gebuik van logische namen (die iets zeggen over de betekenis van de informatie) is verstandig en zorgt voor goede leesbare programma's. 
  
## Opdracht 1 - een variabele gebruiken
Open een extra tab met [online python](https://www.online-python.com/) (rechter muisknop "Openen in een nieuwe tab") en voer onderstaande code in:


En vervang de inhoud door onderstaande regels:

```python
naam = "Jan de Rooi"
leeftijd = 15
```

En druk op F8 of klik op de groene button met Run... Als het goed is zie je na een paar seconden onderin:

```
** Process exited - Return Code: 0 **
Press Enter to exit terminal
```

Well-done, je hebt je eerste programma gemaakt! Je hebt twee variabelen gebruikt en die beide een waarde geggeven. De variabele ***naam*** is nu een reeks letters. Een letterreeks begint en eindigt met een aanhalingsteken ". De variabele ***leeftijd*** heeft de waarde 15 (geen aanhalingstekens) en is een getal.

In python zijn het gebruik van spaties erg belangrijk. De opdrachten moeten direct aan het begin van de regel beginnen. 

## Opdracht 2 - iets afdrukken
Met alleen variabelen kan je nog niet veel. Je wilt er ook iets mee doen. Dat doen we met zogenaamde opdrachten (commands in het engels). Een eenvoudige opdracht is ***print***. Het gebruik van de opdracht is wel aan python regels gebonden. Wat je wilt afdrukken moet je tussen ronde-haakjes zetten. Een print opdracht sluit altijd af met een regel-einde.

Als je die niet meer hebt, open een extra tab met [online python](https://www.online-python.com/) (rechter muisknop "Openen in een nieuwe tab").
Voer onderstaande code in:


```python
naam = "Jan de Rooij"
leeftijd = 15

print("hallo")
print(naam)
print(leeftijd)
```
Zoals je ziet kun je ook direct informatie meegeven aan de print opdracht. De eerste regel met print druk ***hallo*** af. Daarna drukt het programma de "Jan de Rooij"  af en daarna 15.

## Opdracht 3 - je iegen invoer
Verander de code van opdracht 2 zodat je eigen naam en leeftijd wordt gebruikt.
Lukt het om die af te drukken?

## Opdracht 4 - tekenreeksen samenvoegen
In Python kun je tekenreeksen makkelijk aan elkaar plakken. Dat gebeurt met de opdracht +.

Neem de code van opdracht 2 en druk af "Hallo" + naam

Hint: je moet nog iets aanpassen, want het ziet er niet goed uit. Dat komt omdat de computer letterlijk doet wat wij zeggen.

## Opdracht 5 - een beslissing
Leuk dat afdrukken maar dat is nog niet alles. Een programma bestaat ook uit beslissingen, herhalingen en andere opdrachten.

In python wordt een beslissing gemaakt door het gebruik van een ***if*** opdracht. Daarachter moet iets komen dat een ja of nee antworod geeft. en de reglem moet je aflsuiten met een dubbele punt. We kunnen  bijvoorbeeld kijken of je oud genoeg bent om vakken te vullen bij albert-heijn.

Probeer eens onderstaande code en gebruik je iegen naam en leeftijd.

```python
naam = "Jan de Rooij"
leeftijd = 15

print("hallo")
print(naam)

if leeftijd > 14:
  print("Je bent oud genoeg")
```

Waarom kijkt het programma of leeftijd > 14 is. ***>*** betekent groter dan. Je mag ***vanaf*** je 15e werken, dus groter dan 14. Dit is een veel en makkelijk gemaakte fout (>15 in plaats van >14). Je moet dus steeds testen om te kijken of je code goed werkt.

## Opdracht 6 - een uitgebreide beslissing

```python
naam = "Jan de Rooij"
leeftijd = 15

print("Hallo " + naam)

if leeftijd > 14:
  print("Je bent oud genoeg")
 else:
  print("Sorry bent nog niet oud genoeg")
 
```




