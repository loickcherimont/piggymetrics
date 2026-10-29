## DEV PREREQUISITES

**Java 8 is required.**

### 1. Install SDKMAN
Follow the [official installation guide](https://sdkman.io/install/).

### 2. Install Java 8

```bash
sdk install java 8.0.504.0+1-tem
```

If you have multiple Java versions installed, select Java 8:

```bash
sdk use java 8.0.504.0+1-tem
```

### 3. Verify Java

```bash
sdk current java
java -version
```

### 4. Build the project

From the project root:

```bash
mvn -U package
```