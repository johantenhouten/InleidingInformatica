![Webpagina](https://github.com/johantenhouten/InleidingInformatica/blob/main/media/programeren.png)

In deze module (ongeveer 70 minuten), gaan we de basis van programmeren leren.

In de eerste module is gesproken over informatie. In een computer wordt informatie binair opgeslagen (dus alleen een 0 of een en 1). 
De ***context*** bepaalt wat die bits betekenen. Soms zijn de bits een deel van een video, soms zijn ze een deel van een tekstbericht en soms betekenen die bits een stipje op een foto. Soms zijn ze een programma.

Een programma is een aantal opdrachten voor de computer die tezamen een bepaalde taak uitvoeren. Die taak kan een spelletje zijn, het berekenen van je cijfergemiddelde of het zenden en ontvangen van berichten met vrienden. 

Een programma wordt gemaakt met een programmeertaal. Het maken van een programma met een programmeertaal heet programmeren. Programmeren is niet voor iedereen weggelegd. Wie daar geen zin in heeft of het niet kan kan kant en klare programma's van het internet downloaden of kopen. Hier gaan wij zelf een programma maken.

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
Het is niet de bedeling dat je elke taal kan schijven of zelfs begrijpen. Ze lijken ook veel op elkaar, maar er zijn belangrijke verschillen. Bij deze ene taal MOET je een regel afsluiten met een puntkomma bij een andere taal moeten opdracht gevat zijn in haakjes.

In deze les gaan we met Python en met Scratch aan de gang. Python is een programmeertaal waar je tekst invoert (print "hallo") om de computer te laten werken. Bij scratch werk je met grafische blokjes die een bepaalde taak uitvoeren.

----

### Programmeren 1 - eerste regels in python

Een computerprogramma voert een bepaalde taak uit. Om die taak uit te voeren heeft het programma informatie nodig. Die informatie wordt opgeslagen in een ***variabele***. Een variabele is een plekje in het computergeheugen. De naam zegt het al : die kan veranderen. Een variabele heeft een naam. Met die naam rekent het programma. 

Laten we met een eenvoudig voorbeeld beginnen. Stel je wilt je opgeven om te werken bij Albert-Heijn. Er is een website die vraagt wat je naam is en wat je leeftijd is. 

Dat zijn twee variabelen. Laten we die voor het gemak "naam" en "leeftijd" noemen. Een logische  en verstandige keuze, maar je mocht ze ook n en l noemen of x en y. Het gebruik van logische namen (die iets zeggen over de betekenis van de informatie) is verstandig en zorgt voor goede leesbare programma's. 
  
## Opdracht 1 - een variabele gebruiken
Open een extra tab met [online python](https://www.online-python.com/) (rechtermuisknop "Openen in een nieuwe tab") en voer onderstaande code in:


En vervang de inhoud door onderstaande regels:

```python
naam = "Jan de Rooi"
leeftijd = 15
```

En druk op F8 of klik op de groene button met Run... Als het goed is, zie je na een paar seconden onderin:

```
** Process exited - Return Code: 0 **
Press Enter to exit terminal
```

Well-done, je hebt je eerste programma gemaakt! Je hebt twee variabelen gebruikt en die beide een waarde gegeven. De variabele ***naam*** is nu een reeks letters. Een letterreeks begint en eindigt met een aanhalingsteken ". De variabele ***leeftijd*** heeft de waarde 15 (geen aanhalingstekens) en is een getal.

In python zijn het gebruik van spaties erg belangrijk. De opdrachten moeten direct aan het begin van de regel beginnen. 

## Opdracht 2 - iets afdrukken
Met alleen variabelen kan je nog niet veel. Je wilt er ook iets mee doen. Dat doen we met zogenaamde opdrachten (commands in het Engels). Een eenvoudige opdracht is ***print***. Het gebruik van de opdracht is wel aan python regels gebonden. Wat je wilt afdrukken moet je tussen ronde-haakjes zetten. Een print opdracht sluit altijd af met een regel-einde.

Als je die niet meer hebt, open een extra tab met [online python](https://www.online-python.com/) (rechtermuisknop "Openen in een nieuwe tab").
Voer onderstaande code in:


```python
naam = "Jan de Rooij"
leeftijd = 15

print("hallo")
print(naam)
print(leeftijd)
```
Zoals je ziet kun je ook direct informatie meegeven aan de print opdracht. De eerste regel met print druk ***hallo*** af. Daarna drukt het programma de "Jan de Rooij"  af en daarna 15.

## Opdracht 3 - je eigen invoer
Verander de code van opdracht 2 zodat je eigen naam en leeftijd wordt gebruikt.
Lukt het om die af te drukken?

## Opdracht 4 - tekenreeksen samenvoegen
In Python kun je tekenreeksen makkelijk aan elkaar plakken. Dat gebeurt met de opdracht +.

Neem de code van opdracht 2 en druk af "Hallo" + naam

Hint: je moet nog iets aanpassen, want het ziet er niet goed uit. Dat komt omdat de computer letterlijk doet wat wij zeggen.

## Opdracht 5 - een beslissing
Leuk dat afdrukken maar dat is nog niet alles. Een programma bestaat ook uit beslissingen, herhalingen en andere opdrachten.

In python wordt een beslissing gemaakt door het gebruik van een ***if*** opdracht. Daarachter moet iets komen dat een ja of nee antwoord geeft. en de regel moet je afsluiten met een dubbele punt. De volgende regel moet inspringen (of met een aantal spaties of met een TAB teken).

We kunnen  bijvoorbeeld kijken of je oud genoeg bent om vakken te vullen bij Albert-Heijn.

Probeer eens onderstaande code en gebruik je eigen naam en leeftijd.

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

Een als opdracht (if statement in het Engels) heeft een stukje programma dat wordt uitgevoerd als het waar is, je kunt ook met de ***else*** opdracht programma code uitvoeren als het NIET waar is. Kijk naar onderstaand voorbeeld:

```python
naam = "Jan de Rooij"
leeftijd = 15

print("Hallo " + naam)

if leeftijd > 14:
    print("Je bent oud genoeg")
else:
    print("Sorry bent nog niet oud genoeg")
 
```

## Opdracht 7 - invoer en compleet programma
In het voorbeeld van opdracht 6 moet je de naam en leeftijd in de programma code aanpassen. Dat kan makkelijker, zonder dat iemand de programma code hoeft te zien. We gebruiken de opdracht ***input()***. Die geeft een tekenreeks terug. Je moet de input afluiten met een ENTER.

In het voorbeeld hieronder zit een ook extra regel ***leeftijd = int(leeftijd)***. Deze regel zoirgt ervoor dat leeftijd een gtal is (int betekent INTEGER). Anders kun je niet zien of iemand oud genoeg is. Python kan niet goed appels (cijfer) met peren (tekst) vergelijken.


```python

naam = input("Wat is je naam  ")
leeftijd = input("Hoe oud ben je  ")
leeftijd = int(leeftijd)

print("Hallo " + naam)

if leeftijd > 14:
    print("Je bent oud genoeg.")
else:
    print("Sorry bent nog niet oud genoeg.")
```


## Opdracht 8 - een spelletje
![hogerlager](https://github.com/johantenhouten/InleidingInformatica/blob/main/media/hogerlager.png)

Niet alle commando's in python zijn ingebouwd. Maar die kun je makkelijk laden met ***import***. Probeer eens onderstaande code. 

```python
from random import randrange
getal = randrange(1000)

print(getal)
```
De eerste regel laadt een extra bibliotheek  ***random*** (willekeurige getallen). De tweede regel roept een commando randrange (random range) aan. Dit commando komt uit de bibliotheek en kiest een willelkeurig getal tussen de 0 en 999. Samen zijn zijn 1000 getallen.

```python
from random import randrange
getal = randrange(50)

print(getal)
```

Met een willkeurig getal kunnen we een spelletje maken. De speler moet het getal raden, de computer zegt hoger, lager tot je het hebt geraden

```python
from random import randrange
geheim = randrange(50)

getal = input("Welk getal denk je (0..49) ")
if getal > geheim:
  print("Te hoog")

if getal < geheim:
  print("Te laag")
  
if getal == geheim:
  print("Je hebt het geraden")
```

Het nadeel van bovenstaand programma is dat je maar 1 keer mag raden. Een ***IF*** opdracht werkt maar 1 keer. Python kent een constrctie die doorgaat tot dat... Dat heet een ***while*** opdracht. 

In het voorbeeld hieronder gaan we door totdat het getal gelijk is aan het geheim. Dat betekent dat we doorgaan zolang het getal ongelijk is aan het geheim. In python gebruik je == als je twee variabelen wil vergelijk en je gebruik != als je het ongekeerde wil testen. Probeer eens onderstaande code


```python
from random import randrange
geheim = randrange(50)
getal = -1

while getal  != geheim:
    getal = input("Welk getal denk je (0..49) ")
    getal = int(getal)
    if getal > geheim:
      print("Te hoog")
    
    if getal < geheim:
      print("Te laag")
      
    if getal == geheim:
      print("Je hebt het geraden")

```

## Opdracht 9 - anders programmeren
![scratch](https://github.com/johantenhouten/InleidingInformatica/blob/main/media/scratch.png)

Programmeren met tekst is veel werk, een spelfout en het programma doet het niet meer. Er is een alternatef. Visueel programmeren. 
Open [deze website](https://scratch.mit.edu/projects/editor/) in een nieuwe tab.

Je ziet een nieuwe wesite met links blokjes, in het midden een leeg veld en rechts een kat. Als je wilt kun je de taal op Nederlands zetten door op de werledbol (linksboven) te klikken.

Selecteer uit de blokken (links) de Oranje blokken (gebeurtenissen / events). Sleep het blokje ![spatie](https://github.com/johantenhouten/InleidingInformatica/blob/main/media/spatie.png) in het lege veld. Selecteer nu links uiterlijken het blokje ![hallo](https://github.com/johantenhouten/InleidingInformatica/blob/main/media/hallo.png). Duw het hallo blokje in het spatie blokje, het werkt als een puzzel.

![prog1](https://github.com/johantenhouten/InleidingInformatica/blob/main/media/spatie_hallo.png)

Je hebt nu een programma gemaakt die het woord Hallo toont waneer je op de spatiebalk drukt. Kun je tekst aanpassen?

## Opdracht 10 - meer 
Selecteer links voor de blokken "beweging" en kies het blokje "Neem 10 stappen" en plak dit onder "Zeg Hallo 2 Seconden". Wat gebeurt er nu?
Kun je de kat meer dingen laten doen? Probeer eens een aantal blokken bij beweging of blokken uiterlijken.

## Opdrcht 11 - een spelletje in Scratch

Open dit [programma](https://scratch.mit.edu/projects/381571855/). Je kunt het spel spelen of je kunt "bekijk van binnen" klikken. 
Dan zie je hoe het spel is gemaakt, elk element van het spelletje moet apart gemaakt worden. Maar je kunt zoeken naar een spelletje 
van iemand anders  en aanpassen... Probeer maar.

## Opdrcht 12 - een app bouwen (alleen voor Android)

Download [dit bestand](https://github.com/johantenhouten/InleidingInformatica/raw/main/media/RunBunnyBunny.aia) naar je computer.

Open [APP Inventor]{http://ai2.appinventor.mit.edu/) en log in met een Google account (school account?)

In APP Inventor kies je voor upload project from your computer. ![Kijk hier he je dat moet doen](https://github.com/johantenhouten/InleidingInformatica/blob/main/media/import_aia.png)

Als het project geladen is, kin je kijken hoe de app het werkt. Er zijn twee schermen. Een scherm met de zichtbare opbouw van de app (designer) en een scherm (blocks) met de werking van de app. De werking is vergelijkbaar met Scratch.

Druk op Build en Kies voor "Android App (.apk)". Het durt even maar je krijgt als het goed is een QR code te zien. Als je die met je camera op je telefoon of Androud Tablet bekijkt, kan je de APP downloaden en installeren. Let wel op dit is een onbekende app en sommige beveiliging laat dat niet toe.

Open de APP RunBunnyRun op je telefoon. 

Druk op RUN en laat weer los..













