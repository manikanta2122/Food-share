# FoodShare

FoodShare is a full-stack platform designed to connect food donors with individuals, charities, and community organizations to reduce food waste and support those in need.

---

## 📦 GitHub Repositories

| Component | GitHub Repository | Description |
|---|---|---|
| **Full Project (Monorepo)** | [Food-share](https://github.com/manikanta2122/Food-share) | Unified project containing both services |
| **Frontend Service** | [food-share-frontend](https://github.com/manikanta2122/food-share-frontend) | React + Vite UI application (Vercel-ready) |
| **Backend Service** | [food-share-backend](https://github.com/manikanta2122/food-share-backend) | Spring Boot 3 REST API (Render / Docker-ready) |

---

## 🚀 Pushing Updates to Separate Repositories

To push your latest changes from this workspace to the individual GitHub repositories:

### 1. Push to Unified Repo (Food-share)
```bash
git add .
git commit -m "your commit message"
git push origin main
```

### 2. Push Frontend changes to `food-share-frontend`
```bash
git subtree push --prefix=frontend frontend-origin main
```

### 3. Push Backend changes to `food-share-backend`
```bash
git subtree push --prefix=backend backend-origin main
```

---

## 🛠 Local Development

### Frontend
```bash
cd frontend
npm install
npm run dev
```

### Backend
```bash
cd backend
mvn clean spring-boot:run
```
