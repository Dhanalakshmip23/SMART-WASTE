# SMART-WASTE MANAGEMENT SYSTEM

A web-based solution to improve waste collection efficiency and promote a cleaner environment by tracking waste levels in bins and notifying the authorities when bins need to be emptied.

---

##  Problem Statement
Waste bins placed in public areas often overflow because workers are not aware of when they are full.  
This leads to:
- Pollution
- Bad smell
- Spread of diseases
- Unclean environment

Our solution *monitors waste levels* and *notifies the system/admin* in real-time to ensure timely disposal.

---

##  Proposed Solution
We develop a *Smart Waste Monitoring System* that:
- Displays the fill-level of the waste bin
- Alerts the admin or municipal authorities
- Ensures waste collection happens *only when needed*, saving time and labor

---

## Key Features
| Feature | Description |
|--------|-------------|
| Smart Bin Monitoring | Tracks the fill-level of bins (via sensor or manual input simulation for now) |
| Real-Time Alerts | Notifies the admin when the bin is full |
| User-Friendly UI | Simple, clean and responsive frontend |
| Scalable Backend | Backend built using Node.js for smooth data exchange |

---

## Technologies Used
| Layer | Technology |
|------|------------|
| Frontend | React.js, HTML, CSS, JavaScript |
| Backend | Node.js, Express.js |
| Database | (Add when implemented: MongoDB / Firebase / SQL) |
| Version Control | Git & GitHub |

---

##  Project Folder Structure
SMART-WASTE/
│
├── frontend/                  # React Frontend (Working)
│   ├── public/
│   └── src/
│       ├── App.js
│       └── index.js
│
├── html-version/              # Static HTML Prototype (Working)
│   ├── index.html
│
├── documentation/             # Project Report Files
│   └── smart_waste_documentation.pdf
│
└── README.md                  # Project Overview

---

##  How to Run the Project

### *Frontend (React)*
```bash
cd frontend
npm install
npm start

HTML VERSION
Just Open:
html-version/index.html

## Team Members and Roles

1. *Dhanalakshmi P* – Frontend Development (React)
   - Designing the UI screens
   - Creating components and routing
   - Integrating basic styles and layout(in progress)

2. *Sneha Shrimadi* – Backend Development (Node.js + Database)
   - Setting up server and API endpoints
   - Database structure planning
   - Backend integration (in progress)

3. *Thanuja K H* – Research & Feature Planning
   - Understanding the problem background
   - Collecting real-world data & solution flow
   - Working on system workflow and architecture diagrams

4. *Varsha* – Documentation & Deployment
   - Preparing documentation (Report & PPT)
   - Maintaining GitHub repository
   - Working on hosting / deployment (in progress)

## Future Enhancements

1. Add IoT sensor for automatic waste level measurement
2. Admin dashboard with multiple bin tracking
3. GPS location for smart city waste routing
4. Mobile App integration

## Conclusion

This Smart Waste Management System supports cleaner surroundings, efficient waste collection, reduced manual checking, and contributes to smart city initiatives.
