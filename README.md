# Coconut Grove Sailing Club Fleet Management

A Java project that models boats and organizes the core logic for managing a sailing club fleet. The repository separates boat information, boat categories, and fleet-management behavior into focused Java files so the code is easier to read, maintain, and extend.

## Project Overview

This project demonstrates object-oriented programming through a small fleet-management system for the Coconut Grove Sailing Club.

The code is organized around three main responsibilities:

- representing an individual boat
- defining boat types
- coordinating fleet-management operations

## Repository Structure

CoconutGroveSailingClub
├── Analysis and Design
├── Boat.java
├── BoatType.java
└── FleetManagement.java

### `Boat.java`

Defines the `Boat` object used by the application. This class represents a boat and keeps the information and behavior associated with that boat together.

### `BoatType.java`

Defines the boat-type options used by the program. Keeping these values in one place makes the code more consistent and avoids repeating category names throughout the application.

### `FleetManagement.java`

Contains the main fleet-management logic and coordinates how the application works with boat records.

### `Analysis and Design`

Documents the planning and design behind the project.

## How the Code Is Organized

The project uses a simple object-oriented structure:

1. A boat is represented as a `Boat` object.
2. Each boat can use a value defined in `BoatType`.
3. `FleetManagement` works with the boat data and controls the application flow.

## Skills Demonstrated

- Java programming
- Object-oriented design
- Classes and objects
- Enumerated types
- Separation of responsibilities
- Code organization and maintainability

## Running the Project

### Prerequisites

- Java Development Kit (JDK)
- A terminal or Java-compatible IDE, such as IntelliJ IDEA, Eclipse, or Visual Studio Code

### Compile

From the repository folder, run:

```bash
javac *.java
```

### Run

```bash
java FleetManagement
```

## Possible Future Improvements

- Add input validation and clearer error messages
- Save fleet data between sessions
- Add automated tests
- Add search, filtering, and reporting features
- Build a graphical or web-based user interface

## Why I Built This Project

I created this project to apply Java and object-oriented programming concepts to a practical scenario. It shows how a real-world subject can be translated into organized classes, shared data types, and management logic.

## Author

**Juliana Geyer-Kim**

