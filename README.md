
# 📱 PMC Present – Attendance Application

PMC Present is a modern **attendance management system** built with **React + Capacitor** for mobile platforms.  
It is designed for **students and faculty** of PMC Tech to simplify **attendance tracking, analytics, and management**.

---

## 🚀 Features
- 🔑 **User Authentication** (Login & Registration for Students and Admins)  
- 🏫 **Department & Year Selection**  
- 📝 **Attendance Entry & Tracking**  
- 📊 **Analytics Dashboard** (attendance reports, charts, insights)  
- 👤 **Profile & Settings Management**  
- 🌐 **Cross-platform Support** (Web + Android via Capacitor)  
- ☁️ **Firebase Integration** (for authentication & database – optional)  

---

## 🛠️ Tech Stack
- **Frontend**: React + TypeScript  
- **Mobile Runtime**: Capacitor  
- **Styling**: Tailwind CSS + ShadCN UI  
- **Backend (Optional)**: Firebase / Node.js  
- **Database**: Firestore / SQLite (offline support)  

---

## 📂 Project Structure
```

pmc-present/
│── android/                # Android-specific build files
│── public/                 # Static assets
│── src/                    # Source code (React components, pages, utils)
│   ├── components/         # Reusable UI components
│   ├── pages/              # App screens (Login, Register, Dashboard, etc.)
│   ├── services/           # API / Firebase / SQLite services
│   └── App.tsx             # Root app component
│── capacitor.config.ts     # Capacitor configuration
│── package.json            # Dependencies & scripts
│── README.md               # Project documentation

````

---

## ⚡ Installation & Setup
### 1. Clone the repository
```bash
git clone https://github.com/Hackb07/pmc-app.git
cd pmc-app
````

### 2. Install dependencies

```bash
npm install
```

### 3. Run on Web

```bash
npm start
```

### 4. Run on Android

```bash
npx cap sync android
npx cap open android
```

Then build & run via **Android Studio**.

---


---

## 🤝 Contributors

* **B. Tharun Bala** (610823U243059)
* Department of **Artificial Intelligence & Data Science**,
  Perumal Manimekalai College of Engineering, Hosur

---

## 📜 License

This project is licensed under the **MIT License** – feel free to use and modify.

---

```

