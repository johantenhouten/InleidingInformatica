![Webpagina](https://github.com/johantenhouten/InleidingInformatica/blob/main/media/webpagina.png)

In deze module (ongeveer 70 minuten),gaan we ontdekken hoe je een webpagina's maakt.

In de eerste module is gesproken over informatie. In een computer wordt informatie binair opgeslagen (dus alleen een 0 of een en 1). De ***context*** bepaalt hoe die bits weergegeven worden. Soms zijn de bits een deel van een video, soms is het een deel van een tekstbericht en soms betekenen die bits een stipje op een foto. De context kan worden bepaald door het programma dat je gebruikt of de context wordt bepaald door het bestand waarin je iets opslaat. In deze module maken we een bestand met een bepaalde opmaak. Als we dat bestand opslaan met de extensie .HTML zal Windows het bestand herkennen als een webpagina. 

### Een webpagina 
Webpagina's worden opgemaakt in HTML. ***H***yper***T***ext ***M***arkup ***L***anguage. HTML is eigenlijk een gewoon tekst bestand, maar dan met extra aanduiding voor opmaak, afbeeldingen en links. HTML is ook een set van afspraken, als je aan die afspraken houdt kan elke browser dat bestand weergeven.

Webpagina's worden gebruikt om informatie te geven (mijn winkel, de speeltiun, informatie van de gemeente, wanneer komt de bus). Die informatie is redelijk statisch, wat betekent dat de inhoud niet veel veranderd. 

Veel belangrijker is de functie van een interactieve webpagina. Denk bij interactief aan online bestellen (bol.com, zalando, wehkamp), social media, online boekhouden, video kijken, muziek luisteren of gamen. Met een interactieve pagina kun je geld verdienen. Bijvoorbeeld door het vragen van een abonnement of door het verkopen van advertenties. Voor een interactieve pagina heb je dan ook een computer nodig die de verwerking van informatie doet (een webserver). In deze module kijken we alleen naar de voorkant.


### Standaard opmaak van een statische pagina
De aanduidingen worden aangegeven met een woord tussen een < en > teken. Zo betekent `<small>` dat de tekst voor taan kleiner is. Het einde wordt aangegeven met `</small>`, let op het `/` teken. 

Een standaard webpagina bestaat uit verschillende secties, ook aangeduid met een `<TAG>`. De woorden tussen `<` en `>` worden TAGs genoemd. In het voorbeeld hieronder zie je duidelijk de sectie html (het is ook een html document) aangegeven met de tag `<HTML>`, maar ook de `<HEAD>` wat zoiets betekent als kop, en een sectie `<BODY>` waar de eigenlijke inhoud in staat. Hoofdletters zijn niet belangrijk voor TAGS. 
  
```html
<!DOCTYPE html>
<html>
  <head>
    <title>FC-xx</title>
  </head>

  <body>
    <h1>Mijn voetbal club FC-xx</h1>
    <p>De allerbeste voetbal club in de wereld is FC-xx</p>
  </body>

</html> 
```
Wie meer wil weten kan terecht bij [W3Schools.com](https://www.w3schools.com/html/default.asp)
  
  
### Opdracht 1
Start Notepad.exe [(kijk deze Video als je niet weet hoe)](https://www.youtube.com/watch?v=RgL4mq53IAc) in Windows en kopieer de inhoud van standaardopmaak hierboven in een nieuw leeg bestand. Sla het bestand op als opdracht1.html. Tip: bij het opslaan kies voor de optie [Alle bestanden (`*.*`)](https://github.com/johantenhouten/InleidingInformatica/blob/main/media/opslaanals.png?raw=true) of bekijke deze [Video](https://www.youtube.com/watch?v=xqMKHHj6cdQ). Open het document daarna door vanuit de Verkenner er op te kkikken. Als het goed is zie je aan de icon dat het een webpagina is en als het nog beter is zie je een webpagina met tekst.
 
Om jouw persoonlijke webpagina compleet (anders?) te maken kun je bijvoorbeeld experimenteren met de TAGS `<H1>`, `<H2>`, `<H3>`, `<strong>`. Dat zal de opmaak van een stukje tekst aanpassen.

`<BR>` voegt een nieuwe regel toe en `<HR>` zet een horizontale streep.
 
 [Hier](https://www.w3schools.com/html/html_colors.asp) wordt uitgelegd hoe je bijvoorbeeld kleur kan toevoegen aan je webpagina.
  
 [Hier](https://www.w3schools.com/html/html_images_background.asp) wordt uitgelegd hoe je een afbeelding als achtergrond kan toevoegen.
  
 Probeer maar eens in je HTML pagina onder of bove de regel met `<H1>` een afbeelding toe te voegen.

```html
<img src="https://github.com/johantenhouten/InleidingInformatica/blob/main/media/fcxx.png?raw=true" alt="FC-XX">
```
 
[Hier](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_images_background7) is een voorbeeld hoe je een afbeelding als achtergrond kan toevoegen.
  
Maak je eigen webpagina (bijvoorbeeld van deze module). Kies een kop tekst, zorg voor een titel, en voeg wat text toe. Houd het simpel, voeg als je wilt een afbeelding toe. Let wel op dat je dan een link opneemt naar een afbeelding op internet (als je een afbeelding ziet, rechtermuisknop copy Image Link).


### Opdracht 2
Heb je je eigen webpagina geopend in je browser? 

Rechts klik op de webpagina en selecteer "view page source"  of "bron pagina bekijken". De exacte omschrijving kan verschillen - afhankelijk van taal en type browser (Firefox, Chrome, Edge, Safari). Herken je je eigen broncode? Je kan op deze manier zien waar de afbeelding vandaan komt (en opslaan op je eigen computer mocht je dat willen). Soms heb je dit nodig om te begrijpen hoe een webpagina werkt.

### Opdracht 3 
De webpagina is saai en komt niet verder dan mijn pony of mijn voetbal club. Een beetje goede opmaak vergt met het zelf schrijven heel veel tijd. Een goede oplossing is het gebruik van een Framework. Hierin zijn heel veel stijlen vooraf gedefinieerd. Ze zijn gratis te gebruiken. Mijn persoonlijke favoriet is Bootstrap. [Hier]() kan je meer leren

Probeer eens onderstaande code

```html
<!DOCTYPE html>
<html>
  <head>
    <title>FC-xx</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"></script>
  </head>
  
  
  <body>
  <div class="container-fluid p-5 bg-primary text-white text-center">
    <img src="https://github.com/johantenhouten/InleidingInformatica/blob/main/media/fcxx.png?raw=true" alt="FC-XX">
  </div>
  
  <div class="container mt-5">
    <div class="row">
      <div class="col-sm-4">
        <h1>FC-xx</h1>
          <p>De allerbeste voetbal club in de wereld is FC-xx</p>
      </div>
    </div>
  </div>

  
  
  </body>

</html> 
```


Laten we het een stap verder nemen.
- In Chrome, Firefox, of Safari: rechts-klik op een webpagina en selecteer ***Inspect***.
- In Internet Explorer of Edge, rechts-klik op een webpagina en selecteer ***Inspect Element***.

