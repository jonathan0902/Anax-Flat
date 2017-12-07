#Inledning
vi valde Facebook för att vi arbetade med det i förra kursmomentet och det känns som det ska finnas en röd tråd i det hela.

#Mättning
Vi tog oss användning av Google Pagespeed för att få fram en googles mättning hur snabbt sidan laddare upp och så beskriver google själva vad som man kan göra. Sedan gjorde vi en inspekt med chrome verktyg för att få ut data.

![Facebook](img/facebook2.png)

På facebook.com så behövde sidan "Needs work". Där den beskriver att de ska ta bort JavaScript och CSS-kod som blockerar renderingen. 81/100. Sedan mobilen var Poor med 49/100 och hade samma klaggningar.

![Facebook](img/coop2.png)

På Coop.se var optimeringen riktigt dålig både Dator versioen och mobilen versionen var Poor där datorn versioen har 53/100. Där sidan kunde Optimera Bilder utnyttja cachelagring i webbläsaren aktivera komprimering, Ta bort JavaScript och CSS-Kod, blockerar rendering från innehåll ovanför mitten minska svarstiden från servern förminska HTML. Mobil versionen hade 45/100 och hade samma fel som kunde rättas

![Facebook](img/ica2.png)

På ica.se var optimeringen Poor där dator versionen hade 49/100 där optimera bilder, aktiver komprimering, Ta bort JavaScript- och CSS-Kod som blockerar rendering från innehåll ovanför mitten. Undvik omdirgeringar från målsidan. Prioitea synligt innehåll, utnyttja cachelagring i webbläsare och förminska HTML. Sedan har vi mobil versionen som har ett mätt värde på 37 / 100 och har samma funderingar som desktop.

[Page Render data](https://docs.google.com/spreadsheets/d/1K7oYgn88uwTRL6xdgsh01SJEG84paMHbpW6jMrzF8aU/edit?usp=sharing)

De vanligaste saker som kan optimeras är

Ta bort JavaScript- och CSS-kod som blockerar renderingen från innehåll ovanför mitten.
Optimera bilder.

Ica.se
Har många bilder.
Coop.se
Har många bilder.
Facebook.se
Slutar aldrig ladda.

Det beror helt på sidan, för lite information kan ta 2 sekunder men sidor som hantera mycket data så har det rätten till att inte sluta ladda. För mig är det mer en defintions fråga och det beror helt på sidans bakgrund är.

Gruppmeddlemar: Filip, Jonathan Hellberg
