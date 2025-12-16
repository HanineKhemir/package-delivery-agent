# Package Delivery Planning System

An AI-powered package delivery planning system that uses search algorithms to find optimal delivery routes in a grid-based environment with traffic constraints, stores, tunnels, and multiple destinations.

<img width="930" height="728" alt="image" src="https://github.com/user-attachments/assets/ccb896a7-47bd-4bb2-a858-2d2f0897c2eb" />


## 🎯 Overview

This project implements a delivery planning system that generates random grid environments with:
- **Stores (S)**: Locations where packages can be picked up
- **Destinations (D)**: Customer locations where packages need to be delivered
- **Tunnels (T)**: Fast-travel connections between two locations
- **Traffic costs**: Variable costs for moving between adjacent grid cells
- **Obstacles (X)**: Blocked paths with infinite cost


## 🔧 Prerequisites

- **Java 17** or higher
- **Apache Maven 3.6+**
- **Git** (for version control)

## 📥 Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/KhUssef/Package-Delivery.git
   cd Package-Delivery
   ```

2. **Verify Java version**:
   ```bash
   java --version
   ```
   Ensure you have Java 17 or higher installed.

3. **Verify Maven installation**:
   ```bash
   mvn --version
   ```

## 🚀 Usage

### Running with Maven (Recommended)

```bash
# Navigate to project directory
cd "Package-Delivery"

# Compile and run
mvn clean compile exec:java -Dexec.mainClass="ai.proj.Main"
```

### Running with Manual Compilation

```bash
# Navigate to source directory
cd "Package-Delivery/src/main/java/ai/proj/"

# Compile all Java files
javac *.java

# Run from java source root
cd "../../../.."
cd "src/main/java"
java ai.proj.Main
```

### Building a JAR

```bash
# Create JAR package
mvn clean package

# Run from compiled classes
java -cp target/classes ai.proj.Main
```



# package-delivery-agent
