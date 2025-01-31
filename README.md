# BinConnect - Smart Waste Management System

## Overview
BinConnect is a smart waste management system that monitors the fill levels of garbage bins across the city and alerts the authorities when the fill level exceeds a threshold of 75%. The system helps optimize waste collection routes using AI-driven algorithms, ensuring timely garbage disposal and efficient fleet management.

## Features
- **Real-time Fill Level Monitoring:** Continuously tracks garbage levels in bins.
- **Automated Alerts:** Sends notifications when bins reach 75% capacity.
- **Data Storage & Management:** Uses ThinkSpeak cloud server to store:
  - Time of fill-level updates
  - Location coordinates of bins
  - Collecting truck details
  - Fill level status
- **Efficient Route Optimization:** Uses Google Maps API with A* and Dijkstra’s algorithm to find the shortest and most efficient route for garbage collection.
- **User-Friendly Interface:** Provides a dashboard to monitor bin status and route details.

## Technologies Used
- **Hardware:** IoT-enabled sensors to detect garbage levels
- **Cloud Platform:** ThinkSpeak for data storage and retrieval
- **Mapping & Navigation:** Google Maps API for route optimization
- **Algorithms:** A* and Dijkstra’s for shortest path calculation
- **Programming Languages:** Python, JavaScript

![bin](https://github.com/user-attachments/assets/803a5f11-6484-4784-a016-83a5ccad4e77)
