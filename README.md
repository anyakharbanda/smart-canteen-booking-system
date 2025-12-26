# Smart Canteen Table Booking System

A real-time canteen table occupancy detection and booking platform built using **YOLOv8**, **Streamlit**, **Twilio SMS**, and **QR-based verification**.  
This system helps students/staff reserve tables efficiently, reducing wait times and improving dining space utilization.


## Features

- Detects **occupied vs empty tables** using YOLOv8 on live video/image input
- Users can **book tables instantly** via Streamlit interface
- Generates **QR code + SMS confirmation** after booking
- **Timer-based auto-expiry** for bookings (default: 45 mins)
- Supports **group size input & phone verification**
- Scalable design suitable for **hostels, college canteens, cafeterias**


## Tech Stack

| Component | Technology Used |
|----------|-----------------|
| Model | YOLOv8 Object Detection |
| Frontend UI | Streamlit |
| Backend | Python |
| Notifications | Twilio SMS API |
| QR Code Generation | `qrcode` library |
| Environment | Anaconda / Virtualenv |


