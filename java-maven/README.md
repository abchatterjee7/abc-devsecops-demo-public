# How to run this java program

## Build the project
From the directory containing pom.xml, run:
```
mvn clean package -DskipTests
```

- This will,
    - Compile the code
    - Run tests (skipped here)
    - Create a shaded (fat) JAR

## Run the generated JAR

After build completes, run:
```
java -jar target/abc-devsecops-demo-1.0.0-SNAPSHOT.jar
```