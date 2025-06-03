# 🏷️ GitHub Labelstruktur – Wikonia Cockpit

Standardisierte Labels für Issues in diesem Repository – für Klarheit, Struktur und Effizienz.

---

## 🔧 TYPE (Art des Tickets)

| Label             | Beschreibung                         |
|------------------|--------------------------------------|
| `type: bug`       | Something isn’t working              |
| `type: feature`   | New feature or request               |
| `type: refactor`  | Code cleanup, no new behavior        |
| `type: docs`      | Dokumentation oder Kommentare        |
| `type: question`  | Unklare Stelle, offene Frage         |
| `type: decision`  | Offene Architektur-/Projektentscheidung |

---

## 🚦 STATUS (Bearbeitungsstand)

| Label                  | Beschreibung                                 |
|------------------------|----------------------------------------------|
| `status: todo`         | Noch nicht geplant oder definiert            |
| `status: planned`      | Eingeplant, z. B. für Release 1.x            |
| `status: in progress`  | In aktiver Bearbeitung                       |
| `status: blocked`      | Wartet auf Entscheidung oder anderen Task    |
| `status: canceled`     | Wird nicht umgesetzt                         |
| `status: done`         | Abgeschlossen und erledigt                   |

---

## 🔥 PRIO (Wichtigkeit)

| Label             | Beschreibung                          |
|------------------|----------------------------------------|
| `prio: critical`  | Muss sofort bearbeitet werden          |
| `prio: high`      | Wichtige Funktion, soll zeitnah rein   |
| `prio: low`       | Hat keine hohe Dringlichkeit           |
| `prio: trivial`   | Kaum relevant, eher kosmetisch         |

---

## 🧩 MODULE (Betroffener Bereich)

| Label                  | Beschreibung                         |
|------------------------|--------------------------------------|
| `module: auth`         | Authentifizierung, Benutzerrechte    |
| `module: customer`     | Kundenmodell, UI, Adressen usw.      |
| `module: wiki-core`    | Wiki-Provisioning, Domain-Handling   |
| `module: billing`      | Rechnungen, API, Buchhaltung         |
| `module: legal`        | Rechtliches: AGB, DSGVO, Zustimmung  |
| `module: cockpit-core` | Logging, Adminfunktionen, Config     |
| `module: ui`           | Optik, Design, Panels                |
| `status: tilt`         | (Optionaler Gag) System denkt sich: nope. |

---

> ✨ Dieses Schema hilft uns, Issues zu priorisieren, zu filtern und zu automatisieren.
