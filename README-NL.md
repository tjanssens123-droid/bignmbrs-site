# BIGnmbrs website — gratis GitHub Pages

Dit is een statische website zonder hostingabonnement, tracking, formulieren of scripts van derden. De pagina's zijn Home, Support en Privacy; de taal schakelt automatisch NL/EN op basis van de browser, met een handmatige wisselknop.

## VOORDAT JE PUBLICEERT
1. Vervang `SUPPORT EMAIL TO ADD BEFORE PUBLISHING` in `support.html` en `privacy.html` door een door de uitgever goedgekeurd supportadres. Maak er desgewenst een `mailto:`-link van.
2. Controleer privacyclaims aan de hand van de **laatste commerciële Xcode-release**, die hier niet beschikbaar is. Verwijder pas daarna de conceptwaarschuwing op de Privacy-pagina en herschrijf onjuiste passages. Vergelijk met App Store Connect privacyantwoorden.
3. Controleer de functies van de actuele app. De aan deze conversatie eerder toegevoegde Xcode-code is ouder dan je recente Codex-wijzigingen.
4. Het logo is afkomstig uit het eerder gegenereerde BIGnmbrs-beeld. Controleer de weergave op klein scherm.
5. Pas de prijsvermelding aan indien de prijs in App Store Connect verandert; de website zegt alleen 'eenmalig' en toont niet een vast landafhankelijk bedrag.

## PUBLICEREN VIA GITHUB PAGES
1. Maak of gebruik een GitHub-account op github.com.
2. Klik rechtsboven op + → New repository. Kies bv. `bignmbrs-site`, zet hem **Public** en maak hem aan.
3. Kies `Add file` → `Upload files` en upload de *inhoud* van de uitgepakte map: `index.html`, `support.html`, `privacy.html`, `style.css`, `i18n.js` en de map `assets` met logo. Of upload via GitHub Desktop. Zorg dat `index.html` in de hoofdmap van de repository staat.
4. Ga in de repository naar Settings → Pages → Build and deployment → Deploy from a branch → `main` en `/ (root)` → Save.
5. De URL krijgt de vorm `https://GEBRUIKERSNAAM.github.io/bignmbrs-site/` en de twee andere pagina's krijgen `/support.html` en `/privacy.html`. Gebruik alleen de werkelijke URL die GitHub Pages toont.
6. Test de site en beide pagina's in een privévenster, ook op iPhone. Ze moeten zonder inloggen bereikbaar zijn.
7. Vul de exacte publieke link van `support.html` in bij **Support URL**, en de exacte link van `privacy.html` bij **Privacy Policy URL** in App Store Connect.

GitHub Pages voor een publieke repository is doorgaans gratis. Deel geen persoonlijke gegevens of geheimen in een publieke repository.
