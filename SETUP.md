# 🚀 GitHub Setup & Deploy Guide

Follow these steps to push your portfolio live in under 5 minutes.

---

## Step 1 — Create GitHub Repository

1. Go to 👉 https://github.com/new
2. Fill in:
   - **Repository name:** `portfolio`
   - **Visibility:** ✅ Public
   - **Add README:** ❌ No (we already have one)
3. Click **Create repository**
4. Copy the repo URL shown — it will look like:
   `https://github.com/YOUR_USERNAME/portfolio.git`

---

## Step 2 — Install Git (if not already)

**Windows:** https://git-scm.com/download/win  
**Mac:** Run `xcode-select --install` in Terminal  
**Linux:** `sudo apt install git`

Verify: `git --version`

---

## Step 3 — Configure Git (first time only)

```bash
git config --global user.name "Sai Ram Nellore"
git config --global user.email "sairam.1830181@gmail.com"
```

---

## Step 4 — Push Portfolio to GitHub

Open Terminal (Mac/Linux) or Command Prompt (Windows), then:

```bash
# 1. Navigate to the portfolio folder
cd path/to/portfolio-deploy

# 2. Initialize git
git init

# 3. Add all files
git add .

# 4. First commit
git commit -m "🚀 Launch: Sai Ram Nellore Portfolio"

# 5. Set branch to main
git branch -M main

# 6. Connect to your GitHub repo (replace YOUR_USERNAME)
git remote add origin https://github.com/YOUR_USERNAME/portfolio.git

# 7. Push!
git push -u origin main
```

---

## Step 5 — Enable GitHub Pages (Free Hosting)

1. Go to your repo: `https://github.com/YOUR_USERNAME/portfolio`
2. Click **Settings** tab
3. Click **Pages** in the left sidebar
4. Under **Source** → select **Deploy from a branch**
5. Branch: **main** | Folder: **/ (root)**
6. Click **Save**
7. Wait ~60 seconds, then visit:

🌐 **`https://YOUR_USERNAME.github.io/portfolio`**

---

## Step 6 — Update README badge URL

Open `README.md` and replace `YOUR_USERNAME` with your actual GitHub username in the badge links at the top.

```bash
git add README.md
git commit -m "Update README with live URL"
git push
```

---

## 🔄 How to Update Portfolio Later

Whenever you make changes to `index.html`:

```bash
git add index.html
git commit -m "Update portfolio content"
git push
```

GitHub Pages will automatically redeploy within ~30 seconds.

---

## ✅ Final Checklist

- [ ] Repo created on GitHub
- [ ] Files pushed successfully
- [ ] GitHub Pages enabled
- [ ] Live URL working
- [ ] README badge URLs updated with your username
- [ ] Share your live URL on LinkedIn!

---

**Your live portfolio URL:**  
🔗 `https://YOUR_USERNAME.github.io/portfolio`
