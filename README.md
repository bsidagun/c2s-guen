# Carbon to Silicon

**Architekturprojekt · Hochschule Mainz · WS 2026/27**  

## 1. Projektidee und Konzept

„Carbon to Silicon“ ist ein interaktiver Gebäude-Konfigurator, mit dem ein architektonischer Entwurf parametrisch entwickelt und in einer 3D-Umgebung visualisiert werden kann.

Ziel des Projekts ist es, verschiedene Gebäudeeigenschaften digital zu verändern und die räumlichen sowie gestalterischen Auswirkungen direkt am Gebäudemodell nachvollziehen zu können.

Das Gebäude wird mithilfe von **Three.js** generiert. Die Konfiguration erfolgt über eine Benutzeroberfläche mit verschiedenen Eingabefeldern, Slidern und Auswahlmöglichkeiten.

## 2. Funktionen des Konfigurators

Folgende Parameter können angepasst werden:

### Gebäude und Geometrie
- Grundstücksbreite und Grundstückstiefe
- Gebäudehöhe und Geschossanzahl
- Aufteilung der unterschiedlichen Nutzungsflächen

### Fassade und Gestaltung
- Fensterflächenanteil zur Veränderung der Fenstergröße bzw. des Verglasungsanteils
- Balkone und Balkontiefe
- Tragwerksmaterial
- Tragwerksraster bzw. Rastergröße

### Nutzungsbereiche
- Wohnbereiche
- Private Bereiche
- Gemeinschaftsbereiche
- Nebenräume
- Verkehrsflächen

### Umgebung
- Darstellung der Nachbargebäude und des städtebaulichen Kontexts
- Grundstück und bebaubares Volumen
- Anpassung von Sonnenstand und Tageszeit

## 3. Technische Umsetzung

Das Projekt basiert auf folgenden Technologien:

- HTML
- CSS
- JavaScript
- Three.js
- OrbitControls

Three.js wird zur Erstellung und Darstellung des Gebäudemodells verwendet. Die Geometrie wird anhand der eingegebenen Parameter generiert und kann interaktiv aus verschiedenen Perspektiven betrachtet werden.

## 4. Ansichten und aktueller Entwicklungsstand

Die Anwendung enthält eine 3D-Modellansicht sowie eine vorgesehene 2D-Grundrissansicht.

**Hinweis zum Entwicklungsstand:** Die 2D-Grundrissfunktion ist derzeit noch nicht vollständig funktionsfähig. Der Schwerpunkt der aktuellen Umsetzung liegt auf der 3D-Konfiguration und der Anpassung der Gebäudeparameter.

## 5. Testanleitung

1. Die Live-Version über den GitHub-Pages-Link öffnen.
2. Warten, bis die Anwendung geladen ist.
3. Grundstücksbreite, Grundstückstiefe und Gebäudehöhe verändern.
4. Die Fensterflächenanteile und Balkoneinstellungen ausprobieren.
5. Unterschiedliche Materialien und Tragwerksraster auswählen.
6. Die verschiedenen Nutzungsflächen anpassen.
7. Das 3D-Modell mit der Maus drehen und aus unterschiedlichen Perspektiven betrachten.
8. Die 2D-Grundrissansicht ausprobieren. Diese Funktion ist aktuell noch eingeschränkt.

Für die Darstellung ist eine Internetverbindung erforderlich, da Three.js über eine externe Bibliothek eingebunden wird.

## 6. Projektlinks

**GitHub Repository:**  
https://github.com/bsidagun/c2s-guen

**Live-Version (GitHub Pages):**  
https://bsidagun.github.io/c2s-guen/

**HTML-Datei:**  
https://github.com/bsidagun/c2s-guen/blob/main/index.html

---

**Projektname:** Carbon to Silicon  
**Studiengang:** Architektur  
**Hochschule:** Hochschule Mainz
