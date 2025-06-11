| Glasfaser-DSL |
|---|

> Hier ist eine strukturierte Gegenüberstellung der Glasfaserverbindung im Vergleich zu herkömmlichen DSL-Verbindungen.
  - Inklusive einer Statistik zu Up-/Downstream, den Vor- und Nachteilen, sowie einer Erklärung der Hardware-Komponenten.
    - Insbesondere Modulator/Demodulator (Transceiver) und deren Unterschiede zu Standard-DSL-Routern.

# Vergleich: Glasfaser (FTTH) vs. DSL (VDSL2 / ADSL2+)

## 📊 Statistikübersicht (2025)

| Merkmal                        | Glasfaser (FTTH)               | VDSL2                         | ADSL2+                       |
|-------------------------------|--------------------------------|-------------------------------|-------------------------------|
| Download-Geschwindigkeit      | bis zu 1.000 Mbit/s (theoretisch 10 Gbit/s) | bis 250 Mbit/s                | ca. 16 Mbit/s    |
| Upload-Geschwindigkeit        | bis zu 500–1.000 Mbit/s        | ca. 40 Mbit/s                 | ca. 1 Mbit/s                  |
| Latenz (Ping)                 | 1 – 5 ms                       | 20 – 30 ms                    | 40 – 50 ms                    |
| Verbindungsstabilität         | Sehr hoch                      | Mittel bis hoch               | Mittel                        |
| Leitungseinfluss              | Unabhängig von Entfernung      | Geschwindigkeit sinkt mit Entfernung | Sehr stark abhängig    |
| Dämpfung                      | Gering (optisch)               | Mittel                        | Hoch                          |
| Zukunftssicherheit            | Sehr hoch                      | Mittel                        | Gering                        |

---

# 📘 Glossar: Glasfaser (FTTH) vs. DSL – Fachbegriffe & Definitionen

## 🔌 Allgemeine Netzwerktechnologien

### **FTTH (Fiber To The Home)**
> „Glasfaser bis ins Haus“ – Die Glasfaserleitung reicht direkt bis zur Wohneinheit. Bietet maximale Geschwindigkeit und Stabilität ohne Kupfer-Teilabschnitt.

### **FTTC (Fiber To The Curb)**
> „Glasfaser bis zum Bordstein“ – Glasfaser endet an einem Verteilerkasten in der Straße. Der letzte Abschnitt zum Haus erfolgt über Kupfer (z. B. VDSL).

### **DSL (Digital Subscriber Line)**
> Oberbegriff für Technologien, die Daten über bestehende Kupfertelefonleitungen übertragen. Varianten: ADSL, ADSL2+, VDSL, VDSL2.

---

## 📡 DSL-Technologien im Detail

### **ADSL / ADSL2+ (Asymmetric DSL)**
> Download ist schneller als Upload. Datenrate sinkt mit Entfernung zur Vermittlungsstelle. Max. ~16–24 Mbit/s (Down).

### **VDSL / VDSL2 (Very High Bitrate DSL)**
> Weiterentwicklung mit höheren Geschwindigkeiten (bis 250 Mbit/s). Kupferleitung bleibt jedoch begrenzender Faktor.

### **Supervectoring**
> Erweiterung von VDSL2, um elektromagnetische Störungen besser zu kompensieren. Steigert Maximalgeschwindigkeit auf 250 Mbit/s Down.

---

## 📶 Signaltechnik & Übertragungswege

### **Latenz (Ping)**
> Zeitverzögerung in Millisekunden (ms) zwischen Anforderung und Antwort eines Netzwerks. Geringe Latenz ist wichtig für Echtzeitanwendungen.

### **Bandbreite**
> Maximale Datenmenge, die pro Sekunde übertragen werden kann – gemessen in Mbit/s oder Gbit/s.

### **Upstream / Downstream**
> **Downstream** = Datenempfang (z. B. Streaming, Webseiten),  
> **Upstream** = Datensendung (z. B. Uploads, Cloud-Backups).

---

## 💡 Glasfaser-Komponenten

### **ONT (Optical Network Terminal)**
> Wandelt optische Signale in elektrische Signale um. Wird direkt am Glasfaseranschluss installiert und ersetzt das klassische DSL-Modem.

### **SFP-Modul (Small Form-factor Pluggable)**
> Steckbarer Transceiver für Glasfaserverbindungen. Ermöglicht Modulation/Demodulation auf Netzwerkgeräten (z. B. Router, Switches).

### **SC/APC, LC/UPC**
> Steckertypen für Glasfaserverbindungen:
- **SC/APC** = grün, abgeschrägt (geringe Reflexion)
- **LC/UPC** = blau, poliert (hohe Präzision)

---

## 🧰 DSL-Komponenten

### **TAE-Dose (Telekommunikations-Anschluss-Einheit)**
> Anschlussdose für analoge/ISDN-Telefone und DSL-Signale.

### **Splitter**
> Trennt DSL- und Telefonsignal bei analogen

---

## ✅ Vorteile von Glasfaser

- Extrem hohe Bandbreiten (Download und Upload).
- Geringe Latenz → ideal für Echtzeitdienste wie Gaming, VoIP, Cloud.
- Zukunftssicher & skalierbar (z. B. für Smart Homes, Industrie 4.0).
- Unempfindlich gegen elektromagnetische Störungen.
- Symmetrische Geschwindigkeiten möglich.
- Geringer Energieverbrauch.

---

## ❌ Nachteile von Glasfaser

- Hohe Ausbaukosten & aufwendige Verlegung.
- Nicht überall verfügbar (v. a. im ländlichen Raum).
- Neue Hardware erforderlich (ONT, kompatibler Router).
- Höhere Anschluss- und Installationskosten.

---

## ✅ Vorteile von DSL

- Weit verbreitet & schnell verfügbar.
- Nutzung bestehender Kupferleitungen.
- Günstigere Tarife möglich.
- Kompatibel mit gängigen Standardroutern.

---

## ❌ Nachteile von DSL

- Begrenzte Bandbreite, v. a. beim Upload.
- Latenz und Stabilität schwanken je nach Leitung.
- Kupfer ist störanfälliger als Glasfaser.
- Keine echte Zukunftsfähigkeit für datenintensive Anwendungen.

---

## 🔧 Hardware-Vergleich: Glasfaser vs. DSL

| Komponente                     | Glasfaser (FTTH)                        | DSL (VDSL2 / ADSL2+)                |
|-------------------------------|----------------------------------------|-------------------------------------|
| Modulation                    | Optisch (Lichtsignal)                  | Elektrisch (über Kupferadern)       |
| Hauptgerät                    | ONT (Optical Network Terminal)         | DSL-Modem / Router mit Splitter     |
| SFP-Modul (Transceiver)       | Ja, optional bei Profi-Geräten         | Nicht erforderlich                  |
| Verkabelung                   | SC/APC → ONT → RJ45 (Router)           | TAE → Splitter → DSL-Modem          |
| Empfohlene Router             | Fritz!Box 5590 Fiber, Ubiquiti UXG     | Fritz!Box 7590, Telekom Speedport   |

---

## 📈 Diagramme (Auswertung)

### 1. Übertragungsgeschwindigkeiten

- **Download (Mbit/s):**
  - Glasfaser: 1.000
  - VDSL2: 250
  - ADSL2+: 16

- **Upload (Mbit/s):**
  - Glasfaser: 500
  - VDSL2: 40
  - ADSL2+: 1

### 2. Latenzvergleich

- **Latenz (ms):**
  - Glasfaser: 5
  - VDSL2: 25
  - ADSL2+: 50

(Diese Daten lassen sich als Balkendiagramme darstellen, z. B. für Präsentationen mit Matplotlib oder Chart.js)

---

## 📌 Empfehlungen

- **Für moderne Netzwerke & Unternehmen:** Glasfaser ist alternativlos.
- **Für ländliche Übergangslösungen:** DSL kann ausreichend sein, sofern kein Glasfaser verfügbar ist.
- **Langfristig:** Der Fokus sollte auf Glasfaserausbau liegen, da DSL keine nachhaltige Option mehr darstellt.

---

## 🔄 Optional erweiterbare Diagramme (bei Bedarf)

- Preisvergleich pro Mbit/s
- Energieverbrauch pro Haushalt
- Technologische Abdeckung in Deutschland
- Verfügbarkeitsentwicklung (letzte 10 Jahre)
- Schema Netzaufbau: Backbone → Verteiler → Hausanschluss

---

*Erstellt am: 11.06.2025 – Datenstand basierend auf Marktanalysen, Netzbetreiberangaben und technischen Dokumentationen.*

