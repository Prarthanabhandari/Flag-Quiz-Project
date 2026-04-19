# 🏳️ Flag Identification Quiz

An interactive web-based quiz application where users identify the country based on its national flag.

This project was developed for learning backend development and practicing PostgreSQL database integration using **Node.js** and **Express**.

---

## 🎯 Purpose of This Project

This project was created to:

- Practice PostgreSQL database handling  
- Understand how backend fetches dynamic data  
- Work with image URLs stored in database  
- Connect Express server with EJS templates  
- Improve form handling and validation  

---

## 📚 Learning Source

This project was developed while learning from:

**Angela Yu – Developer and Lead Instructor**  

**Course:**  
*The Complete Full-Stack Web Development Bootcamp*

### Topics Covered:
- HTML  
- CSS  
- JavaScript  
- Node.js  
- React  
- PostgreSQL  
- Web3 and DApps  

> This project was independently implemented for better understanding and hands-on practice.

---

## 🛠️ Tech Stack

- Node.js  
- Express.js  
- PostgreSQL  
- EJS  
- CSS  

---

## 📂 Project Structure

```bash
flag-identification-quiz/
│
├── flags.csv
├── index.js
├── package.json
├── package-lock.json
│
├── views/
│   └── index.ejs
│
├── public/
│   └── styles/
│       └── main.css
│
├── README.md
└── .gitignore
```

---

## 🗄️ Database Setup (PostgreSQL)

### Step 1: Create Database

```sql
CREATE DATABASE flagquiz;
```

### Step 2: Create Table

```sql
CREATE TABLE flags (
  id INT PRIMARY KEY,
  country VARCHAR(100),
  flag_url TEXT
);
```

### Step 3: Import CSV File

- Open **pgAdmin**
- Right click on `flags` table  
- Select **Import/Export**  
- Choose `flags.csv`  
- Set Format → CSV  
- Enable **Header** option  

---

## 📦 Install Dependencies

```bash
npm install
```

### If starting fresh:

```bash
npm init -y
npm install express body-parser pg ejs
```

---

## ▶️ How To Run The Project

```bash
node index.js
```

or

```bash
nodemon index.js
```

Open browser:

```
http://localhost:3000
```

---

## 🎮 How The Game Works

- A random flag is displayed  
- User types the country name  
- If correct → score increases  
- If wrong → game ends  
- User can restart the game  

---

## 💡 Future Improvements

- Add multiple-choice options  
- Add timer  
- Add leaderboard  
- Add difficulty levels  
- Deploy application online  

---

## 👩‍💻 Author

**Prarthana Bhandari**  
*MCA Student*

---
