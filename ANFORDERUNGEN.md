# Anforderungen - Game of Life

## Projektbeschreibung
Implementierung von Conways Game of Life - ein zellulärer Automat, der auf einem zweidimensionalen Gitter simuliert wird.

## Funktionale Anforderungen

### 1. Gitter und Zellen
- [ ] Zweidimensionales Gitter zur Darstellung der Zellen
- [ ] Zellen können zwei Zustände haben: lebendig oder tot
- [ ] Konfigurierbare Größe des Gitters (z.B. 50x50, 100x100)

### 2. Spielregeln (Conway's Game of Life)
- [ ] Jede lebende Zelle mit 2-3 lebenden Nachbarn bleibt am Leben
- [ ] Jede lebende Zelle mit weniger als 2 oder mehr als 3 Nachbarn stirbt
- [ ] Jede tote Zelle mit genau 3 lebenden Nachbarn wird lebendig
- [ ] Nachbarschaften berücksichtigen die 8 umliegenden Zellen

### 3. Simulation
- [ ] Generationen / Schritte durchlaufen
- [ ] Alle Zellen werden synchron pro Generation aktualisiert
- [ ] Kontinuierliche Simulation mit konfigurierbarem Tempo

### 4. Benutzerinteraktion
- [ ] Start/Pause/Reset Funktionen für die Simulation
- [ ] Tempo der Simulation einstellbar
- [ ] Möglichkeit, Zellen manuell zu setzen/löschen vor der Simulation
- [ ] Anzeige der aktuellen Generationsnummer

### 5. Visualisierung
- [ ] Grafische Darstellung des Gitters in HTML/Canvas
- [ ] Unterscheidung zwischen lebenden und toten Zellen (z.B. durch Farben)
- [ ] Responsive Layout für verschiedene Bildschirmgrößen

## Technische Anforderungen

### Frontend (HTML/JavaScript)
- [ ] HTML-Struktur für UI (Buttons, Eingabefelder, Canvas/Grid)
- [ ] CSS-Styling für ansprechendes Design
- [ ] JavaScript für Game-Logik und Interaktionen
- [ ] Rendering-Optimierung für flüssige Animation

### Code-Qualität
- [ ] Sauberer, wartbarer Code mit Kommentaren
- [ ] Modularisierte Funktionen
- [ ] Error Handling

## Nice-to-Have Features
- [ ] Vordefinierte Muster (Glider, Blinker, Block, etc.)
- [ ] Speichern und Laden von Konfigurationen
- [ ] Zoom-Funktionalität
- [ ] Statistiken (Anzahl lebender Zellen, Generationen pro Sekunde)
- [ ] Dunkler Modus

## Akzeptanzkriterien
- [ ] Simulation funktioniert gemäß Conway's Regeln
- [ ] UI ist intuitiv bedienbar
- [ ] Performance ist zufriedenstellend auch bei größeren Gittern
- [ ] Code ist dokumentiert und wartbar
