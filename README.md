# 🍽️ RestReach — Cold Outreach Tool for Freelance Web Designers

A fully functional, single-file web app to find restaurant leads without websites in India, generate personalized AI cold messages, send via WhatsApp, and track your entire pipeline.

**Built for freelancers who sell websites to restaurants.**

---

## ✨ Features

- **Lead Management** — Add restaurants manually or bulk-paste from Google Maps
- **AI Message Generation** — Claude AI writes personalized WhatsApp pitches for each restaurant
- **4 Tone Modes** — Friendly, Professional, Hinglish, FOMO/urgency
- **WhatsApp Deep Links** — One click to open WhatsApp with message pre-filled
- **Pipeline Tracker** — Track every lead: New → Sent → Replied → Interested → Closed
- **Follow-up Messages** — AI-generated 3-day, 1-week, and final follow-ups
- **CSV Export** — Export your full lead list anytime
- **100% Browser-based** — No backend, no server, no database. Data lives in localStorage.
- **Mobile responsive**

---

## 🚀 Deploy for FREE (3 options)

### Option 1: Vercel (Recommended — Auto-deploys from GitHub)

1. Fork or clone this repo to your GitHub account
2. Go to [vercel.com](https://vercel.com) → Sign up with GitHub (free)
3. Click **"Add New Project"** → Import this repo
4. Leave all settings as default → Click **Deploy**
5. ✅ Live at `your-app-name.vercel.app` in ~30 seconds

**Bonus:** Every time you push a change to GitHub, Vercel auto-redeploys.

---

### Option 2: Netlify Drop (No account needed — fastest)

1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag and drop the **folder** containing `index.html`
3. ✅ Live URL in 30 seconds — no login required

---

### Option 3: GitHub Pages (Free forever)

1. Push this repo to GitHub
2. Go to repo **Settings → Pages**
3. Set Source: **Deploy from branch → main → / (root)**
4. ✅ Live at `yourusername.github.io/repo-name`

---

## 🔑 Setup: Get Your Free Anthropic API Key

The app uses Claude AI to generate messages. You need a free API key:

1. Go to [console.anthropic.com](https://console.anthropic.com)
2. Sign up (free) → Go to **API Keys** → Create a key
3. Open the deployed app → **Settings tab** → Paste your key → Save
4. Your key is stored **only in your browser** — never sent anywhere except Anthropic's API

> **Free tier:** Anthropic gives you free credits to start. Each message generation costs fractions of a rupee.

---

## 📱 How to Use

### Step 1: Find Leads
- Open Google Maps → Search "restaurants [your area]"
- Click each restaurant — if **no website listed**, it's a lead
- Copy their name + phone number
- Paste into the **Find Leads** tab → Click "Parse & Add Leads"

### Step 2: Generate Message
- Go to **Compose** tab
- Select a restaurant from the list
- Choose your tone (Hinglish works great in Delhi NCR!)
- Click **"Generate AI Message"**
- Hit **"Send on WhatsApp"** → WhatsApp opens with message ready

### Step 3: Track Everything
- **Tracker** tab shows your full pipeline
- Update status as leads reply
- Use built-in follow-up templates or generate AI ones

---

## 🛠️ Tech Stack

- Pure HTML + CSS + Vanilla JS
- No frameworks, no build tools, no dependencies
- Claude API (`claude-sonnet-4-6`) for message generation
- localStorage for data persistence

---

## 💡 Tips for More Replies

- Send between **10am–12pm** or **4pm–7pm** (owners are free)
- Hinglish tone gets **2–3x more replies** in Delhi NCR
- Mention a **competitor restaurant nearby** that has a site
- Keep messages under **100 words** — shorter = more reads
- Follow up on **Day 3** if no reply

---

## 📁 File Structure

```
restreach/
└── index.html    ← Entire app. That's it.
```

Single file. Zero dependencies. Just deploy.

---

## License

MIT — do whatever you want with it.
