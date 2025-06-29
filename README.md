
![PLANIT Logo](logo.png)

# PLANIT - 2D Floor Planner

PLANIT is a Java-based 2D floor planning tool built with Swing. It allows users to visually design room layouts, manage furniture and fixtures, and save/load floor plan projects. The project is structured to be simple and modular, making it easy to extend or integrate.

This has been completed in fulfillment of the requirements for the CS F213 Object-Oriented Programming course.

---

## Features

- Add and customize rooms
- Place furniture and fixtures from a catalog
- Edit room and item properties via dialogs
- Save and load floor plans
- Clean and responsive Swing-based UI
- Structured with OOP principles for maintainability

---

## File Overview

### Core UI and Logic

- `Main.java` – Entry point of the application  
- `MainWindow.java` – Main window and canvas logic  
- `FloorPlanPanel.java` – Handles drawing and room placement  
- `menuBar.java` – Menu and toolbar controls  

### Room and Dialogs

- `Room.java` – Room model  
- `RoomEditDialog.java` – Edit existing room details  
- `AddRoomDialog.java` – Add a new room  
- `RoomDetailsDialog.java` – Shows room info  
- `RoomTableModel.java` – Table view of room data  

### Furniture and Fixtures

- `Furniture.java` – Model class for furniture items  
- `Fixtures.java` – Model class for fixtures  
- `FurnitureCatalogPanel.java` – Furniture selection UI  

### Utilities

- `FileHandler.java` – Load/save floor plans  
- `StartOnLaunchPage.java` / `newLaunchWindow.java` – Launch options and UI  

---

## Assets

- `logo.png`, `logotxt.png`, `biglogo.png` – Branding and UI images  
- `directions.png` – Reference image or guide  

---

## Running the Application

1. Clone the repository:
   ```bash
   git clone https://github.com/roh4n-code/Planit_2D-Floor-Planner.git
   cd Planit_2D-Floor-Planner
   ```

2. Compile the Java files:
   ```bash
   javac *.java
   ```

3. Launch the application:
   ```bash
   java Main
   ```

Requires Java 8 or higher.

---

## Future Work

- Export to image or PDF  
- Snap-to-grid feature  
- Furniture rotation/scaling  
- Improved catalog UI  
- Multi-floor support  

---
