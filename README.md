# Evaluation: Jupyter Notebook-basierte Prüfungsumgebung (Lernfeld 3)

Dieses Repository enthält den Proof-of-Concept für eine interaktive, digitale Prüfungsumgebung im Rahmen einer Masterarbeit am Institut für Didaktics der Demokratie (IDD) / Didaktik der Elektrotechnik und Informatik der Leibniz Universität Hannover. 

Das entwickelte digitale Prüfungsmedium operationalisiert das **Modell der vollständigen Handlung** für das **Lernfeld 3 (Steuerungen analysieren und anpassen)** im Ausbildungsberuf Elektroniker/-in für Betriebstechnik.

---

##  Durchführung der Evaluation

Um an der Expertenevaluation teilzunehmen, folge bitte diesen drei Schritten:

### 1. Klausurszenario durchspielen (ca. 15–20 Minuten)
Klicke auf den folgenden Binder-Button, um die interaktive Prüfungsumgebung direkt in deinem Browser zu starten. 

[![Binder](https://mybinder.org/badge_logo.svg)](HIER_DEINEN_BINDER_LINK_EINFÜGEN)

*Hinweis zum Start:* Der Server baut im Hintergrund eine isolierte Umgebung auf. Dies kann beim ersten Aufruf ein bis zwei Minuten dauern. Die Umgebung startet automatisch im **Voilà-Modus**, wodurch der zugrundeliegende Python-Quellcode aus Gründen der Prüfungsintegrität ausgeblendet wird. Dir präsentiert sich direkt das reine, interaktive Prüfungsinterface (virtueller Leitstand, interaktive Gatter-Visualisierung und Eingabebereiche).

### 2. Den Fehler-Leitstand testen
Bitte spiele die Aufgaben sequenziell durch. Achte besonders auf das didaktische Zusammenspiel zwischen dem virtuellen Referenz-Leitstand, den automatisierten Signalflussplänen (Aufgabe 3.3) und dem dedizierten Fehler-Leitstand in der Diagnosephase (Aufgabe 4.1).

### 3. Evaluationsbogen ausfüllen (ca. 10 Minuten)
Bitte öffne nach dem vollständigen Durchspielen der Klausur den folgenden Link und fülle das anonyme Feedback-Formular aus:

**[Link zum Google Forms Evaluationsbogen](https://docs.google.com/forms/d/e/1FAIpQLScqmFrjQLkEVh7wQ-f67Vj3_EsGvDMR2bCKLa04bJ1c4DA05A/viewform?usp=dialog)**

---

## 🛠️ Technische Infrastruktur (Lokale Ausführung)

Falls du das Notebook lokal in deiner eigenen Jupyter-Umgebung untersuchen oder den Quellcode der Widgets einsehen möchtest, kannst du das Repository klonen und die benötigten Abhängigkeiten installieren:

```bash
git clone [https://github.com/DEIN_BENUTZERNAME/lf3-klausur-evaluation.git](https://github.com/DEIN_BENUTZERNAME/lf3-klausur-evaluation.git)
cd lf3-klausur-evaluation
pip install -r requirements.txt
jupyter lab LF3_Klausur_final_v6.ipynb
