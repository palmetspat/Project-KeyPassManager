# **Allgemeine Bedingungen und Beschränkungen**

## **Technische Bedingungen**
- **Speicherung:**  
  - Passwörter werden entweder **lokal auf dem Gerät** oder **auf einem sicheren, vom Nutzer verwalteten Server** gespeichert.  
- **Plattformen:**  
  - **Primärentwicklung für Windows** als Desktop-Anwendung.  
  - **Unterstützung für gängige Webbrowser** (Chrome, Firefox, Edge) für eine optionale Web-Anwendung.  
  - **Geplante Erweiterung für Linux & macOS** in späteren Versionen.  
- **Sicherheit:**  
  - Alle gespeicherten Daten werden mit **AES-256** verschlüsselt.  
  - **TLS-Verschlüsselung** stellt eine sichere Datenübertragung sicher.  
  - **Kein unverschlüsseltes Speichern oder Übermitteln** von Passwörtern.  
  - **AutoFill-Funktion:** Die Software erkennt Anmeldefelder und bietet die automatische Speicherung von Zugangsdaten an.  

---

## **Systemanforderungen**
- **Hardware:**  
  - Ein **aktueller Computer oder Laptop** mit Windows 10 oder neuer.  
- **Software:**  
  - Keine zusätzlichen Programme erforderlich, außer ein **optionaler Server** für Synchronisation.  

---

## **Einschränkungen**
🚫 **Die erste Version fokussiert sich auf die Windows-Desktop-Anwendung** – andere Plattformen werden später ergänzt.  
🚫 **Keine mobile Version oder erweiterte Synchronisation in der ersten Veröffentlichung**.  
🚫 **Plattformübergreifende Funktionalität wird nur auf offiziell unterstützten Betriebssystemen (Windows, Linux, macOS) getestet**.  
🚫 **Keine zentrale Cloud-Lösung in Version 1 – das Hosting liegt in der Verantwortung des Nutzers**.  

---

## **Wer ist der Host?**
💡 **Die Anwendung ist primär Self-Hosted**, d. h. der Nutzer entscheidet selbst, ob er die Daten **lokal oder auf einem eigenen Server** speichert.  
- **Keine zentrale Serverlösung vorgesehen** in Version 1.  
- Spätere Versionen könnten eine Hosting-Option über einen eigenen Anbieter ermöglichen.  

---

## **Plattformintegration & AutoFill**
Ein zentrales Feature wird die **AutoFill-Funktion** sein, die automatisch erkennt, wenn der Nutzer sich auf einer Website oder in einer App anmeldet. Dabei wird gefragt, ob die eingegebenen Zugangsdaten im Passwortmanager gespeichert werden sollen.  

🔹 **Technische Umsetzung:**  
- **Webbrowser-Integration über eine Erweiterung**  
- **Desktop-Integration durch laufende Erkennung von Eingabefeldern**  

🔹 **Nutzerkontrolle:**  
- **AutoFill kann manuell aktiviert oder deaktiviert werden**.  
- **Alle erkannten Daten bleiben verschlüsselt und lokal gespeichert**.  

