# Ngo-donations-and-volunteer-management-system
# NGO Donations & Volunteer Management System

A Salesforce-based application designed to help NGOs efficiently manage **donations, volunteers, and events** with end-to-end automation, role-based access, and real-time reporting.

---

## 📌 Project Overview

This project provides a centralized CRM solution for NGOs to:

* Track multiple types of donations (Money, Food, Clothes, Groceries, etc.)
* Manage volunteers and their participation in events
* Automate donor and volunteer communications
* Generate insightful reports and dashboards

The entire system is built using **native Salesforce tools** without any third‑party integrations.

---

## 🚀 Key Features

### 💰 Donation Management

* Supports **One-Time** and **Monthly Recurring** donations
* Tracks donor details: name, email, phone, occasion, reason, and related events
* Automatic thank-you emails on donation creation
* Monthly reminder emails for recurring donors
* Occasion-based greetings (Birthday / Anniversary)

### 🤝 Volunteer Management

* Volunteer registration with skills and availability
* Assign volunteers to specific events
* Separate layouts for registration and feedback
* Automated acknowledgment and participation emails

### 📅 Event Management

* Create and manage NGO events
* Link donations and volunteers to events
* View event-wise participation details

### 📊 Reports & Dashboards

* Top Donors Report
* Donations by Occasion
* Volunteers per Event
* Interactive dashboards with:

  * Donut charts
  * Bar graphs
  * Lightning Tables

---

## 👥 User Roles & Access Control

| Role                      | Permissions                                |
| ------------------------- | ------------------------------------------ |
| **NGO Admin**             | Full access to all objects and data        |
| **Donor Manager**         | Create, Read, Edit donations; Read events  |
| **Volunteer Coordinator** | Create, Read, Edit volunteers; Read events |

Security is enforced using:

* Profiles & Permission Sets
* Field-Level Security (FLS)
* Tab visibility controls

---

## 🧱 System Architecture

**Platform:** Salesforce CRM (Lightning + Classic)

### Custom Objects

* `Donation__c`
* `Volunteer__c`
* `Event__c`

### Record Types

* **Donation:** One-Time, Monthly
* **Volunteer:** Registration, Feedback

### Automation

* Record-triggered flows
* Scheduled flows
* Email alerts with reusable templates

---

## ⚙️ Automation & Flows

* **Thank You Email Flow** – Triggered on donation creation
* **Occasion & Monthly Reminder Flow** – Scheduled daily
* **Volunteer Follow-up Flow** – Triggered on volunteer creation and participation

All emails are sent using **Email Alerts** and **Classic Email Templates**.

---

## ✅ Validation Rules

* Donation amount must be greater than 0 for money donations
* Email must contain `@`
* Phone number must be exactly 10 digits
* Occasion date required when an occasion is selected

---

## 🧪 Testing Summary

* Tested with sample data (Donations, Volunteers, Events)
* Verified flows, email triggers, layouts, and permissions
* All test cases passed successfully

---

## 📦 Deployment Details

* Developed and tested in Salesforce Developer Org
* No change sets used
* All flows and automation activated post-testing
* Documentation prepared for demo and handover

---

## 🛠 Tools & Technologies Used

* Salesforce Object Manager
* Profiles & Permission Sets
* Record Types & Page Layouts
* Validation Rules
* Flows (Process Automation)
* Email Templates & Alerts
* Reports & Dashboards

---

## 🔮 Future Enhancements

* Online payment integration (Razorpay / Stripe)
* Mobile-optimized UI (LWC / Salesforce Mobile App)
* AI-based donor insights (Einstein AI)
* Smart volunteer-event matching logic

---

## 📄 Documentation

Step-by-step implementation guide:

* Available in the project documentation folder

---

📬 Contact

For questions, demos, or enhancements, feel free to reach out.

---

⭐ *If you find this project useful, don’t forget to star the repository!*
