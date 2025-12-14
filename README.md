# Java Playground

A showcase of Java mini-applications (Swing GUI).

![Java](https://img.shields.io/badge/Java-11+-orange)
![Swing](https://img.shields.io/badge/GUI-Swing-blue)

## 🎮 Run Online

[**▶️ Run on Replit**](https://replit.com/new/github/millenniumsingha/millennium_java_suite)

*Instructions:*
1. Click the link above and select **"Import"**.
2. Once the editor loads, click the big green **"Run"** button.
3. **Important:** If you see "No external ports", check the tabs above the preview window and switch to **"VNC"** to see the GUI.

## 📦 Applications Included

## 📦 Applications Included

### 1. Trip Planner
*Budget calculator, timezone converter & distance calculator using Haversine formula.*
![Trip Planner](screenshots/tripplanner.png)

### 2. BattleShips
*Classic naval battle game vs computer AI.*
![BattleShips](screenshots/battleships.png)

### 3. Cipher Tool
*Caesar cipher encryption/decryption with live preview.*
![Cipher Tool](screenshots/cipher.png)

### 4. Odd/Even
*Quick odds and evens finger game against computer.*
![Odd/Even](screenshots/oddeven.png)

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
