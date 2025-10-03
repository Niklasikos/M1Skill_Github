# Werken met Git en GitHub

Een remote repository aanmaken:

* Ga naar Github en maak een account aan
* klik dan boven rechts op het plus een maak een nieuw repository aan
* heb altijd add readme aan goed om informatie door te geven
* om het repository te clonen klik op code in jouw remote repository en dan bij https copy de link
* ga dan in een map op jouw computer een open een terminal een schrijf dit daar in `git clone (link)`

![afbeelding met het plus](/Les4/images/Schermafbeelding%202025-09-27%20215422.png)
![afbeelding met het het repository maken](/Les4/images/Schermafbeelding%202025-09-27%20215443.png)
![afbeelding met de clone link](/Les4/images/Schermafbeelding%202025-09-27%20215524.png)


## Onderdelen

starten met een lokale repo en werken met een online repo:

- Een nieuwe lokale repository aanmaken met `git init`
- Bestanden toevoegen met `git add`
- Een commit maken met `git commit -m "bericht"`
- Verbinden met een online repo via `git remote add origin <url>`
- Code uploaden naar GitHub met `git push -u origin main`

## Acties die je moet uitvoeren

- Installeer [Git](https://git-scm.com) en maak een GitHub-account aan
- Maak een nieuwe repository op GitHub
- Koppel je lokale project aan GitHub
- Gebruik `git status` om te zien welke bestanden gewijzigd zijn
- Upload wijzigingen regelmatig naar GitHub met `git push`

## Extra informatie

commands en tips

1. `git clone <url>`  kopieer een bestaande repository
2. `git pull`  haal de nieuwste updates van het repository op GitHub
3. `git log`  bekijk de geschiedenis van commits
4. `git status`  check hoe het staat met jouw git
5. `git add` voegt bestanden toe aan de stage die je commiten gaat
6. `gitk` opend de interface van het repository met git 
7. Maak duidelijke commits messages dan begrijp je ook wat je gedaan hebt later

## Stappenplan (genummerde lijst)

1. Maak een map voor je project
2. Open in de map een integrated terminal
3. Initialiseer een repo met `git init`
4. Voeg een bestand toe met git add en commit het
5. Maak een nieuwe repo aan op GitHub
6. Voeg de GitHub-url toe met `git remote add origin`
7. Push je bestanden naar GitHub
8. Controleer op GitHub of je bestanden er staan


## meer informatie

- [Officiële Git documentatie](https://git-scm.com/doc)
- [GitHub Guides](https://docs.github.com/nl/get-started)
- [Markdown handleiding](https://www.markdownguide.org/basic-syntax/)

