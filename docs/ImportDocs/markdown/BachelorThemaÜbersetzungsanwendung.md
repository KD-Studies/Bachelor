# Thema: KI-gestützte Übersetzungsdienste für mehrsprachige Datenbankanwendungen

## Wissenschaftliche Fragestellung

**Fragestellung:**  
Wie kann die Datenbankstruktur einer zentralen Übersetzungsanwendung gestaltet werden, um die KI-gestützte Verwaltung und Übersetzung mehrsprachiger Einträge effizient und sicher zu gewährleisten?

-> Beantworten: Woher kommt die wissenschaftliche Fragestellung?

---

## Kernidee

- Entwicklung der Anwendung  
- Erstellung eines Packages oder einer API  
- Datenentnahme und -abgabe  
- Erstellung der Übersetzungstabellen bzw. Tabellen-Erweiterungen mit den Zielsprachen  

---

## Theorieabschnitt

### 1. Oracle APEX (max. 1 Seite)
- Überblick über die Architektur  
- Einsatzmöglichkeiten  

### 2. Datenbanken
- Grundkonzept der Datenbank  
- **Datenintegrität:**  
  - Eindeutige Datenzuordnung  
  - Sicherstellung der korrekten Befüllung aller Spalten und Datentypen in der Zielanwendung  
  - Intakte Verknüpfung zwischen Original- und Übersetzungsdaten  
  - Validierung auf vollständige Einträge  
- **Datenkonsistenz:**  
  - Synchronhaltung der Übersetzungen mit den Originaldaten  
  - Sicherstellung, dass Übersetzungen den ursprünglichen Bedeutungszusammenhang bewahren  
  - Initiale Übersetzungsprüfung (z. B. Prüfung, ob Werte bereits in der Zielsprache vorliegen)  
- **Datenaufbereitung:**  
  - Nutzung eines Statusfelds zur Überwachung  
  - Auditspalten zur Protokollierung der Übersetzungen  

### 3. Künstliche Intelligenz in der Übersetzung
- Arten von KI-gestützten Übersetzungen  
- Funktionsweise von KI-Übersetzungsdiensten  
- Herausforderungen bei KI-Übersetzungen  
- Integration von KI-Übersetzungsdiensten in die Anwendung  

### 4. API-Schnittstelle
- Grundlagen von APIs  
- API für Datenübertragung  
- Sicherheitsaspekte bei der API-Nutzung  
- Herausforderungen bei der API-Integration  
- API-Struktur  
- API-Monitoring und Wartung  

### 5. Qualitative Inhaltsanalyse (Mayring-Verfahren)
- Grundlagen der qualitativen Inhaltsanalyse  
- Prinzipien des Mayring-Verfahrens (z. B. Kategorienbildung, induktives und deduktives Vorgehen)  
- Relevanz für die Evaluation von Softwareprojekten  
- Vorteile und Grenzen des Mayring-Verfahrens im Kontext dieser Arbeit  

### 6. Forschungsfragen und Hypothesen
- **Effizienz-Hypothese:**  
- **Qualitäts-Hypothese:**  
- **Skalierbarkeits-Hypothese:**  
- **Benutzerfreundlichkeits-Hypothese:**  
- **Sicherheits-Hypothese:**  

---

## Praxisabschnitt

*Beantworten: Phasenartiges Vorgehen*

### 1. Konzept der Anwendung
- Beschreibung der Übersetzungsanwendung und deren Zielsetzung  
- Datenfluss: Import und Export von Daten  
- Berechtigungsverwaltung: Welche Benutzer haben Zugriff?  
- Zeitpunkt der Übersetzung: Wann und wie sollen Übersetzungen erfolgen?  

### 2. Datenmodell
- Datenbankstruktur der zentralen Übersetzungsanwendung  
- Darstellung des Datenmodells:  
  - Tabellen für Originaleinträge, Übersetzungen, Benutzeranpassungen und Änderungsprotokolle  
  - Statusfelder zur Überwachung  

### 3. Implementierung der API-Schnittstellen
- Darstellung der APIs und deren Verbindungen  
  - **Eingehende API:**  
    - Anforderungen an die eingehenden Daten  
  - **Übersetzungs-API:**  
    - Übergabe relevanter Daten an die API  
    - Rückgabe von Übersetzungsdaten  
  - **Ausgehende API:**  
    - Anforderungen an die Zieltabellen  
    - Erstellung der Zieltabellen für Übersetzungseinträge  

### 4. Kosten durch API-Aufrufe
-> Beantworten: Welche Art von Kosten? Metriken?  
*(Nutzung der APIs / monetäre Faktoren)*  
- Kosten pro Übersetzungsanfrage  

### 5. Benutzeroberfläche → Prototypisierung
- Übersichtsseiten  
- Dashboard:  
  - Anzahl der importierten Einträge und Herkunft der Anwendungen  
- Liste der zu übersetzenden Einträge  
- Verfügbare Zielsprachen  

### 6. Automatisierungen und Statusprüfung
- Initiale Übersetzung:  
  - Kennzeichnung von bereits übersetzten und nicht übersetzten Einträgen  

### 7. Fehlerbehandlung und Sicherheit  
- **Fehlerbehandlung:**  
  - Protokollierung von Fehlern  
- **Sicherheitsaspekte:**  
  - Rechteverwaltung / Datenübertragung sollte verschlüsselt sein  
  - Zugriffsbeschränkungen für APIs und Benutzer  
  - Verschlüsselung sensibler Daten bei der Übertragung  

### 8. Tests und Evaluierungen
- **Testszenarien:**  
  - Import aller Datensätze  
  - Übersetzung unter Berücksichtigung des Übersetzungsbedarfs  
  - Nutzung der API im Zielsystem  
- **Benutzerfeedback (Formular):**  
  -> Beantworten: Auswertung einer Umfrage → quantitative Forschungsmethode  
- Evaluierung der Benutzeroberfläche  
- Evaluierung der Funktionalitäten  

### 9. Interviews und qualitative Analyse
- **Ziel der Interviews:**  
  - Erkenntnisse zu Benutzeranforderungen und -feedback gewinnen  
- **Anwendung des Mayring-Verfahrens:**  
  - Entwicklung eines Kategoriensystems basierend auf den Interviewdaten  
  - Auswertung der Antworten zur Ableitung von Verbesserungsvorschlägen  
  -> Beantworten: In welcher Phase soll die Methode nach Mayring eingesetzt werden?  
  *(Das soll im Kontext der Vorstudie für die Anforderungen geschehen)*  
- **Ergebnisse:**  
  - Darstellung der wichtigsten Erkenntnisse aus den Interviews  
  - Validierung der Hypothesen: Verknüpfung der Interviewergebnisse mit den formulierten Hypothesen und Überprüfung ihrer Gültigkeit  
- Einbindung weiterer externer Übersetzungsanbieter  
- **Kritische Reflexion:**  
  -> Kapitel 4:  
  - Abhängigkeit der Übersetzungsqualität von externen Diensten  
  - Notwendigkeit kontinuierlicher Überprüfung und Optimierung  
  - Balance zwischen Automatisierung und manueller Kontrolle als zentrale Herausforderung  

---

## Inhaltsverzeichnis

1. **Einleitung**  
   1.1 Motivation  
   1.2 Zielsetzung der Bachelorarbeit  
   1.3 Vorgehensweise  
   1.4 Strukturierung der Bachelorarbeit  

2. **Theorieabschnitt**  
   2.1 Oracle APEX  
   &nbsp;&nbsp;&nbsp;&nbsp;2.1.1 Überblick über die Architektur  
   &nbsp;&nbsp;&nbsp;&nbsp;2.1.2 Einsatzmöglichkeiten  
   2.2 Datenbanken  
   &nbsp;&nbsp;&nbsp;&nbsp;2.2.1 Grundkonzept der Datenbank  
   &nbsp;&nbsp;&nbsp;&nbsp;2.2.2 Datenintegrität  
   &nbsp;&nbsp;&nbsp;&nbsp;2.2.3 Datenkonsistenz  
   &nbsp;&nbsp;&nbsp;&nbsp;2.2.4 Statusverwaltung und Auditspalten  
   2.3 Künstliche Intelligenz in der Übersetzung  
   &nbsp;&nbsp;&nbsp;&nbsp;2.3.1 Arten von KI-gestützten Übersetzungen  
   &nbsp;&nbsp;&nbsp;&nbsp;2.3.2 Funktionsweise von KI-Übersetzungsdiensten  
   &nbsp;&nbsp;&nbsp;&nbsp;2.3.3 Herausforderungen bei der Integration  
   2.4 API-Schnittstellen  
   &nbsp;&nbsp;&nbsp;&nbsp;2.4.1 Grundlagen von APIs  
   &nbsp;&nbsp;&nbsp;&nbsp;2.4.2 Sicherheitsaspekte  
   &nbsp;&nbsp;&nbsp;&nbsp;2.4.3 API-Struktur und Monitoring  
   2.5 Qualitative Inhaltsanalyse (Mayring-Verfahren)  
   &nbsp;&nbsp;&nbsp;&nbsp;2.5.1 Prinzipien und Vorgehen  
   &nbsp;&nbsp;&nbsp;&nbsp;2.5.2 Relevanz für Softwareprojekte  
   -> Beantworten: Woher kommen die Hypothesen?  

3. **Hypothesen**  
   3.1 Effizienz-Hypothese  
   3.4 Benutzerfreundlichkeits-Hypothese  

4. **Praxisabschnitt**  
   4.1 Vorstellung des Praxisunternehmens  
   4.2 Konzept der Anwendung  
   &nbsp;&nbsp;&nbsp;&nbsp;4.2.1 Beschreibung und Zielsetzung  
   &nbsp;&nbsp;&nbsp;&nbsp;4.2.2 Datenfluss  
   &nbsp;&nbsp;&nbsp;&nbsp;4.2.3 Berechtigungsverwaltung  
   4.3 Datenmodell  
   &nbsp;&nbsp;&nbsp;&nbsp;4.3.1 Struktur der Datenbank  
   4.4 Implementierung der API-Schnittstellen  
   &nbsp;&nbsp;&nbsp;&nbsp;4.4.1 Eingehende API  
   &nbsp;&nbsp;&nbsp;&nbsp;4.4.2 Übersetzungs-API  
   &nbsp;&nbsp;&nbsp;&nbsp;4.4.3 Ausgehende API  
   4.5 Kosten durch API-Aufrufe  
   4.6 Benutzeroberfläche  
   &nbsp;&nbsp;&nbsp;&nbsp;4.6.1 Dashboard und Übersichtsseiten  
   4.7 Automatisierungen und Statusprüfung  
   4.8 Fehlerbehandlung und Sicherheitsmaßnahmen  
   4.9 Tests und Evaluierungen  
   &nbsp;&nbsp;&nbsp;&nbsp;4.9.1 Benutzerfeedback  
   4.10 Interviews und qualitative Analyse  
   -> Beantworten: Soll die Mayring Methode hier genutzt werden?  
   &nbsp;&nbsp;&nbsp;&nbsp;4.10.1 Ergebnisse und Hypothesenprüfung  
   -> Beantworten: Gegebenenfalls könnten einige Kapitel zusammengelegt werden. / Ansonsten wirkt die Struktur zu kleinteilig.  

5. **Ausblick und Fazit**  
   5.1 Zusammenfassung der Ergebnisse und der gewonnenen Erkenntnisse  
   5.2 Praktischer Mehrwert: Übertragung für die zukünftige Arbeitspraxis und weiterführende Arbeiten  
   5.3 Kritische Würdigung  
