# gmail-cleaner
Java-based Gmail inbox cleaner using MVC architecture


# Gmail Cleaner 🧹📬

Java-based console application for cleaning up your Gmail inbox using the Gmail API. Built with a clean MVC architecture and designed for extensibility and clarity.

## 🚀 Features

- Authenticate with Gmail via OAuth 2.0
- List and delete emails based on custom filters
- Console-based user interface
- Modular MVC structure (Model-View-Controller)
- Input validation and error handling
- Easily extendable for new features

## 🧠 Architecture

This project follows the MVC pattern:

- **Model**: `Email.java` — represents email data  
- **View**: `ConsoleView.java` — handles user interaction  
- **Controller**: `GmailController.java` — coordinates logic  
- **Service**: `GmailService.java` — communicates with Gmail API

## 📦 Technologies

- Java 17+
- Maven
- Gmail API
- OAuth 2.0
- IntelliJ IDEA (recommended)

## 🛠️ Setup

1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/gmail-cleaner.git
   cd gmail-cleaner

2. Set up Gmail API credentials
- Create a project in Google Cloud Console
- Enable Gmail API
- Download credentials.json and place it in the root directory
  
3. Build the project
mvn clean install

4. Run the application
java -jar target/gmail-cleaner.jar

