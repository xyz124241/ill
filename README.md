# ItemLock + Sense + Resourcepack

Dieses Repository enthält das ItemLock-Paper-Plugin und das Resourcepack mit den ACI-Kristallen und der Sense-Textur.

## GitHub-Upload
Alle Inhalte dieser ZIP direkt in das Hauptverzeichnis des GitHub-Repositorys hochladen. Dort müssen `pom.xml`, `src/`, `.github/` und `resourcepack/` direkt sichtbar sein.

Wichtig: `resourcepack/pack.mcmeta` muss existieren. Der GitHub-Workflow sucht die Datei auch dann, wenn `resourcepack/` versehentlich in einem zusätzlichen Unterordner liegt.

## Build
- Java 25
- Maven
- Paper 26.2 API

GitHub Actions baut `ItemLock.jar` und `ACI-Crystals-Sense-ResourcePack.zip` und veröffentlicht beide Dateien als Release.
