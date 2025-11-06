# 🚀 Deploy Commands

## Step 1: Initialize Git Repository

```bash
git init
git add .
git commit -m "Firebase auth test for Shanghai"
```

## Step 2: Create GitHub Repository

1. Go to https://github.com/new
2. Create a new repository (name it anything, e.g., "firebase-shanghai-test")
3. Don't initialize with README (we already have one)

## Step 3: Push to GitHub

```bash
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git push -u origin main
```

## Step 4: Deploy to Render

1. Go to https://dashboard.render.com/
2. Click "New +" → "Web Service"
3. Click "Connect GitHub"
4. Select your repository
5. Settings:
   - **Name**: firebase-shanghai-test
   - **Build Command**: `npm install`
   - **Start Command**: `npm start`
6. Click "Create Web Service"

## Step 5: Get Your URL

After 2-3 minutes, you'll get a URL like:
`https://firebase-shanghai-test.onrender.com`

## Step 6: Test from Shanghai!

Open the URL and watch the Firebase performance metrics.

---

## ⚠️ Important: Enable Firebase Authentication

Before testing, enable Email/Password auth:
1. Go to: https://console.firebase.google.com/project/fir-test-9281a/authentication
2. Click "Sign-in method"
3. Enable "Email/Password"
4. Save

---

## 📋 What's Included

- ✅ Firebase config already set (project: fir-test-9281a)
- ✅ Express server configured
- ✅ Test UI with timing metrics
- ✅ Render deployment config
- ✅ Ready to deploy!

Just push to GitHub and deploy! 🎯
