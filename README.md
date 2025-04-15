# 📦 Storage Management System (SMS)

A modern web-based **Storage Management System (SMS)** that allows users to track, manage, and organize items within storage units. Built using **React.js** for the frontend and **Node.js with Express** for the backend, it provides a seamless interface for efficient inventory and space control.

![image](https://i.ibb.co/wR9G2k3/Readme-Thumbnail.png)


---

## 🚀 Demo

🌐 **Live URL:** [https://sms-3gu33jjdk-sharad-chandra-reddys-projects.vercel.app/](https://sms-3gu33jjdk-sharad-chandra-reddys-projects.vercel.app/)

---

## 🛠️ Tech Stack

- **Frontend:** React.js, TailwindCSS  
- **Backend:** Node.js, Express.js  
- **Deployment:** Vercel (Frontend), Render/Heroku (Backend - optional)

---

## 📦 Features

- ✅ Add, edit, and delete storage items
- ✅ Organize by categories or units
- ✅ Visual layout of storage sections (optional)
- ✅ Responsive dashboard for real-time management
- ✅ Backend APIs for full CRUD operations
- ✅ Clean and responsive UI

---

## 🧑‍💻 Installation Guide

### 📁 Clone the Repository

```bash
git clone https://github.com/SCR01/SMS.git
cd SMS
```

---

### ⚙️ Frontend Setup

```bash
cd client
npm install
npm start
```

The React frontend will run at: `http://localhost:3000`

---

### 🌐 Backend Setup

```bash
cd server
npm install
```

> 📌 Create a `.env` file inside the `server` directory and add the following:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
```

Then run the backend server:

```bash
npm start
```

Backend will run on: `http://localhost:5000`

---

## 📸 Screenshots

| Dashboard | Add Item Page |
|-----------|----------------|
| ![Dashboard](![image](https://github.com/user-attachments/assets/89d96235-b1a2-46be-bba1-2342d7fbdd1d) |
| ![Add Item](![image](https://github.com/user-attachments/assets/7c9679bc-4939-4294-a95e-809fa4933f75) |
 



---

## 📂 Folder Structure

```
SMS/
├── client/           # React frontend
│   ├── public/
│   └── src/
├── server/           # Express backend
│   ├── routes/
│   └── controllers/
├── screenshots/      # App screenshots
├── README.md
└── .gitignore
```

---

## 💡 Future Improvements

- 🔐 User authentication and roles (admin/staff)
- 📊 Inventory analytics dashboard
- 🗃️ Barcode scanning integration
- 📁 CSV import/export functionality

---

## 🤝 Contributing

Contributions are welcome!  
Feel free to fork the repo, raise issues, or submit pull requests.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 👤 Author

**Sharad C Reddy**  
🔗 [GitHub](https://github.com/SCR01)  
🌐 [Portfolio](https://portfolio-scr.vercel.app)




