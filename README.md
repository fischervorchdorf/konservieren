# 🏛️ Konservieren - Artefakt-Analyse App

Eine spezialisierte Web-App zur Konservierungs- und Restaurationsberatung für Museumsobjekte und Archivgut.

## 🎯 Zweck

Diese App unterstützt Museen und Archive bei der professionellen Konservierung ihrer Artefakte durch:

- **Zustandsanalyse**: Detaillierte Bewertung des Erhaltungszustands
- **Schadensdokumentation**: Identifikation sichtbarer und potenzieller Schäden
- **Konservierungsempfehlungen**: Wissenschaftlich fundierte Hinweise zu Lagerung, Reinigung und Restaurierung
- **Materialspezifische Beratung**: Individuelle Empfehlungen für Holz, Metall, Papier, Textil, etc.

## ✨ Features

- 📸 **Multi-Bild-Upload**: Bis zu 4 Fotos gleichzeitig (Gesamtansicht, Details, Schäden)
- 📝 **Kontext-Informationen**: Detaillierte Beschreibung zu jedem Bild
- 🎨 **Verwendungszweck-Auswahl**:
  - Dauerausstellung
  - Wechselausstellung
  - Langzeitlagerung
  - Transport
- 🤖 **KI-gestützte Analyse**: Powered by Google Gemini API
- 📄 **PDF-Export**: Vollständiger Bericht mit allen Bildern
- 💾 **Text-Export**: Einfacher Textexport für Dokumentation
- 📱 **Responsive Design**: Optimiert für Desktop und Mobile

## 🔬 Analysebereiche

Die App analysiert folgende Aspekte wissenschaftlich fundiert:

1. **Material-Identifikation**: Holz, Metall, Papier, Textil, Keramik, Glas, Leder, etc.
2. **Erhaltungszustand**: Risse, Verfärbungen, Korrosion, Schimmel, Insektenbefall
3. **Akute Gefahren**: Sofortmaßnahmen und langfristige Risiken
4. **Konservierungsmaßnahmen**: Reinigung, Reparatur, Schädlingsbekämpfung
5. **Lagerungsempfehlungen**: Temperatur, Luftfeuchtigkeit, UV-Schutz, Verpackung
6. **Ausstellungsbedingungen**: Lichtexposition, Vitrinen, Klimakontrolle
7. **Transport-Empfehlungen**: Verpackung, Polsterung, Klimaschutz

## 🚀 Verwendung

1. **API Key eingeben**: Kostenloser Google Gemini API Key von [Google AI Studio](https://aistudio.google.com/app/apikey)
2. **Verwendungszweck wählen**: Ausstellung, Lagerung oder Transport
3. **Fotos aufnehmen**: Bis zu 4 Bilder mit Kontext-Informationen
4. **Analyse starten**: KI analysiert das Artefakt auf Basis der Bilder
5. **Ergebnis exportieren**: Als PDF oder Text-Datei speichern

## 💡 Kontext-Informationen

Für beste Ergebnisse sollten zu jedem Bild folgende Informationen eingegeben werden:

- Aktuelle Lagerbedingungen (Temperatur, Luftfeuchtigkeit)
- Lichtexposition und Standort
- Alter des Artefakts
- Bekannte Vorschäden oder Restaurierungen
- Besondere Beobachtungen

## 🔧 Installation

### Option 1: GitHub Pages (Empfohlen)

1. Repository erstellen: `konservieren`
2. `index.html` ins Repository hochladen
3. GitHub Pages aktivieren
4. Erreichbar unter: `https://fischervorchdorf.github.io/konservieren`

### Option 2: Lokaler Server

```bash
# Python Server
python -m http.server 8000

# Node.js Server
npx http-server
```

### Option 3: Direkter Upload auf Webserver

Die `index.html` kann direkt auf jeden Webserver hochgeladen werden (z.B. World4You).

## 🔑 Google Gemini API

Die App nutzt die **kostenlose** Google Gemini API:

- **Kostenlos**: Ja (mit Rate Limits)
- **Rate Limit**: 15 Anfragen/Minute, 1500 Anfragen/Tag
- **API Key**: [Hier kostenlos erstellen](https://aistudio.google.com/app/apikey)
- **Speicherung**: API Key wird lokal im Browser gespeichert

## 📋 Systemanforderungen

- Moderner Webbrowser (Chrome, Firefox, Safari, Edge)
- Internetverbindung für API-Anfragen
- Optional: Kamera für mobile Fotografie

## 🎓 Wissenschaftliche Grundlagen

Die App basiert auf etablierten Konservierungsstandards:

- DIN-Normen für Archivgut
- ISO-Standards für Museumsobjekte
- Richtlinien des International Institute for Conservation (IIC)
- Best Practices für präventive Konservierung

## 📱 Mobile Nutzung

Die App ist optimiert für mobile Geräte und ermöglicht:

- Direkte Kameranutzung
- Touch-optimierte Bedienung
- Responsive Layout
- Offline-Fähigkeit (nach erstem Laden)

## 🔒 Datenschutz

- Alle Daten werden lokal im Browser verarbeitet
- Bilder werden nur zur Analyse an die Google Gemini API gesendet
- Kein Server-seitiges Speichern von Daten
- API Key wird ausschließlich lokal gespeichert

## 🤝 Powered by

**Heimatverein Vorchdorf**
[heimatverein-vorchdorf.at](https://heimatverein-vorchdorf.at)

## 📄 Lizenz

© 2024 Heimatverein Vorchdorf
Entwickelt für Museen und Archive

## 🐛 Support

Bei Fragen oder Problemen wende dich an:
Heimatverein Vorchdorf

## 🔄 Version

**Version 2.11** (Dezember 2024)

---

*Diese App wurde speziell für die Bedürfnisse von Museen und Archiven entwickelt und bietet wissenschaftlich fundierte Konservierungsempfehlungen auf Basis modernster KI-Technologie.*
