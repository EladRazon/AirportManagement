# ✈️ Airport Management

## Overview

This project is an **Airport Management System** implemented in **C**, designed to manage data related to airports, flights, and airlines. The system provides functionalities such as managing airports, scheduling flights, and handling airline data efficiently. Key entities include `Airport`, `Flight`, and `Airline`, with an `Airport Manager` overseeing all operations.

The project emphasizes a modular code structure, efficient data handling, and a user-friendly interface for seamless operations.

---

## Features

### 🏢 **Airport Management**
- `isSameAirport`: Check if two airports are the same.
- `isAirportName`: Verify if a given name matches an airport's name.
- `addAirport`: Add a new airport to the system.
- `findAirportByName`: Locate an airport by its name.

### ✈️ **Flight Management**
- `isFlightFromSourceName`: Check if a flight departs from a specific source airport.
- `isFlightToDestName`: Verify if a flight arrives at a specific destination airport.
- `isPlaneCodeInFlight`: Determine if a specific plane code is used in a flight.
- `isPlaneTypeInFlight`: Check if a specific plane type is used in a flight.
- `addFlight`: Add a new flight to the system.
- `doPrintFlightsWithPlaneCode`: Print flights that use a specific plane code.
- `doPrintFlightsWithPlaneType`: Print flights that use a specific plane type.
- `doCountFlightsFromName`: Count the number of flights departing from a specific airport.

### 🏢 **Airline Management**
- Manage airline data, including company name, number of flights, and an array of flights.
- Additional functions optimize airline operations.

---

## Getting Started

### Prerequisites

- **C Compiler** (e.g., GCC or Clang).
- **An IDE or text editor** (e.g., Visual Studio, VSCode, or Clion).

### Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/YourUsername/Airport_Management.git
    ```

2. **Navigate to the Project Directory**:
    ```bash
    cd Airport_Management
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
- Add and manage airport data.
- Schedule and manage flights.
- Query and update flight and airport details using the provided functions.

---

## Project Structure

- `Airport.c` / `Airport.h`: Defines the Airport entity and its operations.
- `Flight.c` / `Flight.h`: Manages flight-related data and operations.
- `AirportManager.c` / `AirportManager.h`: Handles the overall management of airports.
- `Airline.c` / `Airline.h`: Represents the airline with flights and company details.
- `General.c` / `General.h`: Utility functions and general system operations.
- `README.md`: This file.
- `.gitignore`: Specifies files and directories to be ignored by Git.

---

## Acknowledgments

- ✈️ Inspired by real-world airport and airline management systems.
- 🙌 Thanks to contributors and resources from the programming community.
