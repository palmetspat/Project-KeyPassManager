# Allgemeine Bedingungen und Beschränkungen

## Technische Bedingungen
- **Speicherung:**  
  - Passwörter werden **lokal auf dem Gerät** oder **auf einem sicheren, vom Nutzer verwalteten Server** gespeichert.  
  - Eine zentrale Serverlösung ist in der ersten Version nicht vorgesehen, aber eine **optionale Synchronisation über eigene Server** ist später möglich.  
- **Plattformen:**  
  - **Primärentwicklung für Windows** als Desktop-Anwendung  
  - **Unterstützung für gängige Webbrowser** (Chrome, Firefox, Edge) für eine optionale Web-Anwendung  
  - **Muss auch auf älteren Geräten mit begrenzter Leistung und Speicherplatz stabil laufen**  
  - **Erweiterung für Linux & macOS in späteren Versionen geplant**  
- **Sicherheit:**  
  - Alle gespeicherten Daten werden mit **AES-256** verschlüsselt  
  - **TLS-Verschlüsselung** sichert die Datenübertragung  
  - **Keine unverschlüsselte Speicherung oder Übermittlung** von Passwörtern  
  - **AutoFill-Funktion:** Die Software erkennt Anmeldefelder und bietet die automatische Speicherung von Zugangsdaten an  

## Systemanforderungen
- **Hardware:**  
  - Unterstützung für **Windows 7 und neuer**, um auch ältere und leistungsschwächere Geräte zu unterstützen  
  - **Optimierung für Systeme mit wenig Arbeitsspeicher und schwächerer Prozessorleistung**  
  - Keine hohe CPU- oder GPU-Belastung, damit auch ältere PCs nutzbar sind  
- **Software:**  
  - Keine zusätzlichen Programme erforderlich, außer ein **optionaler Server** für Synchronisation  
  - **Geringer Speicherbedarf**, um auch auf Geräten mit wenig freiem Speicher installierbar zu sein  

## Einschränkungen
- Die erste Version konzentriert sich ausschließlich auf die **Windows-Desktop-Anwendung**, andere Plattformen werden später ergänzt  
- Eine **Server-Lösung ist kein Hauptziel**, wird aber später als Option ermöglicht  
- **Keine mobile Version oder erweiterte Synchronisation in der ersten Veröffentlichung**  
- **Plattformübergreifende Nutzung wird nur für offiziell unterstützte Betriebssysteme getestet**  
- **Keine ressourcenintensiven Prozesse**: Software wird so entwickelt, dass sie wenig RAM und Prozessorleistung benötigt  

## Wer ist der Host?
- Die Anwendung ist primär **Self-Hosted**, das bedeutet, dass der Nutzer selbst entscheidet, ob die Daten **lokal oder auf einem eigenen Server** gespeichert werden  
- Eine zentrale Hosting-Lösung durch einen externen Anbieter ist in **Version 1 nicht vorgesehen**  
- Eine **optionale Hosting-Variante könnte in einer späteren Version** implementiert werden  

## Plattformintegration und AutoFill
Ein wesentliches Feature ist die **AutoFill-Funktion**, die automatisch erkennt, wenn der Nutzer sich auf einer Website oder in einer App anmeldet. Dabei wird gefragt, ob die eingegebenen Zugangsdaten gespeichert werden sollen.  

**Technische Umsetzung:**  
- Webbrowser-Integration über eine Erweiterung  
- Desktop-Integration durch laufende Erkennung von Eingabefeldern  

**Nutzerkontrolle:**  
- AutoFill kann manuell aktiviert oder deaktiviert werden  
- Alle gespeicherten Daten bleiben verschlüsselt und lokal gesichert  
- **Optimierung für ältere Geräte**: Keine dauerhafte hohe Hintergrundlast durch AutoFill-Scanning  
