
# 🚀 AI Business Dashboard

An intelligent dashboard that helps businesses track, analyze, and optimize operations using AI-powered insights.

## 📌 Features
- **Frontend (Next.js + Nx)** – Modern UI for dashboards, reports, and AI insights.
- **Backend (NestJS + Nx)** – APIs, authentication, and AI integration endpoints.
- **AI Layer** – Business intelligence, predictions, and recommendations.
- **Modular Monorepo** – Managed with [Nx](https://nx.dev/) for scalable development.

---

## 🛠 Tech Stack
- **Frontend**: Next.js, TailwindCSS, RxJS  
- **Backend**: NestJS, TypeScript, REST APIs  
- **AI/ML**: Python services (to be integrated)  
- **Database**: PostgreSQL (planned)  
- **Dev Tools**: Nx, ESLint, Prettier, GitHub Actions  

---

## ⚙️ Local Setup

Clone the repo:
```bash
git clone https://github.com/engrabid411/ai-business-dashboard.git
cd ai-business-dashboard
```

### Install dependencies
```bash
npm install
```

### Run Frontend (Next.js)
```bash
nx serve frontend
```

### Run Backend (NestJS)
```bash
nx serve backend
```

### Run all apps
```bash
nx run-many --target=serve --all
```

### Run tests
```bash
nx test
```

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
