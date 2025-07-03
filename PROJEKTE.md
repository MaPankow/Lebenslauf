# Projekte

Meinen vollständigen Lebenslauf findest du [hier](LEBENSLAUF.md).

## Frontend-Apps mit React
Nach der Weiterbildung und durch das Praktikum habe ich meine Richtung gefunden und baue meine Fertigkeiten gezielt weiter aus. Hierfür nutze ich Codecademy, das sogenannte Skill Paths anbietet, an deren Ende vollständige Projekte stehen.
Im Rahmen des Skill Paths „Create a Front-End App with React“ habe ich derzeit zwei Projekte veröffentlicht. Beide sind mit React und CSS umgesetzt und nutzen externe APIs:
- Jammming: https://github.com/MaPankow/jammming (aktuell in Bearbeitung)
- Ravenous: https://github.com/MaPankow/ravenous


## Projekt Buchungsplattform für eine medizinische Veranstaltung

Diese Anwendung habe ich während meiner Praktikumszeit in der Firma IT’s Ambio implementiert.

### Projektbeschreibung:
Das End- und Dickdarmzentrum (im Folgenden EDZ) bietet jährlich eine Fortbildung für Ärzt*innen zum Thema Morbus Crohn an. Die Aufgabe war, anhand einer vorhandenen Default-Anwendung mit Next.js eine Anwendung zu bauen, die:

- Eine Registrierfunktion für Interessierte hat, über die sie sich für den Workshop anmelden können.
- Eine Login-Funktion, über die man auf ein Dashboard kommt, auf dem die Datensätze der Registrierten angezeigt werden.
- Informationen eines Flyers der Veranstaltung aus dem letzten Jahr enthält und die Anwendung basierend auf dem Design des Flyers mit Tailwind CSS zu gestalten.

### Genutzte Technologien:
- Next.js
- Tailwind CSS

### Die Homepage/Landing Page
Auf der Homepage sind die Informationen zum Workshop zu finden inklusive Kontaktdaten und Button, der zur Registrierung für die Veranstaltung führt. Für Mitarbeiter*innen des EDZ gibt es des Weiteren eine Login-Funktion. 

Inhalte wie Texte, Bilder und Icons habe ich in einer separaten JSON-Datei organisiert. Dadurch bleibt die Next.js-Komponente mit ihren JSX-Elementen und Styling übersichtlich und gut wartbar. Die Daten lassen sich so leicht austauschen oder aktualisieren, ohne dass man am Code der Seite selbst Änderungen vornehmen muss.

Das ist deshalb praktisch, weil ich zunächst die Informationen von der letzten Veranstaltung übernommen habe und die Inhalte später unkompliziert für zukünftige Workshops angepasst werden können.

![Landing-Page für die EDZ-Fortbildung](src/HP-1.png)
![Landing-Page für die EDZ-Fortbildung, unterer Teil](src/HP-2.png)

### Die Registrierungspage
Der Registrieren-Button auf der Homepage führt zu diesem Formular, in das Interessierte alle erforderlichen Daten eintragen und absenden. Diese werden dann in einer REST-API gespeichert. Der Platzhaltertext zeigt die erforderliche Eingabe an. Um den Flow zu testen, habe ich nach der Implementierung Daten eingegeben.

![Registrierformular, das noch nicht ausgefüllt wurde](src/RegisterFormLeer.png)


![Registrierformular ausgefüllt](src/RegisterFormMitDaten.png)

### Das Dashboard
Nach erfolgreichem Login erhalten die Mitarbeitenden des EDZ Zugriff auf das Dashboard, das eine Liste der registrierten Besucher*innen des Workshops anzeigt. Jedes Listenelement enthält Nachname, Vorname und Titel.

Ein Klick auf eine Zeile öffnet den vollständigen Datensatz der entsprechenden Person. Wird ein anderer Datensatz ausgewählt, schließt sich der zuvor geöffnete automatisch, und der neue Datensatz wird angezeigt. Ein Klick außerhalb der Listenelemente schließt den aktuell geöffneten Datensatz wieder.

![Dashboard mit der Übersicht der Registrierten (Dummydata)](src/Dashboard1.png)

![Dashboard mit offenem Datensatz](src/DashboardMitEingetragenemDatensatz.png)

## Übungsprojekte aus der Weiterbildung zur Backend- und Datenbank-Entwicklerin

Im Rahmen meiner Weiterbildung bei Bergemann und Höhne in den Modulen Backend-Entwicklung und Datenbank-Entwicklung habe ich meine Fähigkeiten durch verschiedene Aufgaben und Projekte vertieft. Eine Auswahl meiner Übungsprojekte findest du hier.

**Hinweis:** Um meinen Lernfortschritt detailliert festzuhalten, sind die Dokumentationen teilweise sehr ausführlich. Trotzdem könnten sie für dich interessant und unterhaltsam sein.

### Datenbank-Projekte
- Übungsprojekt MongoDB: https://github.com/MaPankow/MongoDB_Rezepte_Social_Network  
- Übungsprojekt PostgreSQL: https://github.com/MaPankow/PostgreSQL_Onlineshop  
- Übungsprojekt MariaDB und SQLite: https://github.com/MaPankow/Artivity---Datenbankenprojekt-mit-MariaDB-und-SQLite

### Backend-Projekte
- Übungsprojekt Java Spring Anwendung: https://github.com/MaPankow/Orders-Spring-exercise  
- Übungsprojekt Django Anwendung: https://github.com/MaPankow/Restaurant-Django-exercise
