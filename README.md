# 💳 Retail Order & Cash Manager System (Built with Claude Code)

![Airtable](https://img.shields.io/badge/Backend-Airtable%20API-18BFFF?style=flat&logo=airtable&logoColor=white)
![Claude Code](https://img.shields.io/badge/Agentic%20Dev-Claude%20Code-7B61FF?style=flat&logo=anthropic&logoColor=white)
![JavaScript](https://img.shields.io/badge/Logic-Vanilla%20JS-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Vercel](https://img.shields.io/badge/Deployment-Vercel-000000?style=flat&logo=vercel&logoColor=white)

---

## 🚀 Live Application
Access the production-ready dashboard here:  
👉 **[Launch Retail Order & Cash Manager](https://project-aygsg.vercel.app)**

---

## 📺 System Walkthrough

🎥 Watch the complete technical demonstration and development process:

https://www.loom.com/share/85b70de76b1a4dfd9e7cac3d5e72e662

---

## 🚀 Project Overview
Developed using **Claude Code**, this system is a custom **Full-Stack Logistics Engine** designed to eliminate cash leakage in retail delivery operations. It manages the entire order lifecycle—from creation to final settlement—specifically solving the problem of tracking **"Cash on Road."**

The application provides business owners with **100% financial visibility**, ensuring that every rupee collected by delivery staff is dynamically tracked through a **Digital Wallet Architecture** and reconciled against daily revenue reports.

---

## 🏗️ Technical Specialty: Agentic Engineering
This project was architected using **Claude Code**, Anthropic's agentic developer CLI. By leveraging agentic reasoning in the terminal, I achieved:
*   **Rapid Logic Prototyping:** Built a complex 4-stage financial state machine with real-time math calculations in record time.
*   **Asynchronous API Orchestration:** Engineered a robust Fetch API layer to handle simultaneous `PATCH` and `POST` requests to the Airtable REST API.
*   **Terminal-Driven Debugging:** Resolved state-management issues and ensured real-time dashboard calculations (Revenue vs. Cash on Road) via agentic reasoning.

---

## 📝 The System Workflow

### 1️⃣ Real-Time Financial Dashboard
The command center of the application. It calculates **"Today's Revenue"** (cash returned to store) and **"Cash on Road"** (active liability held by staff) in real-time. This ensures zero data blindspots for the business owner.

<div align="center">
  <img src="https://raw.githubusercontent.com/Muneeb20019/Retail-Order-Cash-Manager-System-Claude-Code/main/retail%201.PNG" width="100%" alt="Financial Dashboard"/>
</div>

### 2️⃣ Relational Staff Management
Every staff member is linked to a **Relational Wallet**. Managers can onboard new drivers and create multi-item orders, which are then programmatically assigned to the specific driver’s digital ledger.

<div align="center">
  <img src="https://raw.githubusercontent.com/Muneeb20019/Retail-Order-Cash-Manager-System-Claude-Code/main/retail%202.PNG" width="100%" alt="Staff Console"/>
</div>

### 3️⃣ Finite State Machine (Kanban)
Orders move through a strict logic gate: **Pending → Dispatched → Delivered → Cash Received**. 
- **The Delivery Trigger:** Moving an order to "Delivered" instantly increases the Staff Wallet and global "Cash on Road" variables.
- **The Reconciliation Trigger:** Only the "Receive Cash" action clears the staff liability and moves funds into "Store Revenue."

<div align="center">
  <img src="https://raw.githubusercontent.com/Muneeb20019/Retail-Order-Cash-Manager-System-Claude-Code/main/retail%203.PNG" width="100%" alt="Kanban Workflow"/>
</div>

### 4️⃣ Data Audit & Historical Reporting
A built-in analytics engine pulls from the **Airtable Persistence Layer**. Managers can filter by any date to audit individual transactions, verify driver performance, and close the books for the day with 100% accuracy.

<div align="center">
  <img src="https://raw.githubusercontent.com/Muneeb20019/Retail-Order-Cash-Manager-System-Claude-Code/main/retail%204.PNG" width="100%" alt="Reporting Engine"/>
</div>

---

## 🧠 Core Technical Pillars
*   **🛡️ Digital Wallet Logic:** Implemented an atomic financial system where staff liability is calculated on-the-fly, preventing "leakage" and theft.
*   **⚡ Serverless Architecture:** A decoupled full-stack approach using a custom JS frontend and **Airtable** as a relational database, resulting in zero server maintenance overhead.
*   **📱 Mobile-First UI:** Optimized with CSS Flexbox/Grid to allow delivery staff to update order states directly from their smartphones on the road.
*   **🆔 Primary Key Generation:** Custom logic generates unique identifiers (`ORD-XXX`) to ensure data integrity across the entire relational schema.

---

## 🛠️ Technical Stack
| Layer | Technology |
| :--- | :--- |
| **🤖 Development** | **Claude Code (Agentic CLI)** |
| **🌐 Frontend** | HTML5 / CSS3 / Vanilla JavaScript |
| **🗄️ Backend** | **Airtable REST API** |
| **🧠 Logic** | Asynchronous Fetch & State Management |
| **🚀 Hosting** | **Vercel** |

---

## ✍️ Author
**Muneeb Ali Khan**
- **GitHub:** [@Muneeb20019](https://github.com/Muneeb20019)
- **LinkedIn:** [Muneeb Ali Khan](https://www.linkedin.com/in/muneeb-ali-khan-2a1675365)
