![Webpagina](https://github.com/johantenhouten/InleidingInformatica/blob/main/media/webpagina.png)

In deze module (ongeveer 70 minuten),gaan we ontdekken hoe je een webpagina's maakt.

In de eerste module is gesproken over informatie. In een computer wordt informatie binair opgeslagen (dus alleen een 0 of een en 1). De ***context*** bepaalt hoe die bits weergegeven worden. Soms zijn de bits een deel van een video, soms is het een deel van een tekstbericht en soms betekenen die bits een stipje op een foto. De context kan worden bepaald door het programma dat je gebruikt of de context wordt bepaald door het bestand waarin je iets opslaat. In deze module maken we een bestand met een bepaalde opmaak. Als we dat bestand opslaan met de extensie .HTML zal Windows het bestand herkennen als een webpagina. 

### Een webpagina 
Webpagina's worden opgemaakt in HTML. ***H***yper***T***ext ***M***arkup ***L***anguage. HTML is eigenlijk een gewoon tekst bestand, maar dan met extra aanduiding voor opmaak, afbeeldingen en links. HTML is ook een set van afspraken, als je aan die afspraken houdt kan elke browser dat bestand weergeven.

Webpagina's worden gebruikt om informatie te geven (mijn winkel, de speeltiun, informatie van de gemeente, wanneer komt de bus). Die informatie is redelijk statisch, wat betekent dat de inhoud niet veel veranderd. Hier is [een voorbeeld van een statische pagina](https://miradehond.w3spaces.com/index.html "miredehond" {:target="_blank"})

<a href="http://example.com/" target="_blank">Hello, world!</a>
[link](URL){:target='_blank'}

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
Wie meer wil weten kan terecht bij [W3Schools.com](https://www.w3schools.com/html/default.asp){:target="_blank"}
  
  
### Opdracht 1 (max 10 minuten)
Start Kladblok.exe (Engels) of Notepad.exe (Nederlands) [(kijk deze Video als je niet weet hoe)](https://www.youtube.com/watch?v=RgL4mq53IAc){:target="_blank"} in Windows en kopieer de inhoud van standaardopmaak hierboven in een nieuw leeg bestand. Sla het bestand op als opdracht1.html. Tip: bij het opslaan kies voor de optie [Alle bestanden (`*.*`)](https://github.com/johantenhouten/InleidingInformatica/blob/main/media/opslaanals.png?raw=true){:target="_blank"} of bekijke deze [Video](https://www.youtube.com/watch?v=xqMKHHj6cdQ){:target="_blank"}. Open het document daarna door vanuit de Verkenner er op te klikken. Als het goed is zie je aan de icon dat het een webpagina is en als het nog beter is zie je een webpagina met tekst.
 
Om jouw persoonlijke webpagina compleet (anders?) te maken kun je bijvoorbeeld experimenteren met de TAGS `<H1>`, `<H2>`, `<H3>`, `<strong>`. Dat zal de opmaak van een stukje tekst aanpassen.

`<BR>` voegt een nieuwe regel toe en `<HR>` zet een horizontale streep.
 
 [Hier](https://www.w3schools.com/html/html_colors.asp){:target="_blank"} wordt uitgelegd hoe je bijvoorbeeld kleur kan toevoegen aan je webpagina.
  
 [Hier](https://www.w3schools.com/html/html_images_background.asp){:target="_blank"} wordt uitgelegd hoe je een afbeelding als achtergrond kan toevoegen.
  
 Probeer maar eens in je HTML pagina onder of bove de regel met `<H1>` een afbeelding toe te voegen.

```html
<img src="https://github.com/johantenhouten/InleidingInformatica/blob/main/media/fcxx.png?raw=true" alt="FC-XX">
```

***De opdracht:*** Maak een webpagina van een stukje van deze module. Zorg voor een titel, kies een koptekst, voeg de afbeelding toe en kopieer de eerste paragraaf. Houd het simpel. Voor tips kijk op [w3school.com](https://www.w3schools.com/html/html_basic.asp){:target="_blank"}. Zelf een pagina maken mag natuurlijk ook. 


### Opdracht 2 (max 5 minuten)
Open de [statische website](https://miradehond.w3spaces.com/index.html "miredehond"){:target="_blank"}.

Rechts klik op de webpagina en selecteer "view page source"  of "bron pagina bekijken". De exacte omschrijving kan verschillen - afhankelijk van taal en type browser (Firefox, Chrome, Edge, Safari). Herken je de HTML broncode? Je kan op deze manier zien waar de afbeelding vandaan komt (en opslaan op je eigen computer mocht je dat willen). Soms heb je dit nodig om te begrijpen hoe een webpagina werkt.

### Opdracht 3 
De sattisache webpagina is saai en komt niet verder dan mijn pony of mijn voetbal club. Een beetje goede opmaak kost heel veel tijd. Een oplossing is het gebruik van een Framework. Hierin zijn heel veel stijlen vooraf gedefinieerd. Ze zijn gratis te gebruiken. Mijn persoonlijke favoriet is Bootstrap. [Hier](https://www.w3schools.com/bootstrap5/index.php){:target="_blank"} kan je meer leren

Kopieer onderstaande code en sla op als opdracht2.html

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
Door het gebruik van een framework heb je in een keer veel meer (soms te veel) mogleijkheden. Met Boostrap kun snel hele complexe website maken. [Bekijk dit voorbeeld](https://www.bootstrapdash.com/demo/majestic-free/template/index.html){:target="_blank"}.

Bekijk de brondcode van de webpagina. Is best wel complex?

Tip: [online zijn er heel veel bootstrap editors die je helpen met het bouwen van een website.](https://bootstrap.build/app){:target="_blank"}


