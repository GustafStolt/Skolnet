# Skolnet
Modern, responsiv skolplattform för schema, uppgifter, betyg och närvaro. Byggd med Node.js, Express och Supabase med fokus på UX/UI.

readme.MD

# Namn på projektet

Skolnet

Namn på alla deltagare:
 
Gustaf Stolt

### Tävlar i kategori: 

* Bästa helhetslösning
* Bästa användarupplevelse (UX/UI)

## Projekt & Teknisk- beskrivning

Skolnet är en modern webbaserad skolplattform som samlar alla viktiga delar av en elevs och lärares skoldag på ett ställe.
Målet med projektet har varit att skapa ett enkelt, snabbt och intuitivt system där användaren direkt förstår hur allt fungerar utan instruktioner.

Plattformen innehåller bland annat:

* Schemaöversikt (veckovy med lektioner)
* Uppgifter & inlämningar
* Betygsöversikt
* Närvarosystem (anmäld/oanmäld frånvaro)
* Aviseringar/notiser
* Mobilanpassat gränssnitt
* Separata vyer för elev och lärare
* Systemet är byggt med responsiv design, vilket innebär att samma app fungerar lika bra på dator, surfplatta och mobil.

Fokus har legat på:

* tydlig layout
* få klick
* snabb laddning
* konsekvent design
* tydliga färger och feedback

UX/UI-fokus

Stor vikt har lagts på användarupplevelsen:

* Designval
* Mörkt/ljust tema
* Tydliga ikoner (Bootstrap Icons)
* Färgkodning:

 * Närvaro = grönt

 * Anmäld frånvaro = gult

 * Oanmäld frånvaro = rött

* Cirkeldiagram som snabbt visualiserar närvaro
* Mobil bottenmeny för enkel navigering med tummen
* Animationer och övergångar för ett mer levande gränssnitt

* Resultat:

 * Appen känns mer som en modern mobilapp än ett traditionellt skolsystem, vilket gör den snabbare och roligare att använda

Teknisk beskrivning:

* Skolnet är byggt som en fullstack webbapplikation

* Backend: 

 * Node.js 
 * Express 
 * Supabase (PostgreSQL databas + API)


* Backend hanterar:

 * inloggning
 * autentisering
 * lagring av schema
 * uppgifter
 * betyg
 * närvaro
 * notiser
 * All data lagras i databasen och hämtas dynamiskt via API-anrop

* Frontend: 

 * HTML
 * CSS
 * JavaScript (vanilla JS, ingen WordPress eller färdig mall)
 * Bootstrap 5

* Frontend:

 * Renderar schemat automatiskt från databasen
 * Visar olika vyer beroende på om man är elev eller lärare
 * Uppdaterar innehåll live utan sidladdning
 * Responsiv layout för mobil/desktop
 * Exempel på tekniska lösningar
 * Dynamiskt schema
 * Schemat lagras i databasen och hämtas per klass.
 * Frontend räknar ut positionen för varje lektion baserat på start- och sluttid och placerar dem visuellt i en kalendergrid

* Detta gör att:
 * Lektioner hamnar rätt automatiskt
 * Inga hårdkodade tider behövs
 * Ändringar i databasen syns direkt
 * Närvarosystem med visualisering

* Elever kan:

 * Anmäla frånvaro heldag
 * Anmäla frånvaro specifika lektioner
 * Ange orsak på frånvaroanmälning (krävs) Eftersom det ska göra det lite svårare för elever som överväger att skolka en dag   Vet av erfarenhet att det hade hjälpt mig...
 * Närvaron visas som ett cirkeldiagram med färgsegment (grön/gul/röd) som ger snabb överblick.

* Detta gör systemet:
 * Lätt att förstå visuellt
 * Mer engagerande
 * Snabbare än att läsa siffror/tabeller
 * Mobilanpassning

* En separat mobilnavigering visas automatiskt på små skärmar:
 * Bottenmeny
 * Större klickytor
 * Färre element
 * Bättre tum-navigering
 * Pinch-to-zoom för lärare med sämre syn

Det gör att appen fungerar lika bra på mobil som på dator

* Visioner för Skolnet i framtiden: 
 * Ai-chatbot integrerad för schemaoptimering
 * Betygsättningssytem för lärare
 * Elever se betyg och bedömmning
 * Tooltips
 * Google Meet-integration
 * Fungerande Google Drive-integration
 * Skapa elevgrupper i Classroom
 * Analyssida på classroom för att se antal elever som öppnat uppgifter och när. 
 * Ämnesgrupper i classroom
 * Möjlighet att synka kalendern i Skolnet med sin privata kalender ex. Google Kalender
 * 

### Externt producerade komponenter

Följande bibliotek används:

* Bootstrap 5: 
 * Används för layout, grid, knappar och modaler.
 * Behövs för snabb och responsiv design.
 * Bootstrap Icons
 * Ikoner för navigation och status.

* Supabase:
 * Molndatabas och API-tjänst.
 * Behövs för att lagra och hämta all data.

* Node.js + Express: 
 * Används för starta projektet på en lokal server.

* Alla övriga funktioner är egenutvecklade.

### Install

* Krav: 

 * Node.js
 * Internetanslutning (för Supabase)
 * Modern webbläsare (Chrome/Edge/Firefox)

* För att köra projektet lokalt: 

 1. Installera projektet på enheten eller clona git-projektet
    * git clone <repo-url>
      cd skolnet

 2. Installera beroenden
    * npm install 

 3. Starta servern
    * node server.js eller npm start

 4. Öppna i webbläsaren
    * http://localhost:3000

 5. Inloggning elev: Användarnamn: gustafstolt | Lösenord: 456
    Inloggning lärare: Användarnamn: magnus | Lösenord: 456
    
