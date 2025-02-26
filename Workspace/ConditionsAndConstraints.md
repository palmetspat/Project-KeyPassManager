# Allgemeine Bedingungen und Beschränkungen

## Technische Bedingungen
- **Speicherung:**  
  - In der **ersten Version** werden Passwörter **ausschließlich lokal auf dem eigenen Gerät** gespeichert.  
  - Eine **optionale Server-Speicherung ist für zukünftige Versionen geplant**, aber es wird **kein externer Anbieter genutzt.**   
  - Bei der Erstellung des Master-Passworts werden **10 einmalige Wiederherstellungscodes** generiert, die der Nutzer ausdrucken oder sicher notieren muss. Diese Codes sind nicht erneut abrufbar und dienen als einzige Möglichkeit zur Wiederherstellung. Gehen sowohl das       Master-Passwort als auch alle Wiederherstellungscodes verloren, gibt es keine Möglichkeit, den Zugriff wiederherzustellen.

- **Plattformen:**  
  - **Primärentwicklung für Windows** als Desktop-Anwendung.  
  - **Linux & macOS Unterstützung ist für spätere Versionen vorgesehen.**  
  - **Webbrowser-Integration (Chrome, Firefox, Edge)**  
  - **Optimiert für ältere Geräte** mit begrenzter Leistung & Speicherplatz.  

- **Sicherheit:**  
  - **AES-256-Verschlüsselung** für gespeicherte Passwörter.  
  - **TLS-Verschlüsselung** für sichere Datenübertragungen.  
  - **Keine unverschlüsselte Speicherung oder Übertragung von Passwörtern.**  
  - **Master-Passwort und Wiederherstellungscodes sind die einzigen Möglichkeiten zur Entschlüsselung.**  

## Systemanforderungen
- **Hardware:**  
  - Unterstützung für **Windows 7 und neuer**, um auch ältere und leistungsschwächere Geräte zu unterstützen.  
  - **Geringe CPU- und Speicherbelastung**, damit auch ältere PCs kompatibel sind.  

- **Software:**  
  - Keine zusätzlichen Programme erforderlich.  
  - **Optional wird in späteren Versionen eine Server-Option bereitgestellt.**  
  - **Geringer Speicherbedarf**, um auf Geräten mit wenig freiem Speicher installierbar zu sein.  

## Einschränkungen der ersten Version
- **Nur lokale Speicherung, keine Server- oder Cloud-Lösung.**  
- **Nur Windows-Desktop, keine mobile Version.**  
- **Plattformübergreifende Nutzung (Linux, macOS, Web) ist für spätere Versionen vorgesehen.**    
- **10 Wiederherstellungscodes werden einmalig generiert, aber nicht erneut abrufbar.**  

## Speicherung & Hosting
- **In Version 1 werden alle Daten lokal gespeichert.**  
- **Ein Server-Support für Synchronisation ist für eine spätere Version geplant.**  
- **Es wird kein externer Hosting-Dienst genutzt – Nutzer behalten volle Kontrolle über ihre Daten.**  

## Plattformintegration & AutoFill
- **Automatische Erkennung von Login-Feldern in der Desktop-Anwendung und in den jeweiligen Webbrowsern.**  
- **Das automatische ausfüllen der Benutzerdaten (Passwort und Username) ist vorgesehen.**  
- **Optimiert für ältere Systeme, kein dauerhaft hoher Ressourcenverbrauch.**  

---

