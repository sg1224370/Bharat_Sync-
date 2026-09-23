# 🇮🇳 BharatSync — AI Civic Intelligence Platform

> **Redefining Citizen Trust Through Civic Intelligence**

BharatSync is an AI-powered civic governance platform designed to bridge the gap between **citizens and government administration**.

The platform helps citizens submit grievances while using intelligent classification, priority detection, geo-intelligence, and automated escalation to improve the grievance-resolution workflow.

---

## 🚀 Features

### 🤖 AI-Powered Grievance Processing

* **Smart Classification** — Automatically categorizes and routes citizen complaints.
* **Emotion & Priority Detection** — Identifies urgency and priority in complaints.
* **Geo-Intelligence** — Maps grievances to geographical zones and responsible departments.
* **Predictive Escalation** — Helps identify complaints that may require escalation.

### 🧑‍💼 Citizen Portal

* File civic complaints
* Track grievance information
* Access the grievance hub
* Explore community information
* View live issue locations

### 🏛️ Officer Console

Officers can access an administration dashboard containing:

* Complaint management
* Analytics
* Escalation management
* Department information
* Officer roster
* SLA settings
* AI routing controls
* WhatsApp alert settings
* Predictive escalation controls

### 🗺️ Live Issue Heatmap

The platform includes an interactive issue heatmap showing civic issue hotspots across different Indian cities.

Example locations include:

* Delhi NCR
* Mumbai
* Pune
* Kolkata
* Bangalore
* Chennai
* Jaipur
* Lucknow

### ⚡ Smart Escalation Workflow

```text
Citizen
   ↓
AI Engine
   ↓
Officer
   ↓
SLA Monitoring
   ↓
Automatic Escalation
   ↓
Resolution
```

The interface represents the complete flow from complaint submission to resolution.

---

## 🎨 UI & Experience

BharatSync uses a futuristic **AI governance / civic-tech interface** featuring:

* Dark futuristic UI
* Glassmorphism / liquid-glass cards
* Animated backgrounds
* Interactive 3D elements
* Animated counters
* Magnetic buttons
* Custom cursor
* Tilt animations
* Scroll-based animations
* Neural-network background
* Responsive layout

The project uses **React, Tailwind CSS, Framer Motion and Three.js** through browser-based CDN imports.

---

## 🛠️ Tech Stack

| Technology    | Purpose               |
| ------------- | --------------------- |
| HTML5         | Application structure |
| React 18      | UI components         |
| Tailwind CSS  | Styling               |
| JavaScript    | Application logic     |
| Framer Motion | Animations            |
| Three.js      | 3D graphics           |
| Supabase      | Database / backend    |
| Google Fonts  | Typography            |

---

## 🗄️ Database

BharatSync is connected to **Supabase** for backend/database functionality.

The application currently uses a `complaints` table for grievance-related data.

> **Important:** Before deploying publicly, configure your own Supabase project and environment/database settings rather than exposing credentials directly in the frontend.

---

## 📂 Project Structure

The current project is designed as a single HTML application:

```text
BharatSync/
│
├── index.html
└── README.md
```

The `index.html` contains the React application, styling, animations, UI components, and application logic.

---

## ▶️ Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/bharatsync.git
```

### 2. Open the project

```bash
cd bharatsync
```

### 3. Run the application

Because the current version is a browser-based HTML application, you can simply open:

```text
index.html
```

in your browser.

For a better development experience, use **VS Code + Live Server**.

---

## 🌐 Deployment

The project can be deployed using platforms such as:

* GitHub Pages
* Vercel
* Netlify

For GitHub Pages, upload the project to a repository and enable **Pages** from the repository settings.

---

## 🔐 Authentication & Roles

BharatSync supports role-based interfaces.

### Citizen

Citizens can access:

* Grievance Hub
* Community section
* Live Map
* Complaint submission

### Officer

Officers can access:

* Officer Console
* Complaint management
* Analytics
* Escalations
* Departments
* Officers
* System settings

The interface changes according to the authenticated user's role.

---

## 🧠 Core Concept

Traditional grievance systems can require citizens to manually determine where their complaint should be submitted.

BharatSync aims to simplify this process:

```text
Citizen Complaint
       ↓
   AI Analysis
       ↓
Category + Priority
       ↓
Department Routing
       ↓
Officer Assignment
       ↓
SLA Monitoring
       ↓
Escalation if Required
       ↓
Citizen Notification
```

This creates a more transparent and structured grievance-management workflow.

---

## 📊 Dashboard

The officer dashboard provides a centralized administration interface with sections for:

* Complaints
* Analytics
* Escalations
* Departments
* Officers
* Settings

It also includes complaint filters, search functionality, SLA controls, officer workload management and notification controls.

---

## ⚠️ Project Status

**Prototype / Hackathon Project**

BharatSync is currently a prototype demonstrating the concept and user experience of an AI-driven civic intelligence platform.

Some displayed statistics, city hotspots, officer information and AI metrics are **demo/prototype data** and should not be interpreted as live government statistics unless connected to verified production data.

---

## 🔮 Future Improvements

Possible future development includes:

* [ ] Real AI/NLP grievance classification model
* [ ] Real-time government data integration
* [ ] Secure authentication
* [ ] Production-ready Supabase database
* [ ] Google Maps / Mapbox integration
* [ ] Multilingual Indian-language support
* [ ] Voice-based complaint submission
* [ ] WhatsApp integration
* [ ] SMS notifications
* [ ] Mobile application
* [ ] Advanced analytics
* [ ] Government API integrations
* [ ] Improved accessibility
* [ ] Production security and privacy controls

---

## 🎯 Use Cases

BharatSync can be adapted for civic issues such as:

* 🛣️ Road and infrastructure problems
* 💧 Water supply complaints
* 💡 Streetlight/electricity issues
* 🗑️ Sanitation problems
* 🚨 Emergency civic complaints
* 🏙️ Local infrastructure issues
* 📍 Location-based public complaints

---

## 👨‍💻 Project

**BharatSync**

AI Civic Intelligence Platform
Built as a civic-tech / AI governance prototype.

---

## 📜 License

This project is intended for educational, demonstration and hackathon purposes.

Add an appropriate open-source license to the repository if you plan to distribute or reuse the project publicly.
