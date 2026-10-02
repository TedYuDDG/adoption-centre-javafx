# Adoption Centre JavaFX

A desktop pet adoption management application built with **Java, JavaFX, FXML and MVC architecture**.

This repository showcases my implementation for an **individual university programming assignment**. The assignment used a provided scaffold, and I implemented the application behaviour and GUI within that structure.

## Features

### Customer
- Log in using customer name and email
- View animals currently available for adoption
- Adopt an animal
- Enforce adoption limits and validation rules
- View customer details and adopted animals
- Receive clear error messages for invalid operations

### Manager
- Log in using a manager ID
- View all animals in a JavaFX table
- Filter animals by **Cat**, **Dog** and **Rabbit**
- Add animals
- Remove animals when permitted
- View registered users
- See adoption status for each animal

## Technical Highlights

- **JavaFX** desktop GUI
- **FXML** view definitions
- **MVC-style architecture**
- Object-oriented domain model for animals and users
- JavaFX observable properties and collections
- Form validation and custom exception handling
- Role-based customer and manager workflows
- CSS-based interface styling

## Project Structure

```text
.
├── Prog2AdoptionCentreApp.java
├── controller/
│   ├── LoginController.java
│   ├── CustomerDashboardController.java
│   ├── ManagerDashboardController.java
│   ├── AddAnimalController.java
│   ├── DetailsController.java
│   ├── UserListController.java
│   └── ErrorController.java
├── model/
│   ├── Animals/
│   ├── Users/
│   ├── Application/
│   └── Exceptions/
├── view/
│   ├── LoginView.fxml
│   ├── CustomerDashboard.fxml
│   ├── ManagerDashboard.fxml
│   ├── AddAnimalView.fxml
│   ├── DetailsView.fxml
│   ├── UserListView.fxml
│   ├── ErrorView.fxml
│   └── style.css
├── image/
└── au/edu/uts/ap/javafx/
```

## Concepts Demonstrated

- Object-oriented programming
- MVC
- Java GUI development
- Tables and lists
- Event handling
- Inheritance and polymorphism
- Validation and exception handling
- Separation of application logic from views

## About the Assignment

The project was created for UTS subject **48024 Programming**. The assignment focused on **OO design, GUIs, MVC, tables and lists**.

## About Me

I am completing a **Bachelor of Information Technology at the University of Technology Sydney (UTS)**, majoring in **Software Development and Cybersecurity**.

Expected graduation: **May 2027**
