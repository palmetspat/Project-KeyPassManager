# Systemkonzept

Unser Konzept basiert darauf, einen Passwortmanager zu entwickeln, der Passwörter lokal oder auf einem sicheren Server speichert. Die Anwendung wird modular aufgebaut, um Flexibilität und zukünftige Erweiterbarkeit zu gewährleisten:

- **Speicherung**: Passwörter werden sicher verschlüsselt gespeichert, entweder lokal auf dem Gerät oder serverbasiert.
- **Plattformen**:
  - Desktop-Anwendung für Windows (weitere Plattformen wie Linux und macOS optional in der Zukunft).
  - Erhältlich auch als Docker Compose-File.
  - Web-Anwendung für den Zugriff über den Browser.
- **Kernfunktionen**:
  - Hinzufügen, Bearbeiten und Löschen von Passwörtern.
  - Sichere Suche innerhalb der gespeicherten Passwörter.
  - Import und Export von Passwörtern im verschlüsselten Format.
- **Sicherheit**:
  - End-to-End-Verschlüsselung bei Datenübertragungen zwischen Geräten.
  - Daten werden niemals unverschlüsselt zwischengespeichert oder weitergegeben.
- **Erweiterbarkeit**:
  - Modularer Aufbau ermöglicht die zukünftige Integration von Funktionen wie Synchronisation, Teamzugriff oder mobilen Apps.
