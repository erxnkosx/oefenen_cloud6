# Oefening 3 — GitHub Actions: repo-visualizer (zoals juni-examen)

Je krijgt een kleine statische site (een paar bestanden). Je hoeft niets aan te passen.

## Gevraagd
1. Maak een publieke repo en push deze bestanden erin.
2. Schrijf een workflow die bij een wijziging op `main` een diagram van je bestanden maakt
   met de action **repo-visualizer** (githubocto/repo-visualizer).
   - Het diagram wordt NIET gecommit (zet de juiste optie zodat er geen commit gebeurt).
   - Upload het diagram als **artifact** met de naam `diagram`.

## Tips
- Zoek de exacte inputs op in de README van de action (output_file, should_push).
- Vergeet `actions/checkout` niet.
- Controleer in het tabblad Actions: groen vinkje + downloadbaar artifact `diagram`.

Zet je oplossing in een mapje `vraag-github-actions`.
