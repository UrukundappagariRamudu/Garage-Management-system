# 🚗 Garage Management System - Salesforce

This project is a **Garage Management System** built on the Salesforce platform. It helps garage owners and service advisors manage customers, vehicles, service appointments, inventory, invoices, and staff workflows efficiently within the Salesforce ecosystem.

---

## 🔧 Features

- ✅ Customer Management (Accounts & Contacts)
- 🚘 Vehicle Tracking (Custom Object)
- 🗓️ Service Appointment Scheduling
- 🧾 Invoice Generation & Tracking
- 📦 Inventory Management
- 👨‍🔧 Mechanic Assignment and Task Management
- 📊 Dashboard and Reports
- 🔔 Email/SMS Alerts for Service Status
- 🛠️ Role-based Access Control

---

## 🏗️ Built With

- **Salesforce Platform**
  - Lightning App Builder
  - Lightning Web Components (LWC)
  - Apex Classes & Triggers
  - Salesforce Flows / Process Builder
  - Custom Objects & Fields
  - Validation Rules & Formula Fields
  - Reports & Dashboards

---

## 📁 Custom Objects

| Object Name        | Purpose                                  |
|--------------------|-------------------------------------------|
| Vehicle__c         | Stores vehicle details (VIN, model, etc.) |
| Service__c         | Records each service request              |
| Invoice__c         | Stores billing and payment info           |
| Mechanic__c        | Stores mechanic/staff information         |
| Inventory__c       | Tracks parts and availability             |

---

## 🔄 Data Flow Overview

1. **Customer** brings a vehicle for service.
2. **Service Record** is created for the Vehicle.
3. A **Mechanic** is assigned to the job.
4. Required **Parts** are allocated from **Inventory**.
5. After completion, an **Invoice** is generated and linked.
6. Status updates are sent to the Customer.

---

## 🧠 Automation Used

- **Auto-assign Mechanic** using Flow
- **Inventory Deduction** via Apex Trigger
- **Invoice Auto-generation** using Process Builder
- **Email Alerts** using Flow

---

## 🔐 User Roles

- **Admin** – Full Access
- **Service Advisor** – Manage customers, vehicles, and appointments
- **Mechanic** – View and update assigned jobs
- **Inventory Manager** – Manage stock

---

## 🚀 Deployment

1. Clone the repo (if available) or retrieve metadata via Salesforce DX.
2. Push components to a Salesforce Org (Scratch Org or Sandbox).
3. Assign necessary permission sets.
4. Test Flows and automation.
5. Populate test data for Vehicles, Mechanics, etc.

---

## 🧪 Test Coverage

- Apex Classes: >85% test coverage
- Triggers tested with positive & negative test cases
- Flow outcomes validated using debug logs

---

## 🤝 Contributions

For collaboration, raise a pull request or log an issue describing the enhancement or bug.

---

## 📄 License

This project is for educational/demo purposes on the Salesforce platform. Contact the author for commercial use.

---

## 📬 Contact

**Developer:** Ramudu
