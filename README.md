First test of Render to host java app

Using Maven.

## Compilation and Running

### Prerequisites

-   Java JDK 8 or higher
-   Maven 3.6 or higher

### Compile the Project

```bash
mvn compile
```

### Run the Application

```bash
mvn exec:java -Dexec.mainClass="com.example.App"
```

### Alternative: Package and Run

```bash
# Package the application into a JAR
mvn package

# Run the JAR file
java -cp target/classes com.example.App
```

### Run Tests

```bash
mvn test
```

### Clean Build

```bash
mvn clean compile
```
