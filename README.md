# Recap letzte Lehreinheit

- Git installieren
- UV installieren



## 🪛 1. Git installieren

Git ist eine freie Software zur Versionsverwaltung von Dateien und Projekten.
Ermöglicht Versionierung und Zusammenarbeit.

GitHub ist eine proprietäre und öffentliche Softwareentwicklungsplattform auf Grundlage der Versionsverwaltungs-Software Git. &copy; [Wikipedia](https://de.wikipedia.org/wiki/GitHub) 

Download:

👉 https://git-scm.com/download/win

Installation starten und folgende Optionen verwenden:

✔ Editor
Use Visual Studio Code as Git's default editor

✔ PATH Option (WICHTIG)
Git from the command line and also from 3rd-party software
👉 sonst findet VS Code Git nicht.

✔ HTTPS Transport
Use the OpenSSL library

✔ Line Endings (sehr wichtig bei Python!)
Checkout Windows-style, commit Unix-style line endings
(core.autocrlf=true)
→ verhindert spätere Diff-Hölle.

✔ Terminal
Use Windows' default console window
(oder Windows Terminal — egal)

Hier ist die [Offizielle Dokumentation](https://code.visualstudio.com/docs/sourcecontrol/overview) mit Introvideo.

Tastenkombination: `Strg + Umschalt + P` Add remote ind die Suche ergibt Git: Add remote. Dort kann euer GitHub Account hinzugefügt werden.

### Testen

` PS C:\Users\UlrichLehre\Documents\Git_Intro> git remote -v 
  origin  https://github.com/ulrichczopak88/Git_Intro.git (fetch)'`

### Git lernen

  [Git Branching interaktiv erlernen: https://learngitbranching.js.org/?locale=de_DE](https://learngitbranching.js.org/?locale=de_DE)

  [https://git-scm.com/learn](https://git-scm.com/learn)

 [Cheatsheet](https://git-scm.com/cheat-sheet)
 
## UV installieren

An extremely fast Python package and project manager, written in Rust. &copy; [https://docs.astral.sh/uv/](https://docs.astral.sh/uv/)

Ermöglicht uns das installieren von Python Packages wie Pandas, Numpy, Matplotlib und erstellt automatisch eine Projektstruktur mit virtueller Umgebung und gitignore File.

Installation im Terminal:

`PS> powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex" `

`uv init` Erstelt ein neues Projekt im aktuellen Terminal Ordner.

## Powershell oder Terminal Grundkenntisse

In einem Terminal oder der Windows Powershell haben wir folgende Befehle verwendet:

`cd`: change directory. Zum Beispiel `cd ../..`geht zwei Ordner Ebenen retour. `cd .\D` dann Tabulatortaste itteriert durch alle Ordner im aktuellen Ordner welche mit D beginnen

`ls`: Listet den ganzen Inhalt auf.

`mkdir`make Directory: Erstellt einen neuen Ordner.

## Mardown
[Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)

# Ziel für die zweite Lehreinheit: Jupyter Notebook Wetter Daten importieren und plotten mit Pandas und Matplotlib

1. Projektordner erstellen
2. `uv add pandas matplotlib jupyter ipykernel`:

`PS C:\Users\UlrichLehre\Documents\Git_Intro> uv add pandas matplotlib `

`Using CPython 3.14.3`

`Creating virtual environment at: .venv`

`Resolved 14 packages in 510ms`
`Prepared 3 packages in 6.03s`
`Installed 13 packages in 1.39s `

## Jupyter Notebook erstellen

Tastenkombi `Strg + Umschalt + P` New schlägt schon vor Create new Jupyter Notebook. (Jupyter Extension muss installiert sein).

Oder: `+` New File mit `.ipynb`Endung (IPython Notebook.)








