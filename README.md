# Supermarket Assistant Robot (Delivero)

## Overview
This repository contains the software components for the **Supermarket Assistant Robot** project, named **Delivero**.  
Delivero is a prototype robot designed to assist customers in supermarkets by carrying selected items to their parking location. Customers can place orders via a mobile application, and the robot handles delivery using technologies like **Arduino microcontrollers** and **sensors**.

The repository includes:
- **Mobile App**: Built with Flutter, allowing users to select products, place orders, and interact with the robot.  
- **Backend API**: Implemented using FastAPI, handling order processing, integration with the robot's point-of-sale (POS) system, and communication between the app and hardware.  

This project was developed as part of the **Higher National Diploma in Software Engineering** at the **National Institute of Business Management (NIBM), Kurunegala, Sri Lanka**.

---

## Technologies Used
- **Mobile App**: Flutter (with HTML/CSS for UI elements where applicable)  
- **Backend**: FastAPI (Python-based web framework)  
- **Database**: *(Specify if known, e.g., SQLite/PostgreSQL – assumed based on project needs)*  
- **Hardware Integration**: Arduino (Uno/Nano), ESP32 Cam, WiFi module for communication  
- **Other**: QR code scanning for product identification, ultrasonic sensors for navigation  

---

## Designs
<img width="594" height="501" alt="image" src="https://github.com/user-attachments/assets/14b7e8cc-fa3b-4062-a8ec-aef90140096c" />
<img width="554" height="287" alt="image" src="https://github.com/user-attachments/assets/323e3334-21dc-45e2-93b2-62c742482485" />
<img width="617" height="539" alt="image" src="https://github.com/user-attachments/assets/f21f8bb2-4be7-4102-8c3e-7228f764efe6" />

## Features
- **Order Placement**: Users can browse products, add them to a cart, and submit orders via the mobile app.  
- **Robot Integration**: The backend API communicates with the robot’s hardware (via WiFi module) to fetch shelf locations, navigate, and deliver items.  
- **User Authentication**: Secure login system to prevent unauthorized access.  
- **Real-Time Updates**: Notifications on order status, robot location, and delivery completion.  
- **Compatibility**: Integrates with supermarket POS systems for seamless order handling.  
---
### Prerequisites
- Python 3.8+ (for FastAPI)  
- Flutter SDK (for mobile app)  
- Git  

