# Einführung
In der heutigen digitalen Welt benötigen Menschen eine immer größere Anzahl an Passwörtern. Egal ob für IT-Applikationen oder alltägliche Aktivitäten – Authentifizierung in Form von Passwörtern ist unverzichtbar. Gleichzeitig spielt die Sicherheit dieser Passwörter eine zentrale Rolle, da sie den Zugang zu sensiblen persönlichen und beruflichen Daten schützen.
Die steigende Komplexität und Anzahl an Passwörtern ergeben zahlreiche Herausforderungen: Viele Menschen greifen auf unsichere Praktiken zurück, um ihre Passwörter zu speichern, oder verlieren den Überblick über ihre Passwörter. Zusätzlich bergen Online-Speicherlösungen wie Cloud-Dienste oder unsichere Passwörter erhebliche Sicherheitsrisiken.

- **Sicherheitsrisiken**: Einfache Passwörter sind anfällig für Brute-Force-Angriffe, während unsichere Speicherung (z.B.: in der Cloud) Datenlecks begünstigen kann.
- **Komplexitätsprobleme**: Nutzer verlieren oft den Überblick über ihre Passwörter, was zu Zugangsschwierigkeiten und daraus resultierender Frustration führt.
- **Abhängigkeit von Drittanbietern**: Viele bestehende Passwortmanager speichern Daten in der Cloud, was Abhängigkeiten schafft und die eigene Kontrolle über sensible Daten reduziert.

Das Bedürfnis nach einer unabhängigen, sicheren und einfach zu bedienenden Lösung wächst stetig. Die existierenden Angebote auf dem Markt weisen jedoch Nachteile auf, die diese Anforderungen nicht vollständig erfüllen.

---

### Marktanalyse: Softwareanbieter

<details>
<summary><strong>Tabellenansicht der Softwareanbieter (Zum Ein- und Ausklappen klicken)</strong></summary>

| **Anbieter**      | **Vorteile** | **Nachteile** |
|--------------------|---------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------|
| **1Password**      | - Benutzerfreundliches Interface<br>- Plattformübergreifend<br>- Cloud-Backup              | - Interface bietet zu viele Funktionen auf einmal<br> - Abhängigkeit von Cloud-Diensten<br>- Zahlungspflichtig (~ 40 USD / Jahr) |
| **Dashlane**       | - Dark-Web-Monitoring<br>- Automatisches Passwort-Update<br>- Integrierter VPN              | - Interface ist komplex und überladen für Nutzer, die nur eine einfache Passwortverwaltung möchten<br>- Teure Premium-Optionen     |
| **LastPass**       | - Große Verbreitung<br>- Browserintegration<br>- Freemium-Modell                           | - Sicherheitsprobleme in der Vergangenheit<br>- Interface wirkt veraltet und wenig modern<br>- Viele Features sind hinter Paywalls |
| **KeePassXC**      | - Open Source<br>- Lokale Speicherung<br>- Umfangreiche Funktionen                         | - UI ist technisch und unattraktiv für Anfänger<br>- Keine zentrale Synchronisationsmöglichkeit<br>- Komplexität erschwert Einstieg |
| **Bitwarden**      | - Open Source<br>- Hohe Sicherheit<br>- Selbst-Hosting-Option verfügbar                    | - Interface ist schlicht, aber weniger intuitiv im Vergleich zu 1Password<br>- Selbst-Hosting benötigt technisches Know-how        |

</details>

---

### Marktanalyse: Website- / Cloud-Anbieter

<details>
<summary><strong>Tabellenansicht der Website- / Cloud-Anbieter (Zum Ein- und Ausklappen klicken)</strong></summary>

| **Anbieter** | **Vorteile** | **Nachteile**  |
|---------------------------|---------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------|
| **Google Password Manager** | - Integration mit Chrome und Android<br>- Kostenlos<br>- Einfach zu bedienen              | - UI ist minimalistisch, bietet jedoch kaum Flexibilität für Benutzerwünsche<br>- Eingeschränkte Plattform-Kompatibilität           |
| **Apple Keychain**           | - Nahtlose Integration in das Apple-System<br>- Kostenlos                              | - Eingeschränkt auf Apple-Geräte<br>- UI ist stark an das Apple-Design gebunden, ohne Optionen für Personalisierung                 |
| **Dropbox Passwords**        | - Einfaches Teilen von Passwörtern<br>- Cloud-Speicherung                                 | - Sehr grundlegendes Interface ohne erweiterte Funktionen<br>- Abhängigkeit von Dropbox                                           |
| **NordPass**                 | - Sicherheit durch Zero-Knowledge-Verschlüsselung<br>- Plattformübergreifend              | - UI bietet wenig Benutzeranpassungen<br>- Komplexer Einstieg für Nutzer, die keine technischen Vorkenntnisse haben                |
| **Zoho Vault**               | - Integriert in andere Zoho-Produkte<br>- Mehrbenutzerfähigkeit                           | - Kompliziertes Interface für Anfänger<br>- Viele Funktionen nur für Teams, nicht für private Nutzer                              |

</details>

---

### Herausforderung: Benutzerfreundlichkeit und Interface-Design

Eine häufige Schwachstelle der bestehenden Lösungen ist die Gestaltung der Benutzeroberfläche (UI) und die Benutzerfreundlichkeit (UX). 
Viele der oben genannten Passwortmanager sprechen entweder ausschließlich technisch veranlagte Nutzer an oder sind durch überladene Interfaces unnötig komplex.

- **Überladene Interfaces**: Anbieter wie Dashlane und LastPass integrieren zahlreiche Zusatzfunktionen (z.B.: Dark-Web-Monitoring oder VPN's), die den eigentlichen Zweck der Software (sichere Passwortverwaltung) in den Hintergrund rücken.
- **Eingeschränkte Zugänglichkeit**: Lösungen wie KeePassXC oder Bitwarden sind technisch und flexibel, aber für Anfänger oft schwer verständlich.
- **Veraltetes Design**: Manche Anbieter (z. B. LastPass) setzen auf eine veraltete Optik, die nicht den Ansprüchen moderner Software-Nutzer entspricht.

Die Marktsituation zeigt, dass ein Bedarf an einer Lösung besteht, die folgende Merkmale kombiniert:
1. **Maximale Sicherheit durch Selbst-Hosting und lokale Datenhaltung.**
2. **Einfaches, intuitives Interface, das sowohl technisch veranlagte als auch unerfahrene Nutzer anspricht.**
3. **Flexibilität und Anpassungsfähigkeit, um individuelle Benutzeranforderungen zu erfüllen.**
