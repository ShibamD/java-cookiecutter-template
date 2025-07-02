# {{cookiecutter.service_name}}

{{cookiecutter.description}}

**Owner:** {{cookiecutter.owner}}

## Getting Started

### Prerequisites
- Java 17+
- Maven 3.6+

### Build and Run
```bash
# Compile
mvn compile

# Run
mvn exec:java -Dexec.mainClass="{{cookiecutter.java_package_name}}.App"

# Package
mvn package
```

### Development
```bash
# Clean build
mvn clean compile

# Run tests
mvn test
```
