# 🍽️ Comprehensive Restaurant and Food Supply Chain Solutions

A full-fledged, end-to-end food supply chain management system tailored for the restaurant industry, emphasizing **efficiency**, **sustainability**, and **smart operations** through centralized oversight and intelligent automation.

🔗 **GitHub Repo:** [Food Supply Chain](https://github.com/C-MOHAMMED-ZAID/Food-Supply-Chain.git)

---

## 🚀 Project Overview

This project introduces an integrated platform that modernizes food supply chain management by bridging the operational gaps between **Restaurants**, **Admins**, **Sustainability Analysts**, and **Delivery Agents**. With a centralized system built on Django and powered by sustainability analytics, this project promotes seamless order processing, real-time inventory tracking, secure access control, and AI-driven environmental insights.

---

## 🎯 Key Features

- 🧠 **Centralized Admin Panel**: Manage food inventory, approvals, and user access.
- 🏪 **Restaurant Portal**: Browse items, manage cart, auto-calculate prices, and checkout.
- 🌱 **Sustainability Module**: Analyze environmental impact using **Random Forest Classifier**.
- 🚚 **Delivery Scheduling**: Optimize delivery routes based on sustainability approvals.
- 📊 **Real-Time Reporting**: Generate financial and sustainability reports for strategic decision-making.
- 🔐 **Secure, Role-Based Access**: Email-based credentials, modular login access.

---

## 🧰 Tech Stack

| Layer          | Technology               |
|----------------|---------------------------|
| **Frontend**   | HTML, CSS, JavaScript     |
| **Backend**    | Python, Django Framework  |
| **Database**   | MySQL                     |
| **IDE**        | PyCharm                   |
| **ML Model**   | Random Forest Classifier  |
| **Emails**     | Gmail SMTP via Django     |

---

## ⚙️ Setup & Installation

Follow the exact steps below to ensure successful local deployment:

```bash
# Step 1: Clone the repository
git clone https://github.com/C-MOHAMMED-ZAID/Food-Supply-Chain.git

# Step 2: Navigate to the project folder
cd Food-Supply-Chain

# Step 3: Activate the virtual environment
cd virtual
cd Scripts
activate virtual

# Step 4: Navigate back to the root project directory
cd ../..

# Step 5: Enter the project folder
cd Foodsupplychain

# Step 6: Run the Django development server
python manage.py runserver
```

✅ Now open your browser and go to: `http://127.0.0.1:8000/`  
You’re ready to explore the full ecosystem!

---

## 🔐 Authentication Workflow

- All modules (Restaurant, Sustainability, Delivery) **must register and get admin approval**.
- Credentials are emailed securely after approval.
- Admin controls inventory, approvals, and overall system coordination.

---

## 🧠 Machine Learning Integration

A built-in **Random Forest Classifier** is used within the sustainability module to assess the environmental impact of food products. These insights directly influence order approval and delivery routing decisions.

---

## 🏗️ System Modules

- **Admin**
- **Restaurant**
- **Sustainability**
- **Delivery**

Each module has a unique workflow, centralized through a single Django project.

---

## 🛠️ Future Enhancements

- ☁️ Deployment on cloud (e.g., Render, Railway, AWS)
- 📱 Mobile app using Flutter or React Native
- 📊 Interactive Admin Dashboards (Chart.js)
- 🔄 Predictive ordering using time-series ML models

---

## 📃 License

MIT License — Free to use, modify, and distribute with attribution.

---

## 🙌 Acknowledgments

- Developed as part of an MCA final-year project.
- Guided by industry use-cases in sustainable and smart supply chain management.
- Built using Django, with secure practices and modular design in mind.

---

💼 _Connect with me on [LinkedIn](https://www.linkedin.com/in/mohammedzaidc)_  
🔗 _Visit the [GitHub Repository](https://github.com/C-MOHAMMED-ZAID/Food-Supply-Chain.git)_

---
