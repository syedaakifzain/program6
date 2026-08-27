# Java Program 6

A simple **Java Maven practice project** created to strengthen Java fundamentals and get familiar with a Maven-based project structure and CI-ready Java applications.

## 📌 About the Project

This repository contains a basic Java application created for practice and experimentation.

The project includes simple Java programs demonstrating:

* Java class and package structure
* `main()` method execution
* Console output using `System.out.println()`
* Maven project configuration
* Java 21 compilation setup
* Basic preparation for Continuous Integration (CI)

The project is built using **Apache Maven** and uses **Java 21** as the source and target version.

## 🛠️ Technologies Used

* **Java 21**
* **Apache Maven**
* **Git**
* **GitHub**

## 📂 Project Structure

```text
program6/
│
├── .idea/
│
├── src/
│   └── main/
│       └── java/
│           └── com/
│               └── example/
│                   ├── App.java
│                   └── Main.java
│
├── .gitignore
├── pom.xml
└── README.md
```

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/syedaakifzain/program6.git
```

### 2. Navigate to the Project

```bash
cd program6
```

### 3. Compile the Project

```bash
mvn compile
```

### 4. Run the Application

You can run the Java classes using your IDE or Java commands.

For example:

```bash
java -cp target/classes com.example.App
```

Expected output:

```text
hello ready to CI
```

## 📦 Maven Configuration

The project uses a `pom.xml` file to manage the Maven project configuration.

The current configuration includes:

* Group ID: `com.example`
* Artifact ID: `program6`
* Version: `1.0-SNAPSHOT`
* Java source version: `21`
* Java target version: `21`

## 🎯 Purpose

The main purpose of this repository is **practice and learning**.

It helps in understanding:

1. Java project organization
2. Maven project structure
3. Java compilation using Maven
4. Running Java applications
5. Git and GitHub repository management
6. Preparing a project for CI workflows

## 🔄 CI Practice

The `App.java` program contains a simple message:

```text
hello ready to CI
```

This indicates that the project can be used as a starting point for practicing **Continuous Integration**, where the Java project can later be automatically built and tested whenever changes are pushed to GitHub.

## 📚 Learning Outcomes

Through this project, you can practice:

* Java basics
* Maven commands
* Project structure
* Version control with Git
* GitHub repository management
* CI/CD fundamentals

## 👨‍💻 Author

