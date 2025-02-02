# Projektziele

Unser Ziel ist es, einen sicheren und benutzerfreundlichen Passwortmanager zu entwickeln, der unabhängig von Drittanbietern funktioniert und die Kontrolle über gespeicherte Passwörter vollständig dem Nutzer überlässt.

## **Kurzfristige Ziele (erste Version)**
- Entwicklung einer **Windows-Desktop-Anwendung** zur sicheren Speicherung von Passwörtern.  
- **Lokale Speicherung mit End-to-End-Verschlüsselung** (AES-256), keine Cloud-Abhängigkeit.  
- **Einfache Bedienbarkeit**, um auch für Nicht-Techniker nutzbar zu sein.  
- **Import & Export-Funktion**, um bestehende Passwörter einfach zu übertragen.  
- **AutoFill-Funktion in der Windows-App**, um Login-Felder automatisch auszufüllen (deaktivierbar).  

## **Langfristige Ziele (zukünftige Erweiterungen)**
- **Web-Anwendung**, um Passwörter plattformübergreifend zu nutzen (nicht in Version 1 enthalten).  
- **Optionale Server-Synchronisation**, um Passwörter geräteübergreifend zu nutzen.  
- **Mobile Version für iOS & Android (zukünftig geplant, nicht in Version 1 enthalten).**  
- **Browser-Erweiterung für AutoFill** zur Erkennung und Speicherung von Passwörtern direkt im Web.  
- **Erweiterte Sicherheitsfunktionen**, z. B. Zwei-Faktor-Authentifizierung.  

---

# Systemkonzept

Unser Konzept basiert auf einer modularen und flexiblen Architektur, die es ermöglicht, die Anwendung sowohl lokal als auch später optional über einen Server zu nutzen.

## **Plattformen**
- **Windows-Desktop-Anwendung** (erste Version).  
- **Linux & macOS-Unterstützung (zukünftig geplant).**  
- **Docker-Compose für einfache Installation.**  
- **Web-Anwendung für spätere Versionen geplant.**  

## **Speicherung**
- **In Version 1 nur lokale Speicherung** auf dem Gerät.  
- **Optionale Server-Synchronisation für spätere Versionen vorgesehen, aber kein Cloud-Zwang.**  
- **AES-256-Verschlüsselung** zum Schutz der gespeicherten Daten.  

## **Sicherheit**
- **End-to-End-Verschlüsselung** bei Datenübertragungen.  
- **Keine unverschlüsselte Speicherung oder Weitergabe** von Passwörtern.  
- **Unterstützung für SSL/TLS** zur sicheren Kommunikation.  

## **Benutzerfreundlichkeit**
- **Einfache Bedienung** für alle Nutzergruppen.  
- **Schnelle Suchfunktion**, um gespeicherte Passwörter leicht zu finden.  
- **Import/Export-Funktion**, um bestehende Passwörter zu übernehmen.  
- **AutoFill-Funktion in der Windows-App**, um Login-Felder automatisch auszufüllen (deaktivierbar).  

### **Benutzungskonzept**
Unser Passwortmanager soll einfach und sicher nutzbar sein. Der Fokus liegt darauf, dass auch unerfahrene Nutzer Passwörter sicher verwalten können, ohne komplexe technische Vorkenntnisse zu benötigen.

- **Erstnutzung:** Nutzer erstellt ein Master-Passwort, mit dem alle gespeicherten Passwörter geschützt werden.  
- **Passwort speichern:** Neue Passwörter können manuell eingegeben oder automatisch erkannt und gespeichert werden.  
- **Passwort abrufen:** Der Nutzer kann gespeicherte Passwörter über eine Suchfunktion schnell finden.  
- **Automatische Sperre nach Inaktivität** zur Erhöhung der Sicherheit.  

## **Erweiterbarkeit**
- **Modular aufgebaut**, um zukünftige Funktionen wie Synchronisation, Team-Zugriff oder mobile Apps zu integrieren.  

---

## **Nicht im ersten Release enthalten (zukünftig geplant)**
- **Keine mobile Version in der ersten Version**.  
- **Keine zentrale Cloud-Speicherung, nur lokale Datenverwaltung.**  
- **Plattformübergreifende Nutzung (Linux, macOS, Web) erst in späteren Versionen.**  
- **Server-Synchronisation wird später als optionales Feature eingeführt.**  
- **Kein Team-Management – der Fokus liegt zunächst auf Einzelbenutzer.**  
