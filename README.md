
# Project Bolt

This is the updated version of the **Project Bolt** website with the following changes:
- ✅ Replaced the logo with a new image-based logo
- ✅ Updated Habibur Rahman's designation to **Director**
- ✅ Ensured responsive design for both web and mobile
- ✅ Configured for deployment to GitHub and Netlify

---

## 🚀 How to Deploy

### 🧱 1. Clone and Initialize Git

Unzip this project and navigate into the folder:

```bash
cd E:/Project
git init
git add .
git commit -m "Initial commit with updated logo and team info"
```

### 🔗 2. Push to GitHub

1. Create a new repo at: [https://github.com/new](https://github.com/new)
2. Then run:

```bash
git remote add origin https://github.com/Azzurra2025/project-bolt.git
git branch -M main
git push -u origin main
```

---

### 🌐 3. Deploy to Netlify

1. Visit [https://app.netlify.com](https://app.netlify.com)
2. Click **"Add new site"** > **"Import an existing project"**
3. Select GitHub and pick the `project-bolt` repo

#### 🔧 Build settings:
- **Framework**: `Vite`
- **Build command**: `npm run build`
- **Publish directory**: `dist`

Click **Deploy site** and you’re live!

---
