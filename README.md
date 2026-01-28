# 🏋️ FarmFit - Precision Coaching & Fitness Evolution

[![Vite](https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E)](https://vitejs.dev/)
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Threejs](https://img.shields.io/badge/Three.js-black?style=for-the-badge&logo=three.js&logoColor=white)](https://threejs.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/)

FarmFit is a high-performance, visually stunning fitness platform designed for modern coaching. It combines cutting-edge **3D WebGL experiences** with robust management systems to provide an unparalleled user journey.

---

## ✨ Key Features

### 🧊 Immersive 3D Interface
Powered by **Three.js** and **React Three Fiber**, the platform features high-fidelity 3D elements that react to user interaction and scroll, creating a premium, tactile feel.

### 📝 Precision Onboarding
A sophisticated **multi-step subscription workflow** that collects health stats, physical goals, and payment proof, ensuring coaches have all the data needed for a perfect plan.

### 📊 Advanced Admin Dashboard
A dedicated management portal for coaches to:
- Review client submissions with real-time status updates.
- Preview body transformation photos securely.
- Generate and manage automated client PDFs.

### 🌍 Multi-language Support
Full **i18next** integration, supporting dynamic language switching (English/Arabic) to reach a global fitness community.

### 🚀 Smooth Performance
Integrated with **Lenis** for industry-standard smooth scrolling and **Framer Motion** for sleek micro-animations.

---

## 🛠️ Tech Stack

| Layer | Technologies |
| :--- | :--- |
| **Frontend** | React (Vite), Three.js, Framer Motion, Lenis, i18next |
| **Backend** | Node.js, Express.js, Multer (Local Storage) |
| **Database** | MongoDB (Mongoose) |
| **Testing** | [TestSprite](https://www.testsprite.com/) |

---

## 🚀 Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v18+)
- [MongoDB](https://www.mongodb.com/try/download/community) installed locally or a MongoDB Atlas URI.

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Pro-Abdallah/FarmaFit.github.io.git
   cd FarmaFit
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Configure Environment:**
   Create a `.env` file in the root:
   ```env
   PORT=5000
   MONGODB_URI=your_mongodb_uri
   JWT_SECRET=your_secret_key
   ```

4. **Run the application:**
   - **Start Backend:** `npm run server:dev`
   - **Start Frontend:** `npm run dev`

---

## 🧪 Testing with TestSprite

This project is optimized for **TestSprite** autonomous testing. 

To run tests:
1. Ensure the **TestSprite MCP Server** is configured in your IDE.
2. Open your AI chat (Cursor/VS Code) and ask:
   > "Help me test this project with TestSprite"

---

## 📄 License
Distributed under the MIT License.

---

### Developed with ❤️ by [Pro-Abdallah](https://github.com/Pro-Abdallah)
