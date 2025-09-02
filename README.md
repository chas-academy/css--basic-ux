# Bootcamp FMW2025 - ♿️ CSS + Grundläggande UX

Vi fortsätter med styling även denna vecka och introducerar grundläggande UX- och tillgänglighetsprinciper i och med att de många gånger går hand i hand. Syftet med denna uppgift är att göra er statiska webbsida så tillgänglig och responsiv som möjligt.

## Förberedelser

- Kopiera över HTML-filerna från förra veckans arbete
- Lägg in följande script-tag `<script type="module" src="/src/main.js"></script>` inuti body på vardera fil enligt exemplet nedan:

```html
</head>
<body>
    <script type="module" src="/src/main.js"></script>
    ...
</body>
```

- Öppna terminalen, se till att du befinner dig i denna mapp (`css--basic-ux`) och skriv följande kommandon
  - `npm install` - för att installera projektets dependencies (Externa JavaScript-bibliotek) inklusive a11y-checker som är vårt tillgänglighetsverktyg för denna övning.
  - `npm run dev`- för att spinna upp en utvecklingsmiljö. Detta kommer bl.a. med fördelen att programmet automatiskt laddas om varje gång ni sparar en ändring så att sidan inte behöver laddas om manuellt.
  - Gå sedan till länken till er utvecklingsmiljö som visas i terminalen - Troligtvis `http://localhost:5174/`.
- Gör också färdigt stylingen från förra veckan om det fortfarande återstår något

## ☯️ Fokuspunkter

### Kontrast

Är all text enkel att urskilja? Står textfärgen i tillräckligt stark kontrast till bakgrundsfärgen?

### Skärmläsare

Kan en skärmläsare enkelt tyda sidan? Finns det beskrivningar på alla element som inte innehåller text? Är HTML-elementen semantiska?

### Intuitivitet

Är det tydligt vilka element som är interaktiva? Är det lätt för en användare som aldrig sett sidan för hur man navigerar till de olika sidorna? Vilken CTA-knappen (Call to action) är?

### Responsivitet

Hur ser sidan ut på olika skärmstorlekar? Blir layouten rörigt på mobil? Använd DevTools för jämföra.

## 📱 Mobilanpassa sidan

Skapa relevanta `@media` queries så att sidan ser bra ut och är enkel att navigera även på en mobilskärm. Glöm inte att skifta mellan liten och stor skärm för att säkerställa att ändringarna inte har några oönskade biverkningar.

## 👩‍🔧 Fixa övriga tillgänglighetsproblem

Öppna konsollen i DevTools och gå igenom alla varningar och felmeddelanden. De försvinner när de är lösta.

Om man föredrar att analysera tillgänglighet på andra vis kan man antingen ladda upp sina filer via [WC3 Markup Validation Service](https://validator.w3.org/#validate_by_upload) eller installera dera VS Code-tillägg - [W3C Web Validator](https://marketplace.visualstudio.com/items?itemName=CelianRiboulet.webvalidator).

## 🎁 Bonusuppgifter

### CSS Variables

Skapa variabler för alla värden som används upprepade gånger.
