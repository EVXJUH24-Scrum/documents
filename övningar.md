Dokumentet är indelat i två sektioner: individuella övningar och gruppövningar.

## Individuella övningar

### 1.

Vilket av följande påståenden är INTE ett av grundvärdena i Agile Manifesto?

a) Fungerande programvara främst, före omfattande dokumentation
b) Anpassning till förändring främst, före följandet av en plan
c) Processer och verktyg främst, före individer och interaktioner
d) Kundsamarbete främst, före kontraktsförhandling

### 2.

Vilken roll i Scrum ansvarar för produktbackloggen och dess prioriteringar?

a) Scrum Master
b) Product Owner
c) Development Team

### 3.

Vilket av följande är Product Owners huvudansvar i Scrum?

a) Maximera värdet av produkten och Development Teams arbete
b) Facilitera Scrum-events och coacha teamet
c) Leverera användbara inkrement av produkten

### 4.

I Scrum, vem är ytterst ansvarig för produktens framgång?

a) Scrum Master
b) Product Owner
c) Development Team

### 5.

Sant eller falskt:
Ett av målen med Daily Scrum är att identifiera hinder som påverkar teamets arbete.

### 6.

Vilken är den huvudsakliga skillnaden mellan Agilt och Vattenfall (Waterfall)?

a) Agilt använder aldrig dokumentation
b) Vattenfall välkomnar förändring i större utsträckning
c) Agilt levererar värde i mindre, iterativa cykler
d) Vattenfall har kortare utvecklingscykler

### 7.

Nämn de tre rollerna i Scrum och beskriv kortfattat deras viktigaste ansvarsområden.

### 8.

Vad kallas den tidsbegränsade perioden i Scrum där ett inkrement av produkten skapas?

a) Iteration
b) Sprint
c) Milestone
d) Release
e) Work cycle

### 9.

Sant eller falskt:
En Sprint Retrospective genomförs före Sprint Review.

Förklara:
Vad är skillnaden mellan dem?

### 10.

Låtsas att ett utvecklingsteam har följande situation:
De har en omfattande process för kodgranskning som alla måste följa. Den tar mycket tid men säkerställer hög kvalitet. Några utvecklare föreslår att de istället ska ha mer parprogrammering och direkta diskussioner, då de tror att detta kan minska på tiden och ändå få kvalité, men projektledningen vill behålla den nuvarande och dokumenterade processen eftersom den är beprövad.

Vilket eller vilka värden från Agile Manifesto är relevanta för att vägleda teamet i denna situation?

a) Anpassning till förändring framför att följa en plan
b) Kundsamarbete framför kontraktsförhandling
c) Individer och interaktioner framför processer och verktyg
d) Fungerande programvara framför omfattande dokumentation

### 11.

Vad är huvudsyftet med en Sprint Review?

a) Planera nästa sprint
b) Granska teamets arbetsprocess
c) Visa upp det färdiga arbetet för intressenter
d) Hålla daglig statusuppdatering

### 12.

Förklara kortfattat vad som menas med "Definition of Done" i Scrum.

### 13.

Vem ansvarar för att ta bort hinder för teamet i Scrum?

a) Product Owner
b) Scrum Master
c) Development Team

### 14.

Sant eller falskt:
I Agil utveckling är det omöjligt att planera framåt och sätta deadlines.

### 15.

I Scrum kallas listan med alla önskade funktioner och förbättringar för ????.

### 16.

Hur långt bör ett Daily Standup vara enligt Scrum?

a) 5 minuter
b) 15 minuter
c) 30 minuter
d) 60 minuter

### 17.

Nämn tre fördelar med Agilt arbetssätt jämfört med traditionell (Waterfall) projektledning.

### 18.

Vad står Scrum för?

### 19.

Vad är skillnaden mellan Agilt och Scrum?

### 20.

Vilken är bäst: Agilt eller Scrum?

## Gruppövningar

### 1.

Låtsas att ni får i uppgift att bygga en e-handelsplattform (webbplats) för en bokaffär. Övningen går ut på att sätta upp ett GitHub repository med issues.

Börja med att skapa ett repository på GitHub och att bjuda in alla i gruppen. Fortsätt med att skapa kort förklarande user stories. Dessa skall sedan beskrivas i mer detalj. Till en början kan det exempelvis se ut såhär (user stories):

- Som användare vill jag kunna söka efter produkter för att hitta specifika varor jag är intresserad av
- Som användare vill jag få upp rekommendationer på varor baserat på tidigare sökningar
- Som användare vill jag se vilka produkter som är populära
- (ni skall lägga till fler här)

Sedan, för att utveckla på dessa user stories kan ni följa denna mall (den innehåller ett exempel som ni skall byta ut):

```markdown
## Beskrivning

Som användare vill jag kunna söka efter produkter för att hitta specifika varor jag är intresserad av.

## Acceptanskriterier

- [ ] Sökfältet ska vara synligt på alla sidor
- [ ] Sökningen ska fungera på produktnamn och beskrivning
- [ ] Resultaten ska visas i en lista med pagination
- [ ] Max 10 resultat per sida visas
- [ ] Tomma sökresultat ska visa ett användarvänligt meddelande

## Tekniska noter

- Implementera sökfunktion med ElasticSearch
- Caching av vanliga sökresultat
- Felhantering vid timeout

## Definition of Done

- [ ] Koden är skriven och testad
- [ ] Dokumentation är uppdaterad
- [ ] Pull request är skapad
- [ ] Code review är genomförd
- [ ] Alla tester går igenom
```

Tänk på att det egentligen inte finns några rätta svar. Ni bestämmer själva vilka issues som är passande. Ni skall dock försöka få de så bra, tydliga och värdefulla som möjligt. Fyll i mallen för alla user stories ni har skapat.

Alla dessa user stories skall läggas in som issues på GitHub.

Ni har inte än kunskaper inom webb, men kan ändå bygga kriterier utan att specificera tekniska detaljer.

### 2. (bygger på #1)

Ni har fått in följande bug-reports:

- När användaren klickar på "Lägg till i kundvagn" visas ingen bekräftelse.
- När användaren besöker webbplatsen första gången så visas inga produkter
- Användare kan beställa fler produkter än vad som finns i lager

Skapa GitHub issues för alla dessa buggar. Ni får hitta på vissa saker då buggarna inte är riktiga. Försök, så mycket det går, att koppla dessa till era tidigare skapade issues. Hitta gärna på egna buggar också.

Använd följande mall (den innehåller ett exempel som skall bytas ut):

```markdown
## Beskrivning av buggen

När användaren klickar på "Lägg till i kundvagn" visas ingen bekräftelse.

## Steg att återskapa

1. Gå till valfri produktsida
2. Klicka på "Lägg till i kundvagn"
3. Observera att ingen bekräftelse visas

## Förväntat beteende

En bekräftelse ska visas när produkten läggs till i kundvaggen.

## Faktiskt beteende

Ingen bekräftelse visas, användaren är osäker på om produkten lades till.

## Miljö

- Browser: Chrome 121.0
- OS: Windows 11
- Skärmstorlek: 1920x1080

## Extra information

- Felet uppstår konsekvent
- Produkten läggs till korrekt, endast bekräftelsen saknas
```

### 3. (bygger på #2)

Ni har fått in några "feature requests" från användare:

- Implementera dark-mode för sidan och knappar för att bytta mellan det och light-mode
- Visa liknande produkter när man besöker en specifik produkt
- Implementera "hover" funktionalitet som visar en kort beskrivning av produkter

Skapa GitHub issues för alla dessa feature requests. Ni får hitta på vissa saker då ni inte har ett riktigt projekt att jobba med. Försök, så mycket det går, att koppla dessa till era tidigare skapade issues. Hitta gärna på andra requests om ni vill.

Använd följande mall (den innehåller ett exempel som skall bytas ut):

```markdown
## Funktionsbeskrivning

Implementera dark mode för hela webbplatsen.

## Motivation

Många användare föredrar dark mode, särskilt vid användning nattetid.

## Föreslagen implementation

- [ ] Lägg till toggle för dark/light mode
- [ ] Skapa variabler för färgteman
- [ ] Spara användarens preferens lokalt
- [ ] Respektera systemets färgtema som default

## Påverkan

- UI/UX components
- Färgschema
- Användarinställningar

## Alternativa lösningar

- Automatisk dark mode baserat på tiden på dygnet
- Endast följa systemets inställningar
```
