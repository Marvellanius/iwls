![Kamertje.nl logo](https://www.kamertje.nl/images/KLogo_Kleur-S.png "Kamertje.nl logo")
# Stageverslag Kamertje.nl Gamification & Monetization

---

| Versiebeheer| |
|---|---|
|Versienummer|0.2|
|Versiedatum|21 september 2017|
|Type|Concept|
|Auteur|Dick van Viegen|
|Studentnummer|s1096864|
|Stagedocent|Robbert Winkel|
|Stagebedrijf|Kamernet B.V.|
|Bedrijfsbegeleider 1|Thijs Luxemburg|
|Bedrijfsbegeleider 2|Steven Ouwerkerk|

---

## Week 1
* Opzet stageplan
* Opzetten VPN server op VPS zodat ik vanuit huis ook bij de Kamertje systemen kan komen
* Bugfixes na lancering Kamertje:
    * Email alerts (kamer plaatsen) lagen er uit, veel geleerd over debugging
    * Logging geïmplementeerd op een Slack-bot
* Eerste sprintplanning



## Week 2
* Onderzoek naar virtual currency based systemen begonnen
    * Google scholar searches leveren niet veel op;
        * 'virtual currency based web transactions' -> veelal bitcoin onderzoeken
        * 'credit based web transactions' -> veelal onderzoeken naar gebruik credit cards web
        * 'token based web transactions' -> veelal onderzoek naar oAuth2 gebaseerde token verificatie
    * Nieuwe searches komen dichterbij;
        * 'monetization through virtual goods web' ->
        * 'microtransactions in gaming'
        * 'in-game currencies'
* Eerste monthly business meeting bijgewoond (voornamelijk Kamernet, maar ook Kamertje milestones besproken)
* PHP-debug leren gebruiken in editor of choice
* Voor het eerst versioning gebruikt voor css/js files
* Eerste onderzoek naar GoogleTagManager gebruik

## Week 3
* Feedback verwerken stageplan
* Inlezen en implementeren UTM campagnes in de mails van Kamertje
* Asynchrone validatie via Ajax en Laravel
* Image retention bij validatie errors kamer plaatsen
* Eerste bezoek stagedocent

## Week 4
* Afronden definitieve versie stageplan
* Bijwerken klad/concept Stageverslag
* Veel support moeten leveren aan klanten op het gebied van plaatsen van kamers, toevoegen van producten aan accounts
* Begonnen met het uitdenk van de back-end implementatie van credits.
* Verder in aan het lezen en inspiratie op aan het doen naar UX-friendly implementaties voor credits
* Roadmap voor Kamertje.nl (tot en met februari) besproken met Thijs
* Collega in de gaten moeten houden i.v.m. kwaliteit en frequentie geleverd werk.

## Week 5
* Javascript crash in IE fixed (IE ondersteund geen ES6 JavaScript syntax, heb dit aangepast naar ES5)
* Code voor het overgrote deel PHP PSR1-compliant gemaakt
* Nieuwe error handling ingebouwd voor 500/404/403 errors
* Begonnen met het ontwerp voor de credit backend
* GA/GTM implementatie basics gefixt

## Week 6
*

## Week 7
* Nieuwe profiel pagina afgerond
* Bezig met tenant-search functionaliteit
* Bovenstaande zijn req's voor achievement/credit systemen
