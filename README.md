PACMAN
A simple Pac-Man clone made in Java Swing.

FEATURES
• Move using arrow keys
• Track score and lives
• Ghost enemies with simple AI
• Collect pellets and power items
• Classic retro style

REQUIREMENTS
• Java 8 or newer
• Works on Windows, macOS, or Linux

PROJECT STRUCTURE
Pacman/
├─ src/
│ ├─ Main.java — main entry point that opens the game window
│ ├─ Pacman.java — handles drawing, movement, and game logic
│ └─ images/ — game graphics and sprites
│ • wall.png
│ • pacmanUp.png
│ • pacmanDown.png
│ • pacmanLeft.png
│ • pacmanRight.png
│ • redGhost.png
│ • blueGhost.png
│ • pinkGhost.png
│ • orangeGhost.png
│ • scaredGhost.png
│ • powerFood.png
│ • cherry.png
│ • cherry2.png
└─ .gitignore — optional ignore file

HOW TO RUN

Option 1 — IntelliJ IDEA

Open the “Pacman” folder in IntelliJ.

Right-click the “src” folder → Mark Directory as → Sources Root.

Run “Main.java.”

Option 2 — Command Line

Compile: javac -d out src/Main.java src/Pacman.java

Run (Mac/Linux): java -cp out:src Main

Run (Windows): java -cp out;src Main

If images don’t appear, make sure the “src” folder is included in the classpath.

CONTROLS
↑ Move Up
↓ Move Down
← Move Left
→ Move Right

NOTES
• Keep the “images” folder in the same layout for the game to work.
• To create a runnable JAR:

Make an “out/images” folder

Copy everything from “src/images” to “out/images”

Run: jar cfe pacman.jar Main -C out .

Then run: java -jar pacman.jar

SAMPLE .GITIGNORE
.idea/
*.iml
out/
bin/
target/
.DS_Store
Thumbs.db

LICENSE
Add your preferred license (MIT, Apache 2.0, etc.).
