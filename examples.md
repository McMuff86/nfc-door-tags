# NFC Door Tags – Beispiel-URLs

## Konzept
Jeder NFC-Sticker enthält eine URL mit Parametern → öffnet Türdatenblatt auf dem Handy.
NTAG215 hat 504 Byte → ~480 nutzbar für NDEF URL → reicht für alle Parameter.

## Hosting
- GitHub Pages (kostenlos): `https://mcmuff86.github.io/nfc-door-tags/door-tag.html?...`
- Oder eigene Domain: `https://doors.bucher-ag.ch/t?...`

## Beispiel-URLs

### 1. Brandschutztür EI30 – Obsthof OH1 EG
```
door-tag.html?id=OH1-EG-T101&building=Obsthof 1&floor=EG&room=Korridor&dtype=Holz 1-flüglig&fire=EI30&vkf=VKF-24891&report=PB-2024-1132&inspect=2027-03&b=900&h=2100&wall=180&hinge=Links&mat=Eiche furniert&surf=Lackiert RAL 9010&lock=Panikschloss BKS&handle=FSB 1023&frame=Stahlzarge Hörmann&thresh=Absenkdichtung&project=Obsthof Ballwil&order=25.1132-101&notes=Fluchtweg. Selbstschliesser obligatorisch.
```

### 2. Standard Innentür – OH2 OG1
```
door-tag.html?id=OH2-OG1-T205&building=Obsthof 2&floor=OG1&room=Schlafen&dtype=Holz 1-flüglig&b=800&h=2100&wall=120&hinge=Rechts&mat=Buche CPL&surf=Weiss 9016&lock=BBS Einsteckschloss&handle=FSB 1076&frame=Holzzarge Buche&thresh=Keine&project=Obsthof Ballwil&order=25.1132-101&status=OK
```

### 3. Schiebetür – OH4a EG
```
door-tag.html?id=OH4a-EG-T401&building=Obsthof 4a&floor=EG&room=Wohnen/Essen&dtype=Schiebetür&b=1200&h=2100&wall=120&mat=Glas ESG 8mm&surf=Satiniert&lock=Muschelgriff&frame=Aluminium-Führung&project=Obsthof Ballwil&order=25.1132-101&status=OK
```

### 4. Haustür Alu – OH7
```
door-tag.html?id=OH7-EG-HT01&building=Obsthof 7&floor=EG&room=Eingang&dtype=Alu Haustür&fire=E30&vkf=VKF-31002&b=1100&h=2200&wall=300&hinge=Links&mat=Aluminium&surf=Eloxiert E6/EV1&lock=Motorschloss KABA&handle=Stossgriff 600mm&frame=Alu-Rahmen thermisch getrennt&thresh=Schwelle 20mm&project=Obsthof Ballwil&order=25.1132-101&notes=Fingerprint + Badge-Leser vorgesehen
```

## Parameter-Referenz

| Param | Beschreibung | Beispiel |
|-------|-------------|----------|
| id | Tür-ID | OH1-EG-T101 |
| building | Gebäude | Obsthof 1 |
| floor | Geschoss | EG, OG1, UG |
| room | Raum | Korridor |
| dtype | Türtyp | Holz 1-flüglig |
| fire | Brandschutz | EI30, E30 |
| vkf | VKF-Nummer | VKF-24891 |
| report | Prüfbericht | PB-2024-1132 |
| inspect | Nächste Kontrolle | 2027-03 |
| b | Breite mm | 900 |
| h | Höhe mm | 2100 |
| wall | Wandstärke mm | 180 |
| hinge | Bandseite | Links, Rechts |
| mat | Material | Eiche furniert |
| surf | Oberfläche | Lackiert RAL 9010 |
| lock | Schloss | Panikschloss BKS |
| handle | Drücker | FSB 1023 |
| frame | Zarge | Stahlzarge Hörmann |
| thresh | Schwelle | Absenkdichtung |
| project | Projekt | Obsthof Ballwil |
| order | Auftragsnr | 25.1132-101 |
| notes | Hinweise | Fluchtweg |
| status | Status | OK, Pendenz |

## Byte-Check
Längste URL (Beispiel 1): ~420 Zeichen → passt in NTAG215 (504 Byte) ✅
