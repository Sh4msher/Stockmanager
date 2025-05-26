# Vorratsmanager – dein intelligentes Lebensmittellogistiksystem

Ein lokal oder serverseitig betreibbarer Vorrats- und Einkaufsmanager mit Rezeptvorschlägen, Verbrauchsanalyse und automatischer Einkaufsliste.  
Frontend in HTML/CSS/JS – Backend in Java (Spring Boot) – Datenhaltung über SQLite.

---

## Projektidee

**Ziel**: Vollständige Verwaltung des persönlichen Lebensmittelvorrats mit Fokus auf Alltagstauglichkeit, Automatisierung und Datenauswertung.

**Use-Cases:**
- Hinzufügen von Lebensmitteln beim Einkauf (Menge, Preis, Haltbarkeit, Lagerort)
- Anzeige verfügbarer Lebensmittel mit Filterfunktionen
- Markierung von "verbraucht“, "weggeworfen“ oder "abgelaufen"
- Rezeptvorschläge basierend auf Vorrat
- Automatische Einkaufsliste bei fehlenden Zutaten
- Statistische Auswertung: Ausgaben, Verbrauchsverhalten, Lagerdauer, Ernährungsmuster

---

## Projektstruktur

```plaintext
vorratsmanager/
├── backend/               # Java Spring Boot Backend
│   ├── src/              
│   └── pom.xml
├── frontend/              # HTML/CSS/JavaScript Oberfläche
│   ├── index.html
│   ├── einkaufsliste.html
│   ├── styles.css
│   └── script.js
├── database/
│   └── schema.sql         # Tabellen für Vorräte, Rezepte, Nutzung etc.
├── README.md              # Dieses Dokument
