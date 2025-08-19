# Problem

The Egyptian metro system is outdated and lacking in services for both manegment and normal day to day citizense of the Egyptian government

## Solution

A modernized system inspired by the Egyptian metro, with added enhancements for both passengers and administrators.  

## User Types  

The system has two main types of users:  

- **Normal Users** (passengers)  
- **Admin Users** (metro staff/management)  

---

## Features for Normal Users  

- **Nearest Metro Location**  
  View the nearest metro station and metro and the estimated travel time to reach their desired destination.  

- **Metro Type Selection**  
  Choose the type of metro they prefer (air-conditioned, normal, express, slow, etc.) and schedule when they want to travel and estimate when will they arrive.  

- **Service Updates**  
  Stay informed about any issues (delays, maintenance, etc.).  

- **Crowd Monitoring**  
  Check whether a metro station is currently crowded (using data and algorithms).  

---

## Features for Admin Users  

- **Metro Monitoring**  
  Track all metro locations in real time, including speed, delays, and operational issues (via algorithms and data provided from conductors).  

- **Conductor Communication**  
  Quickly communicate with conductors using predefined codes to handle situations efficiently:  
  - **Green** – Minor issues  
  - **Blue** – Maintenance issues  
  - **Gray** – Minor disturbances (small-scale violence)  
  - **Red** – Major disturbances (large-scale violence)  
  - **Black** – Extreme emergency (e.g., terrorism, metro unable to stop)  

- **Issue Detection**  
  Receive alerts or send early warnings to conductors if problems are suspected.

---

## Tech Stack

- Front-end
  - Flutter
  - Dart
  - Material Design / Cupertino (UI tool-Kit)
  - Riverpod, Provider, or Bloc (state manegment)
  - Google Maps API or mapbox (for metro location)
  
- Back-end
  - FireStore (Real time tracking and Crowd monitring)
  - FireBase Auth
  - FireBase Cloud Functions (Alerts, notification)
  - FireBase Cloud Messeging (Push notification)
  - Firebase Realtime Database (live metro positions)
