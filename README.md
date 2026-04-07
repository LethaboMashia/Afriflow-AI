# 🌍 Afriflow AI — Complete Package
## by Bohlale Automated Services

---

## 📁 FOLDER STRUCTURE (Open this folder in VS Code)

```
afriflow/
├── index.html          ← The website your CLIENTS see (your sales page)
├── admin/
│   └── index.html      ← YOUR private admin dashboard (only you see this)
└── README.md           ← This guide
```

---

## 🚀 HOW TO OPEN IN VS CODE (Step by Step)

1. Download and unzip this folder
2. Open **VS Code**
3. Click **File → Open Folder** → select the `afriflow` folder
4. Install the **"Live Server"** extension (click Extensions icon on left, search "Live Server" by Ritwick Dey)
5. Right-click `index.html` → click **"Open with Live Server"**
6. Your website opens in the browser at `http://127.0.0.1:5500`
7. To open admin: go to `http://127.0.0.1:5500/admin/index.html`

---

## 🔐 ADMIN LOGIN DETAILS

URL: `admin/index.html`

- **Username:** `lethabo`
- **Password:** `BAS2025admin!`

⚠️ To change your password:
Open `admin/index.html` in VS Code → find this line near the bottom:
```javascript
const ADMIN_PASS = 'BAS2025admin!';
```
Change the text between the quotes to your new password and save.

---

## 💡 WHAT IS THIS SYSTEM? (Plain English)

You are building a **business** called **Afriflow AI** under **Bohlale Automated Services**.

You sell a service to small businesses (hair salons, gyms, restaurants, etc.) where you set up AI automation for them. Here is exactly what that means:

### The 4 Things You Sell:

**1. WhatsApp AI Bot**
- The client's WhatsApp automatically reads and replies to every customer message
- It uses AI (ChatGPT) trained on that business's info — their prices, services, hours
- A customer asks "Do you have space Saturday at 2pm?" — the bot replies instantly, 24/7
- The business owner doesn't lift a finger

**2. Booking System**
- Customers can book appointments through WhatsApp
- The booking goes directly into a calendar
- The AI sends the customer a reminder the day before
- No double bookings, no no-shows

**3. CRM (Lead Tracker)**
- Every person who contacts the business gets recorded in a system
- You can see: who enquired, whether they booked, whether they paid
- You follow up with anyone who didn't book yet
- Nothing falls through the cracks

**4. Email Sequences**
- When someone enquires, automated emails go out over the next few days
- "Thanks for enquiring!" → "Here's a special offer" → "Don't miss out"
- This turns cold leads into paying clients automatically

---

## 💰 HOW YOU MAKE MONEY

| Package | Monthly Charge | What You Provide |
|---------|---------------|-----------------|
| Starter | R3,000/month | WhatsApp AI replies only |
| Growth | R8,500/month | WhatsApp + Booking + CRM + Emails |
| Enterprise | R20,000/month | Everything + custom builds |

**Example:** Sign up 5 Growth clients = **R42,500 per month**. Recurring. Every month.

Your actual costs per client are roughly:
- OpenAI API: ~R100–300/month per client
- WhatsApp Business API: ~R200–500/month per client
- Your time: ~2 hours/month for maintenance

**Margin on Growth package: ~R7,500–8,000 per client**

---

## 📊 YOUR ADMIN DASHBOARD FEATURES

The admin page (`admin/index.html`) lets YOU:

| Feature | What It Does |
|---------|-------------|
| 📊 Dashboard | See all clients + total monthly revenue at a glance |
| 🏢 Clients | Add, view, and manage every client business |
| 💰 Revenue | See your MRR, annual run rate, and breakdown per package |
| 🔔 Alerts | See system warnings and action items |
| ⚡ System Status | Check which integrations are connected |
| ⚙️ Settings | Your credentials, contact details, API key info |

---

## 🎯 HOW TO MARKET THIS (What to Say to Clients)

### The One-Liner:
> *"I set up an AI system that replies to all your WhatsApp messages 24/7, books appointments, and tracks your leads — so you never miss a customer again. Starting from R3,000 a month."*

### Best Target Industries:
- Hair & beauty salons
- Gyms & fitness studios
- Restaurants & food businesses
- Clinics & medical practices
- Estate agents
- Tutoring & education
- Any business with lots of WhatsApp enquiries

### How to Close a Sale:
1. Show them the **live website** (index.html) on your phone
2. Point to the **WhatsApp chat demo** on the site
3. Ask: *"How many WhatsApp messages do you miss every week?"*
4. Show them the **Starter package at R3,000**
5. Say: *"I'll set it up in 48 hours — all I need is a 30 minute call with you"*
6. Get them on the **Growth package** once they see results (2-3 months in)

---

## 🔧 NEXT STEPS — TO MAKE IT FULLY LIVE

This package gives you the **website + admin dashboard**. The actual AI needs to be connected.

Here's the order of what to do next (ask Claude to help with each step):

### Step 1: Get Your API Keys
- **WhatsApp Business API** → Apply at [business.whatsapp.com](https://business.whatsapp.com)
  - You need a Meta Business account
  - Verification takes 2–5 business days
- **OpenAI API Key** → Sign up at [platform.openai.com](https://platform.openai.com)
  - Costs ~$0.01–0.05 per conversation
  - Start with GPT-3.5 for affordability, upgrade to GPT-4 for quality

### Step 2: Build the Flask Backend
- Flask is a Python-based server that connects everything together
- Ask Claude: *"Help me build a Flask backend that receives WhatsApp messages and sends them to OpenAI, then replies"*
- This is the brain of the whole system

### Step 3: Deploy Online
- Use **Railway** (railway.app) — free to start, easy to deploy
- Or **Render** (render.com) — also free tier available
- Once deployed, you'll get a URL like `https://afriflow.up.railway.app`

### Step 4: Connect Google Calendar
- For the booking system
- Uses Google Calendar API
- Ask Claude: *"Help me connect Google Calendar to my Flask backend"*

### Step 5: Set Up Email
- Use Gmail SMTP or SendGrid (free tier available)
- For sending confirmation + follow-up emails

---

## 📞 YOUR CONTACT DETAILS (Already in the website)

- **WhatsApp:** +27 658 619 866
- **Email:** lethabomashia17@gmail.com
- **Business:** Bohlale Automated Services
- **Product:** Afriflow AI

---

## 💳 HOW TO SET UP PAYFAST (Step by Step)

PayFast is a South African payment gateway. It deposits money directly into your SA bank account (FNB, Standard Bank, Capitec, etc.).

### Step 1 — Create a PayFast account
1. Go to [payfast.co.za](https://www.payfast.co.za)
2. Click "Sign Up" → choose "Merchant"
3. Fill in your details (use your real name and Bohlale Automated Services)
4. Complete FICA verification (ID + proof of bank account — required by SA law)
5. Once approved, go to **Settings → Merchant Credentials**
6. You'll see your **Merchant ID** and **Merchant Key**

### Step 2 — Add your credentials to checkout.html
Open `checkout.html` in VS Code and find these lines:
```html
<input type="hidden" name="merchant_id" value="YOUR_MERCHANT_ID" />
<input type="hidden" name="merchant_key" value="YOUR_MERCHANT_KEY" />
```
Replace `YOUR_MERCHANT_ID` and `YOUR_MERCHANT_KEY` with your real values from PayFast.

### Step 3 — Set your URLs (after hosting)
Once your site is live (e.g. on Netlify), update these 3 lines:
```html
<input type="hidden" name="return_url" value="https://yourdomain.co.za/thankyou.html" />
<input type="hidden" name="cancel_url" value="https://yourdomain.co.za/checkout.html" />
<input type="hidden" name="notify_url" value="https://yourdomain.co.za/payfast-notify" />
```
- `return_url` = where to send the user after payment (your thankyou.html)
- `cancel_url` = where to send if they cancel (back to checkout)
- `notify_url` = PayFast will POST payment data here (needs a server — for now leave it)

### How money reaches your bank
- Client pays on the checkout page → PayFast processes it securely
- PayFast deposits into YOUR bank account daily/weekly (you set the schedule)
- You get an email notification for every payment
- PayFast fee: **3.5% + R2.00** per transaction (they deduct this automatically)
- Example: Client pays R8,500 → you receive ~R8,200

### Testing before going live
PayFast has a **sandbox mode** for testing. Use these test credentials:
- Sandbox URL: `https://sandbox.payfast.co.za/eng/process`
- Test merchant_id: `10000100`
- Test merchant_key: `46f0cd694581a`
When ready to go live, change the form action back to `https://www.payfast.co.za/eng/process`

---

## 🌐 HOW TO PUT THE WEBSITE ONLINE (Host It)

To share the website with real clients:

**Option 1 — Netlify (Free, easiest)**
1. Go to [netlify.com](https://netlify.com)
2. Sign up free
3. Drag and drop your `afriflow` folder
4. You get a URL like `https://afriflow-ai.netlify.app`

**Option 2 — Buy a domain**
1. Buy `afriflow.co.za` on [domains.co.za](https://domains.co.za) (~R150/year)
2. Connect it to Netlify
3. Now your website is at `www.afriflow.co.za`

---

*Afriflow AI — System #2 by Bohlale Automated Services*
*Contact: lethabomashia17@gmail.com | +27 658 619 866*
