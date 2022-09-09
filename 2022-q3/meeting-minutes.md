# Open source council meeting notes

> 07/09/2022
>
> Inleiding -> Stryker.NET -> Maven -> StrykerJS -> Research Center update -> Marketing -> Rondvraag

- [Open source council meeting notes](#open-source-council-meeting-notes)
  - [Inleiding (Nico)](#inleiding-nico)
    - [Projectsponsoring rond](#projectsponsoring-rond)
    - [Aanmelding nieuwe projecten?](#aanmelding-nieuwe-projecten)
  - [Stryker](#stryker)
    - [Stryker.NET (Richard)](#strykernet-richard)
    - [StrykerJS (Nico)](#strykerjs-nico)
    - [Stryker4S](#stryker4s)
  - [Maven (Giovanni)](#maven-giovanni)
  - [Research Center update (Jan-Jelle)](#research-center-update-jan-jelle)
  - [Marketing](#marketing)
  - [Rondvraag](#rondvraag)

## Inleiding (Nico)

### Projectsponsoring rond

- 200 euro per maand per project
  - Fluentassertions
    - [Tweet](https://twitter.com/ddoomen/status/1564982954362900482?cxt=HHwWhMC8pZLt97crAAAA)
  - Buildalyzer
  - Babel
  - JUnit
  - Replace Tokens task

- Elke 3 maanden nieuwe projecten

### Aanmelding nieuwe projecten?

- Geen nieuwe projecten

## Stryker

### Stryker.NET (Richard)

- Downloads +159k, totaal 623k
- v3.0
  - Nieuwe comment voor static mutant
  - Detecteren van test discovery failure
  - YAML config files
  - Meer Azure storage API support
  - Markdown summary reporter
  - Optie om Stryker te laten falen als unit tests falen
- What's next?
  - Vstest issues oplossen in solution mode en voor M1 macs
  - Test information in HTML report
  - Allow creating fresh baseline

### StrykerJS (Nico)

- 1,9M downloads ytd (+60% sinds vorig jaar!)
- 5M totaal

- v6.2 shipped
  - Incremental mode (incredible)
    - Demo Nico
    - `--incremental` flag
    - Haalt historische data uit json file
    - 1m53s --> 31s na toevoegen nieuwe test 🤩
    - [Blog over incremental mode](https://stryker-mutator.io/blog/announcing-incremental-mode/)
- Afstudeerder werkt aan Svelte support (Teun)
  - (Frontend framework)

### Stryker4S

- Hugo is met vakantie

## Maven (Giovanni)

- Maven bijdragen Q3 2022
  - MNG-7443: Consistente logging tussen optional projects en profiles
  - MNG-7444: Niet alle optional projects worden gebuild
  - MPH-183: Tonen waar POM dependencies en hun versies vandaan komen

- Other news
  - Maarten heeft diverse bugs onderzocht
  - Giovanni heeft MNG-7444 opgelost

- Maven: waar moet ik beginnen? (Abdel)
  - Vraag het aan Giovanni

## Research Center update (Jan-Jelle)

- Twee opdrachten voor projectgroep Universiteit Twente
  - Praktisch softwareontwikkelen
  - 5 maanden, 1,5 dag per week
  - Stryker4JVM
  - Stryker cloud runner (Stryker Agent)
  - Beide opdrachten zijn gekozen
- Ideeën voor WO-afstudeeropdrachten?
  - Feature request: dashboard voor tijdsverloop mutations, historische data (Michaël)

## Marketing

- Hacktoberfest
  - Datum geprikt: 28/10/2022 + 29/10/2022
    - Vrijdag van Info Support, zaterdag eigen tijd
    - Rouke is er ook bij
  - Organisatie: Yorrick is geïnteresseerd
- Rol functiehuis voor open source

## Rondvraag

- Geen vragen
