# Machine-Ordering-App
The Machine Ordering Application is a low-code business application developed using Microsoft Power Apps to digitize and simplify the process of ordering industrial machines. The app allows users to browse machines, place orders, track order status, and manage machine-related data efficiently. 

🎯 Project Objectives

To automate the traditional manual machine ordering process

To provide a user-friendly interface for placing and managing orders

To demonstrate the use of low-code development using Power Apps

To integrate data storage and business logic efficiently

To improve accuracy, speed, and transparency in machine procurement

🧠 Problem Statement

Many organizations still rely on manual or spreadsheet-based systems for machine ordering, which leads to:

Data inconsistency

Human errors

Lack of real-time tracking

Time-consuming approval processes

This project aims to solve these issues by creating a centralized, digital ordering system.

🛠️ Tech Stack Used
Technology	Purpose
Microsoft Power Apps	Frontend app development
Power Fx	Business logic & formulas
SharePoint List / Dataverse	Data storage
Power Automate	Workflow automation
Microsoft 365	User authentication
Power Platform	Low-code development ecosystem
⚙️ Key Features

User login and authentication

Machine catalog with details

Order placement functionality

Order status tracking

Admin approval workflow

Data validation using Power Fx

Responsive design for mobile and desktop

🧩 Application Modules
1️⃣ Login & User Authentication

Secure access using Microsoft credentials

Role-based access (User / Admin)

2️⃣ Machine Catalog

Displays machine name, category, price, and specifications

Easy navigation and selection
Screen 1 : The Main Screen
<img width="1224" height="743" alt="image" src="https://github.com/user-attachments/assets/12886018-29a6-4790-8bd1-52f02151b395" />


3️⃣ Order Management

Users can place new orders

Automatic order ID generation

Quantity and pricing calculation
Screen 2: Comparing Screen 
<img width="1439" height="806" alt="image" src="https://github.com/user-attachments/assets/4db047fb-0f58-46da-8ebf-c05f821e7e22" />


4️⃣ Admin Panel

View all orders

Approve or reject requests

Update order status

🔁 Workflow of the Application

User logs into the app

Selects a machine from the catalog

Places an order with required details

Order is stored in the database

Admin reviews and updates order status

User tracks order progress
 Workflow Diagram: The Tree Structure of the Components
 <img width="333" height="811" alt="image" src="https://github.com/user-attachments/assets/2f99f59d-906b-4b59-9cbc-20fc982044be" />


🧮 Business Logic (Power Fx)

Form validation using If(), IsBlank()

Conditional visibility of controls

Automatic calculations (Total Price)

Status-based UI changes
