# Viikko 2 – Jekyll-sivuston automatisointi GitHub Actionsilla

Jekyll-sivuston julkaisu voidaan automatisoida hyödyntämällä **GitHub Actions** -toimintoja. Kun koodivarastoon tehdään muutos (esimerkiksi push tai pull request), GitHub Actions voi automaattisesti käynnistää työnkulun, joka rakentaa ja julkaisee sivuston GitHub Pagesiin. Työnkulku määritellään `.github/workflows/`-hakemistossa YAML-tiedostona, jossa kuvataan vaiheet kuten Jekyllin asennus, sivuston rakentaminen ja lopullisen version siirtäminen julkaisualustalle. Tämä poistaa tarpeen manuaaliselle build- ja deploy-prosessille.

CI/CD-putkisto (Continuous Integration / Continuous Deployment) voidaan toteuttaa käyttämällä työkaluja kuten **GitHub Actions**, **Docker**, **Jenkins** tai **GitLab CI**. Kehitystyössä hyödynnetään versiohallintaa (Git), automaattisia testejä (esim. RSpec, Cypress), sekä linttereitä ja koodianalytiikkaa laadun varmistamiseksi. Kun muutokset hyväksytään, CI/CD-putkisto rakentaa, testaa ja julkaisee sovelluksen automaattisesti valitulle ympäristölle (esim. staging tai production).


