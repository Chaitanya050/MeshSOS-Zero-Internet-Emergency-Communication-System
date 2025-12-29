# MeshSOS-Zero-Internet-Emergency-Communication-System
MeshSOS enables offline SOS messaging using phone-to-phone mesh networking during disasters.
# 🚨 MeshSOS – Zero-Internet Emergency Communication System

MeshSOS is a disaster-resilient mobile application that enables users to send SOS messages **without internet access** by forming a **peer-to-peer mesh network** between nearby smartphones.

---

## 🧩 Problem Statement
During natural disasters such as floods, earthquakes, or cyclones, mobile networks and internet connectivity often fail. This makes it impossible for victims to send emergency SOS messages, delaying rescue operations and increasing the risk to human life.

---

## 💡 Solution Overview
MeshSOS allows smartphones to communicate **offline** using device-to-device connections. SOS messages hop from one phone to another until any device regains internet access, at which point the message is synced to the cloud and emergency alerts are triggered.

📱 Phone A → 📱 Phone B → 📱 Phone C → ☁️ Cloud

This approach removes dependency on traditional infrastructure and enables **community-powered emergency communication**.

---

## ✨ Key Features
- Offline SOS message creation
- Peer-to-peer mesh networking
- Multi-hop message forwarding
- Automatic cloud synchronization
- Location tagging for SOS alerts
- Duplicate and loop prevention logic

---

## 🛠️ Google Technologies Used
- **Google Nearby Connections API** – Offline peer-to-peer communication
- **Firebase Realtime Database** – Cloud synchronization of SOS messages
- **Firebase Cloud Functions** – Alert triggering and logging
- **Google Maps Platform** – Visualizing SOS locations (dashboard)

---

## 🧱 System Architecture
- Android mobile application
- Nearby Connections-based mesh layer
- Local message storage (offline)
- Firebase cloud backend
- Web or console-based SOS visualization

---

## ⏱️ MVP Scope (Hackathon)
- Functional Android prototype
- Offline message hopping across devices
- Firebase cloud sync when internet is available
- Live demo using multiple phones

---

## 🚀 Future Enhancements
- End-to-end encrypted messaging
- Priority-based SOS routing
- Government and rescue authority integration
- Battery-aware message forwarding
- Cross-platform (iOS) support

---

## 🎥 Demo
- **Demo Video:** *(to be added)*
- **MVP Link:** *(to be added)*

---

## 📂 Repository Structure
