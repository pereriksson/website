---
views:
    flash:
        region: flash
        template: default/image
        data:
            src: "image/webtec/logo-php.png"
author:
    - mos
revision:
    "2022-06-28": "(A, mos) Första utgåvan."
...
kmom04: PHP...
==================================

[WARNING]

**Kursutveckling pågår inför hösten 2022. Använd inte materialet innan denna rutan är borttagen.**

[/WARNING]

Form, Post, Session.


<small><i>(Detta är instruktionen för kursmomentet och omfattar det som skall göras inom ramen för kursmomentet. Momentet omfattar cirka **20 studietimmar** inklusive läsning, arbete med övningar och uppgifter, felsökning, problemlösning, redovisning och eftertanke. Läs igenom hela kursmomentet innan du börjar jobba. Om möjligt -- planera och prioritera var du vill lägga tiden.)</i></small>


<!--stop-->

Läs & Studera  {#lasanvisningar}
---------------------------------

*(ca: 2-4 studietimmar)*

Här kan du på egen hand studera och förbereda dig inför övningar och uppgifter.



### Föreläsning {#flas}

Titta på följande föreläsningar. Föreläsningarna kan innehålla tips om läsanvisningar.

* [PHP och arrayer](./../forelasning/php-arrayer)
* [PHP och funktioner](./../forelasning/php-funktioner)

<!--
Finns ej

* [PHP och HTML formulär](./../forelasning/php-html-formular)
* [PHP, cookies och sessioner](./../forelasning/php-cookie-session)

Ovan föreläsningar ersätts av en längre lektion.
-->


* Om innehåll i webbplatsen? (markdown kanske, som en filbaserad databas)



### Litteratur  {#litteratur}

Läs enligt följande.

1. ...
1. Läs igenom följande sektioner i guiden "[Kom igång med programmering i PHP](guide/kom-igang-med-programmering-i-php)".
    * [Egenskapade funktioner](guide/kom-igang-med-programmering-i-php/egenskapade-funktioner)



Övningar & Uppgifter  {#ovningar_uppgifter}
-------------------------------------------

*(ca: 8-12 studietimmar)*

Övningar är träning inför uppgifterna, det är ofta klokt att jobba igenom övningarna. Uppgifter skall utföras och redovisas.

Jobba gärna i grupp med dina studiekompisar, men skriv alltid din egen kod för hand. Även om du tjuvkikar för att hitta bra lösningar så är det en stor skillnad att skriva koden själv jämfört med att kopiera från någon.



### Övningar {#ovningar}

Jobba igenom övningarna, de förbereder dig inför uppgifterna.


<!--
* Arrayer
* (Funktioner)
* POST med processingsida
* Session

* Programmera något med PHP, som en övningssida i report?

* I lektionen "[Bygg en webbplats med PHP](./../forelasning/bygg-en-webbplats-med-php)" får du hjälp att komma igång med uppgiften. Lektionen spelas in.
-->



### Uppgifter {#uppgifter}

Följande uppgifter skall utföras och resultatet skall redovisas.

* Gör uppgiften "[Bygg en webbplats med PHP](uppgift/bygg-en-webbplats-med-php)".

<!--
Kalender, månadens babe

Kalender samt bytta månad med länk.

Galleri med bilder, klicka runt, läsa av filer i katalog. Next

Bygg formulär. (som övning?)
https://jonkopingenergi.se/privat/fiber/serviceavgift (använd även till databasen)

Session, formulär med POST

Inloggning av användare med lösenord.

Som uppgift?
https://arkiv.dbwebb.se/kod-exempel/business-card-generator/

1. Jobba igenom övningen "[Att bygga en styleväljare till sin webbplats](kunskap/att-bygga-en-stylevaljare-till-sin-webbplats)".


Inför labbarna (kmom04-06) om det känns som det behövs och om det känns att det finns utrymme (koppla till guiden?)

1. Gör uppgiften "[PHP lab 3: Arrayer](uppgift/php-lab3-arrayer)". Spara alla filerna i katalogen `me/kmom03/lab3`.

1. Gör uppgiften "[PHP lab 4: skapa egna funktioner](uppgift/php-lab4-skapa-egna-funktioner)". Spara alla filerna i katalogen `me/kmom04/lab4`.

1. Gör uppgiften "[PHP lab 5: utforska inbyggda funktioner](uppgift/php-lab5-utforska-inbyggda-funktioner)". Spara filerna i katalogen `me/kmom05/lab5`.

-->


### Överkurs och extra uppgifter {#extra}

Här följer extra uppgifter som du kan utföra för att lära dig mer, om du har tid, lust och energi.

<!--
* Markdown, läs in fil och konvertera, kräver composer och PHP i pathen (låt vara tills design-kursen)
-->




Resultat & Redovisning  {#resultat_redovisning}
-----------------------------------------------

*(ca: 1-2 studietimmar)*

Läs [instruktionen om hur du skall redovisa](./../redovisa).

Se till att följande frågor besvaras i din redovisningstext.

* Hur är din uppfattning om programmeringsspråket PHP så här långt?
* Är du bekväm med att använda GET, POST, SESSION och COOKIE i din webbutveckling?
* Hur kändes det att bygga webbplatsen med sidkontroller och vyer?
* Vilken är din TIL för detta kmom?

Glöm inte att testa din inlämning med `dbwebb test kmom04`.