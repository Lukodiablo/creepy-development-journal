# DreamHack Stockholm 2025 - Setup Guide

## 🎯 Primary Goal
**Get 500+ members in Creepy Labs for Discord Partner badge**

## 🎯 Secondary Goal  
Acquire 50+ paying customers through event promotion

---

## 📋 Pre-Event Checklist

### 1. Populate Universal Promo Code
```bash
node scripts/populate-codes.js --dreamhack
```

This will create **ONE universal code: `DREAMHACK-2025`** with:
- ✅ 1000 usage cap (once per Discord server)
- ✅ 14-day Creepy PRO access
- ✅ 50 AI calls per day limit
- ✅ Guild-locked (prevents multi-redemption)
- ✅ Auto-expires after 14 days

### 2. Setup Labs Server Pin

**In Creepy Labs #announcements channel, pin this message:**

```markdown
🎮 **DREAMHACK STOCKHOLM EXCLUSIVE** 🎮

Welcome to Creepy Labs! 🎉

You made it! Here's your exclusive 14-day Creepy PRO trial code:

┌─────────────────────────┐
│   DREAMHACK-2025        │
└─────────────────────────┘

**How to Redeem:**
1. Go to https://thecreepy.app/dashboard
2. Select your Discord server
3. Click "Subscription" 
4. Enter code: DREAMHACK-2025
5. Enjoy 14 days of PRO features! ✨

**What You Get:**
✅ AI-powered auto-moderation
✅ Advanced anti-spam protection  
✅ 50 AI interactions per day
✅ Professional announcement system
✅ Complete analytics dashboard

**⚠️ Limited to 1000 redemptions - use it while you can!**

Questions? Ask in <#support-channel>
Feedback? We'd love to hear it in <#feedback-channel>

Let's build something amazing together! 🚀
```

### 3. Print 1000 Promotional Cards

**CRITICAL: NO CODE ON THE CARD!**

**Card Design Specs:**
- Size: Standard business card (85mm x 55mm)
- Material: Glossy cardstock
- Quantity: **1000 identical cards**
- Cost: **~€150 for 1000 cards** (€15 per 100)

**Front Side:**
```
╔═══════════════════════════════════╗
║                                   ║
║         [CREEPY LOGO]            ║
║                                   ║
║   Discord's Smartest Bot         ║
║                                   ║
║      [QR CODE TO WEBSITE]        ║
║    https://thecreepy.app         ║
║                                   ║
╚═══════════════════════════════════╝
```

**Back Side:**
```
╔═══════════════════════════════════╗
║  🎮 EXCLUSIVE DREAMHACK OFFER 🎮  ║
║                                   ║
║   Join Creepy Labs to unlock     ║
║   your FREE 14-day PRO trial!    ║
║                                   ║
║   [QR CODE TO LABS DISCORD]      ║
║                                   ║
║  ✨ AI-Powered Moderation         ║
║  🤖 50 AI Calls/Day               ║
║  ⏰ 14-Day Trial                  ║
║  🎁 Limited to 1000 users         ║
║                                   ║
║   Scan now - spots filling fast! ║
╚═══════════════════════════════════╝
```

---

## 🎤 Event Strategy

### The Funnel (Key Innovation!)
1. **Card handout** → QR scan
2. **Join Labs Discord** → See pinned code
3. **Redeem code** → Get 14-day trial
4. **Try features** → Convert to paid

**Why This Works:**
- ✅ Forces Labs join (builds community for Partner badge)
- ✅ Filters serious users (only engaged people redeem)
- ✅ Cheaper printing (1000 identical cards)
- ✅ Creates urgency (1000 cap visible in Labs)
- ✅ Community building from day 1

### Booth Setup
- **Banner:** Large Creepy logo + "AI-Powered Discord Bot"
- **Demo:** Live bot in action on tablet
- **Cards:** Easy-grab stack with clear CTA
- **Staff:** 1-2 people to engage and explain

### Pitch (30 seconds)
> "Want to automate your Discord server? Creepy is an AI bot that moderates for you - it reads your rules and configures everything automatically. Scan this card, join our community, and get 14 days of PRO features free. No credit card needed!"

### Key Talking Points
- 🤖 **AI-powered** (auto-config from rules channel)
- ⚡ **Set and forget** (severity system handles everything)
- 🎮 **Built-in RPG** (keeps members engaged)
- 📊 **Professional tools** (analytics, announcements)

### The Hook
- "Only 1000 spots available"
- "Join the testing community"
- "Shape the bot's future with your feedback"

---

## 📊 During Event Tracking

### Real-time Monitoring
Monitor the code's redemption count in Firebase Console:
```
Collection: redeemCodes
Document: DREAMHACK-2025
Fields to watch:
  - usageCount (current redemptions)
  - maxUsageCount (1000 cap)
  - redemptions[] (list of guilds)
```

### Hourly Check-ins
- **Cards distributed:** Manual count
- **Labs joins:** Check Discord member count
- **Code redemptions:** Check usageCount
- **Conversion rate:** Cards → Labs → Redemptions

### Engagement Tactics
- Update Labs announcement with live count: "823/1000 codes remaining!"
- Create FOMO: "Almost at capacity!"
- Celebrate milestones: "500 members - halfway to Partner!"

---

## 📧 Post-Event Follow-up

### In Labs Server - Daily

**Day 1 (Event Day):**
```
🎉 Welcome to all our DreamHack visitors!

We've had [X] people join today! 

Haven't redeemed your code yet? 
Code: DREAMHACK-2025
👉 https://thecreepy.app/dashboard

Questions? Drop them in <#support>!
```

**Day 3:**
```
👋 Hey DreamHack crew!

Just a reminder - your promo code is still waiting!

DREAMHACK-2025

Only [X] redemptions left before we hit the cap.
Get your 14-day PRO trial while you can! ✨
```

**Day 7 (Mid-trial for redeemers):**
```
🔥 One week into your trial!

How's Creepy working for you? We'd love your feedback!

💡 Pro tip: Check out the AI Rules Auto-Config feature - 
it's a game-changer for moderation setup.

Drop your thoughts in <#feedback>!
```

**Day 12 (CRITICAL - 2 days before expiry):**
```
⚠️ Your Creepy PRO trial expires in 2 days!

EXCLUSIVE LABS MEMBER OFFER:
Get 25% off your first month if you subscribe before your trial ends!

Use code: LABS25 at checkout
👉 https://thecreepy.app/dashboard

This offer expires with your trial! ⏰
```

**Day 15 (Post-expiry):**
```
👋 Hope you enjoyed Creepy PRO!

Your trial has ended, but you're always welcome to upgrade.

Standard pricing: €5/month for PRO, €10/month for ULTRA
👉 https://thecreepy.app/dashboard

Thanks for being part of the community! 💜
```

---

## 🎯 Success Metrics

### Primary Goals (Labs Growth):
- ✅ **1000 cards distributed**
- ✅ **600+ Labs joins** (60% scan rate)
- ✅ **500+ sustained members** (Partner badge!)
- ✅ **400+ code redemptions** (40% of joins)

### Secondary Goals (Revenue):
- ✅ **100+ active trials** (25% of redemptions)
- ✅ **50+ paid conversions** (50% of active trials)
- ✅ **€250/month recurring** (50 × €5)

### ROI Calculation:
**If 50 people subscribe to PRO (€5/mo):**
- Month 1: €250
- Annual value: €3,000  
- LTV (12 months): €36,000

**Event Cost:**
- Cards: **€150** (1000 cards @ €15/100)
- Travel/booth: Variable
- Time: 3 days

**Break-even:** 30 monthly subscribers = profitable (€150 ÷ €5)
**Target:** 50 subscribers = **HUGE WIN**

---

## 🚨 Troubleshooting

### "Code not working"
1. Check usageCount hasn't hit 1000
2. Verify guild hasn't already redeemed (check redemptions array)
3. Confirm user is guild admin/owner

### "AI limit not working"
1. Verify bot commands call checkAiCallLimit()
2. Check proRestrictions field in moderation settings
3. Verify daily counter resets properly

### "Trial not expiring"
1. Check proTierExpiresAt timestamp in Firestore
2. Verify bot's clientReady checks expirations
3. Manual fix: Set proTierActive = false

### "Usage count not incrementing"
1. Check transaction completed successfully
2. Verify redemptions array updated
3. Check for race conditions (should be atomic)

---

## 📝 Post-Event Analysis

### Track These Metrics:
- **Distribution rate:** Cards given out per hour
- **Scan rate:** Labs joins ÷ cards distributed
- **Redemption rate:** Code uses ÷ Labs joins
- **Conversion rate:** Paid subs ÷ redemptions
- **Retention rate:** Members still in Labs after 30 days

### Document:
- Best pitch variations
- Common objections and responses
- Most requested features
- Conversion triggers (what made people subscribe)
- Demographic insights

### For Next Event:
- Card design improvements
- Pitch refinements
- Booth setup optimizations
- Follow-up sequence timing
- Offer structure changes

---

## 🎉 Launch Day Checklist

```bash
# Morning - Before Event
□ Bot is running (npm run start:bot)
□ Dashboard is live (npm run dev)
□ Universal code populated (check Firebase)
□ Labs announcement pinned
□ Cards printed and ready
□ QR codes tested (both work)
□ Team briefed on pitch

# During Event
□ Track cards distributed (tally counter)
□ Monitor Labs member count
□ Check code usage hourly
□ Engage with booth visitors
□ Answer questions promptly
□ Adjust pitch based on responses

# Evening Wrap-up
□ Count remaining cards
□ Check Firebase redemption count
□ Post Day 1 message in Labs
□ Note any issues or patterns
□ Plan adjustments for tomorrow
```

---

**Let's crush this event and build an amazing community! 🚀**

**Target: 500+ Labs members + 50+ paying customers = MISSION ACCOMPLISHED**

