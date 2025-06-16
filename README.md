# Employee-Directory-Application
This is a very basic employee directory application that mainly implements the navigation and routing mechanisms for SAP UI5.
# 👥 Employee Directory App 📇  
*A sleek, intuitive, and efficient way to manage employee information — built using SAPUI5 and Web IDE*

![UI5 Logo]()

---

## 🔥 Why You'll Love This App

- ✅ **Modern UI** with SAP Fiori Design Guidelines  
- ✅ **Real-time Employee Search** & Auto-suggestions  
- ✅ **Responsive Design** (Mobile, Tablet, Desktop)  
- ✅ **Modular Architecture** for scalability  
- ✅ **Deployed via SAP Web IDE** with clean, production-ready code

---

## 🚀 Project Structure 
EmployeeDirectoryApp/
│
├── controller/
     ├── employee/
         ├── overview/
              └── EmployeeOverview.controller.js # Handles all events: CRUD, theme toggle, export, sort, undo
              └── EmployeeOverviewContent.controller.js # Handles all events: CRUD, theme toggle, export, sort, undo
            
│ └── Main.controller.js # Handles all events: CRUD, theme toggle, export, sort, undo
│
├── view/
│ └── Main.view.xml # UI layout with card elements, buttons, inputs
│
├── model/ # (optional, if using external models)
│
├── webapp/
│ ├── Component.js # Initializes the app
│ ├── index.html # Entry point for the app
│ └── manifest.json # App metadata (routing, models, i18n, etc.)
│
├── i18n/
│ └── i18n.properties # Internationalization strings
│
└── README.md # Project overview and setup instructions

---

## 💻 Tech Stack

| Layer        | Technology         |
|--------------|--------------------|
| Frontend     | **SAPUI5 (MVC)**   |
| Backend      | **Mock Server (for demo)** |
| IDE & Tools  | **SAP Web IDE**    |
| Styling      | **Fiori Design Guidelines** |
| Data Format  | **JSON**           |

---

## 🧠 Features at a Glance

- 🔍 **Search Employees** by name, ID, or role  
- 📄 **Employee Detail View** with department, email, contact, and profile  
- 🧭 **Responsive Split App** layout  
- 📁 **Modular Component-based Design**  
- 💡 Built for **enterprise scalability** & **clean maintenance**

---

## ✨ Screenshots

> _(Add images here using Markdown syntax. Example below:)_

```md
![Master View](screenshots/master-view.png)
![Detail View](screenshots/detail-view.png)

