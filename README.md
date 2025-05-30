

# 🚀Moneyamour - A Next.js + Firebase App (Dockerized with pnpm)

This project is a Dockerized Next.js application using Firebase as a backend and `pnpm` as the package manager.

## 🧰 Features

- Next.js (App/Pages directory support)
- Firebase SDK (Client-side)
- `pnpm` for faster and efficient dependency management
- Dockerized for easy setup — no local Node.js or pnpm installation required

---

## 📦 Requirements

- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/) (comes with Docker Desktop)

---

## 🚀 Getting Started

1. **Clone the Repository**

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
---
```
### **2. Create Environment Variabless**
```bash
cp .env.example .env.local
```
Edit .env.local with your Firebase credentials:
```env
NEXT_PUBLIC_FIREBASE_API_KEY=your-api-key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your-project.firebaseapp.com
...
```
### **3. Run the App**
```bash
docker-compose up --build
```
Your app should now be running at: http://localhost:3000

### **🛑 Stopping the App**
Press Ctrl + C to stop

Then run:
```bash 
docker-compose down
```
### **🐳 Useful Docker Commands**
```bash 
# Rebuild after code or dependency changes
docker-compose up --build

# List all containers
docker ps

# Stop all containers
docker stop $(docker ps -q)
```
### **🤝 Contributing**
Pull requests are welcome! For major changes, please open an issue first. 

### **📝 License**
MIT 
```yaml

---

Let me know if you want a variant for Firebase Admin SDK or dev mode (`pnpm dev` instead of `pnpm start`).
```

```bash 
Thanks to @amour, @mosnyik and @victortterry for their contibution to this project 
```