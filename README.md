# 🧬 Game of Life

Eine interaktive Browser-Implementierung von Conways Game of Life - einem klassischen Zellularautomaten.

## 🎮 Features

- ✨ Interaktive Canvas-basierte Visualisierung
- 🎯 Klicke auf Zellen, um sie zum Leben zu erwecken oder zu töten
- 🖱️ Fahre mit der Maus über Zellen, um sie interaktiv zu bearbeiten (Optional: Shift-Taste gedrückt halten)
- ⚙️ Regelbare Geschwindigkeit der Simulation
- 📊 Live-Statistiken (Generation & lebende Zellen)
- 🔄 Verschiedene Gittergrößen (20x20 bis 100x100)
- 📱 Responsive Design für mobile Geräte
- ⏸️ Start/Pause/Reset Funktionalität

## 🎯 Wie es funktioniert

Das Game of Life basiert auf vier einfachen Regeln:

1. **Überbevölkerung**: Eine lebende Zelle mit mehr als 3 lebenden Nachbarn stirbt
2. **Einsamkeit**: Eine lebende Zelle mit weniger als 2 lebenden Nachbarn stirbt
3. **Überleben**: Eine lebende Zelle mit 2 oder 3 lebenden Nachbarn bleibt am Leben
4. **Geburt**: Eine tote Zelle mit genau 3 lebenden Nachbarn wird lebendig

## 🚀 Verwendung

1. **Öffne** `index.html` in deinem Browser
2. **Klicke** auf Zellen, um sie zu aktivieren/deaktivieren
3. **Fahre mit der Maus** über Zellen (mit gedrückter Shift-Taste), um diese interaktiv zu bearbeiten
4. **Starte** die Simulation mit dem "Start"-Button
5. **Beobachte**, wie Zellen basierend auf den Regeln entstehen und vergehen
6. **Passe** die Geschwindigkeit und Gittersize an

## 📁 Dateistruktur

```
GameOfLife/
├── index.html       # HTML-Struktur
├── style.css        # Styling und Responsiveness
├── gameOfLife.js    # Game-Logik und UI-Handling
└── README.md        # Dokumentation
```

## 🛠️ Technologie-Stack

- **HTML5** - Struktur
- **CSS3** - Styling mit Gradients und Flexbox
- **Vanilla JavaScript** - Komplette Game-Logik (keine Dependencies!)
- **Canvas API** - Rendering

## 💡 Beispiel Muster

Probiere diese klassischen Muster aus:

- **Blinker** (Period 2): Drei Zellen in einer Reihe
- **Block** (Still Life): 2x2 Quadrat
- **Glider** (Spaceship): Diagonales Bewegungsmuster
- **Beacon** (Oscillator): Vier Zellen in einem Quadrat mit Lücke

## 📝 Lizenz

Frei verwendbar für Bildungs- und Demonstrationszwecke.

Viel Spaß beim Ausprobieren! 🎉
