# ✈️ Airport Management

## Overview

This project is an **Airport Management System** implemented in **C**, designed to efficiently manage data related to airports, airlines, and flights. The system provides functionalities such as adding airports, managing flights, and handling airline data, with a focus on modular code, data processing, and user-friendly operations. 

Key entities in the system include `Airport`, `Flight`, and `Airline`, alongside an `Airport Manager` that oversees and coordinates operations between them.

---

## Features

### 🏢 **Airport Management**
- `isSameAirport`: Determines if two airports are the same.
- `isAirportName`: Verifies if a given name matches an airport's name.
- `addAirport`: Adds a new airport to the system.
- `findAirportByName`: Searches for an airport by its name.

### ✈️ **Flight Management**
- `isFlightFromSourceName`: Checks if a flight departs from a specific source airport.
- `isFlightToDestName`: Verifies if a flight arrives at a specific destination airport.
- `isPlaneCodeInFlight`: Determines if a specific plane code is used in a flight.
- `isPlaneTypeInFlight`: Checks if a specific plane type is used in a flight.
- `addFlight`: Adds a new flight to the system.
- `doPrintFlightsWithPlaneCode`: Prints flights that use a specific plane code.
- `doPrintFlightsWithPlaneType`: Prints flights that use a specific plane type.
- `doCountFlightsFromName`: Counts the number of flights departing from a specific airport.

### 🏢 **Airline Management**
- Stores and manages data about the airline, including the company name, the number of flights, and an array of flight details.
- Includes utility functions for optimizing airline operations.

---

## Getting Started

### Prerequisites

To compile and run the project, you'll need:
- **C Compiler** (e.g., GCC or Clang).
- **An IDE or text editor** (e.g., Visual Studio, VSCode, or CLion).

---

### Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/EladRazon/AirportManagement.git
    ```

2. **Navigate to the Project Directory**:
    ```bash
    cd AirportManagement
    ```

3. **Compile the Code**:
    ```bash
    gcc -o airport_management main.c *.c
    ```

4. **Run the Program**:
    ```bash
    ./airport_management
    ```

---

## Usage

Once the application is running, you can:
- Add and manage airports.
- Schedule and manage flights.
- Query and update details about flights and airports using the provided functions.

The system allows efficient data management and modular operations, making it easy to scale or modify as needed.

---

## Project Structure

- `Airport.c` / `Airport.h`: Defines the `Airport` entity and its related operations.
- `Flight.c` / `Flight.h`: Manages flight-related data and operations.
- `AirportManager.c` / `AirportManager.h`: Handles overall airport management and interactions.
- `Airline.c` / `Airline.h`: Manages airline details, flights, and associated operations.
- `General.c` / `General.h`: Utility functions and general system operations.
- `main.c`: Entry point of the program.
- `README.md`: This file.
- `.gitignore`: Specifies files and directories to be ignored by Git.

---

## Acknowledgments

- ✈️ Inspired by real-world airport and airline management systems.
- 🙌 Special thanks to resources and contributors from the programming community.
