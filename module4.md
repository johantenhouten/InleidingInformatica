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
  
## Opdracht 1
ga naar https://www.online-python.com/

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

Bravo, je hebt je eerste programma gemaakt, je hebt twee variabelen gebruikt en die beide een waarde geggeven. De variabele naam is nu een reeks letters. Een letterreeks begint en eindigt met een aanhalingsteken ". De variabele leeftijd heeft de waarde 15 (geen aanhalingstekens) en is een getal.

## Opdracht 2
Met alleen variabelen kan je nog niet veel. Je wilt er ook iets mee doen. Dat doen we met zogenaamde opdrachten (commands in het engels). Een eenvoudige opdracht is ***print***. Het gebruik van de opdracht is wel aan python regels gebonden. Wat je wilt afdrukken moet je tussen ronde-haakjes zetten. Een print opdracht sluit altijd af met een regel-einde.

Ga naar https://www.online-python.com/ en voer onderstaande code in:

 <a href="https://www.online-python.com/" target="_blank">Online python</a> 

```python
naam = "Jan de Rooi"
leeftijd = 15

print("hallo")
print(naam)
print(leeftijd)
```


De website van Albert-Heijn moet beslissen of je in aanmerking komt voor een baantje. Dat mag alleen als je 15 jaar of ouder bent.






