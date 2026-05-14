# Micah Intelligence — v2.7.1

> A hyper-intelligent, socially awkward AI chat interface. Completely free to run.

## 🚀 Deploy to Vercel (Free, ~10 minutes)

### Step 1 — Get a free OpenRouter API Key
1. Go to [openrouter.ai](https://openrouter.ai) and sign up (free, no card needed)
2. Go to **Keys** → click **Create Key**
3. Copy the key (starts with `sk-or-...`)

### Step 2 — Push to GitHub
1. Go to [github.com](https://github.com) and create a new repository (call it anything, e.g. `micah-intelligence`)
2. Click **uploading an existing file** and drag all 4 files in:
   - `index.html`
   - `vercel.json`
   - `api/chat.js` ← make sure this goes inside a folder called `api`
   - `README.md`
3. Click **Commit changes**

### Step 3 — Deploy on Vercel
1. Go to [vercel.com](https://vercel.com) → sign up with your GitHub account
2. Click **Add New → Project** → select your repo
3. Before deploying, open **Environment Variables** and add:
   - **Name:** `OPENROUTER_API_KEY`
   - **Value:** your key from Step 1
4. Click **Deploy** — you'll get a live URL in about 30 seconds!

### Step 4 — Share with Friends
Send them your Vercel URL. Done! Completely free, forever.

---

## 📁 Project Structure

```
micah-intelligence/
├── index.html        # The full UI
├── api/
│   └── chat.js       # Serverless function (keeps your API key safe)
├── vercel.json       # Vercel routing config
└── README.md
```

## 💸 Cost breakdown
- **Vercel:** free
- **OpenRouter free models:** free (rate limited but totally fine for friends)
- **Total: $0**

---

*"Statistically speaking, this README has a 97.3% chance of being sufficient."*
