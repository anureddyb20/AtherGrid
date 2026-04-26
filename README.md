# ⚡ AetherGrid: The Next-Gen Decentralized Smart Grid 🔋

![AetherGrid Header](https://images.unsplash.com/photo-1473341304170-971dccb5ac1e?auto=format&fit=crop&q=80&w=1200&h=400)

**AetherGrid** is a state-of-the-art energy management system built by team **ELITES** 🏆. Our mission is to optimize grid stability and enable seamless Peer-to-Peer (P2P) energy trading for a greener future. 🌍✨

---

## 🚀 Amazing Features

### 📊 Real-time Grid Analytics
Stay on top of everything! 🕵️‍♂️ Monitor **KW Usage**, **Load Factors**, and **Voltage stability** with beautiful, easy-to-read charts. 📈

### 🤝 P2P Energy Marketplace
Trade energy like a pro! 💰 Our live marketplace allows you to buy and sell surplus solar or wind energy directly with others in your community. 🏠✨🏠

### 🤖 AI-Powered Forecasting
Let the machines do the work! 🧠 AetherGrid uses smart AI to predict energy demand and generation, keeping the grid perfectly balanced. ⚖️

### 🗺️ Live Map Insights
See the grid in action! 📍 View all energy resources (Solar, Wind, Batteries) on an interactive map to spot issues before they happen. 🔍

### 🔋 Smart Battery Storage
Never run out of power! ⚡ Monitor your battery levels and optimize storage for use when the sun isn't shining. 🌙

### 🛠️ Elite Admin Control
Full power at your fingertips! 🕹️ A comprehensive dashboard for managing billing, datasets, and regional energy flow. 🏢

---

## 🛠️ Tech Stack (The Magic Behind AetherGrid)

- **Frontend**: ⚛️ [React 19](https://react.dev/) + ⚡ [Vite](https://vitejs.dev/)
- **Visuals**: 📊 [Recharts](https://recharts.org/) + 🎨 Vanilla CSS 
- **Icons**: 🎭 [Lucide React](https://lucide.dev/)
- **Maps**: 🗺️ [Leaflet](https://leafletjs.com/)
- **Backend**: 🟢 [Node.js](https://nodejs.org/) + 🚀 [Express](https://expressjs.com/)
- **Real-time**: 📡 [Socket.io](https://socket.io/)
- **Database**: ☁️ [Supabase](https://supabase.com/) (PostgreSQL)

---

## 📂 How It's Organized

```text
├── src/
│   ├── components/      # 🧩 Small UI parts
│   ├── pages/           # 📄 Main screens (Market, Admin, etc.)
│   ├── services/        # 🔌 Database & Socket connections
│   └── App.jsx          # 🚦 The main router
├── p2p-server.js        # 📡 The Real-time Trading Engine
├── supabase_setup.sql   # 🗄️ Database blueprints
└── datasets/            # 📊 Energy & Solar CSV files
```

---

## 🚦 Getting Started (Simple Steps)

### 1️⃣ Clone the Project
```bash
git clone https://github.com/anureddyb20/AtherGrid.git
cd AetherGrid
```

### 2️⃣ Install Everything
```bash
npm install
```

### 3️⃣ Setup Your Secrets 🤫
Create a `.env` file and add your Supabase details:
```env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

### 4️⃣ Setup the Database 🗄️
1. Go to your [Supabase Dashboard](https://app.supabase.com/).
2. Paste and run the code from `supabase_setup.sql` in the SQL Editor.

---

## 🖥️ Running the App

### 🏃‍♂️ Step 1: Start the Dashboard
```bash
npm run dev
```

### 🏃‍♂️ Step 2: Start the Trading Server
Open a new terminal and run:
```bash
node p2p-server.js
```

Now open `http://localhost:5173` and start trading! 🎊

---

## 🏆 Developed by Team ELITES
We are a group of passionate innovators dedicated to building sustainable energy solutions. 💡

- **Anu Reddy** - [GitHub](https://github.com/anureddyb20) 👨‍💻
- Team **ELITES** 🌟

---

## 📜 License
This project is licensed under the MIT License. 🛡️
