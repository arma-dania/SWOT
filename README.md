# SWOT-værkstedet

Undervisningsmateriale om SWOT-analysen og TOWS-matricen: viden, træningsøvelser og quiz.

Siderne er selvstændige filer uden byggetrin: `index.html` (værkstedet) og `skabelon.html` (skabelon med tjek). Åbn den direkte i en browser, eller slå GitHub Pages til for repoet (Settings → Pages → branch `main`, mappe `/`).

## Indhold

- **Viden**: SWOT's formål, de to akser, interne og eksterne forhold, kvalitet i SWOT-punkter, prioritering (sandsynlighed × konsekvens, vigtighed × præstation), faldgruber og overgangen til TOWS.
- **Træning**: tre øvelser på den opdigtede case Cykelværket ApS (sortering, find fejlen, prioritering).
- **Quiz**: 13 spørgsmål med forklaringer og resultat fordelt på emner.
- **TOWS**: viden om de fire strategifelter (SO, ST, WO, WT), fremgangsmåde, kvalitet, valg og faldgruber; tre øvelser på Cykelværkets prioriterede SWOT (kombinér, hvilket felt, find fejlen) og en quiz med 13 spørgsmål.
- **I timen**: ni klasseøvelser til sprint 2 (par og grupper) i fire dele, fra begreber til en prioriteret SW for Living Flowers. Hver øvelse kan foldes ud med formål, materialer, trin med minuttal, produkt og tip til underviseren. Tips skjules ved at sætte `VIS_TIPS = false` i scriptet i `index.html`.

## Skabelon med tjek

`skabelon.html` lader de studerende udfylde SWOT (punkt, kilde, betydning, prioritering) og TOWS (strategi, felt, henvisninger, valgt). Et regelbaseret tjek i browseren stiller spørgsmål, når et punkt er vagt, udokumenteret, mangler kilde eller betydning, ligner en handling, eller ser ud til at stå i det forkerte felt. Punkter og strategier kan flyttes med ét klik. Arbejdet gemmes i browseren og kan gemmes som fil, åbnes igen og kopieres som tekst til rapporten.

## Moodle

`moodle/swot-traening.html` er en selvstændig udgave af fanen Træning (casen og de tre øvelser) til upload i Moodle som fil. Alt CSS og JavaScript ligger i filen. Den er trukket ud af `index.html`; ændres øvelserne på sitet, skal filen laves igen.
