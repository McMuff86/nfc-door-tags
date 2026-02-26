# NFC Door Tags 🚪

Digitale Türdatenblätter via NFC-Sticker. Scan → Alle Türinfos auf dem Handy.

## Features

- 🔥 Brandschutz (EI30, VKF-Nummer, Prüfbericht)
- 📐 Masse (Lichtmass, Wandstärke, Bandseite)
- 🔧 Ausstattung (Schloss, Drücker, Zarge, Material)
- 📋 Projekt-Zuordnung (Gebäude, Geschoss, Raum)
- 📱 Mobile-optimiert (Dark Theme, schnell, offline-fähig)

## Wie funktioniert's?

1. **NFC-Sticker** auf die Tür kleben
2. **URL** mit Türdaten auf den Sticker schreiben (NFC Tools App)
3. **Scannen** → Browser öffnet Türdatenblatt

## Beispiel-URL

```
https://mcmuff86.github.io/nfc-door-tags/door-tag.html?id=OH1-EG-T101&fire=EI30&vkf=VKF-24891&b=900&h=2100&hinge=Links&dtype=Holz&mat=Eiche&frame=Stahlzarge&building=Obsthof 1&floor=EG&room=Korridor
```

## Parameter

| Param | Beschreibung | Beispiel |
|-------|-------------|----------|
| id | Tür-ID | OH1-EG-T101 |
| building | Gebäude | Obsthof 1 |
| floor | Geschoss | EG |
| room | Raum | Korridor |
| dtype | Türtyp | Holz 1-flüglig |
| fire | Brandschutz | EI30 |
| vkf | VKF-Nummer | VKF-24891 |
| report | Prüfbericht | PB-2024-1132 |
| inspect | Nächste Kontrolle | 2027-03 |
| b | Breite mm | 900 |
| h | Höhe mm | 2100 |
| wall | Wandstärke mm | 180 |
| hinge | Bandseite | Links |
| mat | Material | Eiche furniert |
| surf | Oberfläche | Lackiert RAL 9010 |
| lock | Schloss | Panikschloss BKS |
| handle | Drücker | FSB 1023 |
| frame | Zarge | Stahlzarge |
| thresh | Schwelle | Absenkdichtung |
| project | Projekt | Obsthof Ballwil |
| order | Auftrag | 25.1132-101 |
| notes | Hinweise | Fluchtweg |
| status | Status | OK / Pendenz |

## Hardware

- **NFC Sticker:** NTAG215, 504 Byte (reicht für alle Parameter)
- **App:** NFC Tools (Android/iOS, gratis)

## License

MIT
