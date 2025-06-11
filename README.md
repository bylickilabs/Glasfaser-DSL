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

# 🔧 Ersetzt ein ONT den DSL-Router? – Technische Erklärung

## 📌 Kurzantwort

**Nein**, ein **ONT (Optical Network Terminal)** ersetzt **nicht den DSL-Router**, sondern **nur das Modem**. Ein zusätzlicher **Router** ist weiterhin erforderlich – außer du nutzt ein Kombigerät mit integriertem ONT.

<br>

---

<br>

## 🧩 Komponentenvergleich: DSL vs. FTTH

| Funktion                        | DSL (z. B. VDSL2)                  | Glasfaser (FTTH)                        |
|---------------------------------|-----------------------------------|-----------------------------------------|
| Signalumwandlung (Modem)        | DSL-Modem                         | **ONT (Optical Network Terminal)**      |
| Router (NAT, DHCP, WLAN, etc.)  | DSL-Router                        | Router hinter ONT                       |
| Verbindung zum Internet         | RJ11 / TAE → DSL-Signal           | SC/APC Glasfaser → ONT → RJ45 (WAN)     |

<br>

---

<br>

## ⚙️ Was macht das ONT?

- Wandelt **optische Lichtsignale** der Glasfaser in **elektrische Ethernet-Signale**.
- Funktioniert als **Modulator/Demodulator** – vergleichbar mit einem DSL-Modem.
- **Keine WLAN-Funktion, keine DHCP-Funktion** – daher **kein vollständiger Router**.

<br>

---

<br>

## 🖧 Erforderliches Setup bei Glasfaser

1. **Glasfaserkabel (z. B. SC/APC)**
2. → **ONT (vom Anbieter bereitgestellt)**
3. → **Ethernet-Kabel (RJ45)**
4. → **Router mit WAN-Port**

<br>

---

<br>

## ✅ Alternativen: Router mit integriertem ONT

Einige Router-Modelle kombinieren Modem und Router für Glasfaseranschlüsse:

| Modell                      | Integriertes ONT | Bemerkung                             |
|----------------------------|------------------|----------------------------------------|
| AVM Fritz!Box 5590 Fiber   | ✅ Ja            | Direktanschluss an Glasfaser möglich   |
| AVM Fritz!Box 5530 Fiber   | ✅ Ja            | Kompakt, SFP-Modul wechselbar          |
| Ubiquiti UDM + SFP-Modul   | ❌ Nein          | ONT erforderlich oder SFP-Erweiterung  |

<br>

---

<br>

## 🧠 Sonderfall: SFP-Modul als ONT-Ersatz

Wenn dein Router einen **SFP-Port** besitzt (z. B. bei MikroTik, Ubiquiti), kannst du ein **passendes SFP-Transceivermodul** einsetzen:

- Dadurch wird **der separate ONT überflüssig**
- Du brauchst:
  - Kompatibles **SFP GPON-Modul**
  - Konfiguration über CLI / Webinterface
  - Genehmigung des Providers (manche Anbieter schreiben ein bestimmtes ONT vor)

<br>

---

<br>

## 📎 Zusammenfassung

| Frage                                     | Antwort                                |
|------------------------------------------|----------------------------------------|
| Ersetzt ONT den Router?                  | ❌ Nein                                 |
| Was ersetzt das ONT?                     | ✅ Das Modem (optisch ↔ elektrisch)     |
| Brauche ich noch einen Router?           | ✅ Ja (für WLAN, DHCP, Firewall etc.)   |
| Gibt es Router mit integriertem ONT?     | ✅ Ja (z. B. Fritz!Box 5590 Fiber)      |
| Kann ich SFP statt ONT nutzen?           | ✅ Ja, bei passender Hardware           |

<br>

---

<br>

## 📈 Fazit

- **FTTH ist 4x schneller im Download als VDSL2**
- **FTTH ist bis zu 500x schneller im Upload als ADSL2+**
- **FTTH erreicht symmetrische Geschwindigkeiten**, während DSL immer asymmetrisch ist
- **FTTH skaliert in Zukunft auf 10 Gbit/s und mehr**, DSL ist technologisch ausgereizt

<br>

---

<br>

## ✅ Empfehlung

> Wenn verfügbar, sollte **FTTH** jeder Form von DSL-Technologie vorgezogen werden – vor allem bei datenintensiven Anwendungen
  - (Cloud, Streaming, Home-Office, Smart Home).
    - *Erstellt am: 11.06.2025 – Datenstand basierend aus Wissensstand*

