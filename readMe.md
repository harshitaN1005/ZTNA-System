# 🔐 Blockchain-Based Zero Trust Network Access (ZTNA) System

## 📌 Project Overview
This project implements a **Blockchain-Based Zero Trust Network Access (ZTNA) system** designed to enhance secure access control in modern networks. It follows the principle of **"Never Trust, Always Verify"** by continuously validating users and devices before granting access.

---

## 🎯 Objectives
- Eliminate implicit trust in network access  
- Ensure secure authentication and authorization  
- Maintain tamper-proof access logs using blockchain  
- Enhance data privacy and security  

---

## 🛠️ Technologies Used
- Python  
- Django  
- Blockchain (Smart Contracts)  
- HTML, CSS, JavaScript  

---

## 🔑 Key Features
-  Secure user authentication and authorization  
-  Blockchain-based access control and logging  
-  Real-time monitoring of access requests  
-  Immutable audit logs for security tracking  
-  Web-based interface for system interaction  

---

# 🚀 Project Deployment Guide

This section provides step-by-step instructions to deploy the **Blockchain-Based ZTNA System** using Python, Truffle, and Django.

---

## Prerequisites
- Python 3.7.4  
- Node.js (for Truffle)  
- Internet connection  

---

## Step 1: Install Python 3.7.4
Download Python 3.7.4 (64-bit):  
https://www.python.org/ftp/python/3.7.4/python-3.7.4-amd64.exe  

### Steps:
- Run the installer  
- Check **"Add Python to PATH"**  
- Click **Install**  

---

## Step 2: Extract Project Files
- Extract the project ZIP  
- Ensure the following exist:
  - Main project folder  
  - `hello-th/` folder  
  - `software/` folder  
  - `manage.py` file  

---

## Step 3: Install Dependencies

Open Command Prompt in the project folder:

### Upgrade pip

pip install --upgrade pip

### Install dependencies



pip install -r requirements.txt


(Ensure all required packages are listed in requirements.txt)

---

## ⛓️ Step 4: Setup Truffle (Blockchain)

Navigate to: hello-th/

Then run:

>truffle develop


# After it starts:
Run:
> migrate

Wait until contract deployment completes.

---

## 🌐 Step 5: Run Django Server

Open a new terminal in the main project folder:

Run:
> python manage.py runserver


You should see:

Starting development server at http://127.0.0.1:8000/


Open browser:

http://127.0.0.1:8000/


---

