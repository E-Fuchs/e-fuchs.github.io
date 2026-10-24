# e-fuchs · Projekte

Sammelseite unter **https://e-fuchs.github.io/** – Übersicht der öffentlichen Projekte von Jochen G. Fuchs
([efuchs.net](https://efuchs.net)). Jedes Projekt ist ein eigenes Repo mit eigener Pages-Seite unter `/<repo>/`.

| Projekt | Seite | Repo |
|---|---|---|
| Thekenfuchs | https://e-fuchs.github.io/thekenfuchs/ | [E-Fuchs/thekenfuchs](https://github.com/E-Fuchs/thekenfuchs) |

## Dateien

| Pfad | Inhalt |
|---|---|
| `index.html` | Übersicht mit Projektkarten (bewusst ohne JavaScript) |
| `datenschutz.html` | Datenschutzhinweis für diese Seite und alle Projektseiten |
| `assets/style.css` | Stylesheet, hell/dunkel |
| `assets/fonts/` | Barlow, Barlow Condensed (SIL Open Font License 1.1) |
| `assets/projects/` | Vorschaubilder je Projekt |

Impressum: kein eigenes – alle Seiten verlinken auf https://efuchs.net/impressum/.

Pages: Settings → Pages → Deploy from a branch → `main` / root.

## Neues Projekt aufnehmen

Neue `<article class="project">` in `index.html` kopieren, Bild nach `assets/projects/` legen.

## Regeln (gemeinsamer Ursprung aller Projekte)

- **Kein Service Worker** auf dieser Seite und keiner mit Scope `/` in einem Projekt.
- **Nie** `localStorage.clear()`, `sessionStorage.clear()` oder alle Caches löschen. Jedes Projekt nutzt
  eigene Schlüssel mit Präfix (Thekenfuchs: `thekenfuchs.`).
- **Keine externen Ressourcen**, kein Tracking, keine Cookies.
- **Eigene Domain nur jetzt oder nie:** Eine Domain auf diesem Repo gilt für alle Projektseiten. Sie darf nur
  gesetzt werden, bevor Geräte produktiv eingerichtet sind – sonst verlieren installierte Web-Apps ihre Updates.
- Der Datenschutzhinweis deckt alle Projekte ab. Ein neues Projekt, das anders mit Daten umgeht, muss hier
  ergänzt werden.

Schriften: Barlow und Barlow Condensed, © The Barlow Project Authors, SIL Open Font License 1.1.
