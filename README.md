📦 Project AZ – Barcode Scanner & Product Management System

📌 Overview
Project AZ is a full-stack web-based barcode scanning and product verification system designed to streamline product tracking and documentation processes. The application allows users to scan barcodes using a device camera or enter them manually, validate product information through a backend system, capture product images, and generate downloadable Excel reports.
This system is ideal for inventory management, warehouse operations, retail environments, and product quality control.

🚀 Features
📷 Real-time barcode scanning using device camera
✍ Manual barcode entry option
🔍 Backend barcode validation
📸 Capture and upload product images
📊 Automatic Excel report generation
📥 Downloadable Excel file
🎨 Color-coded validation results (Success / Warning / Error)

🛠 Technologies Used
Frontend
HTML5
CSS3
JavaScript
html5-qrcode library
Backend
Python
Flask framework
Data Handling
Excel file processing
JSON communication between frontend and backend

⚙️ How It Works
The user scans a barcode or enters it manually.
The barcode is sent to the Flask backend using a POST request.
The backend checks the barcode against stored product data.
A response message is returned with status (green / yellow / red).
The user can capture and upload a product image.
The system logs results and allows downloading an updated Excel report


📂 Project Structure
project_az/
│
├── index.html        # Frontend interface
├── eco.py            # Flask backend server
├── products.xlsx     # Product database
└── README.md



🎯 Purpose
The goal of this project is to provide a simple, efficient, and scalable barcode management solution that integrates camera scanning, backend validation, image capture, and Excel reporting in one system.
