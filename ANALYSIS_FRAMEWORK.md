# Analysis Framework – Fib-Projekt

## Ziel des Frameworks

Das "Fib-Analysis Framework" stellt systematisch sicher, dass unsere Fibonacci-basierten Handelsregeln und Algorithmen klaren, reproduzierbaren Qualitätskriterien folgen. Alle Testfälle, Muster und Entwicklungsschritte werden transparent dokumentiert und unter echten Chartbedingungen geprüft.

---

## Kernpunkte

- **Testfall-Basierung:**  
  Alle Codes und Regelwerke werden direkt an Mustercharts aus dem Archiv validiert und getestet (siehe README.md).
- **Objektive Dokumentation:**  
  Jeder Analyse-Schritt ist nachvollziehbar inkl. Zeit, Markt, Screenshot, Regelversion.
- **Erweiterbarkeit:**  
  Neue Muster/Bedarfe können einfach ins Framework aufgenommen werden; jeder neue Testfall verbessert unser System.
- **Feedback-Schleife:**  
  Nova und Wolfgang prüfen regelmäßig Muster und Fehlermeldungen, um das Regelwerk weiter zu schärfen.

---

## Vorgehensweise (Best Practice)

1. **Fall hinzufügen:**  
   - Neuer Fib-Muster-Chart dokumentieren (siehe README.md Tabelle).
   - Instrument, Typ, Besonderheit & Zeitrahmen eindeutig festhalten.
2. **Regelmodul entwickeln:**  
   - Code/Regel muss das Chart-Muster korrekt erkennen.
   - TDD: Besteht das Modell den Testfall am Muster?  
3. **Review/Optimierung:**  
   - Wolfgang und Nova kontrollieren gemeinsam den Output.
   - Fehler werden direkt in Framework dokumentiert und angepasst.

---

Alle Schritte werden transparent im Repo festgehalten (z.B. als Markdown-Tabelle, CSV, Quelltext-Kommentar).

---

**Hinweis:**  
Dieses Framework ist exklusiv für das Team „Wolfgang & Nova“ optimiert und dient als Leitlinie zur Entwicklung des Fib-Systems.