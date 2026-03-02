# Chiuchau Intelligentes Ventilator-Überwachungssystem — Benutzerhandbuch


## Titelseite

![](../../assets/images/ce13f776-26b4-4cf6-8a77-1d9748c98e4e.jpg)

### **Inhaltsverzeichnis**

1. Einführung - S. 02

1. Sicherheitshinweise - S. 03

1. Produktübersicht - S. 04

1. Installationsanleitung - S. 06

1. Hardware-Einrichtung & Inbetriebnahme - S. 14

1. Software-Bedienungsanleitung - S. 16

1. Software-Fehlerbehebung - S. 27

1. Technischer Support & Kontaktinformationen - S. 28

1. Anhang - S. 29

### 1. Einführung

Willkommen beim **Chiuchau Intelligenten Überwachungssystem**. Dieses System wurde speziell für die Echtzeitüberwachung und vorausschauende Wartung industrieller Anlagen entwickelt und vereint modernste Sensortechnologie mit künstlicher Intelligenz, um Anwendern eine umfassende und präzise Lösung für das Anlagengesundheitsmanagement zu bieten. Unser System unterstützt Anwendungen in verschiedensten industriellen Umgebungen — von der Halbleiterfertigung bis zur klassischen Fertigungsindustrie — und steigert effektiv die Anlagenverfügbarkeit, senkt Wartungskosten, verhindert ungeplante Ausfälle und ermöglicht eine nahtlose intelligente Produktionssteuerung.

Das System besteht aus zwei Hauptkomponenten: **Hardwaregeräte** und eine **Softwareplattform**. Auf der Hardwareseite bieten wir hochpräzise Drei-Achsen-Vibrationssensoren, Temperatursensormodule und Leistungsüberwachungsgeräte mit vielfältigen Kommunikationstechnologien wie Wi-Fi, LoRa und 4G LTE, um eine stabile Datenübertragung an Cloud- oder lokale Server sicherzustellen. Das integrierte USV-Schutzmodul sichert Daten bei unerwarteten Stromausfällen und gewährleistet den unterbrechungsfreien Betrieb.

Auf der Softwareseite unterstützt das System Echtzeit-Datenvisualisierung, Anomalie-Alarme (basierend auf dem **ISO 20816-Vibrationsstandard**) sowie KI-gestützte Vorhersagemodelle für den Anlagenzustand, um den Gerätestatus präzise zu überwachen. Durch intelligente Algorithmen kann das System potenzielle Ausfälle frühzeitig vorhersagen und Wartungsempfehlungen geben. Darüber hinaus können Benutzer **LINE-Gruppenbenachrichtigungen** und **E-Mail-Alarme** einrichten, um bei Anomalien sofort informiert zu werden.

Das System unterstützt außerdem ein **CO₂-Emissionsüberwachungsmodul**, das den Energieverbrauch und die CO₂-Emissionsdaten der Anlagen erfasst und Unternehmen hilft, Energiespar- und CO₂-Reduktionsziele im Einklang mit Umweltvorschriften zu erreichen. Alle Daten werden automatisch in monatlichen Diagnoseberichten zusammengestellt, die Betriebstrends und Gesundheitsbewertungen der Anlagen übersichtlich darstellen und fundierte Entscheidungen ermöglichen.

Das **Chiuchau Intelligente Überwachungssystem** bietet effiziente, zuverlässige und flexible Lösungen. Ob anspruchsvolle Halbleiter-Reinraumumgebungen oder standardmäßige Industrieumgebungen — wir erfüllen Ihre Anforderungen. Mit unserem System steigern Sie die Anlagenzuverlässigkeit, senken Wartungskosten und verbessern die Produktionseffizienz erheblich.

## 2. **Sicherheitshinweise**

Um einen sicheren und effektiven Betrieb des Chiuchau Intelligenten Überwachungssystems zu gewährleisten, lesen Sie bitte die folgenden Sicherheitshinweise sorgfältig durch. Dieses System umfasst Hochspannungsgeräte und Datenübertragung. Bitte befolgen Sie alle Betriebsvorschriften, um Unfälle oder Geräteschäden zu vermeiden.

---

#### 2.1 Stromversorgung & Installationssicherheit

- **Unabhängige Stromversorgung**: Stellen Sie sicher, dass das Überwachungsmodul über eine unabhängige 110V/220V-Stromquelle versorgt wird, die den örtlichen Vorschriften für elektrische Sicherheit entspricht.

- **Hochspannungsverkabelung — Warnung**: Hochspannungsanschlüsse an Motoren (380V/440V) dürfen ausschließlich von zertifizierten Elektrofachkräften durchgeführt werden. Arbeiten an stromführenden Leitungen sind strengstens untersagt.

- **Erdungsanforderungen**: Alle Geräte müssen ordnungsgemäß geerdet sein, um statische Störungen und Stromschlagrisiken zu vermeiden.

- **USV-Stromschutz**: Das System verfügt über ein integriertes USV-Modul, das Daten bei plötzlichem Stromausfall automatisch schützt. Das USV-Modul darf nicht demontiert oder modifiziert werden.

---

### 2.2 Sicherheit bei der Gerätebedienung

- **Wasser- und Staubschutz**: Dieses System verfügt über die Schutzarten IP65/IP67. Stellen Sie sicher, dass die Schutzdichtungen bei der Installation nicht beschädigt werden, um das Eindringen von Feuchtigkeit oder Staub zu verhindern.

- **Explosionsschutz-Einschränkungen**: Ist eine Installation in explosionsgefährdeten Bereichen erforderlich, bestätigen Sie, dass die Geräte den IEC-Explosionsschutzzertifizierungsstandards entsprechen, und befolgen Sie die Installationsvorschriften strikt.

- **Sensorinstallation**: Stellen Sie bei der Installation von Vibrationssensoren und Stromwandlern (CT) sicher, dass alle Stromquellen getrennt sind, und vermeiden Sie den Kontakt der Sensoren mit hohen Temperaturen oder korrosiven Substanzen.

---

### 2.3 Kommunikations- & Datensicherheit

- **Netzwerksicherheitseinstellungen**: Stellen Sie sicher, dass Wi-Fi-, LoRa- oder 4G-LTE-Verbindungen mit Verschlüsselungsprotokollen (z. B. WPA2) gesichert sind, um unbefugten Datenzugriff zu verhindern.

- **Datenschutz**: Alle Überwachungsdaten werden verschlüsselt auf Cloud- oder lokalen Servern gespeichert. Verwenden Sie keine nicht autorisierten Drittanbieter-Software für den Datenzugriff.

- **Firmware-Updates**: Prüfen und aktualisieren Sie die System-Firmware regelmäßig, um Sicherheit und Stabilität zu gewährleisten. Laden Sie Update-Dateien ausschließlich von offiziellen Quellen herunter.

---

### 2.4 Wartungs- & Inspektionshinweise

- **Spannungsfreie Wartung**: Schalten Sie vor jeder Wartung oder Inspektion die Stromversorgung ab und stellen Sie sicher, dass das System vollständig spannungsfrei ist.

- **Keine eigenmächtigen Änderungen**: Modifizieren Sie Hardware oder Software nicht ohne Genehmigung, da dies zu Systemausfällen oder Sicherheitsrisiken führen und die Garantie beeinträchtigen kann.

- **Regelmäßige Inspektionen**: Überprüfen Sie Sensoren und Datenkabel regelmäßig, um einen stabilen Gerätebetrieb sicherzustellen.

---

### 2.5 Notfallverfahren

- **Geräteanomalie**: Erkennt das System Anomalien (wie überhöhte Temperatur, ungewöhnliche Vibrationen oder Stromabweichungen), werden automatisch Alarme an die festgelegten LINE-Gruppen oder E-Mail-Adressen gesendet. Befolgen Sie umgehend die Systemempfehlungen zur Inspektion oder Abschaltung.

- **Brand- oder Stromschlaggefahr**: Bei Rauchentwicklung, Überhitzung oder Brandgeruch am Gerät sofort die Stromversorgung unterbrechen und den Bereich räumen. Versuchen Sie keine Reparaturen — kontaktieren Sie professionelles Wartungspersonal.

---

### 2.6 Weitere Hinweise

- **Schulungsanforderungen**: Nur professionell geschultes Personal darf dieses System bedienen, um Sicherheitsrisiken durch unbefugte Bedienung zu vermeiden.

- **Umweltgerechte Entsorgung**: Außer Betrieb genommene oder ersetzte Geräte sind gemäß den örtlichen Umweltvorschriften zu entsorgen.

---

Bitte befolgen Sie diese Sicherheitshinweise strikt, um einen sicheren Betrieb und eine stabile Geräteleistung zu gewährleisten. Bei Fragen wenden Sie sich an den Chiuchau Enterprise Kundendienst oder den technischen Support.

## 3. Produktübersicht

### 3.1 Systemarchitektur

![](../../assets/images/2d4ab7dd-334a-4ff4-9b70-751986f140d4.png)

### 3.2 Hauptkomponenten des Überwachungsmoduls

- Beschreibung der Komponentenfunktionen

- 3.3 Produktspezifikationen

## 4. Installationsanleitung

### 4.1 Hardware-Installation

- **Anleitung zur Stromverkabelung**

4.2 Sensorinstallation (Positionswahl & Befestigungsmethoden)

![](../../assets/images/1c15d3ca-264c-40ef-ab27-a2a363893dd2.png)

#### 4.2.1 Installationspositionsanleitung

Das System wird standardmäßig mit zwei hochpräzisen Drei-Achsen-Beschleunigungssensoren zur Überwachung des Ventilator-Vibrationszustands geliefert, die je nach Komponenteneigenschaften an folgenden Positionen installiert werden:

1. **Motorseitiger Sensor:**

1. **Lüfterradseitiger Sensor:**

#### 4.2.2 Installationsausrichtung (VAH-Positionierung)

Die Sensorinstallation muss gemäß der **VAH-Positionierung (Vertikal V, Axial A, Horizontal H)** für eine präzise Platzierung erfolgen, um Datengenauigkeit und Vergleichbarkeit sicherzustellen.

- **V-Achse (Vertikal):** Zeigt in die vertikale Richtung der Anlage zur Erfassung von Auf-Ab-Vibrationen.

- **A-Achse (Axial):** Parallel zur Motorwelle zur Überwachung axialer Vibrationen, insbesondere des Wellenausrichtungszustands.

- **H-Achse (Horizontal/Quer):** Parallel zur Horizontalebene der Anlage, senkrecht zur A-Achse, zur Erfassung lateraler Vibrationsanomalien.

#### 4.2.3 Befestigungsmethoden

Für Datengenauigkeit und langfristigen stabilen Betrieb müssen Sensoren mit professionellen Methoden montiert werden. Lockerungen oder Positionsverschiebungen, die die Überwachungsergebnisse beeinträchtigen könnten, sind zu vermeiden.

1. **Schraubbefestigung (empfohlen):**

1. **Starkklebermonatge (für temporäre Überwachung):**

1. **Magnetfuß (abnehmbare Installation):**

#### 4.2.4 Installationshinweise

- Stellen Sie sicher, dass die Geräteoberflächen vor der Installation sauber und ölfrei sind, um eine instabile Sensorbefestigung oder Datenverfälschung zu vermeiden.

- Installieren Sie Sensoren nicht auf Schweißnähten oder unebenen Oberflächen, um die Datengenauigkeit sicherzustellen.

- Sensorleitungen dürfen nicht parallel zu Hochspannungskabeln verlegt werden, um elektromagnetische Störungen zu minimieren.

- Führen Sie nach der Installation Kalibrierungstests durch, um eine normale und stabile Sensorausgabe zu bestätigen.

---

### 4.3 Netzwerk- & Kommunikationseinrichtung

- 4.3.1 Grundlegende Netzwerkanforderungen

![](../../assets/images/c105216e-8645-4302-a4bb-440832a2ab64.webp)

- **Hardwarekonfiguration:**

- **Dienstbeschreibung:**

- **Vorteile:**

#### 4.3.2 Kommunikationsprotokolle & technische Standards

- **Kommunikationsprotokolle:**

- **Drahtlose Kommunikationstechnologien:**

- **Behördliche Zertifizierungen:**

#### 4.3.3 Installations- & Einrichtungsschritte

- **Netzwerkumgebungstest:**

- **Geräteverbindungseinrichtung:**

- **Netzwerküberwachung & -wartung:**

---

Diese Anleitung bietet vollständige Netzwerk- und Kommunikationseinrichtungsanweisungen, um einen stabilen Betrieb des Überwachungssystems in verschiedenen Netzwerkumgebungen sicherzustellen.

### 4.4 Installation optionaler Zubehörteile

#### 4.4.1 Dreifarbige Statusleuchte

![](../../assets/images/791bc0cd-3312-47e1-b05f-05213e7cfa86.png)

Die dreifarbige Statusleuchte (Rot, Gelb, Grün) zeigt den Echtzeit-Betriebsstatus der Anlage an und hilft dem Vor-Ort-Personal, den Gesundheitszustand der Anlage und Anomaliealarme schnell zu erfassen. Die korrekte Installationsposition gewährleistet eine klare Sichtbarkeit der Signalleuchten und steigert die Betriebseffizienz und Sicherheit.

- **Empfehlungen zur Installationsposition**

- **Installationsschritte**

- **Nutzung & Wartung**

Die korrekte Installation und Nutzung der dreifarbigen Statusleuchte verbessert das visuelle Management des Anlagenbetriebs und hilft dem Vor-Ort-Personal, den Gerätezustand schnell einzuschätzen, Ausfallrisiken zu senken und die Sicherheit und Effizienz am Arbeitsplatz zu gewährleisten.

#### 4.4.2 4G-LTE-Router & Netzwerkkarte

Bitte beachten Sie den Abschnitt [Netzwerk- & Kommunikationseinrichtung](https://www.notion.so/1ade69175b11805a921ed4d24a70c9b9#%E7%BD%91%E7%BB%9C%E4%B8%8E%E9%80%9A%E8%AE%AF%E8%AE%BE%E7%BD%AE).

#### 4.4.3 Touch-Display

![](../../assets/images/d2c1961b-4ee3-429a-8b15-13d2109fe8e8.png)

Das Touch-Display bietet eine intuitive Bedienoberfläche, über die das Vor-Ort-Personal Echtzeit-Gerätedaten, Alarmstatus und Verlaufsaufzeichnungen einsehen sowie grundlegende Systemeinstellungen und -steuerungen vornehmen kann.

- **Installationsanleitung**

- **Bedienungsanleitung**

- **Wartung & Hinweise**

Das Touch-Display bietet eine intuitive und komfortable Bedienerfahrung und hilft dem Vor-Ort-Management, den Anlagenzustand schnell zu erfassen, die Betriebseffizienz zu steigern und die Geräteverwaltung zu vereinfachen.

#### 4.4.4 Hochpräziser RJ45-CT-Eingangszähler

![](../../assets/images/aebc6493-3fb1-4ef3-a6f3-40226d6d0ff8.png)

- **Installationsanleitung für den hochpräzisen RJ45-CT-Eingangszähler**

- **Installationsanleitung**

- **Hinweise**

## Hardware-Einrichtung & Inbetriebnahme

### 5.1 System-Startvorgang

Nach Abschluss der 110V/220V-Strominstallation den Schalter nach oben umlegen, um einzuschalten.

![](../../assets/images/7fdb32a2-1a09-4e4e-b716-fd95ca9eec17.png)

- Zum Herunterfahren den Schalter einfach nach unten umlegen, um die Stromversorgung zu unterbrechen. Das interne System führt automatisch den Abschaltvorgang durch — warten Sie ca. 10–15 Sekunden. Nachdem die Relais-Anzeige unten einmal erlischt, kann der nächste Neustart durchgeführt werden.

### 5.2 Hardware-Überprüfung bei Erstinstallation

- Prüfen Sie nach dem Einschalten, ob die Betriebsanzeige des Netzteils grün leuchtet (DC OK).

- Überprüfen Sie, ob der Router dauerhaft grün leuchtet.

- Bestätigen Sie, dass der Signalempfang ordnungsgemäß funktioniert (rote und grüne Leuchten aktiv).

### 5.3 Hardware-Fehlerbehebung

- Falls die Netzteil-Anzeige nach dem Einschalten nicht leuchtet, kann die Sicherung durchgebrannt sein. Ersetzen Sie die Sicherung (2A/250V Feinsicherung, Größe 6,35×32 mm).

- Falls die dreifarbige Leuchte nicht in der Reihenfolge Grün → Orange → Rot anzeigt, starten Sie das System neu (siehe „System-Startvorgang" Schritt 3).

- Falls das System nicht ordnungsgemäß heruntergefahren oder neu gestartet werden kann, schalten Sie die Steuerplatine des Überwachungssystems aus und wieder ein.

---

## 6. Software-Bedienungsanleitung

### 6.1 Kernfunktionen & Vorteile

- Echtzeitüberwachung & -analyse

![](../../assets/images/4d0fb650-2430-434e-a013-7046745ba3ad.png)

![](../../assets/images/5a9b1f04-a26d-4f91-9066-a40f0f565f85.png)

Bietet Echtzeit-Betriebsdatenüberwachung der Anlagen, einschließlich Vibration, Temperatur und anderer Schlüsselparameter, mit Unterstützung für Trenddiagramme und FFT-Spektralanalyse.

- **KI-gestützte intelligente Vorhersage**

![](../../assets/images/30833126-8869-4070-89e9-035752f210e9.png)

Kombiniert KI-Vorhersagemodelle, um potenzielle Anlagenanomalien und -ausfälle frühzeitig zu erkennen, Wartungskosten zu senken und die Betriebseffizienz zu steigern.

- Multiplattform-Unterstützung

![](../../assets/images/0eb522a6-c930-4e9e-ad3c-f35e90bc6fe5.png)

Ermöglicht Benutzern die Fernüberwachung des Anlagenstatus über verschiedene Endgeräte (Smartphones, Tablets, Computer).

- CO₂-Emissionserfassung

![](../../assets/images/72067d30-10aa-42ba-9521-262770985859.png)

Sofortige Alarmbenachrichtigungen bei Anlagenanomalien sowie CO₂-Emissionserfassungsfunktion.

### 6.2 Gerätediagramm

Bietet Echtzeit-Visualisierung des Anlagenstatus für schnellen Zugriff auf wichtige Betriebsinformationen jedes Geräts.

![](../../assets/images/71922abb-a453-4eaf-acc8-0e39f327f67c.png)

### **6.3 Überwachungsdaten**

Stellt Rohdaten in Tabellenform dar, einschließlich Temperatur, Vibration, Strom und weiterer detaillierter Kennwerte zur vertieften Analyse.

![](../../assets/images/8e9b8727-f178-45fc-87cf-b613d8a4fe08.png)

### **6.4 Trenddiagramme**

Zeigt die zeitliche Entwicklung der Anlagenbetriebsdaten, um Benutzern die Beurteilung des langfristigen Gerätezustands zu ermöglichen.

![](../../assets/images/98a5b725-a1eb-41c6-b446-11bcf8b2d016.png)

![](../../assets/images/3f8bce38-1865-4fb4-a7a1-fd492039d7f0.png)

### **6.5 CO₂-Emissionsüberwachung**

![](../../assets/images/6f6648db-7e18-4396-9d8e-9bcc55291b0e.png)

Echtzeitüberwachung der CO₂-Emissionsdaten der Anlagen, um Unternehmen bei der Erreichung von Energiespar- und CO₂-Reduktionszielen zu unterstützen.

---

### 6.6 Datenanalysefunktionen

- Anomalieerkennung & Gesundheitswert

---

### 6.7 Benachrichtigungs- & Alarmeinstellungen

- LINE-Gruppenbenachrichtigungen einrichten

- Dauerhafte Alarmbenachrichtigungen

- Alarmverwaltung

- Grundlagen der Alarmbenachrichtigung

---

### 6.8 Monatliche Berichtserstellung

#### Automatische Monatsbericht-Erstellung

Das System erstellt automatisch vollständige Anlagenbetriebsberichte mit Aufzeichnungen zu Vibration, Temperatur, Strom, Spannung und anderen Schlüsselparametern.

#### Anomalie-Ereignisverfolgung

Detaillierte Aufzeichnung jedes Anomalieereignisses einschließlich Auslösezeitpunkt, Systemreaktion und Wartungsempfehlungen.

#### CO₂-Emissions- & Anlagengesundheitsüberwachung

Erfasst CO₂-Emissionsdaten und überwacht Anlagengesundheitswerte mit Zukunftstrendprognosen.

#### Erdbeben-Alarmintegration

Echtzeit-Integration von Erdbebenalarminformationen zur schnellen Bewertung und Ausschließung potenzieller erdbebenbedingter Anlagenschäden.

- **Einstellungen zur automatischen Berichterstellung**

- **Berichtsformat & Ausgabe (PDF)**

- **Leitfaden zur Interpretation des Berichtsinhalts**

![](../../assets/images/4496ce7c-590f-44d8-a342-1b1d56d6df2e.png)

![](../../assets/images/f59a85db-2c2f-4de7-845c-64019ac366e6.png)

![](../../assets/images/798a32cf-ed46-4920-a93d-e304045f9d01.png)

![](../../assets/images/140ff412-f2f7-48db-b704-884528790762.png)

![](../../assets/images/2a0d6fe9-d2cb-4212-9f99-161b90476201.png)

---

## 7. Software-Fehlerbehebung

#### 7.1 Anmeldung nicht möglich

**Mögliche Ursachen & Lösungen**

- **Netzwerkverbindungsprobleme**

- **Falscher Benutzername oder Passwort**

- **Systemwartung oder Serverprobleme**

---

#### 7.2 Datenverzögerung oder -anomalien

**Mögliche Ursachen & Lösungen**

- **Serverbetriebsprobleme**
