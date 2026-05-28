# Health Prediction Application

## Project Overview

The Health Prediction Application is a healthcare-based web application developed using Python Flask and SQLite. The application allows users to manage patient blood test records and generate basic AI-based health predictions based on blood test values.

This project demonstrates CRUD operations, database integration, backend development, and basic healthcare prediction logic.

---

## Features

- Add new patient records
- View all patient records
- Edit patient information
- Delete patient records
- AI-generated health remarks
- Form validation
- Responsive user interface using Bootstrap
- SQLite database integration

---

## Technologies Used

- Python
- Flask
- SQLite
- HTML
- CSS
- Bootstrap

---

## CRUD Functionalities

### Create
Users can add new patient records.

### Read
Users can view all patient records in a table.

### Update
Users can edit patient information.

### Delete
Users can remove patient records.

---

## AI Prediction Logic

The application generates health-related remarks based on blood test values.

Example:
- High glucose level → Diabetes risk
- High cholesterol → Cholesterol risk
- Low haemoglobin → Possible anemia

---

## Project Structure

health-prediction-app/
│
├── app.py
├── database.db
├── requirements.txt
│
├── templates/
│   ├── index.html
│   ├── add.html
│   └── edit.html
│
└── static/
    └── style.css

---

## Installation Steps

### Step 1: Clone Repository

git clone https://github.com/yourusername/health-prediction-app.git

### Step 2: Install Flask

pip install flask

### Step 3: Run Application

python app.py

### Step 4: Open Browser

http://127.0.0.1:5000

---

## Future Improvements

- Integration with external AI/ML APIs
- User authentication
- Advanced health prediction models
- Cloud deployment

---

## Developer

Shivani S S
MCA Student
Bangalore Institute of Technology
