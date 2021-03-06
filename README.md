# Frontend uppdrag

Du har fått i uppdrag att skapa en webbplats utifrån en existerande design.
Innehållet ska vara anpassat efter enhet.

Sidan kan skapas med valfri teknik och ramverk, på så sätt kan dess funktion
även utökas.

Resultatet ska hostas med github pages från docs mappen.

## Design

Allt material för uppgiften hittar du här nedan. Text kopierar du från Figma.

* [Figma skiss](https://www.figma.com/file/n9dJBwH4mYwa4dMU7ysDyF/Jessica-Mavis-Cox?node-id=0%3A1)
* [Bild på tanten](https://unsplash.com/photos/eY1_nQs9aNI)
* [Choklad](https://unsplash.com/photos/tppi1oZAdZI)

För att ta bort bakgrunden på bilderna använde jag ett onlineverktyg, [remove.bg](https://www.remove.bg/).

Om du har synpunkter på designen eller förbättringar så är det okej att använda dessa.
Tänk på att det ska passa uppdraget dock och att du då bör motivera dina ändringar
i dina anteckningar/postmortem.

## Teknik

Det är tämligen fritt att välja teknik för detta projekt, så länge det är anpassat
till den tid vi har (~2 veckor).

Du kan till exempel använda pug, bootstrap och sass. Här kan såklart pug ersättas av
en annan templatteknik eller bara html. Bootstrap kan vara css eller ett annat 
ramverk. Sass kan ersättas av css eller annan teknik, men det är viktigt att du
visar att du kan använda sass eller liknande(gör det enkelt och skriv scss).

Vill du utöka detta så kan du efter att frontend delen är klar skapa ett node projekt
där sidan hostas och det till exempel finns CRUD funktion för nyhetsflöde. 

### Om du vill köra pug / sass

Då finns det en package.json för dig. Kör npm install (du kan eventuellt behöva installera med -g).
Sedan har du två scripts att starta.

```
npm run build-pug
npm run build-sass
```

Scriptsen watchar src mapparna och skapar nya filer i docs mappen när du sparar ändringar.

## Dokumentation

I ditt arbete så får du gärna föra [anteckningar](dokumentation/anteckningar.md).
I dokumentet [checklista](dokumentation/checklista.md) så ska du anteckna hur du
validerat, optimerat och testat ditt resultat.
En utgångspunkt kan vara kursbokens [checklista](https://jens-andreasson.gitbook.io/webbutveckling/tester/checklista-foer-webbsidor).

När projektet är slutfört så skriver du en kort [post mortem](dokumentation/postmortem.md) 
där du beskriver dina lärdomar.
