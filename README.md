# 🍷 Wineyards -- Home Assistant Theme & Card Collection

![GitHub release (latest by
date)](https://img.shields.io/github/v/release/cheinisch/ha-wineyards?style=for-the-badge)
![GitHub last
commit](https://img.shields.io/github/last-commit/cheinisch/ha-wineyards?style=for-the-badge)
![GitHub](https://img.shields.io/github/license/cheinisch/ha-wineyards?style=for-the-badge)
![HACS
Custom](https://img.shields.io/badge/HACS-Custom-orange?style=for-the-badge)

Modernes Farbschema und stilvolle Karten für Home Assistant.

Dieses Repository enthält:

-   Wineyards Theme (Dark & Light)
-   Updatefähig über HACS

------------------------------------------------------------------------

## Installation über HACS (empfohlen)

Klicke auf den Button unten, um das Repository direkt in HACS
hinzuzufügen:

[![Open your Home Assistant instance and add this
repository](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?repository=https://github.com/cheinisch/ha-wineyards-theme&category=theme)

### Danach:

1.  HACS → Themes
2.  Wineyards Theme installieren
3.  Home Assistant neu starten
4.  Profil → Theme auswählen

------------------------------------------------------------------------

## ⚙️ Voraussetzung

Theme-Unterstützung muss in deiner `configuration.yaml` aktiviert sein:

``` yaml
frontend:
  themes: !include_dir_merge_named themes
```

------------------------------------------------------------------------

## Enthaltene Themes

-   wineyards_dark\
-   wineyards_light


------------------------------------------------------------------------

## Updates

Sobald neue Versionen veröffentlicht werden, zeigt HACS automatisch ein
Update an.

------------------------------------------------------------------------

## Lizenz

MIT License
