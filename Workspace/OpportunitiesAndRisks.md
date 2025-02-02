# Chancen und Risiken des Projektes

## Konzept für die Entwicklung eines Passwort Managers

### Finanzielle und technische Rahmenbedingungen

#### 1. Software und Entwicklungstools
- **IDE (Integrated Development Environment)**: Kostenlose Versionen wie Visual Studio Code oder JetBrains IntelliJ IDEA können genutzt werden. Falls erweiterte Funktionen benötigt werden, können kostenpflichtige Versionen in Betracht gezogen werden.
  - **Kosten**: 0 € – 500 € (für professionelle Lizenzen, falls erforderlich)
  
- **Bibliotheken und Frameworks**: Open-Source-Tools wie OpenSSL für die Verschlüsselung oder andere bestehende Authentifizierungsframeworks können verwendet werden.
  - **Kosten**: 0 € – 500 € (für spezielle kommerzielle Lizenzen oder API-Nutzung)
  
- **Versionierung und Codeverwaltung**: Plattformen wie GitHub oder GitLab bieten kostenlose Repositories an. Für private Repositories fallen ggf. Kosten an, aber dies kann minimiert werden.
  - **Kosten**: 0 € – 100 € pro Jahr (wenn private Repositories benötigt werden)

#### 2. Server und Infrastruktur
- **Web-Hosting und Datenbanken**: Wenn ein Cloud-Backend benötigt wird, können Cloud-Dienstleister wie AWS, Azure oder Google Cloud genutzt werden. Diese Anbieter bieten oft ein gewisses Freikontingent für kleine Anwendungen.
  - **Kosten**: 0 € – 500 € pro Jahr (je nach Nutzung)
  
- **Datenverschlüsselung und Sicherung**: Open-Source-Tools zur sicheren Datenhaltung und Backup-Systeme (z. B. verschlüsselte Datenbanken oder Dateispeicherung).
  - **Kosten**: 0 € – 200 € pro Jahr

#### 3. Marketing und Branding
- **Website und Domain**: Eine einfache Website für die Vorstellung des Passwort Managers und für Downloads. Kosten für Domain und Hosting.
  - **Kosten**: 10 € – 100 € pro Jahr (je nach Anbieter)
  
- **Social Media und Werbeanzeigen**: Für die Promotion des Passwort Managers können Social Media Marketing oder bezahlte Werbeanzeigen auf Plattformen wie Google Ads oder Facebook genutzt werden.
  - **Kosten**: 100 € – 500 € (initiales Marketingbudget)
  
- **App Store Gebühren**: Wenn der Passwort Manager als mobile App angeboten wird, fallen App Store Gebühren an (Apple Developer Program oder Android).
  - **Kosten**: 100 € – 400 € einmalig (je nach Plattform)

#### 4. Sonstige Kosten
- **Rechtliche Beratung**: Rechtliche Aspekte wie Datenschutzbestimmungen (z. B. DSGVO) oder AGBs müssen berücksichtigt werden. Eine eventuelle Beratung durch einen Anwalt könnte notwendig sein.
  - **Kosten**: 200 € – 1.000 € einmalig (je nach Bedarf)

#### Zusammenfassung des Budgets
- **Minimal (nur für Entwicklung und kostenlose Tools)**: 0 € – 500 €
- **Moderate Investition (inkl. Marketing und kleinen Lizenzgebühren)**: 500 € – 2.500 €
- **Höhere Investition (mit Servern, professionellen Tools und umfangreicher Werbung)**: 2.500 € – 5.000 €

Das Budget kann je nach spezifischen Anforderungen und dem geplanten Umfang des Projekts variieren. Open-Source-Software hilft jedoch, die Kosten erheblich zu reduzieren. Marketing und Infrastruktur können je nach Zielgruppe und Umfang eine größere Rolle spielen.

### Technische Rahmenbedingungen

### Plattformen und Technologien
Der Passwortmanager soll für mehrere Plattformen entwickelt werden: Windows, macOS, Android und iOS. Es wird eine plattformübergreifende Lösung mit Technologien wie **Flutter** oder **React Native** angestrebt, um sowohl mobile als auch Desktop-Versionen mit einer einzigen Codebasis zu erstellen. Für die Backend-Entwicklung werden **Node.js** oder **Python** verwendet, da diese Technologien eine hohe Flexibilität bieten und gut mit Cloud-Lösungen harmonieren.

#### Sicherheit
Die Sicherheit der Nutzerdaten hat höchste Priorität. Alle Passwörter und sensiblen Daten werden verschlüsselt gespeichert:
- **Verschlüsselung**: AES-256-Algorithmus für die Datenverschlüsselung.
- **Passwortschutz**: Hashing mit Salt unter Verwendung von **bcrypt** oder **Argon2**, um Passwörter vor unbefugtem Zugriff zu schützen. Diese Algorithmen sind resistent gegen Angriffe wie Brute-Force- und Rainbow-Table-Angriffe.

#### Synchronisation
Der Passwortmanager soll Daten über verschiedene Geräte hinweg synchronisieren können, um eine nahtlose Benutzererfahrung zu bieten. Cloud-Storage-Lösungen wie **Google Cloud**, **AWS** oder **Azure** werden genutzt, wobei die Daten sowohl in der Cloud als auch während der Übertragung (durch SSL/TLS) verschlüsselt sind. Nutzer haben zudem die Möglichkeit, ihre Daten lokal zu speichern, falls sie keine Cloud-Synchronisation wünschen.

#### Benutzerfreundlichkeit
Die Benutzeroberfläche wird schlicht und intuitiv gestaltet, sodass Nutzer den Passwortmanager ohne große Lernkurve verwenden können. Es wird auf ein modernes, minimalistisches Design gesetzt, das auf mobilen Geräten und Desktops gut funktioniert. Wichtige Funktionen wie das Hinzufügen, Bearbeiten und Abrufen von Passwörtern sind einfach und schnell zugänglich. Eine Suchfunktion ermöglicht den Nutzern, Passwörter und Anmeldedaten schnell zu finden.

#### Datenschutz und Compliance
Der Passwortmanager wird alle relevanten Datenschutzbestimmungen einhalten, insbesondere die **DSGVO**. Nur die notwendigsten Daten werden gesammelt, und es erfolgt keine Weitergabe sensibler Informationen ohne ausdrückliche Zustimmung des Nutzers. Alle Nutzerdaten werden verschlüsselt gespeichert, und Nutzer haben die vollständige Kontrolle über ihre Daten, einschließlich der Möglichkeit, diese zu exportieren oder zu löschen. Zusätzlich wird eine **Zwei-Faktor-Authentifizierung (2FA)** implementiert, um die Sicherheit weiter zu erhöhen.


## Chancen 

### Marktanalyse
Unsere Online-Recherche ergab, dass es zwar viele Anbieter auf dem Markt gibt, die Passwortmanager zur Verfügung stellen. Dabei werden aber wesentliche Punkte oft nicht geklärt oder nicht ausreichend behandelt:

- **Datenschutz**: Viele Anbieter speichern Passwörter in der Cloud, wodurch Nutzer die Kontrolle über ihre Daten verlieren.
- **Sicherheit**: Oft fehlen transparente Sicherheitsmechanismen oder es gab bereits Sicherheitsprobleme (z. B. Datenlecks).
- **Speicherort der Daten**: Viele Nutzer möchten selbst entscheiden, wo ihre Passwörter gespeichert werden, doch die meisten Anbieter bieten keine lokale Lösung an.
- **Zugriffsmöglichkeiten von Drittanbietern**: Einige Lösungen ermöglichen Unternehmen oder Administratoren den Zugriff auf gespeicherte Passwörter, was für viele ein Risiko darstellt.

Diese Erkenntnisse werden durch unsere **Umfrage bestätigt**:

### Umfrageergebnisse
- **Altersgruppe 16–50 Jahre**:  
  - Passwortmanager sind bekannt, aber viele Nutzer haben **Sicherheitsbedenken**.
  - Cloud-Speicherung wird oft kritisch gesehen.
- **Altersgruppe über 50 Jahre**:  
  - Passwortmanager sind weniger bekannt.  
  - Viele nutzen stattdessen **einfache oder wiederverwendete Passwörter** mit minimaler Länge.
  - Es besteht eine hohe Skepsis gegenüber digitalen Passwortlösungen.

➡ **Fazit:** Es gibt eine klare Marktlücke für eine **einfache, sichere und lokal gespeicherte Lösung**.

### Umfrageergebnisse (20 Befragte Personen)

| Bar-Chart | Pie-Chart |
|------------------------|---------------------------|
| ![Survey BarChart](../Ressources/Survey_Data/Survey_BarChart.png) | ![Survey PieChart](../Ressources/Survey_Data/Survey_PieChart.png) |

### Zielgruppe erweitern
Die Umfrage zeigt, dass ältere Nutzer Passwortmanager seltener nutzen und eher einfache, wiederverwendete Passwörter bevorzugen.  
Um diese Zielgruppe zu erreichen, sind einfache Bedienbarkeit und Vertrauensbildung entscheidend.

## Risiken

### Sicherheitsaspekte
- **Sicherheitslücken**:  
  Ein potenzielles Risiko besteht darin, dass Sicherheitslücken auftreten oder sich Drittpersonen unerlaubt Zugriff verschaffen.  

- **Trust-Prinzip**:  
  Das Vertrauen der Nutzer darf nicht gebrochen werden, da dies den Erfolg des Systems gefährden würde.  

### Verfügbarkeit
- **Erreichbarkeit der Anwendung**:  
  - Da der Passwortmanager primär lokal arbeitet, muss sichergestellt werden, dass der Zugriff **jederzeit und ohne Internetverbindung** funktioniert.
  - Falls ein optionaler Server später integriert wird, ist eine **Backup-Lösung** nötig, um Datenverlust zu vermeiden.

### Technische Risiken: Benutzerfreundlichkeit & Nutzererfahrung

- **Zu viele Funktionen auf einmal:**  
  - Einige Passwortmanager bieten sehr viele Einstellungen und Extras, was für **unerfahrene Nutzer verwirrend** sein kann.  
  - **Beispiel:** Manche Programme haben komplizierte Menüs, bei denen man erst herausfinden muss, welche Funktionen wirklich wichtig sind.  

- **Schwierige Bedienung für Anfänger:**  
  - Manche Programme sind technisch gut, aber **nicht selbsterklärend**.  
  - Nutzer müssen oft **selbst herausfinden**, wie sie Passwörter speichern oder synchronisieren.  

- **Unübersichtliches oder veraltetes Design:**  
  - Manche Passwortmanager wirken **veraltet** und sind **nicht modern gestaltet**.  
  - Wenn eine Software **nicht ansprechend aussieht oder schwer zu bedienen ist**, nutzen viele sie **nicht gerne**.

###  Unsichere Betriebssysteme & Passwortsicherheit

#### Veraltete Betriebssysteme (z. B. Windows 7, alte Linux-Versionen oder OS Versionen)
- **Keine Sicherheitsupdates** → bekannte Schwachstellen bleiben offen.
- **Passwortmanager sind angreifbar**, wenn das OS bereits kompromittiert ist.

### Schlechte Implementierung von Sicherheitsmechanismen
- **Kein ASLR (Address Space Layout Randomization) oder DEP (Data Execution Prevention)**  
  → erleichtert Exploits gegen Passwortmanager.
- **Schwache Speicherisolation** → andere Programme könnten Passwörter auslesen.

#### Keylogger & Malware
- Wenn das Betriebssystem infiziert ist, kann ein **Keylogger** alle eingegebenen Passwörter mitlesen.
- **Trojaner** können die Datenbank des Passwortmanagers kopieren und offline angreifen.
- **Bildschirmaufnahme- oder Clipboard-Malware** kann automatisch eingefügte Passwörter abgreifen.

#### Manipulation der Hardware selbst
- **Unsichere Firmware** (z. B. infizierte UEFI- oder BIOS-Versionen) könnte einen Passwortmanager bereits vor dem Booten kompromittieren.
- **Schadcode in der Firmware** von SSDs oder USB-Sticks könnte Daten direkt ausspähen.

#### Fehlende Hardware-Sicherheitsmechanismen
- **Keine TPM-Unterstützung (Trusted Platform Module)** → Keine sichere Schlüsselverwaltung möglich.
- **Keine Härtung gegen physische Angriffe** (z. B. Cold Boot Attacken oder RAM-Scraping).



### Fazit
Das Projekt bietet eine **klare Chance**, sich von bestehenden Lösungen abzuheben, indem es sich auf **Datenschutz, einfache Bedienung und lokale Speicherung** fokussiert. Gleichzeitig müssen **technische Herausforderungen** (Benutzerfreundlichkeit, Sicherheitsmechanismen) sorgfältig berücksichtigt werden, um das Vertrauen der Nutzer zu gewinnen und eine nachhaltige Lösung bereitzustellen.

## Ziele

Die Ziele des Passwortmanagers sind es, den Benutzern zu ermöglichen, dass sie ihre Passwörter sicher speichern und verwalten können, ohne dass sie sich diese ständig merken müssen. Dabei werden die Sicherheit, Benutzerfreundlichkeit und der Komfort für die Nutzer maximiert, während gleichzeitig der Datenschutz und die Kontrolle seitens des Users gewährleistet wird. Außerdem soll der Schutz vor Cyberangriffen wie Phising und Passwortdiebstahl an oberster Stelle stehen. Dadurch ergeben sich folgende Punkte, die essentiell sind und bei der Entwicklung nicht vernachlässigt werden dürfen! 

### Sicherheit

- **Starke Verschlüsselung**: Alle gespeicherten Passwörter und sensible Daten werden mit einer starken Verschlüsselung (AES-256) geschützt. Auch im Falle eines Datenlecks oder Angriffs können wir versichern, dass Daten nicht so ohne Weiteres entschlüsselt werden können.
  
- **Zero-Knowledge-Prinzip**: Durch dieses Prinzip wird sichergestellt, dass der Anbieter keine Daten des Benutzers kennt und solche auch nicht gespeichert oder ausgelesen werden können.
  
- **Sicheres Hauptpasswort**: Das Hauptpasswort, mit dem sich der Benutzer auf dem Passwortmanager einloggt bzw. auf den Passwortspeicher zugreift, wird nicht auf dem Server gespeichert. Daher muss es ausreichend stark und einzigartig sein, um die Sicherheit des gesamten Systems zu gewährleisten. Durch strenge Richtlinien in der Passworterstellung wird sichergestellt, dass das Hauptpasswort stark genug ist.

### Benutzerfreundlichkeit

- **Einfache Handhabung**: Der Passwortmanager wird mit einer benutzerfreundlichen Oberfläche ausgestattet, die es einfach macht, Passwörter zu speichern, zu organisieren und abzurufen. Automatisches Ausfüllen von Anmeldeformularen und Passwortgenerierung wird zusätzlich integriert.
  
- **Automatische Synchronisierung**: Passwörter können auf allen Geräten des Benutzers synchronisiert werden (z. B. PC, Smartphone, Tablet), um den Zugriff zu erleichtern und ohne die Sicherheit zu gefährden.

### Komfort und Flexibilität

- **Passwortgenerierung**: Die Applikation ist in der Lage, starke und zufällig generierte Passwörter zu erstellen, die für jede Website oder Anwendung einzigartig sind. Dies verhindert das Wiederverwenden von Passwörtern.

### Transparenz und Kontrolle

- **Überwachung von Sicherheitslücken**: Es wird die Möglichkeit geben, regelmäßig zu überprüfen, ob gespeicherte Passwörter kompromittiert oder zu schwach sind. Die Benutzer werden in der Software benachrichtigt bzw. in Kenntnis gesetzt, wenn das erzeugte Passwort schon öfter verwendet wird oder es zu schwach ist. Dieser muss mit einer Aktion am Display bestätigen, dass er die Information gelesen und verstanden hat.
  
- **Datenhoheit**: Der Benutzer hat jederzeit die Kontrolle über seine gespeicherten Daten. Datenschutzrichtlinien werden transparent und nachvollziehbar sein, sodass der Benutzer verstehen kann, wie seine Daten verarbeitet und gespeichert werden.

