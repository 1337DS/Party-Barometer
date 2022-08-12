# Party-Barometer
Scraping web for events in mannheim, their number of likes and predict the number of people who want to go out on a given day based on their likes.
Additional scraping for exams on universities and consider the influence to create a "Party-Score" of any given day


## TODO
- Algorithmus Code
- Prüfungstermine HS Mannheim ❌ -> benötigt Einloggdaten
- Prüfungstermine Uni Mannheim erst- und Zweittermine ✔️
- Studierende Uni Mannheim (Bounding Boxes in PDF) ✔️
- App✔️
- Wetter ✔️
- Dokumentation/Anleitung ✔️


## Algorithmus:

Ausgangswert 100 (alle Studenten verfügbar und partywillig) ✔️

Minus:

- Prüfungsbelastungsfaktor (Anzahl Studenten x Prüfungen) ✔️
- Schlechtwetterfaktor (Schneckenhof, Hafen 49)✔️
- Sommerpause berücksichtigen ??

Plus:

- Anzahl Events✔️
- Monatsanfang/Ende ? ✔️
- Partyfaktor der Fakultät (generell/ Anzahl w Studenten)

## APP
 Es gibt verschiedene Möglichkeiten eine App mit Python-Code zu programmieren. 
 Bibliotheken die auf C basieren werden jedoch noch nicht unterstützt.
 Hier unsere Erfahrungen damit:
 
 1. Beeware / Briefcase 
    https://docs.beeware.org/en/latest/
    --> Hello World Anleitung hat nicht funktionert,  
    *RuntimeError: Failed to initialize Python.Runtime.dll
     Unable to start application 'helloworld'*

 2. Flutter/pyFlut/Flet
    https://flet.dev/
    https://dev.to/yash_makan/how-to-run-python-code-in-your-flutter-app-with-pyflut-hgc
 3. Kivy
    https://kivy.org/doc/stable/guide/packaging-android.html
 4. Dash ✔️
    https://plotly.com/dash/
