# Datenökonomie - Welche Möglichkeiten gibt es für Personen, aktiv ihre Daten ökonomisch zu verwerten?
## Installation in VS Code
1. Repository klonen
`git clone ...`
2. LaTex-Workshop-Extension in VS Code installieren
3. Ordner in VS Code öffnen
4. Prüfen, ob im Ordner `.vscode` die Datei `settings.json` liegt. Diese dient der Überschreibung der Build-Settings, um das Glossar und das Literaturverzeichnis direkt mit zu übersetzen
5. Build durchführen

## Hinweise für VS Code
- Mit der Tastenkombination `Alt + Z` werden in VS Code die Wörter gewrappt
- PDF öffnen: Tex-Plugin öffnen -> Commands -> View LaTex PDF oder im Explorer die IWBIS_Datenoekonomie.pdf öffnen

## Grundlagen LaTex
- **Überschriften:** `\chapter{*}`, `\section{*}`, `\subsection{*}`, `\subsubsection{*}`
- **Zitate:** Quelle in der Bibliography.bib hinzufügen und mit `\cite{*}` in den Fließtext einbinden
- **Glossar:** Glossareintrag in der Glossaar.tex hinzufügen und mit `\gls{*}` in den Fließtext einbinden
- **neue Datei einbinden:** neue Datei `*.tex` erstellen und an gewünschter Stelle in der IWBIS_Datenoekonomie.tex per `\input{*.tex}` einbinden
