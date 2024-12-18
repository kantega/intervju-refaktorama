# Refaktorering og kodekvalitet

Det begynner så fint, men før du aner det slutter koden din å være lett å jobbe med. Mange små endringer både i kode og forretningslogikk 
gjør at koden blir tidkrevende og kompleks å jobbe med og frustrasjonen øker. Derfor er det viktig å vedlikeholde koden og 
gjøre rent etter seg, altså refaktorere (eller refaktorisere).

## Hva trenger du? 
- IntelliJ
- Java 11
- Git

Klon repositoriet ned på maskinen din. Om dere skal parprogrammere ved å dele kode mellom dere kan det være en fordel å forke i stedet for å klone. 


# Dagens oppgave

Gå gjennom Pub.java i no.kantega. Hvilke problemer identifiserer du? Det 
ligger en liten testsuite (PubPricesTest.java) som dekker funksjonaliteten som finnes. Selv om det er rom for forbedringer 
feks på navngiving i testene, er det Pub.java du skal konsentrere deg mest om i denne workshopen. Det finnes også varianter 
av refaktorering som vil kreve nye tester, i så fall skriver du dem.  

## Hvordan starte

:pencil2: Åpne prosjektet i IntelliJ ved å velge *Open* fra File-menyen, og klikke på intro-refaktoreringsmappen

:pencil2: Kjør alle testene, gå gjennom både testene og koden

:question: Hva gjør koden? Diskuter slik at dere har samme forståelse av hva koden gjør

:question: Hvilke problemer finner dere? Navngiving? Kommentarer? Magiske tall? Struktur-problemer? 

:pencil2: Fiks alle de magiske tallene

:pencil2: Forbedre navngiving på variabler og funksjoner som finnes slik at navnene reflekterer hva innholdet er

:pencil2: Fjern kommentarer som ikke er nødvendige

:pencil2: Lag funksjoner for uavhengige deler av koden som kan stå for seg selv

Det er mange måter å refaktorere denne koden på, og selv om vi viser en variant til slutt betyr ikke det at andre måter å løse 
dette problemet på er feil. Diskuter design og hvilke ideer dere har for å løse de problemene dere ser. Trenger dere 
flere klasser, hva gjør de ulike klassene? Hvor er det tilstrekkelig med enkle grep, og hvor trengs større inngrep for å forbedre koden? 
Hva er sannsynlige utvidelser av koden, og hvordan kan koden støtte dette på best mulig måte?

Lykke til! 


## Litt tips
Noen tips til hvordan IntelliJ fungerer hvis du ikke har brukt det noe særlig: 
- [IntelliJ video tutorials](https://www.jetbrains.com/idea/documentation/)
- [IntelliJ testing](https://www.jetbrains.com/help/idea/2016.3/testing.html)
