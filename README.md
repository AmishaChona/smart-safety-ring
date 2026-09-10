# Smart Safety Ring System

An end-to-end IoT safety wearable platform featuring real-time location tracking, emergency alert dispatching, a Node.js/TypeScript backend API, and an interactive React web dashboard.

---

## 1. System Overview

```text
 [ Smart Safety Ring ] ────► [ Hardware Module ] ────► [ Backend API ] ────► [ Web Dashboard ]
(Hardware Button/Sensors)     (Sends GPS/SOS via LTE)   (Node.js/Express)    (React/Vite UI)

smart-safety-ring/
├── docs/                   # System architecture, API specs, and database design
│   ├── API.md              # REST API endpoint documentation
│   ├── ARCHITECTURE.md     # High-level architecture & data flow
│   ├── DATABASE.md         # Database schema and models
│   ├── PROJECT_PRESENTATION.md # Overview slides and notes
│   └── SECURITY.md         # Security protocols & encryption guidelines
├── backend/                # Node.js + Express TypeScript backend server
│   ├── .env.example        # Environment variables template
│   ├── package.json        # Backend dependencies
│   ├── tsconfig.json       # TypeScript configuration
│   └── src/server.ts       # Server entry point
├── web/                    # React + Vite frontend web dashboard
│   ├── index.html          # HTML entry point
│   ├── package.json        # Web dependencies
│   ├── tsconfig.json       # Web TypeScript configuration
│   ├── vite.config.ts      # Vite build configuration
│   └── src/                # React source code (main.tsx, style.css)
└── hardware/               # Embedded firmware and microcontroller configs
    └── README.md           # Sensor setup, pinouts, and hardware guides

git clone [https://github.com/Anupriya/smart-safety-ring.git](https://github.com/Anupriya/smart-safety-ring.git)
cd smart-safety-ring

