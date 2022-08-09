# Party-Barometer
Scraping web for events in mannheim, their number of likes and predict the number of people who want to go out on a given day based on their likes.
Additional scraping for exams on universities and consider the influence to create a "Party-Score" of any given day


## TODO
- Algorithmus Code
- Prüfungstermine HS Mannheim ❌
- Prüfungstermine Uni Mannheim erst- und Zweittermine ✔️
- Studierende Uni Mannheim (Bounding Boxes in PDF) ✔️
- Präsi 
- App
- Wetter 
- Dokumentation/Anleitung


## Algorithmus:

Ausgangswert 100 (alle Studenten verfügbar und partywillig)

Minus:

- Prüfungsbelastungsfaktor (Anzahl Studenten x Prüfungen)
- Schlechtwetterfaktor (Schneckenhof, Hafen 49)
- Sommerpause berücksichtigen ??

Plus:

- Anzahl Events
- Monatsanfang/Ende ?
- Partyfaktor der Fakultät (generell/ Anzahl w Studenten)

## APP
 Es gibt verschiedene Möglichkeiten eine App mit Python-Code zu programmieren. 
 Bibliotheken die auf C basieren werden jedoch noch nicht unterstützt.
 1. Beeware / Briefcase 
    https://docs.beeware.org/en/latest/
 2. Flutter/pyFlut/Flet
    https://flet.dev/
    https://dev.to/yash_makan/how-to-run-python-code-in-your-flutter-app-with-pyflut-hgc
 3. Kivy
    https://kivy.org/doc/stable/guide/packaging-android.html
 
