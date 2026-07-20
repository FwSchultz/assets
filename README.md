<div align="center">

  <img src="bots/FwS-Bots/Bot.png" alt="FwSchultz Assets" width="200" height="auto" />
  <h1>FwSchultz Assets</h1>

  <p>Zentrale Ablage für Logos, Symbole, Screenshots und weitere Medien meiner GitHub-Projekte.</p>

</div>

## Über das Repository

Dieses Repository stellt wiederverwendbare Bilddateien für die Dokumentation meiner Projekte bereit. Mehrere öffentliche Repositories binden Logos und andere Medien direkt über GitHub-URLs aus dieser Ablage ein.

Typisches Beispiel:

```html
<img src="https://github.com/FwSchultz/assets/blob/main/bots/FwS-Bots/Bot.png" alt="Projektlogo" width="200" />
```

## Verwendung

Für eine Darstellung innerhalb einer GitHub-README kann die normale `github.com/.../blob/...`-Adresse verwendet werden.

Für Anwendungen oder Webseiten, die eine direkte Bilddatei benötigen, eignet sich die Raw-Adresse:

```text
https://raw.githubusercontent.com/FwSchultz/assets/main/PFAD/ZUR/DATEI.png
```

## Struktur

Die Medien werden nach ihrem Verwendungszweck beziehungsweise dem zugehörigen Projekt gruppiert. Bestehende Pfade sollten nicht ohne Weiteres umbenannt oder verschoben werden, da andere Repositories direkt darauf verweisen können.

Empfohlene Struktur für neue Dateien:

```text
assets/
├── bots/
│   └── PROJEKTNAME/
├── tools/
│   └── PROJEKTNAME/
├── screenshots/
│   └── PROJEKTNAME/
└── README.md
```

## Regeln für neue Dateien

- eindeutige, verständliche Dateinamen verwenden
- nach Möglichkeit Kleinbuchstaben und Bindestriche nutzen
- Leerzeichen und Sonderzeichen vermeiden
- Bilder vor dem Hochladen sinnvoll komprimieren
- keine Zugangsdaten, privaten Fotos oder personenbezogenen Informationen hochladen
- bestehende öffentlich verwendete Pfade nicht verändern
- ersetzte Dateien möglichst unter demselben Pfad aktualisieren

## Hinweise zu Dateiformaten

- `PNG` für Logos, Symbole und Transparenz
- `JPG` oder `WEBP` für größere Screenshots und Fotos
- `SVG` nur aus vertrauenswürdiger Quelle und ohne eingebettete Skripte

## Urheberrecht

Die Dateien in diesem Repository können unterschiedliche Ursprünge und Nutzungsrechte besitzen. Eine Datei darf nur außerhalb des jeweils zugehörigen Projekts weiterverwendet werden, wenn die entsprechenden Rechte dies erlauben.

## Kontakt

**Fw.Schultz**

- Website: https://fwschultz.de
- GitHub: https://github.com/FwSchultz
- LinkedIn: https://de.linkedin.com/in/oliver-blume
