# **Travel Management System**

## **Project Overview**
The **Travel Management System** is a Java-based desktop application designed to simplify and manage travel-related tasks such as booking, planning, and managing trips. Built using Java Swing for the user interface, the application ensures a seamless and user-friendly experience for travelers and administrators alike.

---

## **Features**
- **User Authentication:**
  - Secure login and registration functionality for users.
- **Travel Package Management:**
  - Browse and manage travel packages.
  - Add, update, or delete packages as an admin.
- **Booking System:**
  - Easy booking process for users.
  - View and manage past bookings.
- **Payment Integration:**
  - Dummy payment gateway for booking confirmation.
- **Dashboard:**
  - Interactive dashboard with a summary of bookings and user activity.
- **Search and Filters:**
  - Quickly find travel packages based on destinations, price, or type.
- **Loading Screen:**
  - A visually appealing splash/loading screen during application startup.

---

## **Technologies Used**
- **Programming Language:** Java  
- **IDE:** NetBeans  
- **User Interface:** Java Swing  
- **Database:** MySQL  
- **Build Tool:** Apache Maven (if used)

---

## **Setup and Installation**
Follow these steps to run the project locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/travel-management-system.git
   cd travel-management-system

2.   **Setup the Database**:

Import the travel_management.sql file (included in the repository) into your MySQL server.
- String url = "jdbc:mysql://localhost:3306/travel_management";
- String username = "your-username";
- String password = "your-password";

3. **Build and Run the Project**:

- Open the project in NetBeans.
- Build the project using Clean and Build.
- Run the project.


  **folder structre**
-**src/**
-├── com.travelmanagement
-│   ├── About.java         # Entry point of the application
-│   ├── Login.java         # User login functionality
-│   ├── Dashboard.java     # Main dashboard UI
-│   ├── AddCustomer.java   # Add customer
-│   ├── ViewCustomer.java  # View customers
-│   ├── BookHotel.java     # Book hotels
-│   ├── CheckPackages.java # Check packages
-│   ├── Destinations.java  # Destinations
-│   ├── Payment.java       # Payment interface
-│   ├── Signup.java        # Signup features
-├── database/
-│   └── travel_management.sql  # Database schema and sample data
-**resources/**
-├── images/                   # Icons and UI images
  -├── docs/                     # Additional documentation and screenshots



