# Coderr/ Frontend Project

![Coderr Logo](assets/logo/logo_coderr.svg)

Dieses Projekt ist ein einfaches Frontend, das mit **Vanilla JavaScript** (reines JavaScript ohne Frameworks) erstellt wurde. Es wurde speziell entwickelt, um Schülern der **Developer Akademie** mit Backend-Erfahrung den Einstieg in kleinere Frontend-Anpassungen zu erleichtern.

---

## Voraussetzungen

- Ein funktionierendes Django-Backend (`Coderr/`), das **nicht** in diesem Projekt enthalten ist.
- Visual Studio Code mit der **Live Server**-Erweiterung oder eine ähnliche Möglichkeit, die `index.html` lokal im Browser zu starten.
- A separate local backend repository is required for full functionality.
- The backend must run locally at:

```text
http://127.0.0.1:8000/api/
```

---

## Project Structure

This frontend is part of a separated full-stack project setup.

Recommended local structure:

```text
project_coderr/
├── frontend/
└── backend/
```

---

## Nutzung

1. Stelle sicher, dass das Backend `Coderr/` läuft.
2. Öffne dieses Projekt in **Visual Studio Code**.
3. Rechtsklicke auf die Datei `index.html` und wähle **Open with Live Server**, um das Projekt zu starten.

---

## Guest Logins

The frontend provides predefined guest login buttons for testing.

Configured guest users:

```text
Customer:
username: KarlKalle
password: Dagi1234

Business:
username: WillWill
password: Dagi1234
```

---

## Frontend Configuration

Important configuration file:

```text
shared/scripts/config.js
```

---

## Ziel des Projekts

Dieses Frontend wurde bewusst mit **Vanilla JavaScript** erstellt, um die folgenden Ziele zu erreichen:

- **Einfacher Einstieg**: Durch den Verzicht auf Frameworks wie React oder Angular bleibt der Code leicht verständlich und nachvollziehbar.
- **Lernen durch Anpassung**: Schüler können den Code anpassen, um kleine Änderungen vorzunehmen und Frontend-Konzepte besser zu verstehen.
- **Backend-Erweiterung**: Das Projekt lässt sich einfach an das bestehende Django-Backend `Coderr/` anbinden.

---

## Hinweis

Dieses Projekt ist **ausschließlich für Schüler der Developer Akademie** gedacht und nicht zur freien Nutzung oder Weitergabe freigegeben.

---

## JSDoc - ansehen

1. Navigiere in den Ordner `docs/`
2. Du kannst das Projekt öffnen mit Doppelklick auf `docs/index.html`, oder im Terminal
   Windows: `start docs/index.html`
   macOS: `open docs/index.html`
   Linus: `xdg-open docs/index.html`
