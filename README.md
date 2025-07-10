# JAVA Project

This project is an Object-Oriented Guitar Manager implemented in Java. It demonstrates the use of object-oriented programming principles to manage guitar objects and provides a simple interface for interacting with guitar data. The system is designed for educational purposes, showcasing Java classes, encapsulation, and basic object manipulation.

## Prerequisites

- Java Development Kit (JDK) 8 or higher
- (Optional) An IDE like IntelliJ IDEA, Eclipse, NetBeans, or VS Code for easier code navigation

## Installation

1. **Clone the repository** (if not already downloaded):
   ```sh
   git clone <repository-url>
   cd Guitar-Management-main
   ```
2. **Compile the source code:**
   Use the following command from the project root to compile all Java files:
   ```sh
   javac -d out src/GUI/*.java
   ```
   This will compile the Java files and place the `.class` files in the `out` directory.

   Alternatively, if you use NetBeans, you can build the project using the provided `build.xml` (Ant build script).

## How to Run

After compiling, run the main class to start the Guitar Manager application. For example:

```sh
java -cp out GUI.Tester
```

Or, if you use NetBeans, simply run the project from the IDE.

## Project Structure

```
Guitar-Management-main/
├── src/
│   └── GUI/
│       ├── Guitar.java     # Guitar entity class
│       └── Tester.java    # Main entry point and demo logic
├── lib/                   # Libraries (if any)
├── build.xml              # Ant build script (for NetBeans)
├── manifest.mf            # Manifest file
├── README.md              # Project documentation
└── ... (other project and build files)
```

- The `GUI` package contains the main Java source files for the Guitar Manager application.
- The `lib` directory may contain additional libraries required for the project.
- The `build.xml` file is used for building the project with Apache Ant (commonly used in NetBeans projects).

## Learn More

- [Java Documentation](https://docs.oracle.com/javase/tutorial/)
- [How to Compile and Run Java](https://www.oracle.com/java/technologies/javase/codeconventions-137265.html)
- For questions or contributions, please open an issue or pull request.
