| Glasfaser-DSL |
|---|

> Hier ist eine strukturierte Gegenüberstellung der Glasfaserverbindung im Vergleich zu herkömmlichen DSL-Verbindungen.
  - Inklusive einer Statistik zu Up-/Downstream, den Vor- und Nachteilen, sowie einer Erklärung der Hardware-Komponenten.
    - Insbesondere Modulator/Demodulator (Transceiver) und deren Unterschiede zu Standard-DSL-Routern.

---

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

<br>

---

<br>

# 📘 Glossar: Glasfaser (FTTH) vs. DSL – Fachbegriffe & Definitionen

## 🔌 Allgemeine Netzwerktechnologien

### **FTTH (Fiber To The Home)**
> „Glasfaser bis ins Haus“ – Die Glasfaserleitung reicht direkt bis zur Wohneinheit. Bietet maximale Geschwindigkeit und Stabilität ohne Kupfer-Teilabschnitt.

### **FTTC (Fiber To The Curb)**
> „Glasfaser bis zum Bordstein“ – Glasfaser endet an einem Verteilerkasten in der Straße. Der letzte Abschnitt zum Haus erfolgt über Kupfer (z. B. VDSL).

### **DSL (Digital Subscriber Line)**
> Oberbegriff für Technologien, die Daten über bestehende Kupfertelefonleitungen übertragen. Varianten: ADSL, ADSL2+, VDSL, VDSL2.

<br>

---

<br>

## 📡 DSL-Technologien im Detail

### **ADSL / ADSL2+ (Asymmetric DSL)**
> Download ist schneller als Upload. Datenrate sinkt mit Entfernung zur Vermittlungsstelle. Max. ~16–24 Mbit/s (Down).

### **VDSL / VDSL2 (Very High Bitrate DSL)**
> Weiterentwicklung mit höheren Geschwindigkeiten (bis 250 Mbit/s). Kupferleitung bleibt jedoch begrenzender Faktor.

### **Supervectoring**
> Erweiterung von VDSL2, um elektromagnetische Störungen besser zu kompensieren. Steigert Maximalgeschwindigkeit auf 250 Mbit/s Down.

<br>

---

<br>

## 📶 Signaltechnik & Übertragungswege

### **Latenz (Ping)**
> Zeitverzögerung in Millisekunden (ms) zwischen Anforderung und Antwort eines Netzwerks. Geringe Latenz ist wichtig für Echtzeitanwendungen.

### **Bandbreite**
> Maximale Datenmenge, die pro Sekunde übertragen werden kann – gemessen in Mbit/s oder Gbit/s.

### **Upstream / Downstream**
> **Downstream** = Datenempfang (z. B. Streaming, Webseiten),  
> **Upstream** = Datensendung (z. B. Uploads, Cloud-Backups).

<br>

---

<br>

## 💡 Glasfaser-Komponenten

### **ONT (Optical Network Terminal)**
> Wandelt optische Signale in elektrische Signale um. Wird direkt am Glasfaseranschluss installiert und ersetzt das klassische DSL-Modem.

### **SFP-Modul (Small Form-factor Pluggable)**
> Steckbarer Transceiver für Glasfaserverbindungen. Ermöglicht Modulation/Demodulation auf Netzwerkgeräten (z. B. Router, Switches).

### **SC/APC, LC/UPC**
> Steckertypen für Glasfaserverbindungen:
- **SC/APC** = grün, abgeschrägt (geringe Reflexion)
- **LC/UPC** = blau, poliert (hohe Präzision)

<br>

---

<br>

## 🧰 DSL-Komponenten

### **TAE-Dose (Telekommunikations-Anschluss-Einheit)**
> Anschlussdose für analoge/ISDN-Telefone und DSL-Signale.

### **Splitter**
> Trennt DSL- und Telefonsignal bei analogen Anschlüssen (heute meist integriert im Router).

### **DSL-Modem**
> Wandelt digitale Signale für Kupferleitungen, meist integriert im Router.

<br>

---

<br>

## 🌐 Router-Technologie

### **Router**
> Verbindet interne Netzwerke mit dem Internet. Viele moderne Router bieten zusätzlich WLAN, Firewall, NAS-Funktionen etc.

### **Mesh-System**
> Netzwerk aus mehreren Router- oder Repeater-Knoten zur besseren WLAN-Abdeckung in großen Gebäuden.

<br>

---

<br>

## ⚙️ Weitere Begriffe

### **Dämpfung**
> Signalverlust über eine Leitung. Bei Kupferleitungen stark ausgeprägt – bei Glasfaser minimal.

### **Backbone**
> Hochleistungsnetzwerk, das große Mengen Daten zwischen Knotenpunkten transportiert (Rückgrat des Internets).

### **Verteilerkasten (KVz)**
> Knotenpunkt zwischen Hausanschluss und zentraler Vermittlungsstelle. In FTTC-Szenarien endet hier das Glasfaserkabel.

<br>

---

<br>

## 🔎 Vergleichstechnologien (Zusammenfassung)

| Begriff         | DSL (VDSL2 / ADSL)                        | Glasfaser (FTTH)                     |
|----------------|-------------------------------------------|--------------------------------------|
| Übertragungsweg| Kupfer (elektrisch)                        | Glasfaser (optisch)                  |
| Modulation     | Elektrische Signale (Modem)                | Lichtsignale (ONT, SFP-Modul)        |
| Bandbreite     | max. 250 Mbit/s                            | bis zu 10 Gbit/s                     |
| Upload-Speed   | meist deutlich geringer als Download       | symmetrisch möglich                  |
| Entfernungseinfluss | sehr hoch                             | irrelevant                           |
| Zukunftssicherheit | begrenzt                               | sehr hoch                            |

<br>

---

<br>

*Erstellt am: 11.06.2025 – Datenstand basierend aus Wissensstand*

