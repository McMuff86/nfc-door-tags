# NFC Door Tags – Product Roadmap 2026-2028

**Version:** 1.0  
**Letzte Aktualisierung:** 26. Februar 2026  
**Status:** Initial Draft → Review & Approval

---

## Vision

**"Jede Tür erzählt ihre digitale Geschichte"**

Von der traditionellen Schreinerei zum digitalen Türdatenmanagement – NFC Door Tags verbindet die physische Welt der Holzverarbeitung mit der digitalen Zukunft des Facility Managements.

---

## Phasen-Übersicht

| Phase | Zeitraum | Fokus | Investment | ROI Target |
|-------|----------|-------|------------|------------|
| **Phase 1** | Q1-Q2 2026 | PoC & Pilot | CHF 25k | Proof of Concept |
| **Phase 2** | Q3-Q4 2026 | IFCraft Integration | CHF 75k | Break-Even |
| **Phase 3** | Q1 2027+ | Produktisierung | CHF 150k+ | Profitabilität |

---

## Phase 1: Proof of Concept (Q1-Q2 2026)

### 🎯 Hauptziele

- **Technische Validierung:** NFC-Hardware in realen Türen
- **Partner-Akquisition:** 3-5 Schreinerei-Partner gewinnen
- **User Experience:** Feedback von echten Nutzern sammeln
- **Compliance:** VKF-konforme Lösung entwickeln

### 📋 Was schon existiert

#### ✅ Bereits vorhanden
- [x] GitHub Pages Viewer ([Live Demo](https://mcmuff86.github.io/nfc-door-tags/door-tag.html))
- [x] URL-Parameter System für alle Türdaten
- [x] Mobile-optimierte Darstellung mit Dark Theme
- [x] Repository-Struktur und Deployment-Pipeline
- [x] Basis-Hardware: NTAG215 Tags (25mm, schwarz)

#### ⚠️ Identifizierte Probleme
- [ ] **HDF-Penetration:** 25mm Tags funktionieren nicht zuverlässig
- [ ] **Brandschutztüren:** Metalleinlagen blockieren Standard-Tags
- [ ] **Reichweite:** Zu geringe Distanz für komfortable Bedienung

### 🔧 Was noch entwickelt werden muss

#### Hardware-Upgrades (Priorität: HOCH)
- [ ] **38-40mm NTAG215 Tags** bestellen und testen
- [ ] **Anti-Metal Tags** für Brandschutztüren evaluieren
- [ ] **Field Testing** mit verschiedenen Smartphone-Modellen
- [ ] **Montage-Optionen** dokumentieren (Türkante, Zarge, frontal)

#### Software-Features (Priorität: MITTEL)
- [ ] **NFC-Generator Tool:** Web-Interface für Tag-Programmierung
- [ ] **QR-Code Fallback:** Für Geräte ohne NFC
- [ ] **Daten-Validierung:** Eingabeprüfung und Fehlermeldungen
- [ ] **Analytics:** Basic Tracking für Tag-Interaktionen

#### Business Development (Priorität: HOCH)
- [ ] **Partner-Gespräche:** 5 Schreinereien kontaktieren
- [ ] **VKF-Abklärung:** Rechtliche Validierung der Hybrid-Lösung
- [ ] **Pilot-Projekt:** Obsthof als Referenz-Kunde gewinnen
- [ ] **Pricing-Model:** Erste Kostenstruktur definieren

### 📊 Success Metrics Phase 1

| KPI | Target | Aktuell |
|-----|--------|---------|
| Pilottüren installiert | 15+ | 3 |
| Partner-Schreinereien | 3+ | 0 |
| Tag-Erfolgsrate | >95% | ~70% |
| User Feedback Score | 4.0+ | TBD |

### ⏰ Timeline Phase 1

```
März 2026:  Hardware-Tests & Partner-Kontakte
April 2026: Pilot-Installation Obsthof + 2 weitere Kunden
Mai 2026:   Field Testing & User Feedback
Juni 2026:  Phase 1 Review & Go/No-Go für Phase 2
```

### 💰 Budget Phase 1

| Kategorie | Budget CHF | Details |
|-----------|------------|---------|
| Hardware | 5.000 | Tags, Tools, Prototypen |
| Entwicklung | 15.000 | Software-Features (75h à CHF 200) |
| Marketing | 3.000 | Partner-Events, Material |
| Operations | 2.000 | Testing, Travel, Admin |
| **Total** | **25.000** | Side-Hustle Budget |

---

## Phase 2: IFCraft Integration (Q3-Q4 2026)

### 🎯 Hauptziele

- **USP entwickeln:** Automatische BIM → NFC Pipeline
- **Skalierung:** 100+ Türen erfolgreich ausgerollt
- **FM-Integration:** Erste APIs für Facility Management Tools
- **Business Model:** Erstes recurring Revenue generieren

### 🏗️ IFCraft-Pipeline entwickeln

#### Technische Architektur
```
BIM-Modell (IFC) 
    ↓
IFCraft Parser (Python)
    ↓
Tür-Objekte extrahieren
    ↓
NFC-URLs automatisch generieren
    ↓
Batch-Writing Interface
    ↓
Physische Tag-Programmierung
```

#### Entwicklungsziele
- [ ] **IFC-Parser Integration:** Türdaten aus BIM-Modellen extrahieren
- [ ] **Datenbank-Design:** Zentrale Verwaltung aller Türdaten
- [ ] **API-Layer:** RESTful APIs für externe Systeme
- [ ] **Batch-Tools:** Masse-Programmierung von NFC-Tags
- [ ] **Web-Dashboard:** Admin-Interface für Projektmanager

### 📱 Product Features Phase 2

#### Mobile App MVP
- [ ] **Native App** (iOS/Android) oder Progressive Web App
- [ ] **Offline-Funktionalität:** Daten auch ohne Internet verfügbar
- [ ] **QR-Backup:** Automatischer Fallback für Non-NFC Devices
- [ ] **Multi-Language:** DE/EN Support für internationale Projekte
- [ ] **Benutzer-Management:** Rollen für Monteur/Inspektor/FM

#### Web-Platform
- [ ] **Project Management:** Multi-Projekt Verwaltung
- [ ] **Analytics Dashboard:** Tag-Interaktionen visualisieren
- [ ] **Export/Import:** CSV, JSON, IFC für bestehende Workflows
- [ ] **API Documentation:** Developer Portal für Integrationen
- [ ] **White-Label Option:** Partner-Branding für Schreinereien

### 🔗 FM-Tool Integration

#### Priorisierte Integrationen
1. **Planon:** Marktführer in Europa, starke API
2. **Archibus:** DACH-Fokus, BIM-Integration vorhanden
3. **CAFM Connect:** Schweizer Player, lokale Partnerships
4. **Custom APIs:** Für größere Facility Management Firmen

#### Integration-Features
- [ ] **Webhook-Support:** Real-time Updates bei Tag-Interaktionen
- [ ] **Single Sign-On:** SAML/OAuth für Enterprise-Kunden
- [ ] **Data Synchronization:** Bidirektionale Daten-Synchronisation
- [ ] **Reporting:** Compliance-Reports für Brandschutz-Audits

### 📊 Success Metrics Phase 2

| KPI | Target | Measurement |
|-----|--------|-------------|
| Türen im System | 100+ | Database Count |
| Aktive Projekte | 10+ | Dashboard Analytics |
| API-Calls/Monat | 1.000+ | Server Logs |
| Partner-Revenue | CHF 10k+ | Billing System |

### ⏰ Timeline Phase 2

```
Juli 2026:      IFCraft-Integration Development Start
August 2026:    API-Layer & Database Architecture
September 2026: Web-Dashboard & Batch-Tools
Oktober 2026:   FM-Integration Piloten
November 2026:  Beta-Testing mit Early Adopters
Dezember 2026:  Phase 2 Launch & Partner-Rollout
```

### 💰 Budget Phase 2

| Kategorie | Budget CHF | Details |
|-----------|------------|---------|
| Development | 40.000 | IFCraft-Integration, APIs (200h) |
| Infrastructure | 15.000 | Cloud, Hosting, Security |
| Partner-Support | 10.000 | Training, Marketing, Events |
| Testing & QA | 5.000 | Beta-Testing, Quality Assurance |
| Legal & IP | 5.000 | Patents, Contracts, Compliance |
| **Total** | **75.000** | Growth Investment |

---

## Phase 3: Produktisierung (Q1 2027+)

### 🎯 Hauptziele

- **SaaS-Platform:** Vollständig skalierbare Multi-Tenant Lösung
- **DACH-Expansion:** Deutschland & Österreich erschließen
- **Enterprise-Kunden:** Große Facility Management Firmen akquirieren
- **Profitabilität:** Sustainable Business Model etablieren

### 🚀 Vollständige SaaS-Platform

#### Multi-Tenant Architecture
- [ ] **Tenant-Management:** Verschiedene Kunden/Organisationen verwalten
- [ ] **Role-Based Access:** Granulare Berechtigungen pro Benutzerrolle
- [ ] **Custom-Branding:** White-Label für Partner-Schreinereien
- [ ] **Usage-Based Billing:** Flexible Preismodelle je nach Nutzung
- [ ] **Data-Isolation:** Enterprise-grade Security und Privacy

#### Advanced Features
- [ ] **IoT-Integration:** Sensordaten von Smart-Türen erfassen
- [ ] **AI-Features:** Predictive Maintenance und Anomalie-Erkennung
- [ ] **AR-Interface:** Augmented Reality für Techniker vor Ort
- [ ] **Blockchain-Logging:** Unveränderliche Wartungsprotokolle
- [ ] **Advanced-Analytics:** Business Intelligence und Reporting

### 🌍 Markt-Expansion

#### DACH-Strategie
- **Deutschland:** NFC-Standards ähnlich, große Schreinerei-Landschaft
- **Österreich:** Ähnliche Brandschutz-Regulierungen wie Schweiz
- **Luxemburg:** Kleine, aber zahlungskräftige Märkte

#### Lokalisierung
- [ ] **Regulatorische Compliance:** DIN-Normen, DGUV Vorschriften
- [ ] **Sprach-Lokalisierung:** Native DE/AT Terminologie
- [ ] **Partner-Netzwerk:** Lokale Schreinerei-Partner aufbauen
- [ ] **Support-Struktur:** Technischer Support in Lokalzeiten

### 🏢 Enterprise-Segment

#### Target-Kunden
- **Facility Management Konzerne:** APLEONA, Dussmann, ISS
- **Immobilien-Portfolios:** Deutsche Wohnen, Vonovia
- **Corporate Real Estate:** SAP, Siemens, BMW Campus
- **Öffentliche Hand:** Universitäten, Krankenhäuser, Behörden

#### Enterprise-Features
- [ ] **Advanced-SLAs:** 99.9% Uptime, 4h Response Time
- [ ] **Custom-Integrations:** Legacy-System Konnektoren
- [ ] **Professional Services:** Implementation, Training, Consulting
- [ ] **Dedicated-Support:** Named Support Engineers
- [ ] **On-Premise Options:** Für kritische/regulierte Industrien

### 📊 Success Metrics Phase 3

| KPI | Target 2027 | Target 2028 |
|-----|-------------|-------------|
| Annual Recurring Revenue | CHF 500k+ | CHF 2M+ |
| Enterprise-Kunden | 10+ | 25+ |
| Türen im System | 5.000+ | 20.000+ |
| DACH-Marktanteil | 5% | 15% |

### ⏰ Timeline Phase 3

```
Q1 2027: Multi-Tenant Platform Development
Q2 2027: Deutschland Market Entry
Q3 2027: Enterprise-Features & Advanced Analytics
Q4 2027: Österreich Expansion & IPO-Vorbereitung
2028+:   International Expansion & Exit-Strategien
```

### 💰 Budget Phase 3

| Kategorie | Jahr 1 (CHF) | Jahr 2 (CHF) | Details |
|-----------|--------------|--------------|---------|
| Development | 60.000 | 100.000 | Team-Expansion, Enterprise-Features |
| Sales & Marketing | 40.000 | 80.000 | DACH-Expansion, Lead Generation |
| Operations | 30.000 | 60.000 | Infrastructure, Support, Legal |
| Hiring | 20.000 | 40.000 | Sales, Development, Operations |
| **Total** | **150.000** | **280.000** | Scale-up Investment |

---

## Abhängigkeiten zu anderen Projekten

### 🔗 IFCraft-Integration

#### Technische Dependencies
- **IFC-Parser:** Muss Türobjekte zuverlässig extrahieren können
- **Data-Mapping:** Standard-Attribute auf NFC-Parameter mappen
- **API-Integration:** Bidirektionale Synchronisation zwischen Systemen

#### Timeline-Risiken
- IFCraft-Entwicklung könnte sich verzögern → **Mitigation:** QR-Codes als Interim-Lösung
- BIM-Adoption langsamer als erwartet → **Mitigation:** Manuelle Eingabe-Tools parallel entwickeln

### 💼 DriftERP-Synergien

#### Potential-Areas
- **Customer-Data:** Gemeinsame Kundendatenbank für Schreinereien
- **Project-Management:** DriftERP-Projekte → NFC-Tags automatisch
- **Billing-Integration:** Türpreise + NFC-Service in einer Rechnung
- **Resource-Sharing:** Development-Team, Infrastructure, Know-how

#### Strategic Considerations
- **Fokus behalten:** NFC-Tags nicht als DriftERP-Feature "verwässern"
- **Independence:** Standalone-Produkt mit optionaler Integration
- **Revenue-Split:** Faire Aufteilung bei gemeinsamen Kunden

---

## Technische Roadmap

### Architecture Evolution

#### Phase 1: Monolith
```
Static HTML/JS → GitHub Pages → Direct NFC-URLs
└─ Einfach, schnell, aber nicht skalierbar
```

#### Phase 2: API-First
```
Frontend (React/Vue) ↔ REST-API ↔ Database
└─ Skalierbar, aber Single-Tenant
```

#### Phase 3: Microservices
```
Frontend → API-Gateway → [Auth, Data, Analytics, Integration] Services
└─ Multi-Tenant, Enterprise-ready
```

### Data Architecture

#### Phase 1: File-Based
- URL-Parameter als Single Source of Truth
- Keine persistente Datenbank erforderlich

#### Phase 2: Centralized Database
```
Projects → Buildings → Doors → Tags → Interactions
└─ PostgreSQL mit JSON für flexible Türattribute
```

#### Phase 3: Data Lake
```
Operational-DB → Event-Stream → Analytics-DB → ML-Pipeline
└─ Real-time Analytics und Predictive Insights
```

### Security Roadmap

#### Phase 1: Basic Security
- [ ] HTTPS for all connections
- [ ] Basic input validation
- [ ] No sensitive data in URLs

#### Phase 2: Enterprise Security
- [ ] OAuth 2.0/SAML integration
- [ ] Role-based access control
- [ ] Audit logging
- [ ] Data encryption at rest

#### Phase 3: Advanced Security
- [ ] Zero-trust architecture
- [ ] End-to-end encryption
- [ ] Compliance certifications (ISO 27001)
- [ ] Blockchain for immutable logs

---

## Risiken & Mitigation-Strategien

### Technische Risiken

#### NFC-Adoption Rate
**Risiko:** Langsamere NFC-Adoption als erwartet  
**Wahrscheinlichkeit:** Mittel  
**Impact:** Hoch  
**Mitigation:** QR-Code Hybrid-Lösung, fokus auf Premium-Segment

#### Smartphone-Kompatibilität
**Risiko:** Inkonsistente NFC-Performance zwischen Geräten  
**Wahrscheinlichkeit:** Hoch  
**Impact:** Mittel  
**Mitigation:** Extensive Device-Testing, Progressive Web App als Fallback

### Markt-Risiken

#### Konkurrenz-Reaktion
**Risiko:** Große Player (Dormakaba) kopieren die Lösung  
**Wahrscheinlichkeit:** Hoch  
**Impact:** Hoch  
**Mitigation:** Speed-to-Market, Patent-Strategie, starke Partner-Bindungen

#### Regulatorische Änderungen
**Risiko:** VKF-Vorschriften ändern sich  
**Wahrscheinlichkeit:** Niedrig  
**Impact:** Hoch  
**Mitigation:** Enge VKF-Beziehungen, regulatory Compliance-Team

### Business-Risiken

#### Partner-Abhängigkeit
**Risiko:** Zu starke Abhängigkeit von einzelnen Schreinerei-Partnern  
**Wahrscheinlichkeit:** Mittel  
**Impact:** Mittel  
**Mitigation:** Diversifiziertes Partner-Portfolio, direkter End-Customer Sales

#### Cash-Flow Timing
**Risiko:** Entwicklungskosten vor ersten Umsätzen  
**Wahrscheinlichkeit:** Hoch  
**Impact:** Mittel  
**Mitigation:** Phased Investment, early Revenue durch Hardware-Sales

---

## Success Factors & KPIs

### Leading Indicators
- **Partner-Pipeline:** Anzahl Schreinereien in Gesprächen
- **Pilot-Success Rate:** % erfolgreich installierter Tags
- **User-Engagement:** Tag-Interaktionen pro Woche
- **Development-Velocity:** Features delivered per Sprint

### Lagging Indicators
- **Monthly Recurring Revenue (MRR)**
- **Customer Acquisition Cost (CAC)**
- **Customer Lifetime Value (CLV)**
- **Net Promoter Score (NPS)**

### Critical Milestones

| Datum | Milestone | Success Criteria |
|-------|-----------|------------------|
| Apr 2026 | Phase 1 Complete | 15+ Pilottüren, 3+ Partner |
| Dec 2026 | Phase 2 Launch | IFCraft-Integration, 100+ Türen |
| Jun 2027 | Break-Even | CHF 25k+ Monthly Revenue |
| Dec 2027 | Market Leadership | 1000+ Türen, 5% DACH-Marktanteil |

---

## Fazit & Commitment

### Vision Realization
NFC Door Tags hat das Potenzial, die traditionelle Schreinerei-Branche in die digitale Zukunft zu führen. Die Kombination aus bewährter Hardware-Technologie und innovativer Software-Integration schafft einen defensible competitive moat.

### Investment Thesis
- **Proven Technology:** NFC ist etabliert und zuverlässig
- **Clear Market Need:** Digitalisierungsdruck in konservativer Branche
- **Unique Position:** IFCraft-Integration als Differentiator
- **Scalable Business:** SaaS-Model mit recurring Revenue

### Personal Commitment
Als Side-Hustle für 2026 mit dem Ziel, 2027+ als Vollzeit-Unternehmen zu etablieren. Der Roadmap-Ansatz ermöglicht kontrollierten Ressourcen-Einsatz mit klaren Go/No-Go Entscheidungspunkten.

---

**Next Review:** April 2026 (Phase 1 Mid-Point Review)  
**Document Owner:** Adi McMuff  
**Version Control:** Stored in `~/clawd/projects/nfc-door-tags/ROADMAP.md`  

*"Ein Schritt nach dem anderen – aber das Ziel fest im Blick."*