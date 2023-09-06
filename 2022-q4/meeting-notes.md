# Notulen open source council

> 07/12/2022

## Updates

- Rouke gaat een meeting / procedure starten voor selectie nieuwe sponsorprojecten
- Bezig met opstellen beleid / visie bijdragen aan open source vanuit management
- Hacktoberfest
  - 55 aanmeldingen, 39 deelnemers, 51 PRs/issues/blogs
  - Volgend jaar iets eerder in oktober

## Rondje langs de projecten

### StrykerJS (Nico)

- 2,6M downloads dit jaar, >6M totaal
  - Aan het stagneren? Iets minder stijging
- v6.3 gereleased -> Allemaal tijdens hacktoberfest
  - Jest: support more config files
  - Emojis in clear text reporter
  - pnmp support
  - disableTypechecks
  - Verbeteringen init
  - Worker count env variable
  - etc
- Nieuw team: Danny, Thierry & Odin; Simon legt werkzaamheden neer

### Stryker.NET (Richard)

- 787k total downloads, 577 daily
- Nieuwe features
  - Solution context run
  - Automatically discover solution file
  - Math class mutator
  - ??= mutator
  - a ?? b mutator
  - Object initializer mutator
- Bugfixes
  - Een hoop
- Nieuw teamlid: Liam (welkom!)
- What's next:
  - Test results toevoegen aan report
  - Performance tunen
  - Lijst met issues en feature requests
- Nieuwe afstudeerder: real time reports updaten tijdens draaien van stryker

### Styker4s (Hugo)

- 19k downloads per maand
- Volgende release:
  - Betere report
  - Betere logging
  - Parsing en mutating refactored
  - Contributie: cleanTempDir
  - Contributie: staticTempDir

### Maven (Giovanni)

- Niet veel aan Maven gewerkt, wel bij Hacktoberfest
- Hacktoberfest: documentatie / features
- What's next:
  - Zien waar je dependencies vandaan komen (Maarten, work in progress)
  - Nieuwe flag voor command line, `--status`, om te kijken of installatie gelukt is

### Research center (Jan-Jelle)

- WO afstudeeropdrachten
  - Jan-Jelle doet een oproep om meer WO afstudeeropdrachten. 
  - We hebben nu 1 generieke "Maak Stryker Sneller" opdracht, maar als je al een specifiek idee hebt hoe dan maakt de opdracht meer kans om gekozen te worden.

- Er zijn nu 2 groepjes bezig met voor het ISEP project ("Pas software toe in de praktijk bij een bedrijf")
  - Groepje 1 (Rouke)
    - Performance Stryker verbeteren
  - Groepje 2 (Hugo)
    - Styker4JVM
      - Begonnen met samenvoegen Stryker4Kotlin en Stryker4S
    - Wekelijkse meeting, veel code aan het aanpassen
  - Nieuwe ideeën voor nieuwe software opdrachten welkom
    - 3 a 4 studenten, 2 dagen per week voor 6 maanden.
    - Misschien vervolgopdracht voor StrykerJVM / Performance Stryker verbeteren

## Rondvraag

- Risico's Stryker voor Info Support
  - Afweging risico's en voordelen
  - In gesprek met legal

- Is de open source community een "officiële" community?
  - Nee, maar heeft wel die ambitie
  - Moet nog visie e.d. komen

- Is er nog open source tijd?
  - Ruimte voor 1FTE, 1800 uur
  - 876 uur opgemaakt
  - Dus ja
