# Evaluation: Jupyter Notebook-basierte Prüfungsumgebung

Dieses Repository enthält den Proof-of-Concept für eine interaktive, digitale Prüfungsumgebung im Rahmen einer Masterarbeit an der Leibniz Universität Hannover.

Das entwickelte digitale Prüfungsmedium ist für das Lernfeld 3 (Steuerungen analysieren und anpassen) im Ausbildungsberuf Elektroniker/-in für Betriebstechnik konzipiert.

---

## Durchführung der Expertenevaluation

Um an der fachdidaktischen Evaluation teilzunehmen, folge bitte diesen drei Schritten:

### 1. Klausurszenario durchspielen (ca. 15–20 Minuten)
Klicke auf den folgenden Binder-Button, um die interaktive Prüfungsumgebung direkt in deinem Browser zu starten:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/tobiaswolff1988/lf3-klausur-evaluation/main?urlpath=voila%2Frender%2FLF3_Klausur_final_v6.ipynb)

> **Hinweis zum Start:** Der MyBinder-Server baut im Hintergrund eine isolierte Docker-Umgebung auf. Dies kann beim ersten Aufruf (Cold Start) ein bis zwei Minuten dauern. Die Umgebung startet vollautomatisch im Voilà-Modus, wodurch der zugrundeliegende Python-Quellcode aus Gründen der Prüfungsintegrität ausgeblendet wird. Dir präsentiert sich direkt das reine, interaktive Prüfungsinterface.

### 2. Evaluationsrelevante Beobachtungspunkte während des Durchlaufs
Bitte bearbeite die Aufgaben der Klassenarbeit sequenziell. Um das anschließende Feedback im Evaluationsbogen fundiert abgeben zu können, richte dein Augenmerk als angehende Lehrkraft im Verlauf besonders auf folgende Aspekte[cite: 3]:

* **Didaktischer Aufbau und Kompetenzorientierung:** Achte darauf, wie das Einstiegsszenario der Sortieranlage SA-1 aufgebaut ist und ob die Aufgaben die Stufen der vollständigen Handlung (Informieren, Planen, Entscheiden, Durchführen, Kontrollieren, Bewerten) folgerichtig abbilden[cite: 3].
* **Nutzen der Repräsentationsebenen:** Beobachte, inwiefern der virtuelle Referenz-Leitstand das funktional-systemische Verständnis unterstützt und wie der in Aufgabe 3.3 automatisch generierte Signalflussplan als kognitive Eigenkontrolle wirkt[cite: 3].
* **Inbetriebnahme und Fehlerdiagnose:** Analysiere das didaktische Potenzial des dedizierten Fehler-Leitstands in Aufgabe 4.1. Achte darauf, wie die softwaretechnische Umsetzung des Fehlverhaltens die diagnostischen Fähigkeiten der Prüflinge fordert[cite: 3].
* **Praxistauglichkeit und Usability:** Beurteile während der Eingaben, ob die Bedienung der Dropdown-Menüs, Textfelder und Sortierkacheln für Auszubildende ohne informatische Vorkenntnisse intuitiv verständlich und übersichtlich gelöst ist[cite: 3].
* **Korrekturmodell:** Wenn du am Ende auf den roten Button "Klausur final abgeben" klickst, simuliert das System den Abschluss. Beurteile das eingeblendete Bewertungspanel hinsichtlich der ökonomischen Entlastung für Lehrkräfte (Kombination aus automatischer und manueller Bewertung)[cite: 3].

### 3. Evaluationsbogen ausfüllen (ca. 10 Minuten)
Bitte öffne nach dem vollständigen Durchspielen der Klausur den folgenden Link und fülle das anonyme Feedback-Formular aus. Deine datengestützte Bewertung bildet das Fundament für die wissenschaftliche Auswertung der Masterarbeit[cite: 3]:

[Hier klicken: Zum Google Forms Evaluationsbogen](HIER_DEINEN_GOOGLE_FORMS_LINK_EINFÜGEN)

---

## Technische Infrastruktur & Lokale Ausführung

Falls du das Notebook im Rahmen der wissenschaftlichen Transparenz lokal in deiner eigenen Jupyter-Umgebung untersuchen, den Quellcode der Widgets einsehen oder Anpassungen testen möchtest, kannst du das Repository klonen:

```bash
# Repository klonen
git clone [https://github.com/tobiaswolff1988/lf3-klausur-evaluation.git](https://github.com/tobiaswolff1988/lf3-klausur-evaluation.git)
cd lf3-klausur-evaluation

# Umgebung mit Conda/Mamba aufbauen
conda env create -f environment.yml
conda activate notebook

# Jupyter Lab starten
jupyter lab LF3_Klausur_final_v6.ipynb
```
## Lizenz

Der programmierte Quellcode der interaktiven Widgets und die Simulations-Infrastruktur stehen unter der Apache License 2.0. Die fachdidaktischen Aufgabenstellungen, Grafiken und Texte unterliegen der Creative Commons Attribution 4.0 International Lizenz (CC BY 4.0).
