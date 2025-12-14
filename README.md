# Java Playground

A showcase of Java mini-applications (Swing GUI).

![Java](https://img.shields.io/badge/Java-11+-orange)
![Swing](https://img.shields.io/badge/GUI-Swing-blue)

## 🎮 Run Online

[**▶️ Run on Replit**](https://replit.com/new/github/millenniumsingha/My_Codes_Java)

*Click "Import" and then "Run" to launch the applications instantly in your browser.*

## 📦 Applications Included

| App | Description |
|-----|-------------|
| **BattleShips** | Classic naval battle game vs computer AI |
| **Cipher Tool** | Caesar cipher encryption/decryption with live preview |
| **Trip Planner** | Budget calculator, timezone converter & distance calculator using Haversine formula |
| **Odd/Even** | Quick odds and evens finger game against computer |

## 🛠️ Technology

- **Java Swing** - Desktop GUI framework
- **Maven** - Build automation

## 🚀 Running Locally

### Prerequisites
- Java JDK 11+
- Maven

### Build & Run
```bash
# Build JAR
mvn clean package

# Run
java -jar target/JavaShowcase-1.0.jar
```

## 📁 Project Structure

```
java-showcase/
├── src/main/java/showcase/
│   ├── App.java                 # Main entry, sidebar navigation
│   └── panels/                  # Individual app modules
├── pom.xml                      # Maven build config
└── README.md
```

## 📝 Origin

These applications started as Java coursework exercises demonstrating:
- Control flow and game logic (BattleShips, Odd/Even)
- String manipulation and algorithms (Cipher)
- Mathematical computations (Trip Planner)

Reimplemented as a unified Swing application.

## 📄 License

GNU General Public License v2.
