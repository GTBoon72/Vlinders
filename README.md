# Vlinders
Hierin scrape ik de website waarneming.nl, en gebruik ik de data voor een klein onderzoek en meer.
=======

De .Rmd file is een R markdown file, waarin alle code staat waarmee de .html is gegenereerd.
Om dit zelf uit te voeren heb je R, RStudio, plus alle gebruikte packages nodig. 
Om de website niet te zwaar te belasten, wordt de data eenmalig geladen, en lokaal opgeslagen voor hergebruik.

Pimpernelblauwtje.Rmd bevat een analyse van het voorkomen van de gastheer en de gastplant van deze vlinder,
		met als doel te kijken wat goede plaatsen voor herintroductie zouden kunnen zijn. 
		
Vlinders_SpG.Rmd bevat de logica om per week te kunnen kijken waar de zeldzame vlinders van Nederland vlogen
		in 2015. De allerzeldzaamste vlinders zijn meestal niet elk jaar aanwezig, en bovendien ontbreken met 
		opzet vaak de precieze locatiegegevens. De gegevens worden lokaal opgeslagen als input voor een Shiny app.

Gebieden_per_week.Rmd is de code voor een Shiny app, waarin je kunt zoeken wat in een bepaald weeknummer de beste
		plekken zijn om zeldzame vlinders te kunnen bekijken. Op een Leaflet-wandelkaart kun je zien op welke
		locaties de betreffende vlinders in 2015 zijn gezien. Klik je op een waarneming, dan verschijnen de 
		exacte gps-gegevens van die waarneming (omgerekend van decimalen naar graden).
=======
