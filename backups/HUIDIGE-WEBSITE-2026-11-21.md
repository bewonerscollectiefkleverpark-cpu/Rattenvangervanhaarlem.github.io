# Huidige website — Rattenvanger van Haarlem

**Vastgelegd op:** 21 november 2026  
**Bronbestand:** `index.html` op de standaardbranch van de GitHub-repository  
**Bronbestand-SHA vóór archivering:** `a7b25826e1bc7346bf7406b5661cad308f2a29d8`  
**Exacte HTML-back-up:** [`backups/index-2026-11-21.html`](https://github.com/bewonerscollectiefkleverpark-cpu/Rattenvangervanhaarlem.github.io/blob/main/backups/index-2026-11-21.html)  
**Live website:** https://bewonerscollectiefkleverpark-cpu.github.io/Rattenvangervanhaarlem.github.io/

## Belangrijke afspraak
Dit document en de HTML-back-up leggen de bestaande website vast vóór de voorgenomen vernieuwing. De huidige live `index.html` is bij deze archivering niet gewijzigd. De back-up is een apart bestand in de repository en wordt niet als websitepagina gepubliceerd.

## Wat staat er op de huidige website?

### 1. Identiteit en vormgeving
- Naam: **Rattenvanger van Haarlem**.
- Nederlandstalige startweergave.
- Vormgeving met een lichte crème achtergrond, witte contentvlakken, donkergrijze tekst en rood als accentkleur.
- Logo bovenaan, hoofdtitel, korte introductie en een subtiele bewegende rattenillustratie.
- Navigatie met afzonderlijke onderdelen die binnen dezelfde HTML-pagina worden getoond of verborgen.
- Responsieve vormgeving voor mobiel en desktop.

### 2. Taalkeuze
De website bevat taalondersteuning voor zes talen:
- Nederlands
- Engels
- Turks
- Arabisch (met rechts-naar-links weergave)
- Russisch
- Spaans

De taalkeuze wordt lokaal in de browser onthouden.

### 3. Officieel melden en de bewonerskaart
De website maakt onderscheid tussen twee handelingen:
- **Officiële melding bij Spaarnelanden:** de bezoeker krijgt uitleg en kan de melding via e-mail doorgeven aan Spaarnelanden.
- **Vrijwillige waarneming op de rattenkaart:** bewoners kunnen een waarneming registreren om buurtgenoten inzicht te geven in mogelijke hotspots. Deze kaartregistratie is niet hetzelfde als een officiële melding en vervangt die niet.

De homepage bevat een opvallend keuzepaneel om dit verschil uit te leggen. Ook staat er een rode oproep: **“Meld iedere keer opnieuw!”**

### 4. Rattenkaart
- Interactieve kaart op basis van Leaflet en OpenStreetMap.
- Meldingen worden via de gekoppelde Google Apps Script-webapp opgehaald.
- De kaart groepeert waarnemingen per straat en categorie over de afgelopen twaalf maanden.
- Categorieën: ratten gezien, rattenkeutels en rattenholen.
- Markeringen en pop-ups tonen straat, categorie, aantallen en aantallen registraties.
- De kaart gebruikt straatlocaties/representatieve punten; het zijn geen exacte locaties van individuele ratten of woningen.

### 5. Waarneming registreren
Het formulier vraagt onder meer om:
- Straatnaam.
- Soort waarneming: rat, keutels of hol.
- Aantal waarnemingen (1 tot en met 20).
- Bevestigingen dat de melding bewust en naar waarheid wordt gedaan.

De straat wordt via de PDOK Locatieserver opgezocht. De registratie wordt naar de Apps Script-webapp gestuurd. In de websitecode is ook een apparaatgebonden identificatie en een wachttijdbeperking verwerkt om herhaald snel insturen te beperken.

### 6. Informatie en privacy
Het informatiegedeelte bevat uitleg over het initiatief en een opvallend privacygedeelte. Daarin staat onder meer dat het formulier geen naam, huisnummer of e-mailadres vraagt en dat de kaart meldingen op straatniveau toont. Er staat ook een kanttekening dat hosting en Google-diensten technische loggegevens kunnen verwerken; daarom wordt geen absolute belofte gedaan dat er helemaal geen technische gegevens worden verwerkt.

Verder bevat dit onderdeel een oproep om meldingen te blijven doen en de website te delen, omdat meldingsmoeheid kan leiden tot een onvolledig beeld van de overlast.

### 7. Leefregels en verantwoordelijkheden
Er is een onderdeel met leefregels en praktische adviezen. De website maakt daarnaast onderscheid tussen verantwoordelijkheden rond openbare ruimte/riool en privéterrein.

### 8. Posters
Er is een apart onderdeel met posters en printfunctionaliteit om het initiatief in de buurt te verspreiden.

## Technische koppelingen en afhankelijkheden
De huidige pagina gebruikt onder meer:
- Google Fonts (Montserrat).
- Leaflet voor de kaart.
- OpenStreetMap-kaarttegels.
- PDOK Locatieserver voor straatzoekopdrachten.
- Google Apps Script als meldingenserver en koppeling met de spreadsheet.
- Browseropslag voor de taalvoorkeur en de apparaatgebonden beperking.

## Wat deze back-up wel en niet is
- De HTML-back-up is een exacte kopie van het opgehaalde `index.html`-bestand op het moment van archiveren.
- De back-up is bedoeld om de huidige website later te kunnen herstellen of vergelijken.
- De gekoppelde Apps Script-code, spreadsheet, afbeeldingen en externe diensten zijn niet automatisch onderdeel van deze HTML-kopie.
- Er is geen wijziging aangebracht aan de bestaande live startpagina door deze archivering.
- Dit document is een inhoudelijke inventarisatie; voor het exacte ontwerp en de volledige code is het HTML-back-upbestand leidend.
