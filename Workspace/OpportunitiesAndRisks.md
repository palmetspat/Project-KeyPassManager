# Chancen und Risiken des Projektes

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

### Finanzielle und technische Rahmenbedingungen

#### Software und Entwicklungstools
- **IDE (Integrated Development Environment)**: Kostenlose Versionen wie Visual Studio Code oder JetBrains IntelliJ IDEA können genutzt werden. Falls erweiterte Funktionen benötigt werden, können kostenpflichtige Versionen in Betracht gezogen werden.
  - **Kosten**: 0 € – 500 € (für professionelle Lizenzen, falls erforderlich)
  
- **Bibliotheken und Frameworks**: Open-Source-Tools wie OpenSSL für die Verschlüsselung oder andere bestehende Authentifizierungsframeworks können verwendet werden.
  - **Kosten**: 0 € – 500 € (für spezielle kommerzielle Lizenzen oder API-Nutzung)
  
- **Versionierung und Codeverwaltung**: Plattformen wie GitHub oder GitLab bieten kostenlose Repositories an. Für private Repositories fallen ggf. Kosten an, aber dies kann minimiert werden.
  - **Kosten**: 0 € – 100 € pro Jahr (wenn private Repositories benötigt werden)

#### Server und Infrastruktur
- **Web-Hosting und Datenbanken**: Wenn ein Cloud-Backend benötigt wird, können Cloud-Dienstleister wie AWS, Azure oder Google Cloud genutzt werden. Diese Anbieter bieten oft ein gewisses Freikontingent für kleine Anwendungen.
  - **Kosten**: 0 € – 500 € pro Jahr (je nach Nutzung)
  
- **Datenverschlüsselung und Sicherung**: Open-Source-Tools zur sicheren Datenhaltung und Backup-Systeme (z. B. verschlüsselte Datenbanken oder Dateispeicherung).
  - **Kosten**: 0 € – 200 € pro Jahr

#### Marketing und Branding
- **Website und Domain**: Eine einfache Website für die Vorstellung des Passwort Managers und für Downloads. Kosten für Domain und Hosting.
  - **Kosten**: 10 € – 100 € pro Jahr (je nach Anbieter)
  
- **Social Media und Werbeanzeigen**: Für die Promotion des Passwort Managers können Social Media Marketing oder bezahlte Werbeanzeigen auf Plattformen wie Google Ads oder Facebook genutzt werden.
  - **Kosten**: 100 € – 500 € (initiales Marketingbudget)
  
- **App Store Gebühren**: Wenn der Passwort Manager als mobile App angeboten wird, fallen App Store Gebühren an (Apple Developer Program oder Android).
  - **Kosten**: 100 € – 400 € einmalig (je nach Plattform)

#### Sonstige Kosten
- **Rechtliche Beratung**: Rechtliche Aspekte wie Datenschutzbestimmungen (z. B. DSGVO) oder AGBs müssen berücksichtigt werden. Eine eventuelle Beratung durch einen Anwalt könnte notwendig sein.
  - **Kosten**: 200 € – 1.000 € einmalig (je nach Bedarf)

#### Zusammenfassung des Budgets
- **Minimal (nur für Entwicklung und kostenlose Tools)**: 0 € – 500 €
- **Moderate Investition (inkl. Marketing und kleinen Lizenzgebühren)**: 500 € – 2.500 €
- **Höhere Investition (mit Servern, professionellen Tools und umfangreicher Werbung)**: 2.500 € – 5.000 €

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

### Fazit
Das Projekt bietet eine **klare Chance**, sich von bestehenden Lösungen abzuheben, indem es sich auf **Datenschutz, einfache Bedienung und lokale Speicherung** fokussiert. Gleichzeitig müssen **technische Herausforderungen** (Benutzerfreundlichkeit, Sicherheitsmechanismen) sorgfältig berücksichtigt werden, um das Vertrauen der Nutzer zu gewinnen und eine nachhaltige Lösung bereitzustellen.
