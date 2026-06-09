# Environment Setup Guide

## Prerequisites

The following software must be installed before starting development:

1. Python 3.10 or above
2. Git
3. Visual Studio Code

Verify installation:

python --version

git --version

---

## Clone the Repository

git clone <repository-url>

cd AI-Operator-Copilot

---

## Create Virtual Environment

Create a virtual environment:

python -m venv venv

Activate the virtual environment:

### Windows

venv\Scripts\activate

### Linux / macOS

source venv/bin/activate

---

## Install Dependencies

Install all required packages:

pip install -r requirements.txt

Verify installation:

pip list

---

## Running the Project

Navigate to the project directory:

cd AI-Operator-Copilot

Activate the virtual environment:

venv\Scripts\activate

Run the Streamlit application:

streamlit run frontend/app.py

---

## Deactivating Virtual Environment

When development is complete:

deactivate

---

## Troubleshooting

### Python not recognized

Ensure Python is installed and added to PATH.

### Git not recognized

Reinstall Git and enable the option to add Git to PATH.

### Virtual Environment not activating

Verify that the virtual environment was created successfully and run the correct activation command for your operating system.

### Missing Packages

Reinstall dependencies:

pip install -r requirements.txt
