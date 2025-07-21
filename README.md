# ✈️ Airlines Management System - Salesforce 

## 🏫 College :  `Vishnu Institute of Technology - Bhimavaram`

**🔹 TEAM NUMBER:** 
```bash
 LTVIP2025TMID30989
```
👉 **[Click here to watch the full demo on YouTube](https://youtu.be/Oz1UWI1caGs)**

---

## 👥 Team Members

- Member 1: `Dwarampudi Dinesh Eswar Reddy`, Salesforce Developer
- Member 2: `Gangula Navya Sree`, Salesforce Administrator

---

## ✨ Project Overview

The **Salesforce Airline Management System** is a cloud-based airline operations platform built entirely on Salesforce.  
This system enables airlines to:

✅ Manage **Passengers, Flights, Bookings, and Crew**  
✅ Automate validation of data with **Apex Triggers & Classes**  
✅ Enable smooth record creation with **Screen Flows**  
✅ Provide role-based access using **Profiles & Roles**  
✅ Visualize data with **Reports & Dashboards**

---

## 🛠️ Functionalities

### 🎯 1. Data Modeling
- Created 4 Custom Objects:
  - **Passenger**
  - **Booking**
  - **Flight**
  - **Crew**
- Configured custom fields:
  - Text, Number, Date, Picklists
  - Lookup relationships between objects (e.g., Booking linked to Flight and Passenger)

### 🎯 2. User Access Control
- **Custom Profiles:**
  - General Admin
  - Management Admin
  - Senior Admin
  - Crew Member
- **Roles Hierarchy:**
  - CEO
    - Senior Admin
      - General Admin
      - Management Admin
        - Crew Members

### 🎯 3. Apex Validation
- **Apex Class:**
  - `PhnValid_PassengerObj` to ensure phone number is mandatory.
- **Apex Trigger:**
  - `PhnValidTrigger` to invoke validation before insert.
- **Apex Test Class:**
  - `PhnValid_TestClass` for unit test coverage.

### 🎯 4. Automation with Flows
- **Screen Flow:**
  - Guided booking creation.
- **Create Element:**
  - Automatically saves booking records.
- **Success Screen:**
  - Displays confirmation details dynamically.

### 🎯 5. Reports & Dashboards
- **Reports:**
  - Bookings with Flight Details
  - Bookings with Passenger Names
  - Crew with Flight
- **Dashboards:**
  - Visual summary of bookings and crew assignments.

---

## ⚙️ How It Works

1. **User Management:**
   - Admins create users and assign them profiles and roles.
   - Each user’s access is controlled via profiles.

2. **Creating Records:**
   - Users can create Passenger, Flight, Booking, and Crew records via tabs.
   - Booking creation is streamlined with Screen Flow.

3. **Validation Logic:**
   - Apex Trigger ensures Passenger Phone Number is not empty.
   - If the phone number is missing, an error prevents saving.

4. **Viewing & Managing Data:**
   - Users can view, edit, or delete records according to their profile permissions.
   - Reports give aggregated insights into bookings, passengers, and flights.

5. **Dashboards:**
   - Visual components (e.g., charts and graphs) provide a quick overview of operational data.

---

## 🧭 Getting Started

> **Prerequisites:**
>
> - A Salesforce Developer Account.
> - Appropriate permissions to create Objects, Fields, Apex classes, Flows, Reports, and Dashboards.

**Steps:**

1. **Create Custom Objects and Fields**  
   Setup → Object Manager → Create new custom objects and fields as per specifications.

2. **Create Tabs and Lightning App**
   - Setup → Tabs → New Tabs for each object.
   - Setup → App Manager → Create a Lightning App "Airline Management System."

3. **Define Profiles and Roles**
   - Setup → Profiles → Clone and configure access.
   - Setup → Roles → Create role hierarchy.

4. **Develop Apex Classes & Triggers**
   - Setup → Developer Console → Create Apex Class, Trigger, and Test Class.

5. **Build Screen Flows**
   - Setup → Flows → Create Screen Flow for booking creation.

6. **Generate Reports and Dashboards**
   - Setup → Reports → New Report.
   - Setup → Dashboards → New Dashboard with components.

---

## 🎓 Conclusion

This project demonstrates how Salesforce can be effectively customized to build an end-to-end Airline Management platform:
- Low-code tools for configuration.
- Apex for business logic enforcement.
- Flows for user-friendly automation.
- Reports & Dashboards for real-time insights.

---

