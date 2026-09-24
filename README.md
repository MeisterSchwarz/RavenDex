# RavenDex

**Community-maintained Wizard101 game data.**

RavenDex is a structured data repository for Wizard101 containing internal
game identifiers, localizations, and community-maintained metadata.

It serves as a reusable source of game data for tools built around Wizard101,
including overlays, websites, APIs, Discord bots, desktop applications, and
other community projects.

RavenDex is also used by
[Corvin](https://github.com/MeisterSchwarz/corvin101), a Wizard101 companion
application.

---

## 🎯 Goals

RavenDex aims to:

- Build a structured and reusable dataset for Wizard101.
- Preserve internal game identifiers as stable references.
- Support multiple languages and localizations.
- Separate game data from individual applications.
- Make Wizard101 data easy to consume programmatically.
- Allow community projects to share and improve the same dataset.

---

## 📦 Data

RavenDex currently contains data for entities such as:

- Enemies
- Zones
- NPCs
- Objects
- Internal game identifiers
- Localized names
- Community-maintained translations

The dataset will continue to grow as additional game data is discovered,
collected, and verified.

---

## 🌍 Localization

RavenDex identifies game entities using their internal identifiers rather than
their localized display names.

This keeps references stable across different languages and applications while
allowing each entity to provide multiple localizations.

Example:

```json
{
  "id": "AV-Wyrm-Firespitter-R11-01",
  "translations": {
    "en": "Example English Name",
    "de": "Example German Name"
  }
}