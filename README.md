# 🏦 Fintech Transaction Simulator

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Streamlit](https://img.shields.io/badge/Streamlit-%23FE4B4B.svg?style=for-the-badge&logo=streamlit&logoColor=white)
![JSON](https://img.shields.io/badge/json-%23000000.svg?style=for-the-badge&logo=json&logoColor=white)

A complete backend simulation of a secure money transfer application. Built with Python and Streamlit, this platform demonstrates core financial technology workflows including user authentication, real-time currency conversion, and dynamic transaction fee calculations.

---

## 🌐 Live Demo
Experience the simulation directly in your browser:  
**👉 [Launch Fintech Simulator](https://fintechsim.streamlit.app/)**

> 📱 **Fully Responsive:** Whether you're on a multi-monitor desktop setup or testing it out on your phone, this application scales perfectly to any screen size. Give it a try on mobile!
> 
> ⏳ **A quick heads-up on loading time:** This application is hosted on Streamlit's free community cloud. If it hasn't been interacted with in a few days, it may go to "sleep" to save resources. If you see a sleeping screen, just click "Wake up app" and it will boot up in seconds!

---

## 📸 Application Tour

Here is a look at the core interfaces and financial logic in action.

### Secure Authentication System
<img width="1439" height="693" alt="Screenshot 1447-10-16 at 12 49 12 AM" src="https://github.com/user-attachments/assets/d73c45b3-452d-4f42-88eb-d73986a631da" />


### Cross-Border Transfer & Fee Calculation
<img width="643" height="639" alt="Screenshot 1447-10-16 at 12 50 35 AM" src="https://github.com/user-attachments/assets/99b201ac-0b16-48b8-a5c3-b9ff4bc3b83b" />


---

## ✨ Key Features

* **Role-Based Access Control:** Secure Login, Sign-Up, and Admin portals managing distinct user sessions.
* **Simulated Ledger:** Persistent user balance tracking utilizing a lightweight JSON database.
* **Dynamic Currency Conversion:** Calculates cross-border exchange rates (e.g., INR to USD) on the fly.
* **Automated Fee Processing:** Programmatically calculates transaction fees and total account deductions before executing a transfer.

---

## 📂 Repository Structure

A clean, single-page application architecture using JSON for state management:

~~~text
📦 fintech-transaction-sim
 ┣ 📂 .devcontainer   # Development container configuration
 ┣ 📜 mta.py          # Main application logic, UI, and routing
 ┣ 📜 user_data.json  # Lightweight database for credentials and balances
 ┗ 📜 README.md       # Project documentation
~~~

---

## 💻 How to Run Locally

To run this simulation on your own machine, you will need Python installed.

**1. Clone the repository**
~~~bash
git clone https://github.com/mohdayandev/fintech-transaction-sim.git
cd fintech-transaction-sim
~~~

**2. Install dependencies**
Make sure you have Streamlit installed in your environment:
~~~bash
pip install streamlit
~~~

**3. Start the application**
~~~bash
streamlit run mta.py
~~~
*Streamlit will automatically open a new browser tab serving the application locally.*

---

## 👨‍💻 About the Developer
**Mohammed Ayan** *Architecting intelligent systems and scalable cross-platform experiences.*

🔗 [Connect with me on LinkedIn](https://linkedin.com/in/mohammed-ayan-94ab6a1b6)  
