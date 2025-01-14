# ✈️ Airport Management System


## 📋 Project Overview
This project is a **C-based airport management system** designed to efficiently manage various aspects of airport operations. It offers:
- Creation and management of airports
- Flight scheduling and tracking
- Airline data management

The project is built with modular programming principles, ensuring readability, efficiency, and scalability. It incorporates robust error handling and a user-friendly menu interface to deliver a seamless experience.

## 📄 Project Description
The system simulates an airport management environment with functionalities such as:
- Managing airports and their details
- Scheduling flights and associating them with specific airports
- Handling airline data, including the number of flights and company information

Through an intuitive menu-driven interface, users can:
- Add new airports
- Add flights and link them to airports
- Query flight and airport details

Additionally, the system includes error handling for:
- Duplicate airport or flight entries
- Invalid user inputs

## ⚙️ Program Structure
The project is organized into modular components, with each module focusing on specific functionalities:
- **`Airport` Module**: Manages the creation and lookup of airport entities.
- **`Flight` Module**: Handles flight scheduling, queries, and associations with airports.
- **`Airline` Module**: Tracks airline details and their associated flights.
- **`Main` Module**: Serves as the entry point, offering a menu-driven user interface.
- **`Utility Module`**: Provides helper functions for data validation and manipulation.

## 🛠️ Programming Principles
This project adheres to key programming principles to enhance maintainability and scalability:
- **Modular Design**: Each component (e.g., `Airport`, `Flight`, `Airline`) is independent and reusable.
- **Error Handling**: Ensures a smooth user experience with custom error messages and recovery options.
- **Efficiency**: Employs optimized data structures and algorithms for reliable and fast operations.

## 🏦 Key Features and Functions

### 🔑 Core Features
- **Airport Management**:
  - `isSameAirport`: Determines if two airports are the same.
  - `isAirportName`: Verifies if a given name matches an airport's name.
  - `addAirport`: Adds a new airport to the system.
  - `findAirportByName`: Searches for an airport by its name.

- **Flight Management**:
  - `isFlightFromSourceName`: Checks if a flight departs from a specific source airport.
  - `isFlightToDestName`: Verifies if a flight arrives at a specific destination airport.
  - `isPlaneCodeInFlight`: Determines if a specific plane code is used in a flight.
  - `isPlaneTypeInFlight`: Checks if a specific plane type is used in a flight.
  - `addFlight`: Adds a new flight to the system.

- **Airline Management**:
  - Stores and manages data about the airline, including the company name, the number of flights, and an array of flight details.
  - Includes utility functions for optimizing airline operations.

### 🔔 Custom Error Handling
- **Duplicate Entries**: Prevents adding duplicate airports or flights.
- **Invalid Inputs**: Prompts users to re-enter valid data.

## 🚀 Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/EladRazon/AirportManagement.git

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

## 🚀 Usage Instructions

### 🖥️ User Interface
The system provides an interactive menu with the following options:

1. **✈️ Add a New Airport**: Create and store a new airport.
2. **🛫 Add a Flight**: Schedule a flight for a specific airport.
3. **📋 View Airports**: Display a list of all airports.
4. **🛬 View Flights**: Query and display flight details.
5. **🔍 Search Airports**: Find an airport by its name.
6. **❌ Exit**: Safely exit the program.

## 🔍 Input Validation
The system ensures the correctness of all user inputs:
- **String Inputs**: Names of airports must follow the defined format.
- **Numeric Inputs**: Flight numbers and other numeric data must be within valid ranges.
- **Error Recovery**: Invalid inputs trigger detailed error messages and allow for re-entry.

## 📈 Future Expandability
This system is designed with scalability in mind, allowing for:
- Adding new features, such as real-time flight tracking.
- Extending existing modules without altering the core structure.

## 🙌 Acknowledgments
This project draws inspiration from real-world airport management systems.
