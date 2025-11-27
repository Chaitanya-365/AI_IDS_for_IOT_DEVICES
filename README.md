# AI_IDS_for_IOT_DEVICESAI IDS for IoT Devices

An AI-powered Intrusion Detection System that monitors IoT device activity, detects anomalies using machine learning, and alerts users in real-time through dashboard notifications, sound alerts, SMS, and WhatsApp messages.

🚀 Overview

This project is designed to provide smart intrusion detection specifically for IoT environments.
It uses:

Node.js for backend processing

Machine learning models for anomaly detection

Dashboard UI for real-time monitoring

Alerts through sound, WhatsApp, and SMS

The system is capable of detecting suspicious behaviors such as unknown device connections, sudden spikes, irregular patterns, and more.

🔥 Features

Real-time Intrusion Detection

Machine Learning-based anomaly detection

Node.js Backend for event handling

Live Dashboard showing logs, alerts, device activity

Siren Sound Alert when a threat is detected

WhatsApp & Fast2SMS Alerts

Event Logging System

Supports multiple IoT device inputs

Highly customizable event rules

🏗️ Project Structure
AI_IDS_for_IOT_DEVICES/
│
├── backend/              # Node.js backend
│   ├── server.js
│   ├── app.js
│   ├── controllers/
│   ├── routes/
│   ├── utils/
│   └── models/
│
├── ai_model/             # ML model & processing
│   ├── detect.py
│   ├── preprocess.py
│   └── model_weights/
│
├── public/               # Static frontend files (HTML, CSS, JS)
│   ├── index.html
│   ├── dashboard.html
│   ├── js/
│   └── css/
│
├── alerts/               # Notification system
│   ├── whatsapp.js
│   ├── sms.js
│   └── siren/
│
├── logs/                 # Event data & detection logs
│
├── config/               # API keys, configuration files
│
├── .gitignore
├── README.md
└── package.json

🛠️ Tech Stack
Backend

Node.js

Express.js

AI / ML

Python

NumPy

Sklearn / TensorFlow / PyTorch (depending on your model)

Frontend

HTML

CSS

JavaScript

Alerts

Fast2SMS API

WhatsApp Cloud API

Local siren audio trigger
