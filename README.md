# Make Over – Göteborgs Stad Redesign

## Bakgrund
Den ursprungliga sidan upplevdes som överväldigande och bombarderade användaren med för mycket information på en gång. Sidan tjänade inte sitt syfte – att ge användaren en tydlig och lugn ingång till stadens tjänster.

## Vad jag förändrade och varför

### Struktur
Jag valde att strukturera om sidan för att göra den luftigare och mer intuitiv. En del information flyttades in i egna navigationsmenyer med dropdowns, så att användaren själv kan välja vad de vill se istället för att bli överväldigad direkt.

### Innehåll
Aktuell information presenteras nu i form av kort med bild och text – **Aktuellt** och **I Fokus** – som ger en tydlig visuell hierarki. Kalendern visas som en sidopanel med aktivitetskort som användaren enkelt kan skanna igenom.

### Design
Färgpaletten följer Göteborgs Stads officiella grafiska profil med **Göteborgsblå (#0076bc)** som primärfärg. Designen använder subtila skuggor, rundade hörn och hover-effekter för att kännas modern och tillgänglig utan att vara påträngande.

### Tekniskt
- SCSS med mixins och variabler för återanvändbar och underhållbar kod
- Inga JavaScript-beroenden för navigationen
- Responsiv layout

## Responsivitet
Layouten anpassar sig för mindre skärmar – sidopanelen och fokussektionen staplas under huvudinnehållet på mobil.