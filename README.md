# SWOT shop

Undervisningsmateriale om SWOT-analysen og TOWS-matricen: viden, træningsøvelser og quiz.

Siderne er selvstændige filer uden byggetrin: `index.html` (selve siden) og `skabelon.html` (skabelon med tjek). Åbn den direkte i en browser, eller slå GitHub Pages til for repoet (Settings → Pages → branch `main`, mappe `/`).

## Indhold

- **SWOT**: SWOT's formål, de to akser, interne og eksterne forhold, kvalitet i SWOT-punkter, prioritering (sandsynlighed × konsekvens, vigtighed × præstation), faldgruber og overgangen til TOWS.
- **Træning**: seks øvelser på den opdigtede case Cykelværket ApS. SWOT: sortering, find fejlen, prioritering. TOWS: kombinér, hvilket felt, find fejlen.
- **Quiz**: to quizzer, om SWOT og om TOWS, hver med 13 spørgsmål, forklaringer og resultat fordelt på emner.
- **TOWS**: en animation i syv trin fra prioriteret SWOT til valgte strategier, de fire strategifelter (SO, ST, WO, WT), fremgangsmåde, kvalitet med tjekliste, valg og faldgruber. Øvelser og quiz ligger under Træning og Quiz.
- **I timen**: syv klasseøvelser til sprint 2 (par og grupper) i tre dele, fra kvaliteten af det enkelte punkt til en prioriteret SW for Living Flowers. Hver øvelse kan foldes ud med formål, materialer, trin med minuttal, produkt og tip til underviseren. Tips skjules ved at sætte `VIS_TIPS = false` i scriptet i `index.html`.

## Skabelon med tjek

`skabelon.html` lader de studerende udfylde SWOT (punkt, kilde, betydning, prioritering) og TOWS (strategi, felt, henvisninger, valgt). Et regelbaseret tjek i browseren stiller spørgsmål, når et punkt er vagt, udokumenteret, mangler kilde eller betydning, ligner en handling, eller ser ud til at stå i det forkerte felt. Punkter og strategier kan flyttes med ét klik. Arbejdet gemmes i browseren og kan gemmes som fil, åbnes igen og kopieres som tekst til rapporten.

## Moodle

`moodle/swot-traening.html` er en selvstændig udgave af fanen Træning (casen og de seks øvelser i SWOT og TOWS) til upload i Moodle som fil. Alt CSS og JavaScript ligger i filen. Den er trukket ud af `index.html`; ændres øvelserne på sitet, skal filen laves igen.
