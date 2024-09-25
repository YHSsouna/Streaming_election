# 🗳️ Realtime Election Voting System

This repository contains the code for a **real-time election voting system**. The system is designed using a powerful stack of **Python**, **Kafka**, **Spark Streaming**, **PostgreSQL**, and **Streamlit**, all containerized with **Docker Compose** for easy setup and deployment.

---

## 🛠 System Architecture

The system comprises the following components:

### **1. Voting Data Source**  
📊 **Random Voter Data**  
Votes are simulated using random user data generated from the [randomuser.me](https://randomuser.me/) API and other sources.

### **2. Real-time Data Streaming - Apache Kafka**  
💬 **Kafka** is used for real-time data streaming, allowing the system to handle voting events in real-time.

### **3. Data Processing - Apache Spark Streaming**  
⚡ **Apache Spark Streaming** processes incoming vote data, aggregating and analyzing it in real-time.

### **4. Database - PostgreSQL**  
🗄️ **PostgreSQL** stores the voting data and aggregated results for further analysis.

### **5. Visualization - Streamlit**  
📈 **Streamlit** is used for the front-end, displaying live results from the election in real-time.

### **6. Containerization - Docker Compose**  
🐳 **Docker Compose** simplifies the setup and deployment of all services, ensuring that everything runs smoothly inside Docker containers.

---

## 💻 Technology Stack

The technology stack used in this project includes:

- **Python**
- **Apache Kafka**
- **Apache Spark Streaming**
- **PostgreSQL**
- **Streamlit**
- **Docker Compose**
